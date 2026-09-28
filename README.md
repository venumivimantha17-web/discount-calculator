# Discount Calculator

A Python-based discount calculator that demonstrates Object-Oriented Programming (OOP), abstract classes, inheritance, polymorphism, type hints, and the Strategy Design Pattern.

## Overview

This project calculates the best possible price for a product by evaluating multiple discount strategies.

The calculator supports:

- Percentage-based discounts
- Fixed-amount discounts
- Premium-user discounts
- Automatic selection of the lowest applicable price

## Features

- Product management using classes
- Abstract `DiscountStrategy` interface
- Multiple concrete discount strategies
- Percentage discount validation
- Fixed amount discount validation
- Premium user discount handling
- Best-price calculation
- Python type hints
- Case-insensitive premium user checking

## Discount Strategies

### 1. Percentage Discount

Applies a percentage discount to the original product price.

Percentage discounts are limited to a maximum of 70%.

Example:

```text
Original Price: $50.00
Discount: 10%
Final Price: $45.00

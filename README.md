# Java Projects
 
# Pizza Bill Generating System

## Overview

This project is a Java-based pizza ordering system that simulates a pizza restaurant's ordering and billing process. The system allows users to create and customize pizzas, including adding extra cheese, toppings, and opting for takeaway. The application calculates and displays the final bill based on the user's choices.

## Features

- **Pizza Customization:** Add extra cheese and toppings to a pizza.
- **Takeaway Option:** Choose to have the pizza packed for takeaway.
- **Bill Calculation:** Automatically calculate the total bill based on customizations and takeaway options.
- **Deluxe Pizza:** A specialized pizza type with pre-added extra cheese and toppings.

## Classes and Methods

### `Pizza`
- **Attributes:**
  - `price`: Total price of the pizza.
  - `veg`: Indicates if the pizza is vegetarian.
  - `extra_cheese_price`, `extra_toppings_price`, `back_pack_price`: Prices for extra features and takeaway.
  - `base_pizza_price`, `is_extra_cheese_added`, `is_extra_toppings_added`, `is_opted_for_takeaway`: Various state indicators.

- **Methods:**
  - `add_extra_cheese()`: Adds extra cheese and updates the price.
  - `add_extra_toppings()`: Adds extra toppings and updates the price.
  - `take_away()`: Sets the takeaway option and updates the price.
  - `get_bill()`: Prints the detailed bill, including base price, extra charges, and total cost.

### `DeluxPizza` (extends `Pizza`)
- **Constructor:**
  - Automatically adds extra cheese and toppings upon creation.
- **Methods:**
  - Overrides `add_extra_cheese()` and `add_extra_toppings()` (no additional functionality in this example).

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/pizza-ordering-system.git
   cd pizza-ordering-system

# Using Hash Maps to Create a Car Order Tracker

## Introduction

Hash maps are a powerful data structure that can be used to store and retrieve key-value pairs efficiently. In this tutorial, we will use hash maps to create a car order tracker that can keep track of the orders for different car models.

## Implementation

We will implement the car order tracker using a hash map where the keys are the car models and the values are the number of orders for each model. We will provide functions to add orders, remove orders, and get the number of orders for a specific car model.

Define a hash map to store the car orders and a struct to represent a car model:

```rs
use std::collections::HashMap;
let mut orders: HashMap<i32, Car> = HashMap::new();
```


Insert a new order into the hash map:

```rs
car = car_factory(order, 1000);
orders.insert(order, car);
println!("Car order {}: {:?}", order, orders.get(&order));
```

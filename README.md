# Do you know any of those? can you explain?

Closures
Variable Hoisting
Truthy/Falsy
Callbacks
Promises
Async/Await
Block Scoping
“this” statement
Javascript event loop

# Create a simple product list component that:

Displays a list of products from provided mock data
Implements the CSS requirement: all items have a bottom border except the last item
Includes a simple text filter that filters products by name

# Technical Requirements

Use Vue 3 with Composition API and TypeScript
Create proper type definitions for the product data
Implement proper styling with CSS

Mock Data
´´
interface Product {
id: number;
name: string;
category: string;
price: number;
isAvailable: boolean;
}

const products: Product[] = [
{ id: 1, name: "Smartphone", category: "Electronics", price: 799.99, isAvailable: true },
{ id: 2, name: "Laptop", category: "Electronics", price: 1299.99, isAvailable: true },
{ id: 3, name: "Headphones", category: "Audio", price: 199.99, isAvailable: false },
{ id: 4, name: "Coffee Maker", category: "Kitchen", price: 89.99, isAvailable: true },
{ id: 5, name: "Smartwatch", category: "Wearables", price: 249.99, isAvailable: true }
];
´´

# Expected Functionality

Display all products in a list
Each product should show name, price, and availability status
Add a simple text input that filters the list as the user types
Apply styling where each item has a bottom border EXCEPT the last visible item

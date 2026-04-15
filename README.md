# Python-Super-Market-Billing-System
Smart Mart: Supermarket Billing Automation System

## Project Overview
This project involves the development of a Python-based retail automation system designed to streamline the checkout process for supermarkets. The system automates price calculations, applies dynamic discounts based on purchase volume, and generates professional, time-stamped digital receipts. It demonstrates the practical application of programming logic to reduce manual errors and improve operational efficiency in a retail environment.

## Repository Structure
<img width="640" height="245" alt="image" src="https://github.com/user-attachments/assets/6342ae8c-0b82-471e-8520-6a568993f0b4" />


## Technical Workflow
1. Project Logic & Data Architecture
Variable Management: Utilized specific data types—Strings for item names, Integers for quantities, and Floats for decimal pricing—to ensure high data accuracy during calculations.
Inventory Mapping: Implemented Python Dictionaries to create a searchable database of store inventory, allowing for quick price lookups.

2. Functional Requirements
Multi-Item Entry: Used while loops to allow continuous item input until the operator completes the transaction.
Dynamic Discounting: Integrated if-else conditional statements to apply a 10% bulk discount for total bills exceeding ₹2,000.
Date & Time Integration: Utilized the datetime module to capture the exact moment of transaction, ensuring every receipt is unique and audit-ready.

3. Output & Formatting
Professional Receipt Generation:
Used F-strings with fixed widths to ensure columns (Item, Qty, Price) remain perfectly aligned regardless of text length.
Applied .2f formatting to ensure all currency values display exactly two decimal places, matching standard banking formats.
Included a grand total and footer section enclosed in double-line borders for a professional look.

## Key Features
Automated Calculations: Instant calculation of Price * Quantity for every item in the cart.
Retail Automation: Reduces the need for manual price entry, minimizing human error during peak shopping hours.
User-Friendly Interface: A simple command-line interface that guides the user through the billing process.

## Final Deliverables
Python Project Script: The core logic handling the billing engine and receipt generation.
Project Presentation (PDF): A detailed walkthrough of the code structure, logic justifications, and the "why" behind specific programming choices.
Problem Statement: The original design requirements and project scope documentation.

## Tools & Concepts Used
Language: Python
Data Structures: Lists, Dictionaries
Modules: datetime
Programming Concepts: Loops, Conditional Logic, F-string Formatting, Arithmetic Operators

## Author

Divya Sharma
Email: divya649sharma99@gmail.com
GitHub: github.com/Divya9916
LinkedIn: www.linkedin.com/in/divya9916

## License
This project is open source and available under the MIT License.

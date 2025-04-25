# E-commerce Database Schema

This repository contains the SQL schema for an e-commerce platform database. The schema is designed to handle various aspects of an e-commerce system, including product management, categories, attributes, variations, and more.


## ERD (Entity-Relationship Diagram)


![Ecommerce ERD](https://github.com/user-attachments/assets/1271135b-0384-4186-b853-5c398de98cbd)





## Database Overview

The database is named `ecommerce` and consists of the following tables:

### Tables

1. **brand**
   - Stores brand-related information such as name, description, and logo URL.

2. **product_category**
   - Organizes products into categories, supporting hierarchical relationships with parent categories.

3. **product**
   - Contains general product details like name, brand, category, and base price.

4. **color**
   - Manages available color options with names and hex codes.

5. **size_category**
   - Groups sizes into categories (e.g., clothing sizes, shoe sizes).

6. **size_option**
   - Lists specific sizes within a size category (e.g., S, M, L, 42).

7. **product_variation**
   - Links products to their variations (e.g., size, color) and manages stock and pricing adjustments.

8. **product_image**
   - Stores product image URLs, alt text, and display order.

9. **attribute_category**
   - Groups attributes into categories (e.g., physical, technical).

10. **attribute_type**
    - Defines types of attributes (e.g., text, number, boolean).

11. **product_attribute**
    - Stores custom attributes for products, such as material or weight.

12. **product_item**
    - Represents purchasable items with specific variations, including SKU, barcode, and stock quantity.

### Relationships

- **Foreign Keys**: Relationships between tables are established using foreign keys to ensure data integrity.
- **Indexes**: Indexes are created on frequently queried columns to improve performance.

## Features

- **Hierarchical Categories**: Supports parent-child relationships in product categories.
- **Product Variations**: Handles variations like size and color with stock and pricing adjustments.
- **Custom Attributes**: Allows products to have custom attributes grouped by categories and types.
- **Image Management**: Supports multiple images per product with primary image designation and display order.

![ERD Diagram] (https://github.com/JoeMuchiri25/ecommerce-db/blob/d3466a3f48936c3bc384d6248c2f8e53438c9c83/Ecommerce_ERD%20Diagram.png)


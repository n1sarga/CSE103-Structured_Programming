# N.J.N Super Shop Management System
A simple, console-based Super Shop Management System built in C. This application allows both admins and users to interact with a shop's product inventory. Users can view available products, purchase items, and receive a receipt. Admins can log in to manage inventory, view product lists, add new products, and delete products.

## Features
### User Mode
- **View Products**: Displays available products and their details (code, name, quantity, and price).
- **Purchase Products**: Allows users to enter the product code and quantity to make a purchase.
- **Generate Receipt**: Generates a receipt showing the total price and buyer details.

### Admin Mode (requires login)
- **View All Products**: Displays the entire product inventory.
- **Add New Products**: Enables the addition of new products with specific details (code, name, quantity, and price).
- **Delete Products**: Allows deletion of products by specifying the line number in the inventory list.

### File Management
- **Product Data Storage**: Product data is stored in a text file (`Product.txt`) and is updated when products are added or deleted by the admin.

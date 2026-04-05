# Product Database Structure and Import Steps

## 1. Product Database Structure
The database for a clothing e-commerce store must be designed to accommodate various attributes that describe the products accurately. Below is a simplified structure:

- **Product ID**: Unique identifier for the product
- **Name**: The name of the product
- **Description**: Detailed information about the product
- **Price**: Sale price of the product
- **SKU**: Stock Keeping Unit, a unique code for inventory tracking
- **Category**: The category under which the product falls (e.g., shirts, pants)
- **Sub-Category**: More specific classification (e.g., men's, women's)
- **Stock Quantity**: Number of items available for sale
- **Image URL**: URL to the product image
- **Weight**: Weight of the product for shipping calculations

## 2. CSV Template for Product Upload
The following is a sample CSV template format for importing product data into WooCommerce:

| Product ID | Name          | Description        | Price | SKU     | Category | Sub-Category | Stock Quantity | Image URL                   | Weight |
|------------|---------------|---------------------|-------|---------|----------|--------------|----------------|-----------------------------|--------|
| 1          | T-Shirt       | Comfortable cotton T-shirt | 19.99 | TS-001  | Apparel  | Men's T-Shirts| 100            | http://example.com/images/tshirt.png | 0.2 kg |
| 2          | Jeans         | Stylish blue jeans  | 49.99 | J-002   | Apparel  | Men's Jeans  | 50             | http://example.com/images/jeans.png | 0.5 kg |

## 3. Steps to Import Products into WooCommerce
1. **Prepare Your CSV File**: Ensure your CSV file follows the structure outlined above.
2. **Log into WooCommerce Admin**: Access your WooCommerce dashboard.
3. **Go to Products**: Navigate to `Products` > `All Products`.
4. **Import Products**: Click on the `Import` button.
5. **Upload CSV File**: Select your prepared CSV file from your computer.
6. **Map CSV Columns**: Match the CSV columns with WooCommerce fields.
7. **Run the Importer**: Confirm to start the import process.
8. **Review Imported Products**: Store will notify you on the successful import. Check all products to verify the data.
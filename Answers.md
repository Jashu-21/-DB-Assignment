1.  **"Explain the relationship between the "Product" and "Product_Category" entities from the diagram given.**
A.The 'Product' and 'Product_Category' entities have a one-to-one relationship among them with 'category_id' in product table referencing the primary key 'id' columnin the 'Product_Category' entity.
2. **How could you ensure that each product in the "Product" table has a valid category assigned to it?**
A.We can ensure that each product in the "Product" table has a valid category assigned to it by using a referential integrity through the use of foreign key. We can create a 'foreign key' in Product table for 'category_id' column which references the "id" column in the "Product_Category" table


# Test task UBOS NODE-RED and MongoDB
## Endpoints: 
- /${'product'/'category'/'order'}/all - retrieve all data
- /${'product'/'category'/'order'}/${id} - retrieve a specific item by ID
- /${'product'/'category'/'order'}/new - create
- /${'product'/'category'/'order'}/delete - remove 
- /${'product'/'category'/'order'}/update  - update

- https://nodered-0432-66588390c61f751100000097.ubos.tech/total-quantity - Get the total quantity of products for each category
- https://nodered-0432-66588390c61f751100000097.ubos.tech/best-selling - Get the top 5 best-selling products based on order quantities
- https://nodered-0432-66588390c61f751100000097.ubos.tech/total-revenue - Get the total revenue generated from orders placed within a specific date range with params like startDate=2024-06-01, endDate=2024-06-05
- https://nodered-0432-66588390c61f751100000097.ubos.tech/low-stock-product - Get the list of products that have been ordered but have a quantity less than 10 in stock

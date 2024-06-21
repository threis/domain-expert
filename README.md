#Entities
    - Product
        - id
        - sku
        - description
        - stock
        - minimum_stock
               
    - Product Details
        - id
        - product_id
        - color
        - size

    - Stock
        - id
        - product_id
        - quantity
        - type (income / outcome)
        - reference_date
        - order_origin
        - purchase_origin

    - Notification
        - id
        - title
        - content
        - read_at

    - Orders
        - id
        - product_id
        - quantity
        - supplier_id
        - quantity
        - created_at

    - Purchase
        - id
        - product_id
        - quantity
        - supplier_id
        - quantity
        - delivery_at

    - Supplier
        - id
        - name
        - phone
        - email
    
#Use Cases
    - create product
    - update product
    - get product
    - create product details
    - fetch product list
    - send notification
    - read notification
    - fetch sales history
    - fetch profit by product
    - fetch best sales by product
    - fetch stock
    - create purchase
    - fetch purchase list
    - get purchase
    - create automatic purchase by minimium stock
    - create supplier
    - get supplier
    - fetch supplier list
    - update delivery time
    - create a order
    - fetch order list
    - get order
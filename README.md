# Time-Series-Forcasting

Objective
Assume that you have the following datasets:
• sales.csv, which is basically our train set.
    “customer_id”: customer identifier 
    “month”: period when sales happened 
    “material_id”: sold product identifier 
    “amount”: product quantity sold

• customer.csv, which contains more details about our customer 
    “customer_id”: customer identifier
    “size”: size of the customer (big, small, large, etc.,)
    “type”: type of the customer’s business (convenience store, bar, etc.,)
    
• products.csv, which contains more details about the portfolio of our products 
      “product_id”: sold product identifier
      “category”: category of our products (ProductA, ProductB, etc.,)
      
• test.csv, which is the dataset that we are trying to predict. 
      “customer_id”: customer identifier
      “month”: period when sales happened
      “category”: category of our products (ProductA, ProductB, etc.,) 
      “amount”: actual amount sold
      “baseline prediction”: results obtained from a model developed by another data scientist

      
**The purpose here is to help us develop a prediction model that enables us to predict the “test.csv” values as accurate as possible.**

# Sales Model - Revisited


## Coefficients Graph

![](Coeffs.png)

Top 3 Coefficients:

- Outlet_Size_High: That for every time the product is in High Outlet Size, the value shown will increase the Item Outlet Sale.

- Outlet_Size_Small: That for every time the product is in Small Outlet Size, the value shown will increase the Item Outlet Sale.


- Outlet_Size_Med: That for every time the product is in Med Outlet Size, the value shown will increase the Item Outlet Sale.

## Features Graph

![](DecTree.png)

Top 5 Features:

- Item MRP
- Outlet Type Grocery Store
- Item Visibility
- Outlet Type Supermarket Type3
- Item Weight

## SHAP Graph - Bar

![](ShapGraph.png)

- Comparsion vs Features Graph

    - The top 4 are all the same with just Item Visibility and Supermarket Type 3 switching places.
    
    - After that, it varies quite a bit with each one bringing different features for the last 6 spots

## SHAP Graph - Dot

![](ShapDot.png)

- Top 3 Features

    - Item MRP: This shows that a higher MRP will increase our target.
    
    - Outlet Type Grocery Store: This shows that being classified as a Grocery Store decrease our target.
    
    - Outlet Type Supermarket Type3: This shows that being classified as a Supermarket Type3 increase our target.


## Local Explanations

    - The first example I chose was with being classified at a Grocery Story with a MRP above the 75% while
    
![](LIME Example 1.png)

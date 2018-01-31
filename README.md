# EasyDatabase-Android
Easy Database Library is free to use for both commercial and non commercial use. This library is used to perform database operation with class and objects. for eg. I want to create an tables ‘Categories’ and ‘Products’ since one or more product can have same category we need an relationship here. Below code is to insert data only, read full tutorial for creating and manipulating the data.

VRDML  vrdml = new VRDML();
Category category = new Category();
category.setCategoryName("Dairy Products");
vrdml.insert(category);

Products product = new Products();
product.setCategory(category);
product.setProductName("Milk");
vrdml.insert(product);

Here VRDML class helps to store and retrieve data from database. With this Library you can handle tables with relationship in an easy and understandable code.

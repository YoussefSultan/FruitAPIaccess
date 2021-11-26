# FruitAPIaccess
This is a jupyter notebook that pulls data from a fruit RestAPI in JSON format to a pandas DataFrame format.

### Thanks to https://fruityvice.com for the API

The nutritions column is in a dictionary format for each row,\ 
![image](https://i.gyazo.com/152763195cfbdda11ea0db415f8116cc.png)
In order to turn those keys into columns with their respective data, we turn the entire column to a list, and turn that list into a data frame. We then join both dataframes by index and drop the original nutritions column to have our data fully preprocessed from the API ready for modeling or visualization.
![image](https://i.gyazo.com/616033c0f314cb1ae382237125b86347.png)


Clearly, we can see that Durian has more carbohydrates than Banana's. It is quite an interesting database of fruit that updates constantly and has fruits that I didn't even know about.
![image](https://user-images.githubusercontent.com/89711840/143513569-92edcd43-32a4-409f-9bcf-dcb5951259db.png)

Below we can see more insights on the in depth genus and family of the fruits that one could pull from the API.
![image](https://user-images.githubusercontent.com/89711840/143513605-78a8f116-78da-415a-b58d-200611a3a31d.png)
![image](https://user-images.githubusercontent.com/89711840/143513617-41207de8-2446-4925-bf43-69aff7eef9f0.png)





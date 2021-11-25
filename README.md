# FruitAPIaccess
This is a jupyter notebook that pulls data from a fruit RestAPI in JSON format to a pandas DataFrame format.

### Thanks to !(FruityVice)[https://fruityvice.com] for the API

The nutritions column is in a dictionary format for each row so in order to turn those keys columns with their respective data, we turn the entire column to a list, and turn that list into a data frame. Then we join both dataframes by index and drop the original nutritions column to have our data fully preprocessed from the API ready for modeling or visualization.

Clearly, we can see that Durian has more carbohydrates than Banana's. It is quite an interesting database of fruit that updates constantly and has fruits that I didn't even know about.

Below is some visualization of the final processed data.



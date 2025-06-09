`price`: Product price (float)

`quantity`: Initial quantity in stock (int)

**search product:**

`name`: Product name to search for (str)

**Update Product:**

`name`: Product name (str)
`newprice`: New price (float)

**Delete Products**

`name`: Product name (str)

## Output Data

**Product Information:**

`name`: Product name (str)
`price`: Product Price (float)
`in_stock_quantity`: Current quantity in stock (int)

**Error Notification:**

`error`: Error Message (str)

**Inventory Report:**

A list of `name`, `price`, and `in_stock`, respectively (str, float, int)

**Query Result:**

A `name` object if the product is found, or a message if it is not found. (str)

**Update Result:**

A `name` object if the product is found, a message that it has been deleted, or a message if it is not found. (str)
The new `price` of the product and a message that has been updated (float)

**Delete Result:**

A `name` object if the product is found, a message that it has been deleted, or a message if it is not found. (str)

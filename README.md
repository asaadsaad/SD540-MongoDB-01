### SD540-MongoDB-01
* Define what is [`ObjectId`](https://www.mongodb.com/docs/manual/reference/bson-types/#objectid) and what data it includes?
* How do we set a field to an `ObjectId` type in Mongoose?
* How do we generate a new `ObjectId` in Mongoose?

#### Coding Question
Create a new TypeScript project, and connect with a MongoDB instance using Mongoose. Define a schema for the provided [`data.json`](./data.json) structure, note the accepted `category` values are `vegetable` or `fruit` only, all fields are required, and the product `name` cannot be duplicate. Use [`dotenv`](https://www.npmjs.com/package/dotenv) to save the connection string as an environment variable.
* Write a function to read [`data.json`](./data.json) file and insert all the documents in the database (only run once to feed initial data).
* Write a function to add a new product.
* Write a function to delete a product by `_id`.
* Write a function to update a product properties by `_id`.
* Write a function to apply a discount of 10% across all fruits.
* Write a function to increase the vegetables price 50 cents.
* Write a function to find all products with a price between a range of minimum and maximum value.
* Write a function to find all products in a specific category.
* Write a function to find all products with an amount less than 10.
* Add a simple pagination to the last find query.
* All Mongoose Schemas are pluggable, they allow applying pre-packaged capabilities to extend their functionality. Plugins are a tool for reusing logic in multiple schemas. Install a [Mongoose paginate v2 plugin](https://www.npmjs.com/package/mongoose-paginate-v2) and replace your simple pagination with the one provided with the advanced plugin.

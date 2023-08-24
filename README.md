# Shopify Postman

As we move to Shopify Plus, we had to spend a time working on the full mapping of the Shopify API.
Unfortunately, our Account Manager said that there is no Postman Collection available for the ShopifyAPI Endpoints, so we did our own.

# How to use?

The Postman Collection file is a JSON containing all information about each request.
This Collection is using Postman Environment Variables, so all you have to do is create an Environment at your Postman and register the Postman variables, which are:

- apikey
- password
- yourstore
- token

To learn more about Postman variables: https://www.getpostman.com/docs/environments

Once you register the required variables for your store, you will be able to use the whole Collection.

# How to know what is my API Credentials?

In order to retrieve or create your private API Credentials, follow this link:
https://help.shopify.com/api/guides/api-credentials

# Missing Endpoints

- Checkout
- User
- UsageCharge
- Draft Order

# Collaboration

Feel free to contribute if you believe there is something missing.
Feli (@Feli87) 
# Authors

Lucas Santana (@lucasxxx)
Renato Alves (@renatodex)
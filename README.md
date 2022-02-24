# REST API Testing with Postman

This project is based on Test Automation University (TAU) course Exploring Service APIs through Test Automation, and expands on the examples shown. It uses Postman to create and execute the tests, and Restful Booker API as SUT.

There are three collections in this project:

- **Model Requests:** contains the model for all possible requests available through the Restful Booker API. They contain no tests, no scripts, and use no variables for data input; they exist simply for reference purposes.

- **CVS Data:** this collection validates an assortment of different data types as input for each of the mandatory fields in booking creation. They include different alphabets, numbers, special characters, and emojis, and load those values from the sample csv file in the project. As generic tests are used, when invalid inputs are submitted and therefore rejected, the tests will fail. As not a lot of data specification is provided, it serves as more of an exploratory than a validation test.

- **Smoke Testing:** Validates all the endpoits with both valid and invalid parameters, and are separated into operation collections (creation, retrieval, updating, and deletion), in addition to health check and authetication validations. Further details are provided on the collections descriptions when relevant.


## Resources

### Postman App (version 9.14.4 or above)
According to their own documentation, "Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster."
For more information visit https://www.postman.com/

### Restful Booker API
"An API playground created by Mark Winteringham for those wanting to learn more about API testing and tools", as they describe themselves.
A limited online version is available for immediate usage, and it is also possible to download it and run it locally for more controlled testing.
For more information visit https://restful-booker.herokuapp.com/

Our university project involves creating a Fawary-like system, and we have utilized several technologies for its development. We have chosen H2 Spring Boot DataBase to manage our data, and Intellij IDE for coding. The project is built using Java Version 17.

To ensure smooth functioning, we have implemented a feature that handles inappropriate requests. Whenever an inappropriate action is taken, the system will respond with a message stating that the action is unacceptable, or that no content has been found.

To run the application, we have initialized some data for the database so that manual input of data is not required. This data can be found in the config file, which uses command liner function. It's important to note that the admin user account is the one with the ID 1.

Our application works perfectly as per the requirements, except for the provider module, which may be a bit confusing. In this module, the user sends the provider ID, amount, and form, which are then handled by the provider. The provider then returns the required amount of money, and the user sends the amount back to the provider using their ID. This creates a payment transaction.

It's worth noting that any action that involves payment with a wallet may be rejected if there is insufficient funds. In such cases, the system will respond with a status code to indicate that the action cannot be completed. However, we have ensured that all exceptions are handled in a way that does not disrupt the application's flow.





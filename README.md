# An Public Library
The simple API application about an public library for nodejs workshop.

### Client side, features and end-point

- **Register**  
  `POST :httpAPIURL:/register`
  Register an user

- **Login services**  
  `POST :httpAPIURL:/login-services/confirm-email`  
  `POST :httpAPIURL:/login-services/forget-password`  
  Confirm email, Change password on forget

- **User services**  
  `GET :httpAPIURL:/users/me` Look profile self  
  `POST :httpAPIURL:/users/me/edit` Editing profile self  

- **List of books**  
  `GET :httpAPIURL:/api/books`  
  View list of books available on library

- **View an Book**  
  `GET :httpAPIURL:/api/books/:id`  
  View an Book detail, available to lone, rate book, and write review such as

- **Loan Book**  
  `POST :httpAPIURL:/api/books/lone`  
  Lone available Book or Books.

- **Return Book**  
  `POST :httpAPIURL:/api/books/return`  
  Return books or books


### Admin side, features

- **Login with Web**
- **Add Books**
- **View stats**

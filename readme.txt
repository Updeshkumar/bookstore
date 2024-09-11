# Online Bookstore API

## Setup
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run `python manage.py migrate` to set up the database.
4. Create a superuser using `python manage.py createsuperuser`.
5. Run the server using `python manage.py runserver`.

## Endpoints
1- `POST /api/register/`: Register a new user.
2- `POST /api/login/`: Log in and retrieve JWT token.
3- `GET /api/books/`: Retrieve a list of books.
4- `POST /api/books/`: Create a new book (requires authentication).
5- `GET /api/books/{id}/`: Retrieve details for a specific book.
6- `PUT /api/books/{id}/`: Update a book (requires authentication).
7- `DELETE /api/books/{id}/`: Delete a book (requires authentication).

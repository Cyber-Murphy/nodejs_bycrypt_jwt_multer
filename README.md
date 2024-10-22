# File Upload with User Authentication using Multer, Bcrypt, and JWT

This project implements user registration, login, and file upload functionality. It uses `bcrypt` for password hashing and `jsonwebtoken` (JWT) for token-based authentication. After creating an account and logging in, users can upload files securely to the server.

## Features

- **User Registration**: Users can create an account with secure password hashing using `bcrypt`.
- **User Login**: Secure login with JWT for authentication.
- **Protected File Upload**: Only authenticated users can upload files.
- **File Storage**: Uploaded files are saved in `./public/images/uploads`.
- **Unique Filenames**: Files are saved with a unique, randomly generated name using `crypto`.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>

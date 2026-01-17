# Authentication API (Django + DRF + JWT)

Backend API с регистрацией и авторизацией через JWT.
Сделано как портфолио-проект: документация Swagger, чистая структура, тесты.

## Features
- Register (password + password2)
- Login by email + password
- JWT refresh/access
- Protected profile endpoint (/me)
- Swagger docs

## Tech Stack
- Python, Django
- Django REST Framework
- SimpleJWT
- drf-spectacular (Swagger)

## Endpoints
- POST /api/auth/register/
- POST /api/auth/login/
- POST /api/auth/refresh/
- GET  /api/auth/me/

## Setup
```bash
git clone <https://github.com/aabdusalomoff/auth-api.git>
cd auth_api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

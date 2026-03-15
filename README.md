# Django Modular Entity Mapping API

This project is developed as part of a Django Internship Assignment.

It implements a modular Django REST Framework backend where each entity and mapping is handled through separate apps.

## Technologies Used

- Django
- Django REST Framework
- APIView
- drf-yasg (Swagger Documentation)

## Project Structure

Master Apps
- vendor
- product
- course
- certification

Mapping Apps
- vendor_product_mapping
- product_course_mapping
- course_certification_mapping

## Features

- CRUD APIs for all entities
- Modular Django app structure
- APIView based implementation
- Mapping validation
- Swagger API documentation
- Query parameter filtering

## Setup Instructions

Install dependencies
pip install django djangorestframework drf-yasg

Run migrations
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

## API Documentation

Swagger
http://127.0.0.1:8000/swagger/
http://127.0.0.1:8000/redoc/

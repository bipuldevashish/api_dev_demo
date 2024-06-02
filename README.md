# api_dev_demo

# Python API Development Demo

This repository contains a demo project created while learning API development with Python. The project includes basic setup, routes, and functionality to demonstrate the fundamentals of building an API.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This demo project was developed as part of a learning exercise to understand API development using Python. The project uses [FastAPI](https://fastapi.tiangolo.com/) to create and manage API endpoints. FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.

## Features

- Basic API setup using FastAPI
- CRUD (Create, Read, Update, Delete) operations
- Error handling
- Data validation with Pydantic models
- Interactive API documentation with Swagger UI and ReDoc

## Installation

To get started with this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/python-api-development-demo.git
    cd python-api-development-demo
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the API server, use the following command:

```bash
uvicorn main:app --reload

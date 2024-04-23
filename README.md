

# Nestjs-Microservices

This project is build by microservices. This project implements auth/register and viewing courses which separated on free and payment courses.

# Installing Server

## Prerequisites

Before you begin, ensure you have Node.js version 18.16.0 or later installed on your machine.

## Getting Started

To get started with the project server, you need to install all dependencies:
  ```bash
  npm i
  ```

## Environment Configuration

The repository includes an `example.<app_name>.env` file. You should create the following environment files which located at `envs/`:

- `.account.env`: Default environment for account microservice
- `.api.env`: Default environment for api microservice

You can use the `example.<app_name>.env` files as a template.


PORT - Integer: Port for running server

## Running the Application

To run the application, use the following commands:

  ```bash
  nx run account:serve
  ```
  
  ```bash
  nx run api:serve
  ```
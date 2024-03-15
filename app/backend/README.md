# Backend

This directory contains the backend code for the Chat App.

## Structure

The backend is built using [Quart](https://quart.palletsprojects.com/), a Python framework for asynchronous web applications. The backend code communicates with the frontend using the [AI Chat App HTTP Protocol](https://github.com/Azure-Samples/ai-chat-app-protocol).

The main components of the backend are:

- `approaches`: This folder contains the classes powering the Chat and Ask tabs. Each class uses a different RAG (Retrieval Augmented Generation) approach.

- `main.py`: This is the main entry point for the backend application.

## Running the Backend Locally

To run the backend locally, follow the steps outlined in the [Local development guide](../../docs/localdev.md).

## Customizing the Backend

For more details on how to customize the backend, refer to the [Customization guide](../../docs/customization.md).

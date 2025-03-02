# Kubernetes Demo App with MongoDB and WebApp

This is a simple demo project to deploy a web application with MongoDB using **Kubernetes**. The project consists of four main components:

- **MongoDB Deployment**: A MongoDB database instance deployed in a Kubernetes cluster.
- **MongoDB Service**: A service to expose the MongoDB database to other components.
- **WebApp Deployment**: A web application that interacts with MongoDB.
- **WebApp Service**: A service to expose the web application to external traffic.

This project uses YAML files to define the Kubernetes resources needed for the deployment.

## Project Structure

```bash
├── mongo-config.yaml
├── mongo-secret.yaml
├── mongo.yaml
├── webapp.yaml
└── README.md


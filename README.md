# ShopEngine

**ShopEngine** is a modern, open-source e-commerce platform built with **ASP.NET** and designed using a **microservice architecture**. The platform uses **Angular** for a responsive, dynamic frontend, and **Docker** for easy deployment and scalability.

## Features

- **Microservice Architecture**: Scalable and modular, making it easier to maintain and expand.
- **Responsive UI**: Built with Angular for an intuitive and interactive user experience.
- **Dockerized**: Uses Docker containers for consistent and easy deployment.
- **Extensible**: Easily customizable and ready for integrations.
- **RESTful APIs**: Simplifies communication between services and allows integration with third-party systems.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Node.js](https://nodejs.org/) (for Angular)
- [Docker](https://www.docker.com/get-started)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/behdadn77/shopengine.git
    cd shopengine
    ```

2. **Install backend dependencies**:
    ```bash
    cd src/ShopEngine.API
    dotnet restore
    ```

3. **Install frontend dependencies**:
    ```bash
    cd src/ShopEngine.UI
    npm install
    ```

4. **Run the services using Docker**:
    ```bash
    docker-compose up
    ```

5. **Access the application**:
    Open your browser and navigate to `http://localhost:5000`.

### Running Locally without Docker

To run the services without Docker:

1. **Run the backend**:
    ```bash
    cd src/ShopEngine.API
    dotnet run
    ```

2. **Run the frontend**:
    ```bash
    cd src/ShopEngine.UI
    ng serve --open
    ```

3. Open your browser and navigate to `http://localhost:4200`.

## Usage

Once the platform is running, you can:

- **Create and manage products**: Add, edit, and remove products from the catalog.
- **Manage orders**: Track, process, and fulfill customer orders.
- **User authentication**: Register, login, and manage user profiles.
- **Payment integration**: (Upcoming feature)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions, feel free to reach out to the repository owner at [behdad.nemati@hotmail.com](mailto:behdad.nemati@hotmail.com).

You can also find me on GitHub at [behdadn77](https://github.com/behdadn77).

---

**ShopEngine** is an ongoing project aimed at providing a flexible and scalable e-commerce platform. We welcome feedback and contributions from the community to help improve it further!

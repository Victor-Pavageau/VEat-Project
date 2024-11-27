# VEat

VEat is a platform for food ordering and delivery, supporting multiple user roles and leveraging a microservices architecture.

## Table of Contents

1. [About](#about)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Status](#status)

## About

This project is a TypeScript implementation of a distributed food ordering and delivery platform called VEat. The platform aims to provide an online service for restaurant offers, similar to "Uber Eats" or "Deliveroo." It supports multiple user types, including end-users, restaurateurs, drivers, third-party developers, commercial services, and technical teams. VEat enables users to perform various actions, such as placing orders, managing restaurant menus, and facilitating deliveries. The platform is structured as a collection of applications communicating through APIs, adhering to a microservices architecture.

VEat consists of the following submodules:

- VEat-Client: The main application for end-users to browse restaurants and place orders.
- VEat-Driver: A dedicated application for delivery personnel.
- VEat-External-Package: Tools for third-party developers to integrate with the platform.
- VEat-Microservices: Core services ensuring functionality and communication between components.
- VEat-Restaurant: An interface for restaurateurs to manage their offerings.

This project was undertaken during my fourth year of engineering studies (Bac+4 in the French education system) as part of a school assignment. I worked in a group of four, which provided an excellent opportunity to enhance teamwork skills and gain practical experience in designing, developing, deploying, testing, and using a distributed software platform. My primary contributions included leveraging React and TypeScript for front-end development, implementing microservices architecture, and ensuring seamless API interactions.

## Installation

To install and run VEat, follow these steps:

1. **Clone the repositories**:

```bash
git clone https://github.com/Victor-Pavageau/VEat-Client.git
git clone https://github.com/Victor-Pavageau/VEat-Driver.git
git clone https://github.com/Victor-Pavageau/VEat-Restaurant.git
git clone https://github.com/Victor-Pavageau/VEat-Microservices.git
```

2. **Navigate to the project directories, install the required dependencies, and start the applications**:

```bash
cd VEat-Client
yarn install
yarn start
```

```bash
cd VEat-Driver
yarn install
yarn start
```

```bash
cd VEat-Restaurant
yarn install
yarn start
```

```bash
cd VEat-Microservices
yarn install
yarn start
```

## Status

**Development**: The development of this project was completed in July 2023.

**Maintenance**: This project is no longer maintained.

**Future updates**: No future updates are planned for this project.

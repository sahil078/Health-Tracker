# Health Challenge Tracker

Health Challenge Tracker is a single-page application built with Angular 14+ that allows users to track their workout routines. The application includes features such as user input for workout type and duration, search and filter functionalities, pagination, and optional progress visualization using charts. The project is styled using Tailwind CSS and is hosted on a cloud service. Unit tests are included with 100% code coverage for one component and one service.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Running Tests](#running-tests)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- User authentication and management
- Input workout details (type and duration)
- Display user workout list
- Search by name
- Filter by workout type
- Pagination for workout list
- Visualize workout progress using charts (optional)
- Hosted on a cloud service
- 100% unit test coverage for one component and one service

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- [Node.js](https://nodejs.org/) (version 18.19.1 recommended)
- [Angular CLI](https://angular.io/cli)
- [npm](https://www.npmjs.com/)

### Installation
Installation
Clone the repository:
git clone https://github.com/your-username/health-challenge-tracker.git
cd health-challenge-tracker

Install the dependencies:
npm install

Running the Application
To start the development server, run:
ng serve --open

This will compile the project and open it in your default web browser at http://localhost:4200.

Building for Production
To build the application for production, use:
ng build --configuration production

The compiled files will be located in the dist/health-challenge-tracker directory.


Usage
Log a Workout: Users can log their workout details, including the type of workout and duration.
Search and Filter: Use the search bar to find workouts by user name or apply filters to narrow down by workout type.
Visualize Progress: View charts to see the progress of workouts over time.
Unit Testing


Unit tests are provided for one component and one service. To run the tests, use:
ng test

Acknowledgments
Angular
Tailwind CSS
Chart.js

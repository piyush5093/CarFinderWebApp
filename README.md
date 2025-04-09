# Car Showcase NextJS App

The Car Showcase NextJS App is a web application built using Next.js, TypeScript, and Tailwind CSS to showcase different car models, provide information about them, and display their rental prices. This project also uses an API from Rapid API to fetch data about car models and their rental prices.

# Screenshot

![Car Showcase NextJS App](https://github.com/krishnashah122/Car-Showcase-NextJS-App/assets/64410232/db70c26e-ea71-41d1-855a-1ef1c4607522)

## Features

- View a list of car models with images.
- Click on a car model to view detailed information about it.
- See the rental price for each car model.
- Search for specific car models.
- Responsive design for mobile and desktop devices.


## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/Car-Showcase-NextJS-App.git
    ````

2. Install dependencies:
    ````bash
    cd Car-Showcase-NextJS-App
    npm install
    ````

3. Set up Rapid API:
    - Sign up for a Rapid API account and create a new project.
    - Obtain your API key from Rapid API.
    - Obtain your API key for Cars images from Imagin Studio (https://www.imagin.studio/car-image-api).
    - Create a .env file in the root directory of the project and add your API key like this:
    ````bash
    NEXT_PUBLIC_RAPIDAPI_KEY=Your RapidAPI Key
    NEXT_PUBLIC_RAPIDAPI_HOST=RapidAPI Host
    NEXT_PUBLIC_IMAGE_API=Your Imagin Studio API Key
    ````

4. Start the development server:
    ````bash
    npm run dev
    ````

5. Open your web browser and navigate to http://localhost:3000 to see the app running locally.


## API Usage
This project uses the Rapid API to fetch car model data and rental prices and API from Imagin Studio to get Cars images. You can customize the API endpoints and data by modifying the code in the pages/api/cars.ts file.


## Technologies Used
- Next.js
- TypeScript
- Tailwind CSS
- Rapid API & Imagin Studio API
- Headless UI




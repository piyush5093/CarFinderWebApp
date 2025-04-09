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


## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or create a pull request.


## Acknowledgments
- Thanks to Rapid API for providing the car model data and rental price API and Imagin Studio for providing the car images API.
- Special thanks to the Next.js, TypeScript, and Tailwind CSS communities for their excellent documentation and support.


## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

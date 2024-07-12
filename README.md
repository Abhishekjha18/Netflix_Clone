# Netflix Clone with ML-Powered Recommendations

## Project Overview

This project is a full-stack Netflix clone featuring a machine learning-powered recommendation system. It replicates core Netflix functionalities while showcasing modern web development techniques and practical application of ML algorithms.

## Key Features

- User authentication and profile management
- Responsive, Netflix-inspired UI
- Video streaming capabilities
- Content library with categorization and search
- Personalized movie and TV show recommendations using ML
- Watchlist and "Continue Watching" functionality

## Tech Stack

- **Frontend:** React, Next.js, Tailwind CSS
- **Backend:** Next.js API routes
- **Database:** MongoDB with Prisma ORM
- **Authentication:** NextAuth
- **Machine Learning:** TensorFlow.js (integrated in Next.js backend)
- **Deployment:** Vercel

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables (see `.env.example`)
4. Run the development server: `npm run dev`
5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Architecture

The application follows a modern fullstack architecture:
- Next.js handles both frontend and backend, allowing for server-side rendering and API routes
- Prisma provides a type-safe database interface
- MongoDB stores user data, content metadata, and ML model data
- TensorFlow.js powers the recommendation system, running on the server

## Machine Learning Model

Our recommendation system uses collaborative filtering and content-based approaches to provide personalized suggestions. It analyzes user viewing history, ratings, and content metadata to generate accurate recommendations.

## Deployment

This application is deployed on Vercel, ensuring fast performance and easy updates.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Netflix for inspiration
- Vercel for their excellent deployment platform
- The open-source community for the amazing tools and libraries

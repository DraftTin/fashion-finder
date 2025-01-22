# Fashion Finder

Fashion Finder is a web application designed to provide personalized recommendations for everyday dressing. 
Built during a hackathon at uOttawa, the project utilizes **Gadget AI** to assist in the implementation process 
and React for the frontend. The application features **hand-drawn illustrations**, giving it a unique and artistic touch.

## Features

- **AI-Driven Recommendations**: Tailored outfit suggestions based on preferences, mood, and selected colors.
- **Hand-Drawn Illustrations**: All visuals are custom-made, adding a personal and creative flair to the user experience.
- **Interactive UI**: Intuitive and responsive user interface built with React and Tailwind CSS.
- **Hackathon Innovation**: Developed during a collaborative hackathon at uOttawa.

## Tech Stack

- **Frontend**: React, Tailwind CSS, Radix UI
- **AI Assistance**: Gadget AI
- **Build Tools**: TypeScript, Vite

## Project Structure

```plaintext
fashion-finder-main
├── accessControl          # Access control and user management
├── api                    # API logic and definitions
├── web                    # Frontend application
│   ├── components         # Reusable React components
│   ├── lib                # Utility functions and modules
│   ├── public             # Static assets (images, fonts, etc.)
│   ├── routes             # Application routing and pages
│   ├── root.tsx           # Main entry point for the React app
│   └── app.css            # Global styles
├── package.json           # Project dependencies and scripts
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
├── vite.config.mts        # Vite configuration
└── yarn.lock              # Dependency lockfile
```

## User Interface
### Login
![Login](/screenshots/Login.png)
### Home Page
![HomePage](/screenshots/HomePage.png)
### Wardrobe
![Wardrobe](/screenshots/Wardrobe.png)
### Recommendations
![Recommendations](/screenshots/GetRecommendation.png)
### Add clothes to Wardrobe
![AddClothes](/screenshots/SelectClothes.png)

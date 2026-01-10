🎬 Blazor Movie App
Blazor Movie App is a modern Single Page Application (SPA) built with Blazor WebAssembly and .NET 8. The application explores the cinematic universe using real-time data from The Movie Database (TMDB) API.

🚀 Key Features
Movie Exploration: Browse the most popular and recent movies in a clean and intuitive interface.

Responsive Design: Built with Bootstrap 5, ensuring a fluid experience across desktop, tablet, and mobile devices.

Dynamic Pagination: Efficiently navigate through thousands of titles with an optimized pagination system.

Modern Visual Effects: Integrated "Tilt" animations for movie cards and "Skeleton Placeholder" effects for data loading states.

Detailed Insights: Dedicated pages for each movie, including synopsis, ratings, genres, and external links to IMDb or official websites.

🛠️ Tech Stack
Frontend: Blazor WebAssembly (.NET 8)

Styling: Bootstrap 5 & Custom CSS

Data Source: TMDB API

JS Interop: Used for external graphical libraries (Vanilla Tilt).

Icons: Bootstrap Icons & Devicons

⚙️ Installation & Setup
Clone the repository:

Bash

git clone https://github.com/your-username/BlazorMovie.git
Get an API Key: Create a free account on TMDB to generate your API key.

Configuration: Add your API key to the appsettings.json file:

JSON

{
  "TMDBApiKey": "YOUR_API_KEY_HERE"
}
Run the application:

Bash

dotnet watch run

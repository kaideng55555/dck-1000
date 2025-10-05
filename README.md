# DCK-1000

A simple, deployment-ready Node.js web application.

## Features

- Express.js web server
- Static file serving
- Health check endpoint
- Production-ready configuration
- Environment variable support

## Local Development

### Prerequisites

- Node.js (v14 or higher)
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kaideng55555/dck-1000.git
cd dck-1000
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Deployment

### Heroku

1. Create a Heroku app:
```bash
heroku create your-app-name
```

2. Deploy:
```bash
git push heroku main
```

### Vercel

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Deploy:
```bash
vercel
```

### Other Platforms

This application can be deployed to any platform that supports Node.js applications, such as:
- AWS Elastic Beanstalk
- Google Cloud Platform
- Azure App Service
- DigitalOcean App Platform
- Railway
- Render

## Environment Variables

- `PORT` - The port the server will listen on (default: 3000)

## API Endpoints

- `GET /` - Serves the main application
- `GET /health` - Health check endpoint (returns JSON status)

## Project Structure

```
dck-1000/
├── public/           # Static files
│   └── index.html   # Main HTML page
├── server.js        # Express server
├── package.json     # Dependencies and scripts
├── .gitignore       # Git ignore file
└── README.md        # This file
```

## License

MIT

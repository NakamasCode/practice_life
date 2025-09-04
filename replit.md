# Practice Life - Flask Web Application

## Overview
A Flask web application for practicing web development skills. This project has been successfully configured to run in the Replit environment.

## Project Architecture
- **Language**: Python 3.11
- **Framework**: Flask 3.0.0
- **Template Engine**: Jinja2
- **Development Server**: Configured for 0.0.0.0:5000 (Replit compatible)

## Project Structure
```
practice_life/
├── main.py                 # Main Flask application
├── requirements.txt        # Python dependencies
├── templates/              # HTML templates
│   ├── base.html          # Base template with navigation
│   ├── index.html         # Homepage
│   └── about.html         # About page
├── .replit                # Replit configuration
├── .gitignore             # Git ignore file (Python focused)
├── README.md              # Project description
└── replit.md              # This documentation file
```

## Recent Changes (September 4, 2025)
- Set up complete Flask application structure
- Installed Python 3.11 and Flask 3.0.0
- Created responsive HTML templates with navigation
- Configured Flask server for Replit environment (0.0.0.0:5000)
- Set up Flask Server workflow
- Configured autoscale deployment

## Features
- Basic Flask routing (/ and /about routes)
- Template inheritance with Jinja2
- Responsive CSS design
- Navigation between pages
- Debug mode enabled for development

## Development
The application runs automatically via the Flask Server workflow on port 5000. The server is configured to accept connections from all hosts, making it compatible with Replit's proxy system.

## Deployment
Configured for autoscale deployment, suitable for this stateless web application.
# Image Generator Project using DALL-E API


## Overview

Welcome to the Image Generator Project, an exploration of the DALL-E API's capabilities for image generation. This repository is structured as a monorepo with two primary directories: `client` and `server`. The project's main purpose is to serve as a testing ground for interfacing with the DALL-E API to produce images from textual descriptions.

## Table of Contents

- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Running the Project](#running-the-project)
- [Usage](#usage)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [License](#license)

## How It Works

The project consists of two main components:

1. **Client**: The `client` directory contains the frontend of the application. Users can input textual descriptions of the images they wish to generate. The client then sends these descriptions to the server.

2. **Server**: The `server` directory contains the backend of the application. The server receives the textual descriptions from the client and communicates with the DALL-E API to generate images based on the descriptions. The generated images are then sent back to the client for display.

## Project Structure

The repository structure is as follows:
      
      image-generator-project/
      ├── client/
      │ ├── ... (client-related files)
      ├── server/
      │ ├── ... (server-related files)
      ├── LICENSE
      └── README.md


## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)
- DALL-E API Key (acquire from the DALL-E API provider)

### Installation

1. Clone the repository:
   git clone https://github.com/your-username/image-generator-project.git
   cd image-generator-project
2. Install dependencies for both the client and server:

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install

### Running Dev 
cd ../client
npm run dev

# AI Image Generator

This project is a simple web application that utilizes the OpenAI API to generate images based on user-provided text descriptions. Users can describe what they want to see, and the application will return a generated image based on that description.

## Features

- User-friendly interface for easy interaction.
- Real-time image generation using the OpenAI API.
- Default image display while loading new images.
- Responsive design for various screen sizes.

## Requirements

- [Node.js](https://nodejs.org/) (preferably version 14 or higher)
- [npm](https://www.npmjs.com/) (included with Node.js)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/REPO_NAME.git

2. Navigate to the project directory:

       cd REPO_NAME

3. Install dependencies:

       =npm install

## Usage

1.Start the application:


    npm start
 
2. Open your web browser and navigate to http://localhost:3000.

3.Enter a description of what you want to see in the input field and click the "Generate" button.

4.The application will display the generated image based on your description.


## How It Works
- The application sends a POST request to the OpenAI API endpoint with the provided description.
- It processes the response and updates the UI with the generated image.
- Error handling is implemented to manage issues such as invalid API keys or network errors.

  
## Technologies Used
- React: For building the user interface.
- OpenAI API: For image generation.
- CSS: For styling the application.

  
## Screenshots

![Image]()

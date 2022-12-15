# DALL-E Image Generator
This Node.js app uses the OpenAI JavaScript client library to generate images from text using the DALL-E model.

### Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Node.js
npm (comes with Node.js)
Installation
Clone the repository:

Copy code
`git clone https://github.com/<your-username>/dalle-image-generator.git`
Install the dependencies:

Copy code
`cd dalle-image-generator
npm install`
Set your OpenAI API key:

Copy code
`export OPENAI_API_KEY=<your-api-key>`
Usage
To generate an image from text, run the following command:

Copy code
`node index.js "<your-prompt>"`
For example:

Copy code
`node index.js "Generate a picture of a dog"`
This will generate an image and print the URL to the console.

License
This project is licensed under the MIT License - see the LICENSE file for details.
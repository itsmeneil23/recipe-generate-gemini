# recipe-generate

## Introduction
The `recipe-generate-gemini` project is a web application that allows users to generate custom recipe tutorials based on the ingredients they have available. The application uses the Gemini API to generate the content.

## Features
- Generate custom recipe tutorials based on available ingredients
- Copy the generated recipe to clipboard
- User-friendly interface

## Installation
To install and run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/itsmeneil23/recipe-generate-gemini.git
   cd recipe-generate-gemini
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the Gemini API key:
   ```bash
   export GEMINI_API_KEY="your_api_key_here"
   ```

5. Run the application:
   ```bash
   python api/main.py
   ```

## Usage
1. Open your web browser and navigate to `http://localhost:8080`.
2. Enter the list of ingredients you have available in the input field.
3. Click the "Share with me a tutorial" button to generate a custom recipe tutorial.
4. Copy the generated recipe to clipboard using the "Copy" button.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features to add.

## Vercel Domain
The application is also deployed on Vercel and can be accessed at [recipe-generate-gemini.vercel.app](https://recipe-generate-gemini.vercel.app).

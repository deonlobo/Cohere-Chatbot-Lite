# Cohere-Chatbot-Lite

Cohere-Chatbot-Lite is a simple Flask web application that utilizes the Cohere API to generate text based on user prompts. With this application, users can input text prompts and receive AI-generated responses.

## Features

- **Text Generation**: Users can input text prompts and receive AI-generated responses.
- **Customizable Settings**: The application allows users to adjust parameters such as temperature and max tokens for text generation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/Cohere-Chatbot-Lite.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Cohere-Chatbot-Lite
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Flask application:

   ```bash
   python app.py
   ```

2. Open your web browser and navigate to `http://localhost:5000` to access the application.

3. Enter a text prompt in the provided input field and click the "Submit" button to generate a response.

## Customization

You can customize the behavior of the chatbot by adjusting the parameters in the `app.py` file:

- `model`: The model to use for text generation.
- `max_tokens`: The maximum number of tokens to generate in the response.
- `temperature`: Controls the randomness of the generated text.
- `k` and `p`: Additional parameters for controlling text generation.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new pull request.

## Screen Shot

![Cohere-Chatbot-Lite SS](/picture.png)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

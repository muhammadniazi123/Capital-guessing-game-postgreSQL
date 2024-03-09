# Capital City Quiz

Test your knowledge of world capitals with this interactive quiz web application! Guess the capital city of each country and see how many you can get correct.

## Features

- Randomly selects a country and asks for its capital.
- Keeps track of the total score as you progress through the quiz.
- Provides feedback on whether your answer was correct or incorrect.
- Allows you to restart the quiz at any time.

## Prerequisites

Before running the application, make sure you have the following installed on your system:

- Node.js
- PostgreSQL

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/capital-city-quiz.git
   ```

2. Navigate to the project directory:

   ```bash
   cd capital-city-quiz
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up the PostgreSQL database:

   - Create a database named `world`.
   - Populate the database with a table named `capital` containing columns `country` and `capital`.
   - Add records for each country and its corresponding capital.

5. Start the server:

   ```bash
   npm start
   ```

6. Open your web browser and visit `http://localhost:3000` to access the application.

## Usage

- Enter the capital city of the displayed country in the input field.
- Click the "SUBMIT" button to check your answer.
- If your answer is correct, the total score will increase.
- If your answer is incorrect, the correct capital city will be displayed, and the total score will remain the same.
- The quiz will automatically move on to the next question.
- To restart the quiz, click the "Restart" button.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License
```

Replace `your-username` in the clone URL with your actual GitHub username, and update any other placeholders or sections as needed.

# Simple EJS Web App

This is a simple web application built using Express.js and EJS to create and manage text files.

## Features

- Allows users to create text files with custom titles and details.
- Lists all existing text files on the home page.
- Each text file can be accessed individually.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/iam-neo/EJS-Task-Manager.git
```

2. Navigate into the project directory:

```bash
cd ejs-task-manager
```

3. Install dependencies:
```bash
npm install
npm i ejs
npm i -g nodemon
```

## Usage

1. Run the application:

```
npx nodemon index.js
```

2. Open your web browser and go to [http://localhost:3000](http://localhost:3000).

3. To create a new text file:
   - Enter a title and details in the provided input fields.
   - Click the "Create" button.

4. To view existing text files:
   - Navigate to the home page ([http://localhost:3000](http://localhost:3000)).
   - Existing files will be listed with their titles.

## Project Structure

```bash
├── public # Static assets (CSS, JS, images)
│ └── styles.css # Stylesheet file
├── views # EJS templates
│ └── index.ejs # Home page template
├── files # Directory to store text files
│ ├── example1.txt # Example text file 1
│ └── example2.txt # Example text file 2
├── index.js # Main server file
├── package.json # Project dependencies and scripts
└── README.md # Project documentation
```

## Dependencies

- Express.js: Fast, unopinionated, minimalist web framework for Node.js.
- EJS: Embedded JavaScript templating.
- fs-extra: A module that extends the `fs` module with extra methods.
- path: A module that provides utilities for working with file and directory paths.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

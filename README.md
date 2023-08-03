# README.md Generator

The ReadMe Generator is a command-line application designed to streamline the process of creating a professional and high-quality README.md file for your GitHub projects. It uses Node.js and the inquirer package to prompt the user for project-related information and generates a README.md file based on the provided data.

## How to Use

1. Clone the repository: 

  :git clone https://github.com/keybit-1/Readme.md-Generator.git


2. Navigate to the project directory:

  :cd readme-generator

3. Install the required packages:

  :npm install


4. Run the application:

  :node index.js


5. The application will start prompting you for information related to your project. Answer each question as per your project details.

6. Once you've answered all the questions, the application will generate a README.md file based on your input and save it in the root directory of the project as `README.md`.

7. Here is a quick video demostrating this application: https://youtu.be/jTwTdnW0otw

## User Input

The application will prompt you to provide the following information for your project:

1. **Project Title**: Enter the title of your project.

2. **Description**: Provide a brief description of your project.

3. **Installation Instructions**: Describe the steps needed to install and set up your project.

4. **Usage Information**: Explain how to use your application or library.

5. **Contribution Guidelines**: Specify the guidelines for others who want to contribute to your project.

6. **Test Instructions**: Describe the instructions to run tests for your project.

7. **License**: Choose a license for your project from the provided options: MIT, Apache, GNU, or None.

8. **GitHub Username**: Provide your GitHub username.

9. **Email Address**: Enter your email address for contact purposes.

## Generated README.md

The generated README.md will be formatted with Markdown to provide a professional and organized look. It will include the project title, description, table of contents with clickable links, installation instructions, usage information, license badge, contribution guidelines, test instructions, and contact information.

## Customization

If you want to make any changes to the application or modify the generated README.md template, you can do so by modifying the `index.js` file. Customize the questions array and the `writeToFile` function as needed to suit your project requirements.

## License

This project is licensed under the [MIT License](LICENSE).

## About the Author

This README.md was generated using the ReadMe Generator application. If you have any questions or need assistance, you can contact the author:

- GitHub: [keybit-1](https://github.com/keybit-1)
- Email: Jmontano.8702@gmail.com

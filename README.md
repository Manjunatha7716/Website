# My Fantasy Website

Welcome to the **My Fantasy Website** project! This is a simple static website built with HTML and CSS. The project is designed for learning purposes, showcasing the basics of web design and how to set up a CI/CD pipeline using GitHub Actions.

## Project Features

- A static, responsive website built with HTML and CSS.
- Simple design with a fantasy theme.
- Organized code structure for easy understanding.
  
## Technologies Used

- **HTML**: Markup language used to structure the website content.
- **CSS**: Styling language used to make the website visually appealing.
  
## Project Structure

The project is organized as follows:

```
my-fantasy-website/
│
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
├── .github/
│   └── workflows/
│       └── ci-cd.yml   # CI/CD configuration file for GitHub Actions
└── README.md           # Project documentation
```

## How to Run Locally

To run the website locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Manjunatha7716/Website.git
   ```

2. **Navigate into the project directory**:
   ```bash
   cd my-fantasy-website
   ```

3. **Open the `index.html` file** in a browser to view the website.

## CI/CD Pipeline

This project includes a Continuous Integration and Continuous Deployment (CI/CD) pipeline using **GitHub Actions**. The pipeline automatically tests and deploys the application whenever changes are made to the repository.

### Key Features of the CI/CD Pipeline

- **Continuous Integration**:
  - Linting and code quality checks are automatically triggered on every commit or pull request.
  
- **Continuous Deployment**:
  - The application is automatically deployed to [Heroku/AWS/Digital Ocean] when changes are pushed to the `main` branch.

## How to Trigger the CI/CD Pipeline

1. **Make a change** to the codebase.
2. **Push the change** to GitHub:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

3. The pipeline will automatically run based on the configuration in the `.github/workflows/ci-cd.yml` file.

## Challenges Faced and Solutions

- **Setting up CI/CD Pipeline**: Configuring GitHub Actions for automatic deployment was a bit tricky initially, but following documentation and examples helped set it up correctly.
- **Automated Testing**: Since this is a static website, integrating unit tests for a more dynamic application would be the next step in further development.

## License

This project is open-source and available under the [MIT License](LICENSE).

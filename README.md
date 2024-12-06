## Description
Candidate Search is a web application that allows employers to find and review candidates using data retrieved from the GitHub API. The application provides a user-friendly interface to accept or reject candidates and manage a list of potential hires. It enhances the hiring process by offering a streamlined and efficient candidate evaluation platform.

# Motivation
This project was built to demonstrate the integration of TypeScript with React for building scalable and maintainable applications. It solves the problem of efficiently managing and evaluating candidates for hiring while leveraging the GitHub API.

## Features
Fetch candidate profiles using the GitHub API.
Accept or reject candidates to create a list of potential hires.
Save and persist accepted candidates in local storage.
View a detailed list of accepted candidates.
Responsive design and easy-to-use interface.
Bonus: Sort and filter candidates for easier management.
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)

## Installation
Follow these steps to set up the development environment:

1. Clone the repository:

``` bash
git clone <repository-url>
```

2. Navigate to the project directory:

``` bash
cd candidate-search
```

3. Install the required dependencies:

```bash
npm install
```

4. Create a .env file in the environment folder and add your GitHub Personal Access Token:

```plaintext
VITE_GITHUB_TOKEN=your_personal_access_token
Refer to the GitHub Documentation for more information.
```

5. Start the development server:

```bash
npm run dev
```

## Usage
Candidate Search Page: View a candidate's details, including name, username, location, avatar, email, company, and GitHub profile link.

Click "+" to save the candidate and view the next one.
Click "-" to skip the candidate and move to the next one.
Potential Candidates Page: View a list of saved candidates with their detailed profiles.

Manage the saved candidates directly from this page.

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.<BR>
Click the license above to learn more about this license.

## Badges

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-blue.svg)
![Javascript](https://img.shields.io/badge/Javascript-blue.svg)

## How to Contribute
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add feature').
4. Push to the branch (git push origin feature-name).
5. Open a Pull Request.

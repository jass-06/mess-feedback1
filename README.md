# Mess Feedback Portal

## Overview
The **Mess Feedback Portal** is a web application designed to collect feedback from students regarding the mess facilities. It allows users to submit suggestions, improvements, and general feedback related to mess services. The feedback includes details like student information, mess type, feedback category, and even file uploads for proof.

## Features
- **Mess Feedback Form**: Allows students to submit feedback regarding the quality, quantity, hygiene, timing, and more.
- **File Upload**: Users can upload files (PDF, DOC, JPG) as proof.
- **Simple Navigation**: Easy-to-navigate interface to access the form and submit feedback.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Feedback Categories**: Includes options for quality, quantity, hygiene, timing, and more.
- **Reports**: (To be implemented in backend) Report generation in Excel/PDF format for student-wise, monthly, weekly, and mess-wise analysis.

## Screenshots
![Home Page](./public/screenshots/home-page.png)
![Feedback Form](./public/screenshots/feedback-form.png)

## Project Structure

The project has the following folder structure:

\`\`\`
mess-feedback/
│
├── app.js                 # Backend Express server (not yet created, for future functionality)
├── package.json           # Node project configuration
│
├── public/                # Folder to store static files (CSS, JS)
│   ├── styles.css         # Stylesheet for homepage
│   └── styles-feedback.css# Stylesheet for feedback form page
│   └── script.js          # JavaScript for form submission alert
│   └── screenshots/       # Screenshots (if applicable)
│
├── uploads/               # Folder to store uploaded files (for file upload functionality)
├── reports/               # Folder to store generated reports (Excel/PDF reports)
├── index.html             # Homepage of the application
├── feedback.html          # Feedback form page
└── README.md              # Project documentation (this file)
\`\`\`

## How to Run the Project

### Prerequisites
To run this project locally, you will need the following installed:

- **Node.js** (for backend server if implemented)
- **Git** (to clone the repository)

### Steps to run the project locally:
1. **Clone the Repository**:
   Clone the repository to your local machine using the following command:
   \`\`\`bash
   git clone https://github.com/jass-06/mess-feedback1.git
   \`\`\`

2. **Navigate to the project folder**:
   \`\`\`bash
   cd mess-feedback1
   \`\`\`

3. **Install dependencies (if applicable)**:
   If you are working with a Node.js backend (Express), you might need to install dependencies:
   \`\`\`bash
   npm install
   \`\`\`

4. **Open the project in your browser**:
   - The frontend can be opened by double-clicking on \`index.html\` or \`feedback.html\` to view the pages in your browser.
   - For backend functionality (future updates), you can run the server by executing:
     \`\`\`bash
     node app.js
     \`\`\`
   - Make sure your backend (Node.js server) is running if you're working on integrating with the backend.

5. **Start the Application**:
   - Simply open \`index.html\` or \`feedback.html\` in a browser to view the app.

## Future Improvements
- Backend integration with Express.js for handling form submissions.
- Database integration with MySQL to store the feedback data.
- Report generation in Excel/PDF format for student-wise, weekly, monthly, and mess-wise reports.
- Add user authentication for personalized feedback submissions.

## Contributions
Feel free to fork this repository and submit a pull request if you have any suggestions or improvements!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Creator
This project was created by **Jaspreet**. Feel free to reach out for questions or contributions!

## Contact
For any inquiries, feel free to contact me at:

- **Email**: preetjaglan06@example.com
- **GitHub**: [https://github.com/jass-06](https://github.com/jass-06)

" > README.md

Project Report: Django Form Handling Project
Introduction
This project involved building a form handling application using Django. The primary goal was to create a robust and user-friendly form submission system with various fields like name, email, query method, and message. The project also incorporated features like form validation, custom error messages, and a confirmation page displaying the user's submitted data.

Key Features
Form Handling: The project includes a well-structured form that allows users to submit their queries through a straightforward interface.
Validation: Both server-side and client-side validations were implemented to ensure that the form data is accurate and complete before submission.
Custom Error Messages: The project involved customizing error messages to provide clear feedback to users when the form is not filled out correctly.
Success Page: After successful form submission, users are redirected to a confirmation page that displays their entered information.
Responsive Design: The form is fully responsive, ensuring that it is user-friendly across various devices, including desktops, tablets, and mobile phones.
Challenges Faced
Form Validation: Initially, there were issues with Django’s form validation. The challenge was ensuring that all necessary fields were validated correctly and that custom error messages were displayed appropriately.

Handling Radio Buttons: There was a challenge in handling radio buttons, especially with the default blank option that appeared. It required careful CSS manipulation to hide this option and ensure a clean user interface.

Deployment Issues: Deploying the Django project to Vercel posed some challenges, particularly with setting up the correct environment and configuring the ALLOWED_HOSTS settings to work both locally and on the Vercel platform.

Managing Environment Variables: Keeping sensitive data like the SECRET_KEY secure while deploying the project required learning about environment variables and how to manage them in a production setting.

Git and GitHub Integration: While managing the project, there were challenges related to correctly using Git for version control and pushing the project to GitHub, especially ensuring that the repository name differed from the Django directory name.

Learning Outcomes
Understanding Django’s Form Handling: The project provided a deep understanding of how Django processes forms, handles validation, and manages form data.

Responsive Web Design: Working on media queries and responsive design principles helped in creating a form that is adaptable to various screen sizes.

Deployment Skills: Deploying the Django project to Vercel enhanced understanding of deploying applications in a real-world scenario, including managing environment variables and configuring settings for different environments.

Version Control with Git: The project also served as a practical lesson in using Git for version control, including managing branches, commits, and remote repositories on GitHub.

Conclusion
This Django project was an excellent learning experience, providing insights into form handling, validation, and deployment. Despite the challenges faced, the project was successfully completed with all intended features implemented. The process has significantly strengthened my skills in Django, front-end development, and deployment, laying a strong foundation for future projects.

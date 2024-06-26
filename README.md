## Flask Application Design for Math Tutoring Website

### HTML Files

- **index.html:** Main landing page of the website, providing an overview of the tutoring services and allowing users to log in or register.
- **dashboard.html:** User dashboard, displaying personalized learning recommendations, progress tracking, and access to lessons.
- **lesson.html:** Template for individual lessons, with dynamic content based on the selected topic and difficulty level.
- **exercises.html:** Page for interactive exercises and practice problems, allowing users to test their understanding.

### Routes

- `/`: Redirects to the index page.
- `/login`: Handles user login and authentication.
- `/register`: Handles user registration and account creation.
- `/dashboard`: Serves the user dashboard upon successful login.
- `/lesson/:topic/:difficulty`: Dynamic route to render a specific lesson based on the provided topic and difficulty level.
- `/exercises/:topic/:difficulty`: Dynamic route to generate and serve exercises for a particular topic and difficulty level.
- `/submit-exercise`: Receives user responses from exercises and provides appropriate feedback.
- `/progress`: Displays user progress, including completed lessons and scores in exercises.
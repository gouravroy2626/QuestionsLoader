# Question Loader

A web application for loading, displaying, and navigating questions for multiple topics. Built with **Angular** for the frontend and **Node.js + Express** with **MongoDB** for the backend.

---

## Features

- User authentication with login/signup.
- Select topics and fetch questions dynamically from MongoDB.
- Navigate through questions with **Previous** and **Next** buttons.
- Click on a question to reveal the answer.
- Hover effect to indicate "Click to see the answer".
- Responsive design with CSS for a clean user interface.
- Route protection with **AuthGuard** to prevent unauthorized access.
- Easily extendable to add more topics and questions.

---

## Tech Stack

- **Frontend:** Angular 15, HTML5, CSS3
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT-based
- **Styling:** CSS, Bootstrap (optional)

---

## Folder Structure

QuestionLoader/
├── Backend/
│ ├── models/ # Mongoose models for Users, Questions
│ ├── routes/ # API routes for login, signup, questions
│ ├── server.js # Express server
├── Frontend/
│ ├── src/app/
│ │ ├── login/ # Login component
│ │ ├── signup/ # Signup component
│ │ ├── topics/ # Topics selection component
│ │ ├── quiz/ # Quiz display component
│ │ ├── services/ # Angular services for API calls
│ │ ├── auth.guard.ts
│ │ ├── app-routing.module.ts
│ │ └── app.module.ts
│ ├── index.html
│ └── styles.css


---

## Installation

### Backend

```terminal
cd Backend
npm install

run the server
node server.js
```
### Frontend

```terminal
cd Frontend
npm install
ng serve

The Angular app will run on http://localhost:4200
```

Usage-

1.Open the app in a browser.

2.Sign up or log in.

3.Select a topic.

4.Navigate through the questions.

5.Click a question to view its answer.

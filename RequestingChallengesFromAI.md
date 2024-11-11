<a name="requesting-challenges-from-ai"></a>
# Requesting Challenges from AI
[ChatGPT](https://chatgpt.com) is a fantastic learning resource. While it can come in handy helping you solve problems, it is even more valuable as a tool for generating ideas for what you can practice on as you learn to program.

The trick is in perfecting the art of creating a ChatGPT Prompt (or request) that will result in something that fits your needs.

For the purposes of this guide, I will provide here several prompts which can be modified (by you) as you progress through the curriculum so that you can get fresh and unique practice projects, tailored to your abilities and interests, as you progress.

**Tips for any prompts you riff off this:**
-  lead off with what level you currently are at programming the thing you're asking AI to give you a practice project for (beginner/intermediate/advanced)
-  mention any specific technologies you'd like to use
-  ask for a style guide for anything with an interface
-  ask for a documented api for anything where a front and backend are communicating
-  ask for a data model for any backend project (and any frontend project working with data)
-  ask for use cases you can use to create test cases
-  ask for reference links to the official docs
-  if you want the project to be for something specific, ask for that, either generally or specifically. For instance, you can absolutely ask something like "I would like this project to be a lighthearted page that is somehow related to puppies."


**Tips for using what you get from ChatGPT:**
- You can type any of the prompts contained here, or any prompt you customize from these straight into ChatGPT and it will create for you a full project specification. At that point, all you have to do is go build it.
- When ChatGPT has completed generating your project, you'll see a line of icons at the end of it's response. The icon that looks like two windows will let you copy ChatGPT's entire response. This response is in markdown, which means you can save it in any markdown file with the extension `.md` and retain your full project specification for reference. This would be a really good starter for the `README.md` in your project.
- sometimes, for really big projects, ChatGPT can't finish in one go, just tell it to continue and it will finish 


## Table of Contents
- [Requesting Challenges from AI](#requesting-challenges-from-ai)
   * [The baseline prompt](#the-baseline-prompt)
   * [Example prompt for a more advanced and detailed project](#example-prompt-for-a-more-advanced-and-detailed-project)
   * [Results from the more advanced project prompt ](#these-are-the-results-from-the-more-advanced-project-prompt)
   * [Another example prompt, incorporating full stack](#another-example-prompt-incorporating-full-stack)
   * [Results of the full stack project prompt](#here-are-the-results-of-the-full-stack-project-prompt)
   * [Example prompt for a Java project](#example-prompt-for-a-java-project)
   * [Results from Java project prompt](#here-are-the-results-from-java-project-prompt)



<!-- TOC --><a name="the-baseline-prompt"></a>
## The baseline prompt

```
I am a beginner web developer. Assign me a beginner frontend web development project. Please be very specific and detailed with the requirements. Please add a list of links to suggested tactics, terminology, and various other information I might want to reference while completing this assignment in a reference section at the end of the assignment. Please prioritize using links to the "official docs" in this list rather than random web commentary. Please provide a style guide after the reference section.
```
### This was the output from ChatGPT for this prompt
### Beginner Frontend Web Development Project: Personal Portfolio Website

#### Project Overview
You will create a **Personal Portfolio Website** to showcase your skills, projects, and contact information. This project will help you develop a strong foundation in HTML, CSS, and JavaScript, including responsive design principles.

---

### Features & Requirements

1. **Landing Page**
   - Create a welcoming landing page with a short introduction about yourself.
   - Include your name, a brief description of who you are (e.g., "Aspiring Web Developer"), and a professional photo or avatar.

2. **About Me Section**
   - Include a short bio that covers your background, skills, and goals.
   - Use HTML semantic tags like `<section>`, `<h2>`, and `<p>` for structure.
   - Keep content concise and well-formatted.

3. **Projects Section**
   - Display a few sample projects you’ve worked on, even if they’re simple (e.g., a basic webpage or coding exercises).
   - Each project should include:
     - A title
     - A brief description
     - A link to the live version (if available) or GitHub repository
     - An image or screenshot of the project (optional)
   - Use a responsive grid layout with **CSS Grid** or **Flexbox** to make this section visually appealing.

4. **Skills Section**
   - Create a skills section showcasing your technical skills, like HTML, CSS, JavaScript, or any other relevant skills.
   - Use icons or small graphics to make the section engaging.
   - Implement a progress bar or list to visually display proficiency (e.g., "beginner," "intermediate").

5. **Contact Form**
   - Include a basic contact form with fields for name, email, and message.
   - Form elements should be styled to match the overall design of the website.
   - Use HTML form validation (e.g., required fields) to ensure valid submissions.

6. **Footer**
   - Create a footer with links to your social media profiles, GitHub, LinkedIn, or other professional sites.
   - Include copyright information (e.g., "© 2023 Your Name").

7. **Responsive Design**
   - Implement responsive design for desktop, tablet, and mobile screens.
   - Use media queries to ensure that text, images, and layout adjust properly across different devices.
   - Focus on maintaining readability and usability on all screen sizes.

---

### Step-by-Step Development Process

1. **Set Up the Project**
   - Create a new project folder and include `index.html`, `style.css`, and `script.js` files.
   - Set up basic HTML structure with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags.

2. **Write HTML Structure**
   - Add semantic HTML structure for each section, including the landing page, About Me, Projects, Skills, Contact Form, and Footer.
   - Ensure each section has clear headings, text, and placeholder images if needed.

3. **Style the Website with CSS**
   - Define your CSS styling in `style.css`, starting with global styles (e.g., fonts, colors).
   - Use **CSS Flexbox** or **CSS Grid** for layout, especially in the Projects and Skills sections.
   - Implement media queries for responsive design adjustments at 768px (tablet) and 480px (mobile).

4. **Add JavaScript (Optional)**
   - Use `script.js` to add basic interactivity, such as a toggle effect for a mobile navigation menu.
   - Add form validation or simple animations to enhance the user experience.

5. **Test and Deploy**
   - Test your website on various screen sizes and devices.
   - Deploy the project to a platform like **GitHub Pages** or **Netlify** to make it accessible online.

---

### Reference Section

#### Official Documentation and Tutorials
- **HTML**: [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **CSS**: [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- **JavaScript**: [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- **CSS Flexbox**: [Flexbox Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- **CSS Grid**: [CSS Grid Guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- **Responsive Design**: [Responsive Web Design Basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- **Media Queries**: [Using Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

#### Additional Resources
- **Form Validation**: [Form Validation Documentation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- **GitHub Pages Deployment**: [GitHub Pages Documentation](https://docs.github.com/en/pages)
- **Netlify Deployment Guide**: [Netlify Quick Start](https://docs.netlify.com/get-started/)

---

### Style Guide

1. **Color Palette**
   - **Primary Color**: #007bff (blue)
   - **Accent Color**: #ff5722 (orange)
   - **Background Color**: #f9f9f9 (light grey)
   - **Text Color**: #333333 (dark grey)

2. **Typography**
   - **Font Family**: Use [Roboto](https://fonts.google.com/specimen/Roboto) or [Open Sans](https://fonts.google.com/specimen/Open+Sans).
   - **Font Sizes**:
     - **Headings** (H1): 2em
     - **Subheadings** (H2): 1.5em
     - **Body Text**: 1em

3. **Button Styling**
   - Primary Buttons: Background #007bff, Text #fff, Hover #0056b3.
   - Secondary Buttons: Background #ff5722, Text #fff, Hover #e64a19.

4. **Layout**
   - Use **CSS Flexbox** or **CSS Grid** for layout.
   - Apply consistent padding and margin for clean spacing.

5. **Image Guidelines**
   - Optimize images for web (compressed without sacrificing quality).
   - Use images that are approximately 500px wide for better loading times.

This portfolio project will help you practice frontend basics and allow you to build something you can showcase in your web development journey! 

## Example prompt for a more advanced and detailed project
```
I am an intermediate web developer. Assign me an intermediate frontend web development project. Please be very specific and detailed with the requirements. Please add a list of links to suggested tactics, terminology, and various other information I might want to reference while completing this assignment in a reference section at the end of the assignment. Please prioritize using links to the "official docs" in this list rather than random web commentary. Please provide a style guide after the reference section. Please provide a list of use cases from which I may create test cases. I would like this to be a pretty substantial intermediate level project that uses React, Redux, TypeScript, and Storyboard.
```

<!-- TOC --><a name="these-are-the-results-from-the-more-advanced-project-prompt"></a>
## These are the results from the more advanced project prompt 

### Intermediate Frontend Web Development Project: E-Commerce Dashboard

#### Project Overview
You will develop an **E-Commerce Admin Dashboard** using **React**, **Redux**, **TypeScript**, and **Storybook**. This dashboard will allow an admin to manage products, view sales data, monitor orders, and analyze user metrics. 

The focus will be on implementing clean, modular components with **TypeScript** for type safety, **Redux** for state management, and **Storybook** for component documentation. The project will include robust filtering, pagination, and detailed analytics to support an intermediate-level understanding of web development.

---

### Features & Requirements

1. **User Authentication (Mocked)**
   - Implement basic authentication (e.g., login/logout).
   - Use mock data to simulate authentication (no backend required).
   - Store the user token in Redux and redirect to the dashboard on successful login.

2. **Dashboard Overview Page**
   - Display an overview of key metrics (e.g., total sales, total users, active orders).
   - Use cards or charts for each metric (chart library recommendation: **Recharts**).
   - Implement a date range filter to update metrics dynamically.

3. **Product Management**
   - **Product List**:
     - Display a paginated list of products with columns for ID, name, category, stock, and price.
     - Include filtering by category and search by product name.
   - **Add/Edit Product Form**:
     - Use a modal or dedicated page to add new products and edit existing ones.
     - Form fields: ID (auto-generated), Name, Description, Category, Price, and Stock.
     - Use TypeScript to enforce form data structure.
   - **Delete Product**:
     - Allow the user to delete a product with a confirmation dialog.
     - Update the state in Redux on successful deletion.

4. **Order Management**
   - **Order List**:
     - Display a paginated list of orders, with columns for Order ID, customer name, status, total amount, and order date.
     - Filter by status (e.g., Pending, Shipped, Completed).
   - **Order Details**:
     - Display detailed information for each order, including product list, customer info, shipping address, and status.
     - Allow admin to update the status of an order (e.g., from Pending to Shipped).

5. **User Analytics**
   - Display a series of charts to show user behavior (e.g., weekly active users, top-selling products).
   - Implement filtering options for various date ranges (Last 7 days, Last 30 days, etc.).
   - Use **Recharts** to create bar, line, and pie charts for visualization.

6. **Notifications System**
   - Display notifications for important actions (e.g., successful product addition, deletion confirmation, etc.).
   - Notifications should be dismissible and automatically disappear after a few seconds.

7. **Settings Page**
   - Provide options for changing application theme (light/dark mode).
   - Save theme preference in **local storage** and Redux state.
   - Use **Styled Components** or CSS modules for theme management.

8. **Error Handling and Form Validation**
   - Implement form validation for product and order forms with TypeScript.
   - Use notifications to alert the user of validation errors (e.g., missing required fields).

9. **Component Documentation with Storybook**
   - Document all core components in **Storybook**:
     - Product Card, Order Table, Notification, Chart Components, etc.
   - Write stories for various states (e.g., loading, error, success) and configurations.

10. **Testing**
    - Write unit tests for key components (using **Jest** or **React Testing Library**).
    - Ensure good test coverage for components like Product Card, Order List, and Notification.

11. **Deployment**
    - Deploy your application to a hosting service (e.g., **Vercel** or **Netlify**).
    - Configure Storybook deployment to allow easy review of your documented components.

---

### Step-by-Step Development Process

1. **Project Setup**
   - Set up a new **React** project with **TypeScript** and **Redux**.
   - Integrate **Storybook** into the project and confirm the development server works.

2. **Define TypeScript Interfaces**
   - Define TypeScript interfaces for Products, Orders, and User objects.
   - Use these types throughout the application for type safety.

3. **Create Redux Store and Actions**
   - Define reducers and actions for authentication, product management, orders, and user analytics.
   - Set up selectors and middleware as needed.

4. **Build Each Feature**
   - Start with the Dashboard Overview, building and documenting each component in Storybook.
   - Develop each feature one at a time, testing them as you go.

5. **Style with Styled Components**
   - Define a global theme and apply light/dark modes as you build each page.

6. **Test & Document**
   - Write tests for critical components and document them in Storybook with variations.

7. **Deploy & Finalize**
   - Deploy the application and Storybook.
   - Verify functionality in production and perform final quality assurance.

---

### Use Cases for Test Cases

1. **User Authentication**
   - User can log in with correct credentials.
   - User is redirected to the dashboard upon login.
   - Unauthorized users are redirected to the login page if they try to access dashboard routes.

2. **Product Management**
   - Products are displayed in a paginated list.
   - User can filter products by category.
   - User can add a new product with valid information.
   - Editing a product updates the product list.
   - User receives a confirmation message upon deleting a product.

3. **Order Management**
   - Orders are displayed in a paginated list.
   - User can filter orders by status.
   - User can update order status.
   - Order details display correctly for each order.

4. **Analytics**
   - Analytics reflect correct data for selected date ranges.
   - Charts are responsive to filter changes.

5. **Notifications**
   - Notifications appear after key actions (add product, delete product).
   - Notifications automatically disappear after a few seconds.

6. **Settings**
   - Switching to dark mode updates the theme.
   - Theme preference is saved in local storage and persists on reload.

---

### Reference Section

#### Official Docs
- **React**: [React Documentation](https://reactjs.org/docs/getting-started.html)
- **Redux**: [Redux Documentation](https://redux.js.org/introduction/getting-started)
- **TypeScript**: [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- **Storybook**: [Storybook Documentation](https://storybook.js.org/docs/react/get-started/introduction)

#### Recommended Libraries
- **Styled Components**: [Styled Components Documentation](https://styled-components.com/docs)
- **Recharts (for charts)**: [Recharts Documentation](https://recharts.org/en-US/guide)
- **React Testing Library**: [React Testing Library Docs](https://testing-library.com/docs/react-testing-library/intro/)

#### Useful Terminology
- **TypeScript Types**: [TypeScript Type Documentation](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)
- **Pagination with Redux**: [Redux Pagination Tutorial](https://redux.js.org/recipes/paginated-lists)

---

### Style Guide

1. **Color Palette**:
   - Primary Color: #007bff (blue)
   - Secondary Color: #6c757d (grey)
   - Success Color: #28a745 (green)
   - Warning Color: #ffc107 (yellow)
   - Background Color: #f8f9fa (light grey for dashboard)

2. **Typography**:
   - **Font Family**: Use [Roboto](https://fonts.google.com/specimen/Roboto) or [Open Sans](https://fonts.google.com/specimen/Open+Sans).
   - **Font Sizes**:
     - Headings (H1): 2em
     - Subheadings (H2): 1.5em
     - Body: 1em

3. **Button Styling**:
   - Primary Buttons: Background #007bff, Text #fff, Hover #0056b3.
   - Secondary Buttons: Background #6c757d, Text #fff, Hover #5a6268.

4. **Layout**:
   - Use **CSS Flexbox** and **CSS Grid** for responsive layout.
   - Apply consistent padding and margin for a clean UI.

5. **Component Styling**:
   - Use modular **Styled Components** for each component.
   - Define styles within components to ensure consistency.

This project will give you hands-on experience with React and Redux workflows, reinforce TypeScript skills, and expose you to UI component documentation through Storybook. 

<!-- TOC --><a name="another-example-prompt-incorporating-full-stack"></a>
## Another example prompt, incorporating full stack

```
I am an intermediate web developer. Assign me an intermediate full-stack web development project. Please be very specific and detailed with the requirements. Please add a list of links to suggested tactics, terminology, and various other information I might want to reference while completing this assignment in a reference section at the end of the assignment. Please prioritize using links to the "official docs" in this list rather than random web commentary. Please provide a frontend style guide after the reference section. Please provide a backend API design document. Please provide a data model. Please provide a list of use cases from which I may create test cases. I would like this to be a pretty substantial intermediate level project that uses React on the frontend, Python on the backend, and SQL as the data store.
```

<!-- TOC --><a name="here-are-the-results-of-the-full-stack-project-prompt"></a>
## Here are the results of the full stack project prompt

### Intermediate Full-Stack Web Development Project: Online Book Club Platform

---

#### Project Overview
Build an **Online Book Club Platform** where users can register, join book clubs, add books to read, share reviews, and interact with other users. This project will focus on creating a full-stack web application with **React** on the frontend, **Python (Flask)** for the backend, and **SQL** (e.g., PostgreSQL) for data storage.

The project involves user authentication, CRUD operations for book management, real-time commenting features, and user interactions such as likes on books and comments.

---

### Project Requirements

1. **User Authentication**  
   - **Sign Up and Log In**: Allow users to register and log in with email and password.
   - **Session Management**: Use sessions or JSON Web Tokens (JWT) for authentication.
   - **Profile Management**: Users can edit their profiles, including profile picture, bio, and favorite genres.

2. **Book Clubs**
   - **Join/Create Book Clubs**: Users can create or join book clubs with specific themes or genres.
   - **Club Page**: Each club has a dedicated page with a description, member list, and list of books currently being read.
   - **Club Moderation**: The creator of a club is automatically assigned as the moderator and can add or remove members, as well as delete posts.

3. **Books**
   - **Book CRUD**: Users can add, edit, and delete books to the clubs they moderate.
   - **Book Details Page**: Each book has a dedicated page displaying the title, author, cover, description, and reviews.
   - **Reading Progress**: Users can track their progress (e.g., Not Started, In Progress, Completed) on each book.

4. **Reviews and Comments**
   - **Add Reviews**: Users can write reviews for each book they are reading.
   - **Comments**: Real-time commenting on book reviews (implement with WebSockets).
   - **Likes and Ratings**: Users can like reviews and rate books from 1-5 stars.

5. **User Interactions**
   - **Social Feed**: Display a social feed showing recent activity, such as new book clubs created, reviews added, and books being discussed.
   - **Friend System**: Users can add each other as friends to stay updated on their reading activity.

---

### Step-by-Step Development Process

1. **Set Up Project Structure**
   - Create a new React frontend project and Flask backend project.
   - Set up PostgreSQL as your SQL database and integrate it with Flask using SQLAlchemy.

2. **Implement User Authentication**
   - Use Flask for backend authentication routes and JWT for session management.
   - Implement a simple sign-up and login form on the frontend using React and Axios for requests.
   - Use Context API to manage the authentication state in React.

3. **Book Club and Book Management**
   - Set up API endpoints for book club and book CRUD operations.
   - On the frontend, create React components for creating, listing, and viewing book clubs and books.
   - Use React state to manage book club membership and display club members.

4. **Reviews and Comments**
   - Implement review submission in React with a textarea input.
   - Use WebSockets to enable real-time commenting on reviews.
   - Set up the Flask server with WebSocket functionality to handle real-time interactions.

5. **User Interactions and Social Feed**
   - Create SQL tables and endpoints for user friendships and activity tracking.
   - Display the feed in the frontend with recent activity such as new reviews, book club creations, and likes.

6. **Deploy Application**
   - Deploy the backend to Heroku or Digital Ocean and the frontend to Netlify or Vercel.
   - Ensure frontend and backend are integrated and operating smoothly on production.

---

### Data Model

1. **Users Table**
   - `user_id`: Primary key
   - `email`: Unique, indexed
   - `password_hash`: String
   - `bio`: Text
   - `profile_picture_url`: String
   - `favorite_genres`: Array of strings

2. **Clubs Table**
   - `club_id`: Primary key
   - `name`: String, unique
   - `description`: Text
   - `created_by`: Foreign key to `user_id`
   - `members`: Array of foreign keys to `user_id`

3. **Books Table**
   - `book_id`: Primary key
   - `title`: String
   - `author`: String
   - `description`: Text
   - `cover_image_url`: String
   - `club_id`: Foreign key to `club_id`

4. **Reviews Table**
   - `review_id`: Primary key
   - `book_id`: Foreign key to `book_id`
   - `user_id`: Foreign key to `user_id`
   - `content`: Text
   - `rating`: Integer (1-5 stars)

5. **Comments Table**
   - `comment_id`: Primary key
   - `review_id`: Foreign key to `review_id`
   - `user_id`: Foreign key to `user_id`
   - `content`: Text
   - `timestamp`: Datetime

6. **Friendships Table**
   - `friendship_id`: Primary key
   - `user_id`: Foreign key to `user_id`
   - `friend_id`: Foreign key to `user_id`

---

### API Design Document

1. **User Authentication**
   - `POST /api/auth/signup`: Create a new user.
   - `POST /api/auth/login`: Log in an existing user.
   - `GET /api/user/profile`: Get user profile details.
   - `PUT /api/user/profile`: Update user profile.

2. **Book Clubs**
   - `POST /api/clubs`: Create a new book club.
   - `GET /api/clubs`: Get a list of all clubs.
   - `GET /api/clubs/:id`: Get details of a specific club.
   - `PUT /api/clubs/:id`: Update club details.
   - `DELETE /api/clubs/:id`: Delete a club.

3. **Books**
   - `POST /api/books`: Add a book to a club.
   - `GET /api/books/:clubId`: Get all books in a specific club.
   - `GET /api/books/:id`: Get details of a specific book.
   - `PUT /api/books/:id`: Update book details.
   - `DELETE /api/books/:id`: Delete a book.

4. **Reviews and Comments**
   - `POST /api/reviews`: Add a review for a book.
   - `GET /api/reviews/:bookId`: Get all reviews for a book.
   - `POST /api/comments`: Add a comment to a review.

5. **Friendships**
   - `POST /api/friends`: Add a friend.
   - `DELETE /api/friends/:friendId`: Remove a friend.
   - `GET /api/friends`: Get a list of friends.

6. **Social Feed**
   - `GET /api/feed`: Get recent activities for the user’s social feed.

---

### Use Cases for Test Cases

1. **User Authentication**
   - User can register with a valid email and password.
   - User cannot register with an existing email.
   - User can log in with correct credentials.

2. **Book Club Management**
   - User can create a book club.
   - Club moderator can add and remove members.
   - Only the club creator can delete the club.

3. **Book Management**
   - Moderator can add a book to a club.
   - Non-moderators cannot add/edit/delete books in a club.

4. **Reviews and Comments**
   - Users can add reviews to books they are reading.
   - Users can add comments to reviews in real time.
   - Users can like reviews.

5. **Friendship Management**
   - User can add another user as a friend.
   - User can see the reading activity of friends in the feed.

6. **Social Feed**
   - User’s feed shows recent reviews and comments from friends.
   - Feed updates in real time as activities occur.

---

### Reference Section

#### Official Documentation
- **React**: [React Documentation](https://reactjs.org/docs/getting-started.html)
- **Flask**: [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)
- **SQLAlchemy**: [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/14/)
- **PostgreSQL**: [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- **WebSocket in Flask**: [Flask-SocketIO Documentation](https://flask-socketio.readthedocs.io/en/latest/)

#### Recommended Libraries
- **Axios** for HTTP requests: [Axios Documentation](https://axios-http.com/docs/intro)
- **React Context API** for state management: [React Context Documentation](https://reactjs.org/docs/context.html)
- **JSON Web Tokens (JWT)** for authentication: [JWT Guide](https://jwt.io/introduction/)

---

### Frontend Style Guide

1. **Color Palette**
   - **Primary Color**: #1e90ff (Dodger Blue)
   - **Secondary Color**: #333333 (Dark Grey)
   - **Background Color**: #f4f4f4 (Light Grey)
   - **Accent Color**: #ff6f61 (Coral)

2. **Typography**
   - **Font Family**: [Roboto](https://fonts.google.com/specimen/Roboto)
   - **Font Sizes**:
     - Headings (H1): 2em
     - Subheadings (H2): 1.5em  
     - Body Text: 1em

3. **Button Styles**
   - **Primary Button**: Background #1e90ff, text #fff, rounded corners, hover background #007acc.
   - **Secondary Button**: Background #ff6f61, text #fff, hover background #ff4f41.

4. **Layout**
   - Use **CSS Flexbox** or **CSS Grid** for flexible layouts.
   - Apply consistent padding and margin to ensure a clean, modern look.

5. **Images**
   - Profile pictures: 100px by 100px (circular).
   - Book cover images: 200px by 300px.

6. **Forms**
   - Input fields: Rounded with a light-grey background.
   - Submit button: Styled as a primary button.
   - Form spacing: Use 1em margin between fields for clarity.

7. **Notifications and Alerts**
   - Success: Light green background with a green border.
   - Error: Light red background with a red border.
   - Info: Light blue background with a blue border.

This substantial project will build both your frontend and backend skills by incorporating real-time interactions, managing a SQL database, and implementing secure user authentication. 

<!-- TOC --><a name="example-prompt-for-a-java-project"></a>
## Example prompt for a Java project
```
I am an intermediate level Java developer. Assign me an intermediate level Java project. Please be very specific and detailed with the requirements. Please add a list of links to suggested tactics, terminology, and various other information I might want to reference while completing this assignment in a reference section at the end of the assignment. Please prioritize using links to the "official docs" in this list rather than random web commentary.  Please provide a list of use cases from which I may create test cases. I would like this to be a pretty substantial intermediate level project that leverages using Java for both the frontend and backend. Please document the data model, API, and a style guide for the user interface.

```

<!-- TOC --><a name="here-are-the-results-from-java-project-prompt"></a>
## Here are the results from Java project prompt
### Intermediate Java Project: **Personal Finance Manager**

---

#### Project Overview
Build a **Personal Finance Manager** that provides users with a desktop application to track income, expenses, budgeting, and savings. This application will use Java Swing for the user interface and a backend layer handling the logic and database integration. The project will involve core Java skills, with experience in designing a GUI, using object-oriented principles, multi-threading, and persisting data through an embedded SQL database (like H2).

---

### Project Requirements

1. **User Accounts and Authentication**
   - **Registration/Login System**: Each user should register an account with a unique username and password.
   - **Session Management**: Ensure that only authenticated users can access the finance management features, with each session scoped to the login instance.
   - **Password Security**: Hash passwords before storing them in the database.

2. **Income and Expense Tracking**
   - **Add Income/Expense Entries**: Users can add, view, edit, or delete entries for income and expenses. Each entry should include an amount, date, category, and description.
   - **Category Management**: Define default categories (e.g., Food, Entertainment, Salary, etc.) and allow users to create custom categories.
   - **Recurring Entries**: Allow users to set recurring income or expense entries (e.g., monthly rent or salary).

3. **Budgeting and Financial Goals**
   - **Budget Creation**: Users can set monthly budgets for each category.
   - **Goal Setting**: Allow users to set financial goals, such as a specific amount to save over a period.
   - **Budget and Goal Monitoring**: Notify users when they approach or exceed their budget or are close to achieving their goals.

4. **Data Visualization**
   - **Expense Reports**: Display monthly and yearly breakdowns of expenses and income by category.
   - **Charts**: Use a library like JFreeChart to show visual breakdowns of spending, income, and savings over time.

5. **Search and Filtering**
   - Provide a search feature to find specific entries based on date range, category, or description.
   - Allow users to filter the main display by month, category, or entry type (income/expense).

6. **Persistence and Database Management**
   - Use H2 (or SQLite) as an embedded database to store user, income, expense, and budget data.
   - Implement data models to organize tables for users, transactions, budgets, and goals.

7. **Multi-threading for Data Refresh and Notifications**
   - Implement a background thread to check and notify users when they approach or exceed budgets or reach financial goals.
   - Ensure data refreshes automatically after a set interval.

8. **Desktop Interface using Java Swing**
   - Design an intuitive GUI using Java Swing components (JFrames, JPanels, JTable, JDialog, etc.).
   - Ensure data from the backend is displayed dynamically, allowing users to interact and perform CRUD operations within the interface.

---

### Data Model

1. **User Table**
   - `user_id`: Primary key
   - `username`: Unique
   - `password_hash`: Encrypted string

2. **Income_Expense Table**
   - `entry_id`: Primary key
   - `user_id`: Foreign key
   - `amount`: Double
   - `category`: String
   - `description`: Text
   - `type`: Enum (Income, Expense)
   - `date`: Date

3. **Budget Table**
   - `budget_id`: Primary key
   - `user_id`: Foreign key
   - `category`: String
   - `amount`: Double
   - `month`: Month enum

4. **Goal Table**
   - `goal_id`: Primary key
   - `user_id`: Foreign key
   - `goal_amount`: Double
   - `current_amount`: Double
   - `deadline`: Date

---

### API Design Document

Since this is a Java-based desktop app without a web server, the API will function as methods within service classes to perform CRUD operations. Below is an outline of key methods:

1. **UserService**
   - `boolean registerUser(String username, String password)`: Registers a new user.
   - `User login(String username, String password)`: Validates login and returns a user session.

2. **FinanceService**
   - `void addIncomeExpense(Entry entry)`: Adds a new income/expense entry.
   - `List<Entry> getEntriesByUser(int userId)`: Retrieves all entries for a user.
   - `void editEntry(Entry entry)`: Updates an existing income/expense entry.
   - `void deleteEntry(int entryId)`: Deletes an entry by ID.

3. **BudgetService**
   - `void setBudget(int userId, String category, double amount)`: Sets a budget for a category.
   - `double getBudgetAmount(String category)`: Retrieves the budget amount for a category.

4. **GoalService**
   - `void setGoal(int userId, double goalAmount, Date deadline)`: Sets a financial goal.
   - `Goal getGoal(int goalId)`: Retrieves goal details by ID.
   - `void updateGoalProgress(int goalId, double amount)`: Updates the goal’s current saved amount.

---

### Use Cases for Test Cases

1. **User Registration and Login**
   - Register with unique usernames.
   - Prevent registration with duplicate usernames.
   - Login with valid and invalid credentials.

2. **Add, View, Edit, and Delete Entries**
   - Add a new income or expense entry.
   - View all entries by category or date range.
   - Edit an entry’s details and save changes.
   - Delete an entry and ensure it’s removed from the database.

3. **Set and Track Budgets**
   - Set monthly budgets for specific categories.
   - Notify users when they are close to exceeding the budget.

4. **Set and Monitor Financial Goals**
   - Add financial goals with deadlines.
   - Update goal progress and verify if notifications are triggered.

5. **Data Visualization**
   - Generate reports for monthly income and expenses.
   - Display charts with accurate data for the specified time range.

---

### Reference Section

#### Official Documentation
- **Java SE Documentation**: [Java SE Docs](https://docs.oracle.com/javase/8/docs/)
- **Java Swing**: [Java Swing Docs](https://docs.oracle.com/javase/tutorial/uiswing/)
- **Java Collections Framework**: [Collections Docs](https://docs.oracle.com/javase/8/docs/technotes/guides/collections/overview.html)
- **JDBC**: [JDBC Guide](https://docs.oracle.com/javase/tutorial/jdbc/)
- **JFreeChart**: [JFreeChart Documentation](https://sourceforge.net/projects/jfreechart/files/)
- **Password Hashing**: [Java Security Guide](https://docs.oracle.com/javase/tutorial/security/tools/index.html)

#### Suggested Libraries
- **Java ExecutorService**: [Concurrency Guide](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ExecutorService.html)
- **SQLite JDBC**: [SQLite JDBC Driver](https://bitbucket.org/xerial/sqlite-jdbc)

---

### Style Guide for User Interface

1. **Color Scheme**
   - **Primary Background**: #f8f9fa (light grey)
   - **Primary Text**: #343a40 (dark grey)
   - **Button Colors**: #007bff (blue) for primary actions, #6c757d (grey) for secondary actions

2. **Font**
   - **Font Family**: Use Sans-serif font, such as Arial or Roboto.
   - **Header Text**: 16px, bold
   - **Body Text**: 14px

3. **Button Styles**
   - **Primary Button**: Blue background, white text, slightly rounded corners.
   - **Secondary Button**: Grey background, black text, with a small margin.

4. **Layout**
   - Use consistent padding and margins across all components.
   - Each section (e.g., income/expense form, goal setting, budget setting) should be clearly separated visually with borders or spacing.

5. **Dialogs and Alerts**
   - **Errors**: Use a red background with white text.
   - **Success Messages**: Green background with white text.
   - **Information Messages**: Blue background with white text.

6. **Charts**
   - Ensure clear color coding for each category in pie and bar charts.
   - Use tooltips to display precise values on hover.

This project will exercise both frontend and backend skills within a Java environment, incorporating data management, user interface design, and concurrency. 
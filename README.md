# androidClub

- 4 navigatable pages
- API call implementation is must fetching github data from username
- https://www.google.com/url?sa=i&url=https%3A%2F%2Fin.linkedin.com%2Fcompany%2Fandroid-club-vitc&psig=AOvVaw39BzaAOtZfv2dnJ3TOa4GB&ust=1697880837659000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCOCY5ZKphIIDFQAAAAAdAAAAABAD
- images from unsplash
- Process to how to run the project 
- 1.clone the project
- 2.Then run these two command
- npm install -g create-vite
- npm install --save-dev create-vite
- then to run: npm run dev
- Implementation :
Setup React App: Create a new React.js project using Create React App or your preferred setup method.

Install Dependencies:

Install react-router-dom for handling navigation.
Set up any other dependencies you might need for your project.
Create Pages:
Create four navigable pages (e.g., Home, About, Services, Contact) as functional components.

Set up Routing:

Create a separate component for routing (e.g., AppRouter) using react-router-dom.
Define routes for each page using the Route component, specifying the path and corresponding component.
Implement API Calls:

Create a component for making API calls.
Use the fetch API or a library like Axios to make HTTP requests to your API.
Store the API data in the component's state using hooks (e.g., useState and useEffect).
Integrate API Data:

Display the API data in the appropriate component.
You can conditionally render content based on the API data or show a loading message until the data is fetched.
Update App Component:

Modify the main App component to include the AppRouter for navigation and your API call component to display the data.
Testing:

Test your app by running it using npm start and verify that navigation and API data display work as expected.
Styling and Additional Features:

Add CSS styles or use a CSS framework for styling your pages.
Implement any additional features and functionalities your project requires.
This outline provides a high-level overview of how to implement a React.js project with navigable pages and API call integration. You can customize and expand upon this outline according to your specific project requirements.
- File structure:
androidClub/
  |- node_modules/     
  |- public/           
  |  |- vite.svg    
  |- src/              
  |  |- assets/        
  |  |- components/     
  |  |  |- About
  |  |  |- Contact
  |  |  |- Footer
  |  |  |- github
  |  |  |- Header
  |  |  |- Home
  |  |  |- User
  |  |- App.css(global css)     
  |  |- App.jsx
  |  |- Layout.jsx          
  |  |- index.css       
  |  |- main.jsx      
  |- .eslintrc.cjs       
  |- .gitignore        
  |- package.json   
  |- README.md
  |- index.html
  |- package-lock.json
  |- postcss.config.js
  |- tailwind.config.js
  |- vite.config.js

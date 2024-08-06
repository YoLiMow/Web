# Web

This repository contains various web projects developed by YoLiMow. Below is a brief overview of each project:

## Projects

### Museum of Candy
A static website for a fictional museum dedicated to candy. It showcases different exhibits and provides visitor information.

### Price Table
A responsive price table layout designed using HTML and CSS. It demonstrates different pricing options in a clean and organized manner.

### ScoreKeeper
A simple JavaScript application to keep track of scores for a game. Users can set the winning score and reset the game.

### Fancy Todo List
The Fancy Todo List is a dynamic and interactive to-do list application built using React. Key features include:

- **Add Tasks**: Users can add new tasks by typing into the input field and pressing enter or clicking the add button.
- **Remove Tasks**: Each task has a delete button, enabling users to remove tasks individually.
- **Mark as Complete**: Users can click on a task to mark it as complete or incomplete, with completed tasks visually differentiated.
- **Responsive Design**: The application is designed to be fully responsive, ensuring a seamless experience on both desktop and mobile devices.

#### Technologies Used
- **React**: For building the user interface.
- **JavaScript**: For the interactive functionality.
- **HTML**: For the basic structure.
- **CSS**: For styling the application.

#### React Methodology

The Fancy Todo List leverages React’s component-based architecture to manage the state and render the UI efficiently.

- **Components**: The application is divided into reusable components such as `TodoItem`, `TodoList`, and `AddTodo`.
  - **`TodoItem`**: Represents each task in the list. Handles the rendering of task text, delete button, and complete status.
  - **`TodoList`**: Manages the list of tasks. Responsible for rendering the list of `TodoItem` components.
  - **`AddTodo`**: Contains the input field and add button. Handles the addition of new tasks.
  
- **State Management**: State is managed using React’s `useState` hook.
  - The state includes the list of tasks and their completion status.
  - Functions to add, delete, and toggle tasks are defined in the main component and passed down to child components as props.

- **Event Handling**: 
  - Task addition is handled via an `onSubmit` event in the `AddTodo` component.
  - Task deletion and completion toggling are managed through `onClick` events in the `TodoItem` component.


To do list using HTML, CSS and JS. 
The website should allow users to add tasks, mark them as complete, and delete them.
The content or the tasks added and their status will be saved even after closing the browser. 
1. HTML Structure
   The HTML file defines the structure of the To-Do list application. The following elements are included:
    The <link> element connects an external stylesheet for styling purposes.
    A container <div> is created to wrap the entire application.
    Inside the container, an <h2> heading contains the title "To-Do List" along with an icon.
    An input field and an "Add" button are placed inside a <div class="row">. The input field takes user input, and the button triggers the addition of tasks.
    An empty <ul> tag with the id list-container is used to display the list items dynamically.
2. CSS Styling
   The CSS file is responsible for styling the To-Do list. Key components include:
   The * selector to ensure all elements have zero margins and padding and apply the box-sizing: border-box to standardize sizing.
   The .container class defines the layout of the page and sets the background using an image.
   The .to-do-list class styles the list container, setting dimensions, background             
   transparency, margins, padding, and rounded corners.
   The .row class applies styles to the input and button elements, aligning them horizontally using display: flex.
   Custom styles for the list items (<li> tags) and the "checked" state, including the custom bullet points with images for unchecked and checked tasks.
3. Java Script Functionality
   The Java Script file controls the interactivity of the To-do list. It defines the following instructions:
   3.1 addTask()
     This function is trigerred when the "Add" button is clicked or the Enter key is pressed.
     The function checks if the input field is empty. If so, it alerts the user to add some text.
     Otherwise it:
       Creates a new <li> elemment with task text.
       Appends the newly created <li> to the listContainer.
   3.2 savedata()
     The savedata() function saves the current state of the To-Do list to the browser's local storage by converting the innerHTMNL of the listContainer to a string       and storing it. 
  3.3 show()
     The show() function is executed when the page is loaded. It retrieves the previously saved task list from localStorage and displays it.
  3.4 Event Listeners
     Input field listener: The keypress event listener on the input field allows the user to press the "Enter key" to add a task instead of clicking the button.

Conclusion: 
This project implemnents a fully functional To-Do List application with user - friendly feautures. Key problems such as creating, deleting and saving tasks are solved through an efficient combination of HTML, CSS and JavaScript. 
1. The HTML provides the structural foundation with intuitive elements like input fields and list containers.
2. The CSS enhances the visual desgign, ensuring a clean and modern look with responsive features.
3. The JavaScript implements dynamic functionality, including task creation, deletion, completion and local data persistence. 
     
         
       

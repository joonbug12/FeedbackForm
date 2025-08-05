# README
This repository is part of the react course for coursera. This exercise is meant to practice utilizing reacts useState hook to manage form data state which includes the users name, email, feedback, and rating
The handleChange function updates the form data state as the user inputs information into the form fields. After clicking submit, the 'handleSubmit' function prevents the default form submission behavior, displays a confirmation message with the users details, clears the form fields, and displays a thank you message after confirmation.
The form includes input fields for the user's name and email, a text area for providing feedback, and radio buttons for giving a rating

notes for myself:
when initializing a useState hook (ex. const[food, updateFood] = useState({})), whatever fields you put into the initial useState kindof works like making an empty constuctor in oop (ex. food.name:'',...)
data flow in this exercise in my head goes like
1: initializing the useState fields (ex. food.name, food.price,...)
2: then you're able to use the values of input and set it to food.name... by using a change handler
3: then you can use the new data to do whatever (in this case it was submitting a form) and at the end set all the fields back to the original value which is blank

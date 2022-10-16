# Passing-Thoughts-using-react
  This repository was created with codecademy to learn React.
# The purpose of the app
  Once you add a short thought, it’ll disappear after just 15 seconds.
# What i learned while coding this app
  To complete this project I get acquainted with the syntax of the JSX / function components / useEffect / useState.
You can see the deployment of the app at github pages

# My work

Everything that i write in this exercise is in the app.js / AddThoughtFrom.js / Thought.js.
At first I started with writing a function addThought() inside of App() in app.js. function addThought calling setThought and returns a new state with new thought at the front. Secondly I created a function named handleTextChange() in AddThoughtFrom.js then pass an event argument, and call setText() to update the state. Thirdly I created handleSubmit(when the form is submitted creating a new object and displaying it in the DOM).
At the end I wrote functions like removeThougt that take an id of the thought and removes it from the list. In thought.js I used the useEffect() hook to remove a thought after a 15 sec after a new render.

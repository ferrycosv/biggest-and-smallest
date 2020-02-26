# biggest & smallest: development strategy

Building this site one step at a time

## 0. Setup

(already complete)

## 1. Data & Log

(already complete)

## 2. Init

> * init.js
> * contains the code executed when the browser loads the webpage, renders the initial state of the data object 'numbers' to the screen by html tags, logs the initial operation as first record in the log array.

## 3. User Story: Save button

> * Makes sense to start coding the save function to grab and store the values from the html input and perform the logic to update the information of the data object.
> * save-number.js handler and listener
> * read the user input from the html input element, read the current state of the numbers data object and perform the update of the data object and render the last state to screen.

## 3. User Story: Reset button

> * After using the comparator functionality the user may want to start again from scratch, to save the user a few milliseconds refreshing the page, the reset button comes handy to put everything back to the same state from the start.
> * reset.js handler and listener
> * read the user input from the html input element, read the current state of the numbers data object and perform the update of the data object and render the last state to screen.
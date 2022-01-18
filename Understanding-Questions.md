# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
... The user clicks '1' which fires off the onClick event handle ('handleAddOne') which then dispatches the action (addOne()) that calls the action creator function and the reducer, executes the action, which is the 'state.total +1', and then renders the totalDisplay with the total plus 1

* TotalDisplay shows the total plus 1.

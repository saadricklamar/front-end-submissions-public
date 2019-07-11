# Palette Picker Submission Form

 [Project Spec](http://frontend.turing.io/projects/palette-picker.html)

 # Basics

 #### Link to the GitHub Repository for the BE
[palette-picker BE](https://github.com/AdamN8142/wilson-picker-backend)

 #### Link to the Deployed BE
(N/A)

 #### Link to the GitHub Repository for the FE
[palette-picker FE](https://github.com/saadricklamar/wilson-picker)

 #### Link to the Deployed FE
(N/A)

 ## Completion

 #### Were you able to complete the base functionality?

We have about 80% of the base functionality.

 #### Link to an image of your wireframe(s)

![wilson](https://user-images.githubusercontent.com/42000931/61059154-c7eb3780-a3b5-11e9-87b9-b7669fa415a4.png)

 #### Which extensions, if any, did you complete?
 
 - N/A

 # Code Quality

 #### Link to a specific block of your code on GitHub (from either repository) that you are proud of
 
 Using reduce to generate a hex value
[happy code](https://github.com/saadricklamar/wilson-picker/blob/master/src/components/App/App.js)

 * Why were you proud of this piece of code?  
- Lines 52-57: generateHex function. It was nice to utilize reduce on this project, since we haden't used it in a while. 

 #### Link to a specific block of your code on GitHub that you feel not great about
[sad code](https://github.com/saadricklamar/wilson-picker/blob/master/src/components/Projects/Projects.js)

 * Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?
- Lines 62-72: addPalette function. We really got stuck on trying to grab the id from the project. In the onClick of the save button we tried using an immediately invoked function to grab the project.id, but it would keep coming back undefined even if when we console.logged project.id, it was there. This problem is the main source of all our bugs.

 #### Link to Design Inspiration

 * Show us what you used as design inspiration (another color picker site, a dribbble UI element, a user flow, etc.) and explain what you stole from it  


Adam's love for home improvement. 


 #### Reflection on New Concepts

 * Describe your thoughts on server-side testing  
   Back end testing is easy compared to the front end where you have to mock out or spy on a lot of things. 

* Describe your thoughts on TravisCI  
  I'm not sure we know enough about it to provide any critical thoughts. 
  
* Describe your thoughts in creating a single project whose codebase was distributed across multiple repositories
  I think it makes your code more modular, but it's also a lot to keep track of. 

 -----


 # Instructor Feedback (Instructor Name)

 ## Specification Adherence

 **x score**: 

 ## User Interface

 **x score**: 

 ## Testing

 **x score**: 

 ## Workflow

 **x score**: 

 # Outcome: pass/fail

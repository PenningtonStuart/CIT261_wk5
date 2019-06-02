# CIT261_wk5
## This is to help Bro. Thayne see that my understanding of the intended topic is on par with the material
## due to my absence this week due to moving cross-country. 
This was a project that was intended to help students understand MVC (model, view, controller) 
type of arcetecture. These populate an html document with the proper pieces of the code. 

The model (data layer) - This is where the data is stored for an intended application. The model is
decoupled from the view and controller and has no clue as to the "wider context" of the project. Whenever
the model changes it will notify its observers.

The view (presentation layer) - This part of the app has access to the DOM (html) and is responsable for setting
up event handlers such as: click, onmouseover, onmouseout, etc. This portion of the app is also responsable for
the presentation of the html. 

The controller (application logic) - the controller is the glue that holds the model and view. The controller
processes and responds to events set off by either the model or view. It updates the model whenever the user
manipulates the view.

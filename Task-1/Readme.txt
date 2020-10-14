Maintain the folder hierarchy as given.

Then to run the file just go to "Task-1/Deployement/deployement.ipynb"
and execute that file.

How code is Working?
-------------------

1) In "Task-1/Task-1" My solution.ipynb we have made our simple linear regression 
ml model.

2) Saved that model as "student_marks_pred.pkl" .

3) For the deployement means making web application we have used html forms and 
flask(python web framework).

-> You can find the index.html file "Task-1/Deployement/templates/index.html".
-> In deployement.ipynb "Task-1/Deployement/deployement.ipynb" we have written
the flask code that gets the values from the html forms and by using our saved model
we predict the output and showing it.
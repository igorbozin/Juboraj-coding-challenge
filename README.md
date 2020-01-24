# Juboraj-coding-challenge



Challenge
Make a simple android todo app, where you retrieve data from the following two apis as explained below.

APIs
Please use the following APIs, which contain a json with:

http://jsonplaceholder.typicode.com/photos - albumId - id - title - url - thumbnail URL

http://jsonplaceholder.typicode.com/todos - userId - id - title - completed

### Task The app should display a list of all the users. The name of the user is their ID. Once you click on an user from the app list, the app should display two lists, in two separates tabs: - one with completed tasks and - another one with tasks which are not completed.

The lists have to have a sorting button: ascending, descending. When the user click on the task which is not completed, a new view should appear which is fetching all the images from the 1st api where the albumId = userId; next for each photo a start button should be visible. Also implement a posibility to select multiple images and save them to the photo gallery. Once all the images were saved to the gallery, the task should be completed. The UI should not be blocked while the images are being saved.

Once the user is clicking the button, a timestamp should be created and a timer should be started. From 5 to 0 seconds . When the timer reached 0, the task should be changed from not completed to complete and should be moved to the completed tasks list and the image should be saved to the galery.

In the main screen the user has to have the posibility to have a reset button. Once the user is pressing this button, the tasks have to be reseted to their initial status.

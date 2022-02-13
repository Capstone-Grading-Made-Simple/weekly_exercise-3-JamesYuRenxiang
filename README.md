# Mobile Application Development
## Exercise 3

1.	Modify the onClickListener of Follow/ Unfollow button to show a Toast message. The toast message will show Followed if the user clicks on the Follow button, and vice versa.

![This is an image](/images/toast.png)

2.	Create a new Empty Activity with the following configuration
* Activity Name: ListActivity
* Generate a Layout File: Checked
* Layout Name: activity_list
* Launcher Activity: Checked
* Source Language: Kotlin

3.	In the activity_list layout file, create an ImageView with ID (imageView), position it in the middle of the screen. (ID is case sensitive!)

![This is an image](/images/imageview.png) 

4.	Create an onClickListener for the image created in previous step. Upon clicking the image, an AlertDialog will appear as shown in the figure below.

![This is an image](/images/alertdialog.png)

5.	Upon clicking the View button, a random integer will be generated. The MainActivity (created in previous practical) will be launched, and the random integer is sent over. 

6.	Modify the MainActivity to display the random integer together with the name.

![This is an image](/images/userdesign.png)

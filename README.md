# Android_Studio_Load_Remote_Image
Use Remote Images in android app
The scipt shows how to load images from a remote location , into your android app
Am using Android Llolipop 5.1 as test device
The proceedure involves the use of asynchTask
You can copy the codes and use in your project , kindly replace the online links which I used with yours
Also you can follow these steps if any challenges :
Step One
Start a new project in android studio
Step two
copy in the activity.xml posted in the this  repo
step three 
Copy in the MainActivity ,into your project MainActivity 
Step four 
Creat a second activity and name it Main2Activity
this is for the navigation link which the second Button links to .
You can ignore the step four , but do comment out the intent and the button that refers to it(the intent), Else if you leave it you did get error
Step five 
Create an online location to store your image and use in the Asynch
AsyncTaskExample asyncTask=new AsyncTaskExample();
asyncTask.execute("http://apps.datasek.com/skyswash/test2.png.png");
Run your app.
Note
Please replace the link i used with your image url 
Android studio main flash constarints errors ,is so , please adjust the activity_main using the  design editor to handle possible constraints
textViews and ImageViews , may flag errors in naming e.g use @string , in this case i will suggest use the translations editor to crete the strings and append accordingly 
If any other challenges please contact me at seunamodeni@yahoo.com
Good Luck !

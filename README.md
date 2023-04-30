Role Challenge for Origin Health submitted by Neha HS(1BM19BT029)


Project Summary
here we are creating a single page application (SPA) using Javascript and the framework used here is REACT. I have also used HTML and css for the front end part. Here a link was provided containing 12 images and the objective of this SPA is to display all these images in a carousel format and being able to label and filter them manually as a user.

Features:
1.	Login Page

•	here the login page has two options: user and admin

•	only when the correct credentials are entered you will be able to access the respective dashboards

2.	User page

•	the user login details are neha and password is 123

•	the user can label all the images from the options given by the admin and can also remove any label using the cross button

•	the user can also filter out the images by using the filter option based on the labels which he has assigned to the images

3.	Admin page

•	here the login details are admin and password is 123

•	in the admin dashboard you can manually enter the labels

•	the admin has all the features as the user does except the one mentioned above


Installation 
1.	In the project directory, open the command terminal
2.	type npm install react-scripts: to download the react library
3.	then type npm start: to Run the app in the development mode.
4.	Open http://localhost:3000 to view it in your browser.








How To Use :
1)	This Is how the login page initially looks like once we run it. The dashboard has two login options namely admin and user. 
<img width="960" alt="Screenshot 2023-04-30 155956" src="https://user-images.githubusercontent.com/131997438/235352269-0d2e98bf-9d9d-49f5-a790-6a782c5e04f1.png">

 
2)	Once we click on user, we enter the login details(here the details are neha and the password is 123).
 <img width="960" alt="Screenshot 2023-04-30 160134" src="https://user-images.githubusercontent.com/131997438/235352295-ba2f3fcc-3799-4e47-9e62-829d27f64f0c.png">



3)	as soon as we click on login, we are taken to the user dashboard. here as we can see that no labels are available as the labels can only be entered by the admin and no one else. hence, we click on sign out to go back to the login dashboard and login as admin so that we can enter the labels.
<img width="942" alt="Screenshot 2023-04-30 175531" src="https://user-images.githubusercontent.com/131997438/235352919-095d08b7-e7a9-45bb-a6bf-bdf5541d3245.png">


 

4)	now we login as admin(here the login details are admin and the password is 123)
 <img width="960" alt="Screenshot 2023-04-30 160439" src="https://user-images.githubusercontent.com/131997438/235352398-98d6c1ea-543d-41d4-a3a3-47307982e1cf.png">




5)	 now as you can see in the admin dashboard we now get the option to enter the labels manually.
<img width="939" alt="Screenshot 2023-04-30 160527" src="https://user-images.githubusercontent.com/131997438/235352426-2302380d-a46d-409b-81d2-d968a6bae22d.png">

 
6)	here I have entered the label as horse for this image and now horse will be available as an option for labels for the user. eventually I also added two more labels namely cat and dog so totally now there are three labels for the user to chose from while labelling the images.
 <img width="947" alt="Screenshot 2023-04-30 160810" src="https://user-images.githubusercontent.com/131997438/235352456-d9987ed3-9833-4949-b388-f8bbd050169a.png">



7)	here we have signed out from the admin dashboard and signed back into the user dashboard and now we can see three options for labelling the images which was previously not available.
<img width="946" alt="Screenshot 2023-04-30 160953" src="https://user-images.githubusercontent.com/131997438/235352478-8c2ef171-416c-42c4-a0c3-71aa237e427a.png">

 
8)	here we chose the option horse and labelled this image as horse. there is also a small cross button available for the user to remove the label for a particular image.
 
<img width="947" alt="Screenshot 2023-04-30 161054" src="https://user-images.githubusercontent.com/131997438/235352496-1ebe4bfd-a4fb-4b3a-9a62-df0eb73ae44a.png">



9)	here we have labelled all the 12 images correctly and now we can see all the images with their respective label.
<img width="960" alt="Screenshot 2023-04-30 161238" src="https://user-images.githubusercontent.com/131997438/235352511-e68d46b3-a568-40aa-af9c-69b59f37d3ac.png">

 
10)	Here we are displaying the use of the filter option where in we can chose any one of the labels and this will filter out all the images with that particular label and only show those images and nothing else. Here I chose the label dog so all the images labelled as dog will appear.
 <img width="960" alt="Screenshot 2023-04-30 161326" src="https://user-images.githubusercontent.com/131997438/235352520-31455826-7201-4a3a-adc4-aa75b5c8a132.png">

 

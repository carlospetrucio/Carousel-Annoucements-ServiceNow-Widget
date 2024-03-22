<img src="https://raw.githubusercontent.com/carlospetrucio/ServiceNow/main/Service%20Portal/Widgets/Carousel%20Announcements%20Widget/ignore_files_md/computer-illustration.png" min-width="250px" max-width="250px" width="400px" align="right" alt="Computador CarlosPetrucio">

# Carousel Announcements
<img src="https://img.shields.io/badge/Carousel%20Announcements-Active-green.svg">

📜 This widget creates a carousel in the service portal that displays messages created in announcements.

💡 Use announcements to broadcast messages to Service Portal users.  
💡 Announcements are active on new instances.  
💡 You can activate the Service Portal Announcements plugin.    
💡 When creating announcements, you can define the way an announcement displays.   

You must know how to create a new widget.
```
https://docs.servicenow.com/bundle/rome-servicenow-platform/page/build/service-portal/task/create-new-widget.html
```
You must know what Announcements is and how it works.
```
https://docs.servicenow.com/bundle/rome-servicenow-platform/page/build/service-portal/concept/announcements.html
```
You should know how to create a new message in Announcements.
```
https://docs.servicenow.com/bundle/rome-servicenow-platform/page/build/service-portal/task/create-announcement.html
```  
## 🛠️ Widget Carousel was built with

Applications and Frameworks that I used to create the project.

* [ServiceNow](https://docs.servicenow.com/bundle/quebec-release-notes/) - ServiceNow with instance in Quebec version.
* [BootStrap](https://getbootstrap.com/docs/5.1/) - Framework for developing interface and front-end components with version v5.1.3.
* [Angular](https://code.angularjs.org/1.5.3/docs/api) - JavaScript FrameWork with version 1.5.3.  


### 🔧 Installation


<details><summary><b>Show instructions</b></summary>
  
Step 1 - Fork the project on github so that you have your version of the code and can customize it if necessary.  

![image](https://user-images.githubusercontent.com/50377984/143965623-e8e81700-484b-439c-8f6f-f619e3e13a3e.png)


Step 2 - Using the filter navigator, search for the widget module inside Application menu Service Portal.    

![image](https://user-images.githubusercontent.com/50377984/143965567-f76f38cd-dab6-44a2-b6b3-ea5831f09ceb.png)


Step 3 - Use the "New" button to create a new widget.    

![image](https://user-images.githubusercontent.com/50377984/143965487-9323e659-ebb3-424e-a568-3f986a4e89f2.png)

Step 4 - Now you should define a name, description and "ID" for your widget, then click the context menu and save. (Burger Menu)  

![image](https://user-images.githubusercontent.com/50377984/143965181-178b00b9-5c17-4cc4-abac-812251a75bdb.png)

Step 5 - After performing the fork you will find the folder "Instance files" copy the code from the file "HTML Template.html" and paste it into "Body HTML template" in the widget editor.  

![image](https://user-images.githubusercontent.com/50377984/143966115-c7cc1143-4209-4c05-8ca2-7793d869101a.png)

Step 6 - Copy the contents of the file "CSS - SCSS.css" and paste it into "CSS" in the widget editor.  

![image](https://user-images.githubusercontent.com/50377984/143966291-0b37caf4-4159-4b95-9441-abc2767c3c37.png)

Step 7 - Copy the contents of the file "Serve Script.js" and paste it into "Server script" in the widget editor.
It will be the code responsible for connecting to the annoucements table.  

![image](https://user-images.githubusercontent.com/50377984/143966496-9bdeff93-1f4b-4e66-8cab-d9f4681fb685.png)

Step 8 - Copy the contents of the file "Client Script.js" and paste it into "Client Controller" or "Client Script"  if you are using the editor widget.  

![image](https://user-images.githubusercontent.com/50377984/143966753-1d10ee77-a391-4903-8762-6bebf8c10edd.png)
  
  
</details>

### 🥳 Creating the first "Announcement"
<details><summary><b>Show instructions</b></summary>
Using the filter browser, look for the Ads module within the Service Portal Application menu.
Now on the right you will see the "announcement" table click "new" to create a new message.

![image](https://user-images.githubusercontent.com/50377984/143966985-ccf7ec06-7998-491c-9206-7c9e6c09ed5b.png)
</details>

### ⚠️ How to add the widget to the portal  

<details><summary><b>Show instructions</b></summary>
It is important to remember that after creating the widget and its messages, you must still instantiate the widget in your portal.  

Step 1 - Using the filter navigator, search for the portals module inside Application menu Service Portal and click on the service portal you want to add the widget.  
![image](https://user-images.githubusercontent.com/50377984/143967945-37f67b5a-b61f-46f6-a9d3-c7608b6dc54b.png)  

Step 2 - Using the information icon "i" access directly the record of the index page of your portal which is configured in the "HomePage" field.  
Step 3 - Typically, the carousel is added to the first container on the page, in the first row and in the first column, so that it is at the top of the page. Let's create a new container, with one row and one column, we'll use order to put it first.  
![image](https://user-images.githubusercontent.com/50377984/143968299-c2c8d024-9861-47bb-92b0-60d4e40bf314.png)  

Step 4 - Now inside the column, go down to the bottom of the page in the tab "instances" click on new to create a new instance inside this same column.  
![image](https://user-images.githubusercontent.com/50377984/143968379-ffb18502-cec2-4b21-8715-abff7c651b29.png)

Step 5 - Choose an intuitive name for your instance and in the widget tab choose the widget we created and configured earlier.  
Now just click submit.  
![image](https://user-images.githubusercontent.com/50377984/143968484-3ea24acc-eefa-4fd6-a414-a42b1edac852.png)

Step 6 - Let's see the final result.  
![image](https://user-images.githubusercontent.com/50377984/143969546-57514d54-dd5c-4f79-82a5-d2df147cc61a.png)

</details>




### ⚠️ Important
<details><summary><b>Show instructions</b></summary>
For your message not to be displayed as a banner and only to be displayed inside the created widget, you must remove the option "banner" in type during the creation of the message.  
In the tab "portals" you can choose if you want this message to be displayed in a specific service portal, this is useful when you have many portals and specific messages for each portal.  
  
![image](https://user-images.githubusercontent.com/50377984/143967431-94af8cee-8ad7-4327-afbd-bc49706b07e0.png)
</details>

## ✍️ Created by
<a href="https://www.linkedin.com/in/carlospetrucio/"> Carlos Petrucio </a>
## ☕ You have a project and you need help, let's have some coffee 🥳
<p align="left">
  <a href="mailto:carlospetruciofreitasbarbosa@gmail.com" alt="Gmail">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=" /></a>

  <a href="https://www.linkedin.com/in/carlospetrucio/" alt="Linkedin">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=" /></a>

  <a href="https://api.whatsapp.com/send?phone=5511986053073" alt="WhatsApp">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link="/></a>

  <a href="https://www.facebook.com/CarlosPetrucioo" alt="Facebook">
  <img src="https://img.shields.io/badge/-Facebook-3b5998?style=flat-square&labelColor=3b5998&logo=facebook&logoColor=white&link="/></a>

  <a href="https://www.instagram.com/carlosfreeitas/" alt="Instagram">
  <img src="https://img.shields.io/badge/-Instagram-DF0174?style=flat-square&labelColor=DF0174&logo=instagram&logoColor=white&link="/></a>
</p>  

[⬆ Back to the Top](#Carousel-Announcements)<br>






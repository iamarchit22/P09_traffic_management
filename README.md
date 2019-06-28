# Traffic Management - Face Recognition/Number Plate Detection With Android & OpenCV
TMS is an open source android application that does face recognition using OpenCV and Number plate Detection using Android-OCR, Originally made for Traffic officers who are working on roads, TMS can be used to replace the old method of Challaning traffic offenders(which was done by filling a paper-challan form, that required a lot of effort to store them safe from any disaster)

### Credits
- [https://github.com/shikshaarora/](https://github.com/shikshaarora/)
- [https://github.com/Nivedita29/](https://github.com/Nivedita29/)
- [https://github.com/iamarchit22/](https://github.com/iamarchit22/)

### Technology Stack:
  1. Front-End Language: Java
  2. Back-End Language: PHP 5.0


### Screenshots
<img src="https://github.com/MIETDevelopers/2015_CSE_A1_P9_TrafficMgmtSsytem_Shiksha_Archit_Nivedita/blob/master/docs/static/1.jpg?raw=true" width="60%" height="2800px"/>
<img src="https://github.com/MIETDevelopers/2015_CSE_A1_P9_TrafficMgmtSsytem_Shiksha_Archit_Nivedita/blob/master/docs/static/2.jpg?raw=true" width="60%" height="2800px"/>
<img src="https://github.com/MIETDevelopers/2015_CSE_A1_P9_TrafficMgmtSsytem_Shiksha_Archit_Nivedita/blob/master/docs/static/3i.jpg?raw=true" width="60%" height="2800px"/>
<img src="https://github.com/MIETDevelopers/2015_CSE_A1_P9_TrafficMgmtSsytem_Shiksha_Archit_Nivedita/blob/master/docs/static/4.jpg?raw=true" width="60%" />

***Face Recognition:***
1. **Home page** - For switching between face recognition and number plate detection.
2. **Home > ADD NEW ENTRY (enter name)** - Enter name of person standing in front of camera.
3. **Home > ADD NEW ENTRY (enter name) > Capture** -  Capture image.
4. **Home > Recognition** - Recognize faces
5. **Home > Recognition > Submit** - Display name of person.

***Number Plate Detection***
1. **Home page** - For switching between face recognition and number plate detection.
2. **Home > Number Plate Detection > Choose_from_galary/Take_a_picture**- Insert picture of the vehicle
3. **Home >  Number Plate Detection > Choose_from_galary/Take_a_picture > Textbox**-  Extract the Characters from vehicle number plate and display it.
4. **Home > Number Plate Detection > Challan** - Fill the details of violator along with picture of his/her Driving Licence Card.
5. **Home > Number Plate Detection > Database** - Search the database using any known identity of the violator to get his pervious records.


**General Instructions**

- Clone this repository
- Open project in android studio
- Compile, install the Apk
- For Face Recognition: Go to training, set an ID and capture a face to train. Repeat this a couple of times with different people and IDs
- Go to recognition, click scan and try to capture everyone in the video stream. The detected faces will be recognized and name of person will be shown.
- For Number Plate Detection: Go to Number Plate Detection, Either "click a picture" or "Choose from gallery" picture of vechile, and then the number plate characters will automatically be generated.
- To Challan a Violator: go to Challan, enter his licence number, 
                  if he has previous records, all his personal details will be shown,
                  else he might not have any previous records,
   Enter all the details in the form along with a picture of his Driving Licence Card and register him into database.
- All the Above Details extracted(Name,Licence Plate,Driving Licence Number) can be used to search the existing database to find any previous record of that person.

### Known Issues & TODO
- Face recognition is not accurate.
- Slows down as number of training images increases.

### Server Requirements:
- Server Software Requirement: MYSQL
- Database Hosted at: [https://www.000webhost.com](https://www.000webhost.com)
- Server User Id: 
                   1. DB Name: id7829987_criminals
                   2. DB User: id7829987_crime
                   3. DB Host: localhost
                   4. DB Password: *********
 - Current PHP Version for file hosting: PHP 5.5
 
 ### Steps To Create a Dummy Table in database:
 1. Create a db and give any name to it.
 2. apply the following code under SQL Query: [https://github.com/MIETDevelopers/CRIE_TrafficMgmt/blob/master/dummy%20db%20table.txt](https://github.com/MIETDevelopers/CRIE_TrafficMgmt/blob/master/dummy%20db%20table.txt)
 3. New Dummy Table is created.

### tested on
- Android 6.0 Marshmallow (Oppo A57)
- Android 8.0 Oreo (Samsung J7, Samsung C9, MI A1)

### Licence
MIET

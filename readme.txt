The folder contains:
1. Assignment5.zip--The complete assignment with readme file.
2. rjammula_swe5.zip, the project folder of assignment 5.
3. r4.ear, the ear file of the project.
4. StudentSurvey.jar, the folder containing the ejb modules of the project.
5. swe4.war, the war file for the UI of the project.
6. standalone.xml, the standalone file for the project.
7. readme.txt--the readme file
8.wsdl.txt, the text file containing the generated WSDL,


swe4.war file contains:
1.The homepage.jsp page which contains has links to complete a survey , previously completed surveys and do a custome search.
2.The survey1.jsp page which contains link to the survey page.
3.The Simple Acknowledgement.jsp page which is returned if mean is less than 90 and it contains mean, standard deviation and student name.
4.The Winner Acknowledgement.jsp page which is returned if mean is less than 90 and it contains mean, standard deviation and student name.
  It also displays a message saying the student has won two movie tickets.
4. The search.jsf, the file to perform a custom search.
6. surveylist.jsf, the list of completed surveys.
7. surveylistsearch.jsf, the file returned after a custom search.
 
8.Student.java, the model which has attributes matching on the survey form and a bean that contains a reference to student model object
9.StudentService.java, it contains the business logic to store and read data of the survey form. In addition also has the method to calculate mean and standard 
  deviation and directs accordingly to the respective page.
10.WinningResult.java, a model which contains properties to hold mean and standard deviation. 
11.Searching.java, the model which has attributes matching to the search form.


StudentSurvey.jar contains:

1. Delete.java, DeleteRemote.java, the EJB for deleting data.
2. Save.java, SaveRemote.java, the EJB file for storing data.
3. Show.java. ShowRemote.java, the EJB for displaying data.
4. Survey.java, the EJB for the survey form.


Running the project:
1.Import r4.ear file
2.Replace standalone.xml file in WildFly with the one attached.
3.The WSDL URL of my project is http://localhost:8080/StudentSurvey/Show?wsdl
Show.java is my file where changes have been made to act as SOAP based Web service.
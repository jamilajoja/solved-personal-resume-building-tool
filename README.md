Download Link: https://assignmentchef.com/product/solved-personal-resume-building-tool
<br>
5/5 - (4 votes)

Create a personal resume building tool. Form elements will be used to accept user input which will be assigned to variables. These variable values will make up the content of a new Web page that will be generated when a form button named Create Resume is clicked. This is called building a Web page “on-the-fly”.

1. Create an HTML document named finalProject. The title bar (tab) should read WEB 115 Final Project.

2. Create an external JavaScript document (with the .js file extension) named projectJS.js. In projectJS.js, enter the code that will write your name with the following formatting: H1 header, red, Tahoma font, centered text. On a new line, your JavaScript must write your course and section number with the following formatting: H2 header, Garamond font, red, italicized, centered text. All remaining JavaScript must be coded in this document.

3. In your HTML document named finalProject, write the Javascript code (after the opening BODY tag) that will link to your external JavaScript document named projectJS.js so that your name, course and section number appear in the finalProject.htm Web document.

4. Create a horizontal rule that is sixty percent of the width of the viewer’s screen in finalProject.htm

5. Create a centered title that reads Build Your Resume.

6. Use break and paragraph tags in order to make all of the following elements easy to read and understand.

7. Create a text box with the appropriate prompt (not the prompt method) so that the user knows to enter their full name.

8. Create a text box with the appropriate prompt (not the prompt method)  so that the user knows to enter their full address.

9. Create a text box with the appropriate prompt (not the prompt method)  so that the user knows to enter their phone number

10. Create a text box with the appropriate prompt (not the prompt method)  so that the user knows to enter their e-mail address

11. Write JavaScript code to validate the e-mail address input. Make sure that the user has entered the @ symbol. No resume should be generated until this validation is completed.

12. Use the form textarea tag to create a text entry area with the appropriate prompt (not the prompt method)  so that the user knows to enter their personal data.

13. Use the form textarea tag to create a text entry area with the appropriate prompt (not the prompt method)  so that the user knows to enter their career objective.

14. Use the form textarea tag to create a text entry area with the appropriate prompt (not the prompt method)  so that the user knows to enter their Educational background.

15. Create a text box with the appropriate prompt (not the prompt method)  so that the user knows to enter the entry and exit dates of their most recent employment experience. IMPORTANT! For this item you must use the input “date” element. Example: which will generate a calendar when clicked. Use the value property to extract the user’s selection. Example: var firstDate = document.getElementById(“myDate1”).value16. Use the form textarea tag to create a text entry area with the appropriate prompt (not the prompt method)  so that the user knows to enter the details of their most recent employment experience.

17. Repeat steps 14 and 15 to allow for 3 more prior employment experience data entry areas.

18. Use the form textarea tag to create a text entry area with the appropriate prompt (not the prompt method)  so that the user knows to enter the details of their business references.

19. Create a form button named Create Resume. When clicked this button should call a function that generates a new Web page displaying a resume based on the user input. Use the document.write() method to populate the newly generated Web page with all of the HTML elements, formatting and variable values needed to produce the desired output in Web (.htm) format.

HINT: a monospaced font will allow text wrapping in your output. You may also provide for this using CSS.

Example of a pop up window and form submission:&lt;html&lt;head&lt;title Pop-up on the fly &lt;/title&lt;script

function myWindow(){visitorName = document.getElementById(“myInput”).value;myText = (“&lt;html
&lt;head
&lt;titleWelcome&lt;/title
&lt;/head
&lt;body
”);myText += (“Hello ” + visitorName + “, this page was created on-the-fly!”);myText += (“&lt;/body
&lt;/html”);

flyWindow = window.open(‘about:blank’,’myPop’,’width=400,height=200,left=200,top=200′);flyWindow.document.write(myText);}

&lt;/script&lt;/head

&lt;body&lt;form id = “myForm”
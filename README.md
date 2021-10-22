# WORLDCUP 2019 WEBSCRAPING PROJECT🏏 

## ABOUT:
-The purpose of this project is to extract the information of Worldcup 2019 from Cricinfo
 and present that in the form of excel and pdf scorecards. <br>
-To solve real purpose problems of extracting large information from websites. <br>
-A very good reason to make this project is to have good fun with webscraping. <br>


## TECH STACK:
-JAVASCRIPT <br>
-Node modules used: <br>
    -  Minimist-> Takes command line arguments <br>
    -  Axios-> For making http request <br>
    -  JSDOM-> For getting information from dom tree <br>
    -  EXCEL4NODE-> Used to make excel file <br>
    -  PDF-LIB-> Used to make scorecards in the form of pds <br>


 ## FEATURES AND FUNCTIONS:
 -Read the command line arguments using minimist. <br>
 -Read the HTML file use axios and convert it to DOM using JSDOM. <br>
 -Using HTML elements and their class read the data which we need and push it into a JSO object. <br>
 -Using the above JSO object with all match details we make another JSO which has team details using array manipulation. <br>
 -Using the teams JSO and excel4node create an excel file with every team match details in a sheet. <br>
 -Make folders using fs. <br>
 -Make a template.pdf using MS Word beforehand, and add the data in that pdf for each team and its matches using pdf-lib. <br>
 
 
 ## EXTRACTED INFORMATION USING JSDOM LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136846517-4868ec6f-c2e8-4d4d-ab57-e521b14d52ae.png)<br>
  But we want to categorize the teams with their matches.
  

 ## AFTER ARRAY MANIPULATION THE INFORMATION LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136846870-c12ba320-2e6e-4963-8af0-fae193a22782.png)


 ## EXCEL FILE AFTER EXCECUTION LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136847359-6af18246-4a75-4a43-b930-bcbf284d20ab.png)


 ## TEMPLATE PDF:
 ![image](https://user-images.githubusercontent.com/56155933/136847014-6c8f3b18-1b7e-45b9-8eeb-72b313d2fd78.png)
 

 ## PDF FILE AFTER EXCECUTION LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136847566-9a464689-ad39-4582-8784-7045c4d9987f.png)

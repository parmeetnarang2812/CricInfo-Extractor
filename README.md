# CricInfo-Extractor -> A Web Scrapper

## ABOUT:
-The purpose of this project is to extract the information of Worldcup 2019 from Cricinfo
 and present that in the perform of excel and pdf scorecards. <br>
-To solve real purpose problems of extracting large information from websites. <br>
-A very good reason to make this project is to have good fun with webscrapping. <br>


## TECH STACK:
-JAVASCRIPT <br>
-Node modules used: <br>
    -  Minimist-> Takes command line arguments <br>
    -  Axios-> For making http request <br>
    -  JSDOM-> For getting information from dom tree <br>
    -  EXCEL4NODE-> Used to make excel file <br>
    -  PDF_LIB-> Used to make scorecards in the form of pds <br>


 ## FEATURES AND FUNCTIONS:
 -Dowloading data in the form of HTML by making a http request using axios as we are not using any browser so axios will help to achieve this. <br>
 -Reading HTML and extracting important and useful information using Jsdom. <br>
 -Converting matches to teams using Array Manipulation. <br>
 -Creating excel file and adding appropriate stuff in that excel using excel4node library. <br>
 -Creating pdfs by making changes to Template pdf using pdf-lib library. <br>
 
 
 ## EXTRACTED INFORMATION USING JSDOM LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136846517-4868ec6f-c2e8-4d4d-ab57-e521b14d52ae.png)<br>
  But we want to categorize the teams with their matches.
  


 ## AFTER ARRAY MANIPULATION MADE THE INFORMATION TO LOOK LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136846870-c12ba320-2e6e-4963-8af0-fae193a22782.png)


 ## EXCEL FILE AFTER EXCECUTION LOOKS LIKE THIS:
 ![image](https://user-images.githubusercontent.com/56155933/136847359-6af18246-4a75-4a43-b930-bcbf284d20ab.png)


 ## PDF TEMPLATE BEFORE:
 ![image](https://user-images.githubusercontent.com/56155933/136847014-6c8f3b18-1b7e-45b9-8eeb-72b313d2fd78.png)
 

 ## PDF TEMPLATE AFTER:
 ![image](https://user-images.githubusercontent.com/56155933/136847566-9a464689-ad39-4582-8784-7045c4d9987f.png)

 ## TO RUN THIS ON YOUR LOCAL MACHINE:
   First fork this to your profile, then clone it to your desktop<br>
   
   Then install libraries:<br>
   npm install minimist<br>
   npm install axios<br>
   npm install pdf-lib<br>
   npm install excel4node<br>
   npm install jsdom
  
  To run this project use this command: <br>
  node CricinfoExtractor.js --excel=worldcup.xlsx --dataFolder=data --source="https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415/match-results"

 ## CONTACT:
 In case of any suggestions or enquires, feel free to reach out to me.

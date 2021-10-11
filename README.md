# CricInfo-Extractor - A Web Scrapper

## ABOUT:
->The purpose of this project is to extract the information of Worldcup 2019 from Cricinfo
  and present that in the perform of excel and pdf scorecards.
->To solve real purpose problems of extracting large information from websites.
->A very good reason to make this project is to have good fun with webscrapping.

## TECH STACK:
-JAVASCRIPT
-Node modules used:
    -  Minimist-> Takes command line arguments
    -  Axios-> For making http request <br>
    -  JSDOM-> For getting information from dom tree
    -  EXCEL4NODE-> Used to make excel filr
    -  PDF_LIB-> Used to make scorecards in the form of pds



create folders of every team (data folder -> India, Australia, etc) and prepare pdfs of every team in it.

 ## FEATURES AND FUNCTIONS
 Dowloading data in the form of HTML by making a http request using axios as we are not using any browser so axios will help to achieve this.
 Reading HTML and extracting important and useful information using Jsdom
 Converting matches to teams using Array Manipulation
 Creating excel file and adding appropriate stuff in that excel using excel4node library
 Creating pdfs by making changes to Template pdf using pdf-lib library.
 
 ## EXTRACTED INFORMATION USING JSDOM LOOKS LIKE THIS
 But we want to categorize the teams with their matches
 ![image](https://user-images.githubusercontent.com/56155933/136846517-4868ec6f-c2e8-4d4d-ab57-e521b14d52ae.png)


## AFTER ARRAY MANIPULATION MADE THE INFORMATION TO LOOK LIKE THIS
![image](https://user-images.githubusercontent.com/73028420/136691512-59e3a8aa-9183-464c-bbc5-1ba7e347f4cf.png)

 
 ## TEMPLATE BEFORE 
 ![image](https://user-images.githubusercontent.com/73028420/136662552-6e4c351f-ef22-4a30-bba6-669e453fc13b.png)
 
 ## EXCEL FILE AFTER EXCECUTING SCRAPER
 ![image](https://user-images.githubusercontent.com/73028420/136662663-9493cb60-4773-43dd-9299-67fc711d2fb9.png)
 Have a look at this excel file!
 Below are scorecards and excel file having all info.

## TEMPLATE AFTER
![image](https://user-images.githubusercontent.com/73028420/136662761-076358f4-e672-4c5e-b79e-2edba1223caa.png)

## TO RUN THIS ON YOUR LOCAL MACHINE
   First fork this to your profile, then clone it to your desktop
   
   Then install libraries 
   ```bash
  npm install minimist
  npm install axios
  npm install pdf-lib
  npm install excel4node
  npm install jsdom
  
  ```
  
  To run this project use this command
  
  ```bash
  node --source="https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415?ex_cid=ipl2021:google_cpc:search:dsa_feed:msn&gclid=Cj0KCQjw-4SLBhCVARIsACrhWLVv_gGK-NVT1D36fINNofAKdPwIUdjuwmCWE-PuMJCRl3rGClYu5N4aAuJWEALw_wcB" --dataFolder=data --excel=WorldCup.csv
 ```

## CONTACT
In case of any suggestions or enquires, feel free to reach out to me.

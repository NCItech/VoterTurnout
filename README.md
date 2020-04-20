# Voter Turnout GitHub Primer
### Prepared by the Newcomb Institute Digital Research Interns

## THE DATA
#### This database houses data focused on local services in the general New Orleans area. The databases collected here contain a range of information on services such as Bike Lanes, Hospitals, Public Gardens, and other local government services. The data housed on this GitHub has been collected from a variety of websites that host open data. For the most part, the data was originally collected by Louisiana Government Departments. The websites that the data was pulled from include:
* https://datadriven.nola.gov
* https://www.511la.org/
* http://www.city-data.com
#### The majority of files are stored as CSVs (Comma-separated values) that can be opened in an accessible way in a spreadsheet software (Excel, Numbers,Google Sheets, etc). The titles of the columns are found at the top of the sheet, and descriptions of each data set can be found in the census document. This census document also includes the original link to the data and other information on its quality and can be found in the main directory of this repository, or at this Box link [here](https://app.box.com/file/529825835606).

## WHAT IS GITHUB AND HOW TO ACCESS IT
#### GitHub is a code hosting platform for version control and collaboration, allowing multiple people to access data and code from anywhere. The Voter Turnout data is kept in a repository. A repository is used to organize a project on GitHub and can contain folders and files, videos, spreadsheets, and data sets. 

### Cloning vs Downloading GitHub Data:
#### Cloning vs downloading data is a fundamental difference in how you choose to use GitHub and access data. Your needs and uses for the data will direct you in which method you should move forward with.
#### Downloading:
#### Downloading data is something you regularly do from the internet, as you likely download files daily. Downloading is not unique to GitHub and is not its main functionality. Downloading will store the most recent version of the data at the time of download onto your computer, excluding the fundamental .git folder. The .git folder contains all the information about changes made to the project over time and is not necessary to download with the other data, as it is only used to track changes for version control. The download function should be used if you only wish to store static data (data that will not update if changes are made in the future) from the repository and likely will only access it once.
#### Cloning: 
#### Cloning data enables you to use functions of git, including complete histories of the data and an ability to interact with it after the initial download. Cloning can be compared to Google Docs, in that multiple people can have access to edit the data. However, unlike Google Docs, none of these changes are made directly on the main copy immediately. To do that, you must have access to the main repository (granted by the owner), and then “push” your changes. 

## SOFTWARE AND TOOLS
#### You do not need to download GitHub if you’re only planning to download the data once. However, if you wish to get regularly updated data, you will need to download GitHub [here](https://desktop.github.com/)
#### To use GitHub, you should also be able to open your computer’s terminal or command line, which can be found [here](https://macpaw.com/how-to/use-terminal-on-mac) for Mac users and [here](https://www.digitalcitizen.life/7-ways-launch-command-prompt-windows-7-windows-8) for Windows users.
#### In general, to access or download GitHub and these databases, you will need an internet connection and the ability to download files onto your computer. Additionally, in order to view the databases, you must have access to a spreadsheet software. These include Excel- a program that is included with Microsoft Office, Google Sheets - a free software that can be accessed with a google account, or any other program with similar capabilities. 

## NAVIGATING THE GITHUB
#### In order to access the files stored on the GitHub, find the button in the top right saying clone or download.
![Image of GitHub buttons](https://i.stack.imgur.com/kjeQ9.png)
### To Download: 
#### You can then either select Open in Desktop or Download ZIP, depending on where you would like to store the downloaded files. Once saved on your machine, you can access these files directly.
### To Clone:
#### To clone, you’ll need to copy the web URL given, which can be easily done by clicking the icon next to the link. Then, you’ll need to enter your terminal and use the “git clone” command. Instructions can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## LIMITATIONS
#### The files stored on the GitHub have been downloaded from the most recent data on the nola.gov site as of December 2019. It does not automatically update, which proves to be the greatest limitation of its use. The owner of the repository will need to download data from nola.gov, regularly replacing files. 
#### If the owner updates the files, these changes can be received by anyone previously accessing the data either by redownloading the data or pulling from the repository, if it is cloned on their computer.  The options for pulling data are explained in further detail [here](https://help.github.com/en/github/using-git/getting-changes-from-a-remote-repository).

## DATA QUALITY
#### As previously stated, the data sets housed in this GitHub contain information on the availability and use of public services offered in the New Orleans, Louisiana region. A broader goal of this collection will be to compare this data with voter turnout data to analyze if effective government services, or the lack thereof, affects voter turnout in this particular region. This collection of databases,however, has many applications for research beyond voter turnout analysis. 
#### Since most of these records are collected and reported by government agencies, the data made available is limited to what these agencies choose to make public. 
#### Other factors that affect the quality and usability of this census include the presence of datasets that are large, unclear or disorganized, sparsely populated, or containing data outside of the New Orleans area. 
#### More details on the quality of each dataset can be found by accessing the census [here](./Data_Census.xlsx). Each database has been rated on a scale from 1-10 on quality with notes explaining each rating. 

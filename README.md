# Airbyte
## SET UP FOR A GOOGLE SHEET TO  GOOGLE SHEET CONNECTIONS

1.	Visit the official website for airbyte : https://airbyte.com/. Now click on the login and setup you account.
2.	To begin, set up the source by creating a new one and selecting the desired connection type. Additionally, you have the option to build a custom source using the available option in the left navigation panel. 
3.	To begin using Google Sheets as your data source, you'll first need to authenticate with your existing Gmail account. Once authenticated, create a new Google Sheet in your Google Drive. Next, click on the share URL option and paste the generated URL into the spreadsheet link section. Ensure you provide editor access while sharing, and then generate the link to proceed further. For additional guidance, you can find detailed instructions on the right side of the screen.
 
4.	Create a destination in a similar manner. If you cannot locate Google Sheets, ensure that you have enabled the alpha checkbox directly on the page.  
5.	Now set up the connection by navigating on it from left side panel.Click on the connection and set up a new connection.Define the source that you’ve created i.e Google sheets.  
6.	Now select the destination from the existing and click setup.  
7.	Now configure connection.  
8.	Go to Status→ open details →and then you can select append or overwrite.
9.	  


## SETUP FOR CUSTOM CONNECTION

1.	Go to the builder from the left navigation panel and create new custom connector.
 
2.	Select start from scratch option. 
3.	After completing this fill out the title and enter the API from where you’ll be fetching the data. In this case I’ve used random API: https://randomuser.me/api

 

4.	Now we have to create streams for this connector. Enter the url as random api. 
5.	You can click on the test on right hand side just to check if you are able to get the data from the api.
 

6.	You can scroll down and go to transformation if you wish to remove certain attributes. Here we will remove the info field.Finally publish to workspace. Check this for more info : 
7.	You can view this connector on custom connector section. 
8.	Now go to the source section and search for setup new source.Search for the custom connector that you’ve just created.
  
9.	Now set up the source.  
10.	Now add a connection to this source and define your destination.Select set up a new destination and check the alpha box. Select google sheets.

 
11.	Now sign in with google and enter the URL link of google spreadsheet and you can create on your drive. (Make sure you have given the editor access)
 
12.	Finally set up connection.  
13.	New connection is created.

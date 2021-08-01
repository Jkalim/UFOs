# UFOs

## Project Overview
The purpose of the analysis is to determine be able to filter the data for the date, city, state, country, and shape based on user input. 
As the user input the entry, the table will only show the data searched.  


## Resuslts
The original page of the web app will show all the data. Since the data is lengthy, a filtered option was added to search for the 
data the user is interested in. The user can search the desired data by searching one or more of the following fields: date,
city, state, contry or shape. As the user input more fields the data will narrow down to only the input searched. The more 
specificic a user is, the narrower the table will get. Users have to make sure they use the proper format to input in the field 
as show in the field bar as follow then press enter to get the desired results:
 - To search by dates, the input as to be similiar to 1/10/201
 - To search by cities, the input needs to be the full city name such as Benton
 - Only the state's abbreviation is required for state search such as ca for California
 - Country search is only the US and us is used
 - Shape search requires the shape input such as circle. 

  
## Summary
This is certainly a good start to put the page together but it looks like we can only search one city, or one state and so
one at a time which is a major drawback for web app. A useful recommendation would be to search for more than one key word
in the different fields such as ca and fl for California and Florida or triangle and circle for shape etc. Two other useful 
recommendations are to show the possible option for the fields and use clicked boxes for the desired input instead of user input. 
Because there are so many options for each field, it is best to not have the user guess what to input. It is best to have the user
avoid inputting options that return nothing. For example, it is best to show the users the possible shapes that are available to them 
instaed of having them choose an option that does not exist such as parallellogram. Parallellogram is a shape but does not show here. 
So, it is best to avoid such situation. And the best way to show all the option is to have a clicked box for each field. Users
can easily click on the wanted options and filter the table accordingly. 

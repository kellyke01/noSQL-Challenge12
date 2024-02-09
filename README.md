With this challenge I was able to create an instance in MongoDB and name it uk_food. them i was able to add the collection 'establishments' and have it run through successfully.
I was able to reference the database in jupyter and display both uk_food and the establishments were in MongoDB.

with the update first worksheet of this challenge I was able to do all of the following:
The new restaurant was able to be added to the collection and i was able to check that in MongoDB.
I updated it's Business type ID and was able to return that and the business type in the output.
I used update_many to convert the lat and longitude to decimal numbers AND to convert RatingValue to integer numbers as well.
I deleted all establishments that referenced Dover and was able to run a return showing that respective change as well.


The analysis section was the next step in this challenge.
I ran a query for all establishments with a hygiene score of 20 and was able to count them all up.
I converted my results to a pandas dataframe and displayed the first 10 rows.
The rating value of greater than or equal to 4 was set up in a query using $regex and a count was done to display how many returns it had.
These results were then converted to a pandas dataframe and I displayed the first 10 rows.
The establishments within 0.01 degree of the new restaurant 'Penange Flavours' was set up in another query while also using limits and sorts listed in the challenge's rubric.
The results were then displayed again using Pandas.
I ran an aggregate pipline to include match query, group and sort.
Then I ran the first 10 results of that query with pprint.
I converted the results to a pandas dataframe and displayed the first 10 results as well.


One huge challenge I overcame in this was that my kernel in jupyter was not connecting- it took me 4 days to figure out how to work through it and get it running again.
That was my biggest challenge as of recent.


One thing I struggled with was uploading the uk_food and it's respective collection 'establishments' to this hub. 
I had to export only certain columns in order to get the file size adequate enough to be size capable in github.
So therefore, not all of the columns that were in the original collection are in this json submitted into github. 
However, all of the columns referenced in all of the worksheets are in this json!

I was able to use a lot of references by Dr. A in order to get this homework completed and am happy to say it all ran successfully for me.


## SUMMARY
This is a data summarisation of the difference students in different schools, showing their various id, grades, scores and so on, and how we did a step by step work to get the data, prepare(clean) the data and analysing it using the Big Picture Analysis and Targeted Analysis. The following will be a brief explaination/discoveries of each deliverables:

Deliverable 1; was just creating a path to the file to be opened,turning it to a readable file and also getting the first five rows of the data, this also helps me know that I have properly imported my data file.

Deliverable 2; We checked for the null values which showed that data consisted of alot of null values and duplicated items, which eventually was going to interact with our analysis, thus, had to to be removed. The grades column was saved as string which had to be changed to an integar in order to be able to perform proper calculations, like the Big Picture Analysis and Targeted Analysis on it. This was firstly done by removing the suffix at the end of each number  and then changing the data type to our choice data type(integar).

Deliverable 3; We went futher to summarise the data using the describe function, which provided us with the mean, count, max and a lot more. we also got the mean and min of some score values as shown below:
Screenshot 2023-03-16 at 10.56.32 PM.png![image](https://user-images.githubusercontent.com/109382758/225801172-6b4006de-e134-4224-92ae-c61be2dcd166.png)


Deliverable 4; We checked the grade columns using the loc function, which was another way of getting columns in a dataset and also used it to get specific rows, columns and values from the dataset.

Deliverable 5; We went further to compare types using the groupby function, this helped me the get specific columns from the dataset in groups already specified in the groupby function. Lastly,(in number 34) still using the groupby function, we specified columns to group, which was the school name, we then used the count function to get the count and named the column(student count) and finally, used the sort_values function to sort the new column in descending order by putting a false to the default order(ascending). However, I was not sure which question to answer in number 21, as the questions were different, but I decided to do solve the both.

Additionally, I feel the groupby function really helped compare efficiently to give more insights, so I believed we would have gotten a more explainatory analysis if we had used more of the function.


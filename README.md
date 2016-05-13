# excel4mysql
I built dozens of Excel based systems and each and every one of my client will ask me to improve in 3 areas: 

1. Most importantly, collaboration. A system usually has more than 1 user and how can all users input data into one Excel file and see latest updates.  
2. Data security. How to keep the Excel file secure so no one can easily copy the whole excel file. This is extremely important with sales management system. 
3. Speed with large data. Over time, data in the master file (which normally stores data entries) can grow up to 100k rows. And you will find a simple filter takes more than 1 minute. 

Most of you will say: What you are saying is common sense. It is like telling me a human will die.  Exactly. The problem is so universal that it has become common sense. I myself have been telling my customers the strengths and weakness of Excel  for years until I finally decide to find a solution. 
It turns out that it is not difficult to solve all these 3 pitfalls. You can develop a Excel VBA+MySQL system. To be more specific: Excel for user interface and data processing; MySQL(or other database of your choice) for data storage. 

It is not difficult to see the common sense become false. I’d like to show you an example in which the user interface is in Chinese but should be easy to understand.

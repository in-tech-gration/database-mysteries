# Database Murder Mystery

  [![Illustration of a detective looking at evidence](img/detective.png)](https://in-tech-gration.github.io/database-mysteries/)

  There's been a Murder in SQL City! The SQL Murder Mystery is designed to be both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.

  If you just want to solve the mystery, go to [https://in-tech-gration.github.io/database-mysteries/](https://in-tech-gration.github.io/database-mysteries/).  

## What Else is Here?

  Before we built the web-based version, we designed this for people to download and solve on their own computer. If you're interested in that, read on.

## What you need to solve on your own computer

  * **sql-murder-mystery.db**: This SQLite database file contains all the data that you will be working with.
  * **prompt**: Depending on your experience level with SQL, find the prompt in either the [prompt_experienced](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_experienced.pdf) file or the [prompt_beginner](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_beginner.pdf) file.
  * **[reference](https://github.com/NUKnightLab/sql-mysteries/blob/master/reference.pdf)**: This is a crash course on SQL concepts and commands.
  * **a SQLite environment of your choice**: For beginners, we recommend using [SQLiteStudio](https://sqlitestudio.pl/), which is a good graphical interface to use to inspect your data and write queries.

## Getting Started

  **What is SQL?**   

  SQL, which stands for Structured Query Language, is a way to interact with relational databases and tables in a way that allows us humans to glean specific, meaningful information.  
 
  There are many “flavors” of SQL, but for our mystery we’ll be using ​[SQLite​](https://www.sqlite.org/index.html), which you can download [​here​](https://www.sqlite.org/download.html). We also recommend downloading [​SQLiteStudio​](https://sqlitestudio.pl/), which is a good graphical interface to use to inspect your data and write queries. 
 
  **What is a SQLite database file and how do I import it?** 
 
  In SQLite, a .db file, otherwise known as a database file, is a collection of tables, which are exactly like the tables you might already have dealt with in the past in programs such as Microsoft Excel or Google Sheets. Within a table, each row records a data point and each column contains a specific type of data.

  * **For SQL beginners**: start with the reference, read the [prompt_beginner](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_beginner.pdf) file, then get started by [installing SQLiteStudio and loading the db file](https://github.com/NUKnightLab/sql-mysteries/blob/master/sqlite_studio.pdf). If you get stuck at any point, feel free to refer back to the reference, or file a [GitHub issue](https://github.com/NUKnightLab/sql-mysteries/issues) so we can know where our instructions need to be improved.

  * **For experienced SQL users**: read the [prompt_experienced](https://github.com/NUKnightLab/sql-mysteries/blob/master/prompt_experienced.pdf) file, then download the sql-murder-mystery.db file and use a SQL environment of your choice to solve the mystery. You can use the reference to refresh your memory of SQL. Try to complete the activity all within your SQL environment (without writing down notes)!

## Checking the Solution

  Write the following queries in your SQL environment to check whether you've found the right murderer:

  ```SQL
  INSERT INTO solution VALUES (1, "Insert the name of the person you found here");

  SELECT value FROM solution;
  ```

## Authors

  * [Kostas Minaidis](https://github.com/kostasx)

## Original Authors

  * [Joon Park](https://twitter.com/JoonParkMusic)
  * [Cathy He](https://twitter.com/Cathy_MeiyingHe)

## Inspiration

  This murder mystery was inspired by [a crime in the neighboring Terminal City](https://github.com/veltman/clmystery "command-line murder mystery").

## Copyright and License

  Original code for this project is released under [the MIT License](https://github.com/NUKnightLab/sql-mysteries/blob/master/LICENSE). 

  Original text and other content is released under [Creative Commons CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). 

  SQL query custom web components used here were adapted from code created and released to the public domain by Zi Chong Kao, creator of [Select Star SQL](https://selectstarsql.com/).

  [Detective image by rambleron](https://www.vecteezy.com/vector-art/174092-clue-illustration) used under Vecteezy's free license.

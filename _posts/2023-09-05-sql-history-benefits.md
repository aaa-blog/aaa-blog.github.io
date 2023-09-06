---
title: SQL - History & Benefits
categories:
- SQL
- Data
feature_text: |
  SQL origins & 50+ years of reign
---

Which is the most used programming language in 2023? As per stackoverflow survey of professional developers, JavaScript takes the top spot followed by HTML/CSS & SQL. Why is SQL still featured on leaderboard? Let's explore more in this blog-

{% include figure.html image="https://github.com/aaa-blog/aaa-blog.github.io/blob/main/assets/images/stackoverflow-developer-survey?raw=true" alt="Stackoverflow Developer Survey 2023" %}
[Source](https://survey.stackoverflow.co/2023/#section-most-popular-technologies-programming-scripting-and-markup-languages "Stackoverflow Developer Survey 2023")

<!-- more -->

SQL (Structured Query Language) is a programming language used to communicate with and manipulate databases. To get the most of the mounds of data they collect, many businesses must become versed in SQL. Here’s everything you should know about using SQL to access and manipulate data.

##### What is SQL & when it is used?

Businesses and other organizations use SQL programs to access and manipulate the information and data in their databases and create and alter new tables. To fully understand SQL, you need to know exactly what a database is.

According to Microsoft, a database is a tool for collecting and organizing information. Databases can store information about people, products, orders or anything else. Many databases start in a word processing program or spreadsheet. As they get larger, many businesses find it helpful to transfer them to a database created by a database management system.

SQL helps control information stored in databases, allowing users to retrieve the specific data they’re looking for when they need it.

While it’s a simple programming language, SQL is very powerful. In fact, SQL can insert data into database tables, modify data in existing database tables and delete data from SQL database tables. In addition, SQL can modify the database structure itself by creating, modifying, and deleting tables and other database objects.

SQL uses a set of commands to manipulate the data in databases. Examples include SQL INSERT, which is used to add data to database tables; SQL SELECT, which retrieves data from database tables; and SQL UPDATE, which modifies existing database records.

##### SQL History :

The SQL programming language was developed in the 1970s by IBM researchers Raymond Boyce and Donald Chamberlin. The programming language, known then as SEQUEL, was created following Edgar Frank Codd’s paper, “A Relational Model of Data for Large Shared Data Banks,” in 1970. They took Codd’s languages with the goal of designing a relational language that would be more accessible to users without a formal training in mathematics or computer science.

> When SQL was established in the early 70s, it was called SEQUEL (Structured English Query Language). However, due to a copyright issue, it was changed it to SQL. In fact, SQL is typically pronounced “sequel” today, but some favor the non-acronym pronunciation of “ess-cue-el”.

The original SQL version they designed was used to manipulate and retrieve data stored in IBM’s original relational database systems, known as “System R.” In the succeeding years, SQL was not publicly available. However, in 1979, Oracle, then known as Relational Software, released its own version of SQL called Oracle V2, which was commercially released. It is important to note that SQL wasn’t the first programming language for navigating databases, but it did cut an impeccable presence due to its intuitiveness, power, and reliability.

##### ANSI Standards :

In 1986, the SQL language became formally accepted, and the ANSI Database Technical Committee (ANSI X3H2) of the Accredited Standards Committee (ASC) X3 developed the first SQL standard, ANSI X3.135-1986. This was the beginning of what people mistakenly call the ANSI standard for SQL. In truth, there are no ANSI standards, only standards developed by ANSI-approved committees, many operating in accordance with the ANSI Essential Requirements (American National Standards). Within a few months, ISO published a technically identical standard, ISO 9075-1987, bringing SQL, which was once confined to IBM’s databases in its infancy, to the international stage.

Below are the key features added in each iterations of SQL standards -

{% include figure.html image="https://github.com/aaa-blog/aaa-blog.github.io/blob/main/assets/images/history-of-sql-standards.png?raw=true" alt="History of SQL standards" %}
[Source](https://learnsql.com/blog/history-of-sql-standards/ "History of SQL standards")

##### Why is SQL ubiquitous?

* Built on First Principles
A first principle is a foundational proposition that can not be deduced from any other proposition or assumption. For instance, combining hydrocarbons with oxygen to create a chemical reaction. And this is still the principle that powers the internal combustion engines in every cars.

In 1970, Codd created a new first principle for databases: tuple relational calculus. This new logic created led to the relational model, which then led to SQL. Tuple relational calculus is the chemical reaction, relational models are the internal combustion engines, and SQL is the car.


* Usability & Bushnell’s Law
Building on first principles alone can not guarantee success. Assembly is as close as programmers can get to typing 1s and 0s, but it was still replaced with COBOL (and later C).

The missing ingredient was usability.

> "The best games are easy to learn but hard to master" - Nolan Bushnell, founder of Atari

Nolan Bushnell knew the secret to getting people to use a new product. Assembly unfortunately was both difficult to learn and difficult to master.

SQL found the perfect balance. With ~10 SQL commands, anyone can learn the 20% that will get you 80% of the way there.  But there is a long path of indexing, views, and optimization to becoming a master.

* Listening and Adapting
Query languages are not timeless monoliths but adaptive groups of standards that change over time. The SQL standard has continued to adapt over time and incorporate feedback from its users.

Since the original conception we have seen 10 different SQL standards all with important updates as we noted in History of SQL standards.

* Adoption of APIs
The final secret behind SQL’s success has been the rise of application programming interfaces (API). APIs simplify programming by abstracting the underlying implementation and only exposing objects or actions the developer needs.

APIs allow SQL to continue to adapt to new technologies with specialized syntax. In 2006 Hadoop introduced the distributed file system (HDFS), which was initially inaccessible to the SQL syntax. Then in 2013 Apache created Apache Impala, which allowed developers to use SQL to query HDFS databases.

<!-- more -->

So this was facinating history of SQL which started at the dawn of modern computing & going strong. In a later posts, we’ll discuss new technologies that are trying to create the electric engine for databases. Please like & connect with me on socials for more content like this.

[LinkedIn](https://www.linkedin.com/in/thakkarrahul01 "Rahul Thakkar")


[References](https://arctype.com/blog/history-of-sql/ "History of SQL")
(https://blog.ansi.org/sql-standard-iso-iec-9075-2023-ansi-x3-135/#gref "SQL Standard ISO")
(https://www.businessnewsdaily.com/5804-what-is-sql.html "What is SQL")
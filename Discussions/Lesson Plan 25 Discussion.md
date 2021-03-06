Course: ISTA-220
Lesson Plan: 25
Lee H. Sarduy
21 September 2017

1. You are building a help ticket system. You want to ensure that the older the ticket, the sooner it will be handled by the team. For example, a ticket submitted a week ago has a higher priority than a ticked just submitted. What kind of data structure would you use, and why?
-Queue./FIFO

2. You are building a tracking system for seasonal agricultural farm labor. The labor requirements vary widely, depending on the season. Your requirement is that the newest hires are terminated first, and that our more experienced hires are kept longer. What kind of data structure would you use, and why?
-Stack./FILO

3. You are building a transaction database. Your requirement is that the database adds data very quickly, and that deletions, updates, and searches happen infrequently. In other words, data is typically added in the order in which the transaction occurs. What kind of data structure would you use, and why?
-I would use a List because it offers the basic functionality described.

4. You are building an analytical database. Your requirement is that the database handles queries very quickly, but that the data never changes, i.e., there are no inserts, deletions, or updates. What kind of data structure would you use, and why?
-Dictionary./The search is using key words.

5. You are building a personnel directory, where searches are performed by last name, first name, middle name. 
   What kind of data structure would you use, and why?
-I would use a HashSet is because it is optimized for fast retrieval of data and provides 
set-oriented methods for determining whether the items it holds are a subset of another HashSet object.

6. You are building a username/password database. Your requirement is that updates happen frequently (when users change their passwords) and that searches (to authenticate users) happen extremely quickly. What kind of data structure would you use, and why?
-Dictionary./It offers fast searching and prevents duplicate usernames.

7. What is a lambda expression? Give an example. Why would we use a lambda expression?
-A lambda expression is an expression that returns a method. For example, 
Person match = personnel.Find(p => p.ID == 3);. We would use a lambda expression 
when we want to add functionality without writing a new method.

8. What is the difference between lambda expressions and anonymous methods? What are the advantages of each?
-Lambdas use implied typing, so "(x, y) => x + y;" is much more concise than "delegate(int x, int y) 
{ return x + y; }"./ Use lambdas when they promote readability, and anonymous delegates when they make sense.
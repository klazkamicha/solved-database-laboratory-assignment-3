Download Link: https://assignmentchef.com/product/solved-database-laboratory-assignment-3
<br>
<ol>

 <li>Use the company database created in Assignment # 2.</li>

</ol>

<ul>

 <li>Write a PL/SQL program to raise the salary of employees as follows:</li>

</ul>

All managers: 20% increase

Dno        % of increase

<ul>

 <li>10</li>

 <li>15</li>

 <li>18</li>

</ul>




<ul>

 <li>Write a PL/SQL program to find maximum salary earners name (use cursor)</li>

 <li>Write a PL/SQL program to find top N/2 salary earners name</li>

</ul>

<strong> </strong>




<ol start="2">

 <li>Consider a bank database with only one relation</li>

</ol>

Transaction (transno, acctno, date, amount)

The amount attribute value is positive for deposits and negative for withdrawals

<ul>

 <li>Define an SQL view TP containing the information (accno, T1.date, T2.amount) for every pair of transactions T1, T2 such that T1 and T2 are transactions on the same account and   the date of T2 is  ≤ the date of T1.</li>

</ul>




<ul>

 <li>Using only the above view TP, write a query to find for each account the minimum balance it ever reached (not including the 0 balance when the account is created). Assume there is at most one transaction per day on each account and each account has had at least one transaction since it was created. To simply your query, break it up into 2 steps by defining an intermediate view V.</li>

</ul>




<ol start="3">

 <li>Consider following two relations</li>

</ol>

Book_stock(<strong>Book_id</strong>, Title, No of Copies)

Book_Issue(<strong>card_no</strong>, cholder_name, <strong>book_id</strong>, issue_date, due_date)

Book_Return(<strong>card_no</strong>, cholder_name, <strong>book_id</strong>, return_date, issue_date)




Write a PL/SQL program for issuing/return of books with following conditions:

The program will take option I(issue) / R(return) along with card_no from user. Accordingly, insert records in Issue and Return relations. Date of issue/return must be populated with SYSDATE. Before issuing book, check the following constraints:  A member is not allowed to issue more than 3 books. A member is not allowed to issue more than one copy of same bookid.

After issuing/return of book the no of copies must be updated. If the return date of the book is later than the due date; insert a record in a new table called Fine (card_no, amt). Assume a fixed late fine amt.

<ol start="4">

 <li>Given a relation graph (P,Q, cost) where P and Q attributes represent vertices associated to edges in the graph and cost represent weight.</li>

</ol>

Write SQL/PL-SQL program for the followings

<ul>

 <li>Find the vertices with max and min degree.</li>

 <li>List all the path of length 2 with total cost less than 10.</li>

</ul>

<ol start="5">

 <li>Consider the following Table in a banking database:</li>

</ol>

Account(<strong>Accno</strong>, Accname, Type, Balance)

Write a PL/SQL program for withdraw and deposit of amount on a given account with following features:  The program should check conditions for insufficient fund (before withdraw) and raise error. For successful transaction, the program must update Account relation and subsequently insert records of the transactions in a new table called Transaction with following definition:

<strong>                            Transaction</strong>(Tr_id, Accno, Tr_type, Amt, date of Tr)




<strong>Deadline of Submission: 28.01.2020 </strong>
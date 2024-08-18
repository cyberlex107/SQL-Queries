<h1>Apply Filters to SQL Queries</h1>

<h2>Description</h2>
My organization is working to make their system more secure. It is my job to ensure the system is safe, investigate all potential security issues, and update employee computers as needed. The following steps provide examples of how I used SQL with filters to perform security-related tasks.
<br />


<h2>Languages and Utilities Used</h2>

- <b>SQL</b> 
- <b>BASH</b>

<h2>Environments Used </h2>

- <b>LINUX</b> 

<h2>Program walk-through:</h2>

<p align="center">
Retrieve after hours login attempts:There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.
 <br/>
<img src="https://imgur.com/BWiuYEq.png" height="80%" width="80%" alt="Filtering Steps"/>
<br />
Retrieve login attempts on specific dates: A suspicious event occurred on 2022-05-09. Any login activity that happened on 2022-05-09 or on the day before needs to be investigated <br/>
<img src="https://imgur.com/2Sgslox.png" height="80%" width="80%" alt="Filtering Steps"/>
<br />
Retrieve login attempts outside of Mexico: After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.
 <br/>
<img src="https://imgur.com/rLAa9XW.png" height="80%" width="80%" alt="Filtering Steps"/>
<br />
Retrieve employees in Marketing: My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.  <br/>
<img src="https://imgur.com/pVOxuGC.png" height="80%" width="80%" alt="Filtering Steps"/>
<br />
Retrieve employees in Finance or Sales: The machines for employees in the Finance and Sales departments also need to be updated. Since a different security update is needed, I have to get information on employees only from these two departments.
 <br/>
<img src="https://imgur.com/KMHJFev.png" height="80%" width="80%" alt="Filtering Steps"/>
<br />
Retrieve all employees not in IT: My team needs to make one more security update on employees who are not in the Information Technology department. To make the update, I first have to get information on these employees.
  <br/>
<img src="https://imgur.com/LyIECSq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Summary:  
I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.  <br/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

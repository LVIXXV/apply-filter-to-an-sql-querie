<h1>Applying filters to SQL queries</h1>

<h2>Retrieve after office hours failed login attempts</h2>

I chose all tables and employed 'FROM' to indicate the specific table. Using 'WHERE,' I set conditions to identify the number of login attempts occurring after 18:00. The query is as follows:

<p>
<img src="https://i.imgur.com/r3fBbTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

This query reveals that there have been 19 unsuccessful login attempts.

<p>
<img src="https://i.imgur.com/b6layXH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Retrieve login attempts on specific dates</h2>

Anomalous incidents took place on both May 8, 2022, and May 9, 2022. I employed the OR operator to target these specific dates in the query:

<p>
<img src="https://i.imgur.com/mZxl2W1.png" height="9%" width="10%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
<p>
<img src="https://i.imgur.com/0wwQxVj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

This query indicates that there were a total of 75 login attempts on these two days.

<p>
<img src="https://i.imgur.com/FZrVFu2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/AX8ScJZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Retrieve login attempts outside of Mexico</h2>

I now aim to fetch login attempts originating from locations outside of Mexico. To achieve this, I utilized the NOT and LIKE operators in the following query:
<p>
<img src="https://i.imgur.com/Wix3j3N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

This query identifies 144 login attempts made from locations other than Mexico.

<p>
<img src="https://i.imgur.com/t7llq0k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/LP8QzXO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Retrieve employees in Marketing</h2>

The team is in the process of updating employee machines and requires details about employees in the Marketing department situated in all offices within the East building. To achieve this, they utilized the AND and LIKE operators in the following query:
<p>
<img src="https://i.imgur.com/TCDgUcL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  Now, the team has access to information about the devices in the Marketing department located in various offices within the East building that require an update.

<p>
<img src="https://i.imgur.com/MYgrVr2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Retrieve employees in Finance or Sales</h2>

Additionally, the team is tasked with executing a distinct update for the computers of all employees in either the Finance or Sales department. To achieve this, they employed the OR operator in the following query:

<p>
<img src="https://i.imgur.com/wW5sHqC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Now, the team can review the devices that require an update for employees in either the Finance or Sales department.

<p>
<img src="https://i.imgur.com/6EjWrSr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Retrieve all employees not in IT</h2>

The team is required to perform an additional update that has already been applied to computers in the IT department. To gather information about employees who are not in the IT department, the team used the NOT operator in the following query:

<p>
<img src="https://i.imgur.com/uLLyfaG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Now, the team has access to all the necessary information for this update concerning employees outside the Information Technology department.
  
<p>
<img src="https://i.imgur.com/m2UGy7g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2>Summary</h2>

Effective SQL query execution strategies must be used, and database data retrieval security must be prioritized. Exact filtering is made possible by the use of operators like AND, OR, and NOT, which enhances overall security posture.

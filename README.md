# Final
<h1>Billing System Using Tkinter</h1>
<p>This project can be used for any shops. User can store all the data and generate the bill.</p>

<h2>Tech stack:</h2>
<ul>
    <li>Python</li>
</ul>

<h2>Libraries used:</h2>
<ul>
    <li>Tkinter</li>
    <li>Random</li>
    <li>Os</li>
    <li>Messagebox</li>
    <li>mysql.connector</li>
</ul>
<br>
<table>
<thead>
  <tr>
    <th>Widget Class</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Label</td>
    <td>A widget used to display text on the screen.</td>
  </tr>
  <tr>
    <td>Button</td>
    <td>A button that can contain text and can perform an action when clicked</td>
  </tr>
  <tr>
    <td>Entry</td>
    <td>A text entry widget that allows only a single line of text</td>
  </tr>
  <tr>
    <td>Text</td>
    <td>A text entry widget that allows multiline text entry</td>
  </tr>
  <tr>
    <td>Frame</td>
    <td>A rectangular region used to group related widgets or provide padding between widgets</td>
  </tr>
</tbody>
</table>
<h2>Commands for mysql to Grant Users</h2>
<ul>
    <li><b>This statement will grant all users on all hosts all privileges on all databases.</b></li>
    <p>GRANT ALL PRIVILEGES ON *.* TO ''@'%';</p>
    <li><b>Once you have granted all users the desired privileges, you need to flush the privileges table to make the changes take effect. You can do this with the following SQL statement:</b></li>
    <p>FLUSH PRIVILEGES;
</p>
</ul>
<br>
<p><b>EXAMPLE</b></p>
<code>mysql> GRANT ALL PRIVILEGES ON *.* TO ''@'localhost';
Query OK, 0 rows affected (0.00 sec)

Records: 0  Duplicates: 0  Warnings: 0

mysql> FLUSH PRIVILEGES;
Query OK, 0 rows affected (0.00 sec)
</code>

<h3>To install external modules:</h3>
<p><li>Run pip install tkinter</li></p>
<p><li>Run pip install mysql-connector</li></p>

<h3>To execute the project:</h3>
<p><li>Run billing system.py</li></p>

<h3>Screenshot/GIF of this project.</h3>

![Bill](https://github.com/Ravi191203/Final/blob/9d2f0622b099ba7c4712d67605c21a37b72157ad/Screenshot%20(6).png)

<h1 style="font-family:Bradley Hand ITC"><c>Thank You</c></h1>

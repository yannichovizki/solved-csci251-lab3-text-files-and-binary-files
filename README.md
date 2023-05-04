Download Link: https://assignmentchef.com/product/solved-csci251-lab3-text-files-and-binary-files
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs text files and binary files.</li>

</ul>

<h1>Question 1 (Formatted I/O)</h1>

You are responsible to maintain a simple sales record for the sales of a company.  The company keeps a text file to store the records of the monthly sales made by the salespersons that contains the employee number, name, and sales made for each salesperson. The file may be formatted in the following way:

<table width="742">

 <tbody>

  <tr>

   <td width="104">12345</td>

   <td width="96">Ali Baba</td>

   <td width="48"> </td>

   <td width="494">1040.00</td>

  </tr>

  <tr>

   <td width="104">12233</td>

   <td width="96">Sinbad</td>

   <td width="48"> </td>

   <td width="494">35.98</td>

  </tr>

  <tr>

   <td width="104">23781</td>

   <td width="96">Spongebob</td>

   <td width="48"> </td>

   <td width="494">199.00</td>

  </tr>

  <tr>

   <td width="104">67543</td>

   <td width="96">Cinderella</td>

   <td width="48"> </td>

   <td width="494">500.50</td>

  </tr>

  <tr>

   <td width="104">23781</td>

   <td width="96">Spongebob</td>

   <td width="48"> </td>

   <td width="494">1000.00</td>

  </tr>

  <tr>

   <td width="104">12345</td>

   <td width="96">Ali Baba</td>

   <td width="48"> </td>

   <td width="494">80.00</td>

  </tr>

  <tr>

   <td width="104">67543</td>

   <td width="96">Cinderella</td>

   <td width="48"> </td>

   <td width="494">67.50</td>

  </tr>

 </tbody>

</table>




Your task is to write a program that will allow new sales records to be written to the file and also to read the file  and print out the total sales made by each salesperson together with the overall total sales made so far. Filenames should be entered by the user.

Declare suitable data structure to keep each record. Use individual functions to perform the calculations and display. Include necessary error checking in your program and provide a well-formatted output.

<h1>Question 2 (Formatted I/O and Unformatted I/O)</h1>

You are provided with a text file (chemicalElements.txt) containing a list of chemical elements. Each line on the text file will contain the atomic mass, followed by the element name, chemical symbol, and an integer atomic number. Example of a few lines from the file is as follows:







<table width="199">

 <tbody>

  <tr>

   <td width="144">1.0079 Hydrogen</td>

   <td width="48">H</td>

   <td width="7">1</td>

  </tr>

  <tr>

   <td width="144">4.0026 Helium</td>

   <td width="48">He</td>

   <td width="7">2</td>

  </tr>

  <tr>

   <td width="144">6.941 Lithium</td>

   <td width="48">Li</td>

   <td width="7">3</td>

  </tr>

 </tbody>

</table>




Your task is to read the information for each of the element in this file and produce a binary file containing records of these chemical elements. Each record should be stored in a struct variable declared as: struct ChemicalElement

{

int atomicNumber;  char name[100];  char symbol[3];

float mass;

};




Once the binary file has been created, allow the user to perform a search on the binary file by providing the element name or symbol (display all the details if found), display all the chemical elements’ details that have atomic mass greater than a given value, display the details of all the chemical elements with the atomic number in between two given values, or display the details of a chemical element by giving the record number. The details of the chemical element will then be displayed on standard output.




Separate function should be written to:

<ol>

 <li>Read records from the text file and write to binary file.</li>

 <li>Search by name or symbol</li>

 <li>Display data with atomic mass greater than the value passed to it</li>

 <li>Display data between two given atomic number</li>

 <li>Display data given a record number</li>

</ol>

All functions should be called from main().







<strong> </strong>



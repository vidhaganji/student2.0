---
comments: true
layout: post
title: CSP Final,
description: My CSP Blog post for the final!
type: collab
toc: true
courses: { csp: {week: 16} }
---



<body>


<p>My group's project focuses on tracking mood. It uses a variety of features such as a mood tracker, journal, and quote generator to allow the user to keep a log of their emotions. The feature that I mainly contributed to was the journal. </p>


<h3><strong>Component A: Program Code</strong></h3>


<strong>CPT Requirements:</strong>
<a href="https://apcentral.collegeboard.org/media/pdf/ap-csp-student-task-directions.pdf">Link to CPT Requirements</a>


<table>
 <tr>
   <th>Requirement</th>
   <th>Description</th>
 </tr>
 <tr>
   <td>(1) Input from user/device/online data stream/file:</td>
   <td>
     <ul>
       <li>A variety of features on our project require user input such as the journal page where users can enter text. </li>
      <img src = "https://i.ibb.co/vQGvBSN/Screenshot-2024-02-28-at-11-17-04-AM.png">
     </ul>
   </td>
 </tr>
 <tr>
   <td>(2) Use at least one list (or other collection type) to represent a collection of data that is stored and used to manage program complexity and help fulfill the program’s purpose</td>
   <td>
     <ul>
       <li> Our quote repository makes use of local storage to retrieve quotes and display them.</li>
       <li>Other pages of our project such as the login page make use of JSON which is a storage mechanism to keep track of the several variables that we use.</li>
     </ul>
   </td>
 </tr>
 <tr>
   <td>(3) At least one procedure that contributes to the program’s intended purpose, where you have defined the procedure’s name/the return type (if necessary)/one or more parameters</td>
   <td>
     <ul>
       <li>The journal page requires the use of many functions such as displayWordOfTheDay(), getRandomWord(), and saveEntry(). The getRandomWord() function has a return type of a string. </li>
      <img src = "https://i.ibb.co/QQcsgRW/Screenshot-2024-02-28-at-11-20-08-AM.png">
     </ul>
   </td>
 </tr>
 <tr>
   <td>(4) An algorithm that includes sequencing, selection, and iteration that is in the body of the selected procedure</td>
   <td>
     <ul>
       <li> The saveEntry() function uses an if conditional to test if the user enter has entered text in the journal and parse this text. If the conditional evaluates to True, the provided text will be parsed and saved and the reflect button will also be created for users to access. If the conditional evaluates to False, an error message will be alerted on the screen. </li>
      <img src = "https://i.ibb.co/5ryL2c8/Screenshot-2024-02-28-at-11-23-52-AM.png">
         </ul>
   </td>
 </tr>
 <tr>
   <td>(5) Calls to your student-developed procedure</td>
   <td>
     <ul>
       <li> The displayWordoftheDay() function is called whenever the page is reloaded. </li>
     <img src = "https://i.ibb.co/mNGbPBz/Screenshot-2024-02-28-at-11-25-19-AM.png">
     </ul>
   </td>
 </tr>
 <tr>
   <td>(6) Instructions for output (tactile, audible, visual, or textual) based on input and program functionality</td>
   <td>
     <ul>
      <li> After the journal entry is completed by the user and they click the submit button, an alert will appear on the screen that says the writing has succesfully been saved. </li>
      <img src = "https://i.ibb.co/rQ24csv/Screenshot-2024-02-28-at-11-27-36-AM.png">
     </ul>
   </td>
 </tr>
</table>


<hr>









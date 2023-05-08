Download Link: https://assignmentchef.com/product/solved-web_technology-assignment-4
<br>
<strong>     </strong>

<strong>Question 1.</strong> Consider the following train timetable:​

<table width="624">

 <tbody>

  <tr>

   <td colspan="2" width="624">Wollongong – Kiama, leaving in 5 min</td>

  </tr>

  <tr>

   <td width="81">08:54</td>

   <td width="543">Wollongong Station, Platform 2</td>

  </tr>

  <tr>

   <td width="81">08:56</td>

   <td width="543">Coniston Station, Platform 2</td>

  </tr>

  <tr>

   <td width="81">09:01</td>

   <td width="543">Unanderra Station, Platform 1</td>

  </tr>

  <tr>

   <td width="81">09:07</td>

   <td width="543">Dapto Station, Platform 2</td>

  </tr>

  <tr>

   <td width="81">09:15</td>

   <td width="543">Albion Park Station, Platform 2</td>

  </tr>

  <tr>

   <td width="81">09:21</td>

   <td width="543">Oak Flats Station, Platform 1</td>

  </tr>

  <tr>

   <td width="81">09:25</td>

   <td width="543">Shellharbour Junction, Platform 2</td>

  </tr>

  <tr>

   <td width="81">09:29</td>

   <td width="543">Minnamurra Station, Platform 1</td>

  </tr>

  <tr>

   <td width="81">09:34</td>

   <td width="543">Bombo Station, Platform 1</td>

  </tr>

  <tr>

   <td width="81">09:38</td>

   <td width="543">Kiama Station, Platform 2</td>

  </tr>

 </tbody>

</table>




Write an XML document Question1.xml​ that​ represents the above train timetable which uses the stylesheet Question1.xsl​ and produce the following output:​




Wollongong – Kiama, due: 5 min

<ul>

 <li>Wollongong Station, 08:54, P2</li>

 <li>Coniston Station, 08:56, P2</li>

 <li>Unanderra Station, 09:01, P1</li>

 <li>Dapto Station, 09:07, P2</li>

 <li>Albion Park Station, 09:15, P2</li>

 <li>Oak Flats Station, 09:21, P1</li>

 <li>Shellharbour Junction, 09:25, P2</li>

 <li>Minnamurra Station, 09:29, P1</li>

 <li>Bombo Station, 09:34, P1</li>

 <li>Kiama Station, 09:38, P2</li>

</ul>

<strong>Question 2. </strong>Write a JSON document Question2.json​ that​ represents the above train timetable.<strong>     </strong>

<strong>Question 3. </strong> Create a web page ​ Question3.html ​ that looks like the following:​

The web page should allow the user to enter student full name, student number, subject code, subject title in <strong>text fields</strong>​ , and should allow the user to enter the declaration in the ​           <strong>text area</strong>​ .​

The web page should display a <strong>button</strong>​           “JSON stringify”. When the user clicks the button, do the following tasks:

<ol>

 <li>Create a <strong>Javascript object</strong>​ that contains all the information that the user has entered.​</li>

 <li>Translate the object into <strong>JSON string with indentation.</strong>​</li>

 <li>Display the JSON string in the<strong> text area</strong>​ .​</li>

</ol>




<strong>Question 4.</strong><strong> </strong>Download​ the JSON file Question4.json​ from Moodle with the following content:




{

“studentRefNumber”: “BGX8P21R5”,

“testResult”: [

{

“questionNumber”: 1,

“content”: “Read a table to solve a problem”,

“topic”: “Chance &amp; Data”,

“correctAnswer”: “C”,

“yourAnswer”: “C”,

“difficultyLevel”: 1

},

{

“questionNumber”: 2,

“content”: “Calculate the perimeter of a shape”,

“topic”: “Measures &amp; Units”,

“correctAnswer”: “B”,

“yourAnswer”: “B”,

“difficultyLevel”: 2

},

{

“questionNumber”: 3,

“content”: “Solve a word problem involving speed of a vehicle”,

“topic”: “Algebra &amp; Patterns”,

“correctAnswer”: “C”,

“yourAnswer”: “A”,

“difficultyLevel”: 2

},

{

“questionNumber”: 4,

“content”: “Solve a word problem involving multiple additions”,

“topic”: “Algebra &amp; Patterns”,

“correctAnswer”: “C”,

“yourAnswer”: “C”,

“difficultyLevel”: 3

},

{

“questionNumber”: 5,

“content”: “Identify a shape reflected about a given axis”,

“topic”: “Space &amp; Geometry”,

“correctAnswer”: “A”,

“yourAnswer”: “D”,

“difficultyLevel”: 5

},

{

“questionNumber”: 6,

“content”: “Solve a complex problem involving time”,

“topic”: “Measures &amp; Units”,

“correctAnswer”: “D”,

“yourAnswer”: “A”,

“difficultyLevel”: 3

},

{

“questionNumber”: 7,

“content”: “Solve a complex problem involving fractions”,

“topic”: “Number &amp; Arithmetic”,

“correctAnswer”: “B”,

“yourAnswer”: “B”,

“difficultyLevel”: 4

},

{

“questionNumber”: 8,

“content”: “Solve a complex equation involving two variables”,

“topic”: “Number &amp; Arithmetic”,

“correctAnswer”: “C”,

“yourAnswer”: “B”,

“difficultyLevel”: 5

},

{

“questionNumber”: 9,

“content”: “Identify an object shown from a different position”,

“topic”: “Space &amp; Geometry”,

“correctAnswer”: “B”,

“yourAnswer”: “B”,

“difficultyLevel”: 4

},

{

“questionNumber”: 10,

“content”: “Translate data table into a graph”,

“topic”: “Chance &amp; Data”,

“correctAnswer”: “A”,

“yourAnswer”: “A”,

“difficultyLevel”: 1

}

]

}










Create a web page Question4.html​ .​

On the web page, display a button “Get Test Result”.

When the user clicks this button, use an AJAX call to get the JSON file, parse the JSON into a Javascript object, and then display the Javascript object on the web page as follows:







<strong> </strong>

<strong>Important implementation requirements:</strong>

<ol>

 <li>Difficulty level must be displayed using the star. The HTML Entity code for the star is 11088</li>

 <li>Correct answer must be displayed using the green tick. The HTML Entity code for the tick is 10003</li>

 <li>Question number with incorrect answer must be displayed in a grey background</li>

 <li>All alignment must be exactly as the above example</li>

 <li>The score message must be displayed correctly <strong>above</strong>​ the result table.​</li>

</ol>
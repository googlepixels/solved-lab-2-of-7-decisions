Download Link: https://assignmentchef.com/product/solved-lab-2-of-7-decisions
<br>
<ol>

 <li>Lab 2 of 7: Decisions</li>

</ol>

<ol>

 <li>Lab Overview – Scenario/Summary</li>

</ol>

You will code, build, and execute two programs requiring decisions. The first program will determine the smaller of two numbers input on the screen. The second program will calculate the shipping charge based on the purchase amount input on the screen.

Learning outcomes:

<ol>

 <li>To be able to design program logic using either a flowchart or pseudocode</li>

 <li>To be able to define and use data types</li>

 <li>To be able to prompt the user for input</li>

 <li>To be able to use the assignment statement for calculations</li>

 <li>To be able to display output to the console in a formatted manner</li>

 <li>To be able to debug a program of syntax and logic errors</li>

 <li>To be able to make decisions</li>

</ol>

<strong> </strong>Deliverables




<table>

 <tbody>

  <tr>

   <td width="85"><strong>Section</strong></td>

   <td width="456"><strong>Deliverable</strong></td>

   <td width="136"><strong>Points</strong></td>

  </tr>

  <tr>

   <td width="85"><strong>Part A</strong></td>

   <td width="456">Step 7: Program Listing and Output</td>

   <td width="136"><strong>20</strong></td>

  </tr>

  <tr>

   <td width="85"><strong>Part B</strong></td>

   <td width="456">Step 7: Program Listing and Output</td>

   <td width="136"><strong>25</strong></td>

  </tr>

 </tbody>

</table>




<em> </em>Lab Steps

<strong> </strong><strong>Preparation:</strong>

<strong> </strong>If you are using the Citrix remote lab, follow the login instructions located in the iLab tab in Course Home.

Locate the Visual Studio 2010 icon and launch the application.

<strong>Lab:</strong>




<table width="678">

 <tbody>

  <tr>

   <td width="673"><strong>Part A: Determine Smallest Number</strong></td>

   <td width="5"></td>

  </tr>

  <tr>

   <td width="673"><strong>Step 1: </strong>Requirements</td>

   <td width="5"></td>

  </tr>

  <tr>

   <td width="673">Write a program that inputs two numbers and determines which of the two numbers is the smallest. If the numbers are equal, display a message that they are equal.<strong> </strong>Sample output from program:<em> </em><strong>You will be asked to enter two numbers.</strong><strong>The smallest value will be displayed or a message if they are the same.</strong><strong> </strong><strong>     Please enter a numeric value: 4</strong><strong>     Please enter a numeric value: 7</strong><strong> </strong><strong>     The smallest value is 4</strong><strong>     Press any key to continue . . .</strong><strong> </strong><strong>AND THEN:</strong> <strong>     Please enter a numeric value: 7</strong><strong>     Please enter a numeric value: 4</strong><strong> </strong><strong>     The smallest value is 4</strong><strong>     Press any key to continue . . .</strong><strong> </strong> </td>

   <td width="5"></td>

  </tr>

  <tr>

   <td width="673"><strong>Step 2: </strong>Pseudocode</td>

   <td width="5"></td>

  </tr>

  <tr>

   <td width="673">Using the pseudocode below, write the code that will meet the requirements: Display description of programPrompt the user for the first numberPrompt the user for the second numberIf first number equals second numberDisplay the two numbers are equalElseIf first number is greater than second numberAssign second number to smallestElseAssign first number to smallestEnd-IfDisplay smallest numberEnd-If   </td>

   <td width="5"></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 3: </strong>Create a New Project</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Create a new project and name it LAB2A. Write your code using the processing logic in Part A, Step 2.</td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 4: </strong>Save Program</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Save your program by clicking <strong>File</strong> on the menu bar and then clicking <strong>Save Program.cpp</strong>, or by clicking the <strong>Save</strong> button on the toolbar, or <strong>Ctrl + S</strong>.<em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 5: </strong>Build Solution</td>

  </tr>

  <tr>

   <td colspan="2" width="678">To compile the program, click <strong>Debug</strong> and then <strong>Build solution (F7).</strong> You should receive no error messages. If you see some error messages, check the code above to make sure you didn’t key in something wrong. Once you make your corrections to the code, go ahead and click Build &gt;&gt; Build Solution again.<em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 6: </strong>Execute the Program</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Once you have no syntax errors, to execute or run your program, click <strong>Debug</strong> on the menu bar, and then click <strong>Start Debugging.  </strong><em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 7: </strong>Capture the Output</td>

  </tr>

  <tr>

   <td colspan="2" width="678"><em> </em>1.    Capture a screen print of your output. (Do a PRINT SCREEN and paste into an MS Word document.)2.    Copy your code and paste it into the same MS Word document that contains the screen print of your output.3.    Save the Word Document as Lab02A_LastName_FirstInitial.<em> </em><em> </em></td>

  </tr>

  <tr>

   <td width="673"><strong>END OF PART A</strong></td>

   <td width="5"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<table width="678">

 <tbody>

  <tr>

   <td width="677"><strong>Part B: Calculate Shipping Charge</strong></td>

   <td width="1"></td>

  </tr>

  <tr>

   <td width="677"><strong>Step 1: </strong>Requirements</td>

   <td width="1"></td>

  </tr>

  <tr>

   <td width="677">Write a program that inputs the amount of the purchase and calculates the shipping charge based on the following table:$0.00 – $250.00: $5.00$250.01 – $500.00: $8.00$500.01 – $1,000.00: $10.00$1,000.01 – $5,000.00: $15.00over $5,000.00: $20.00<strong> </strong>Sample Output from Program:<strong>     Enter a purchase amount to find out your shipping charges.</strong><strong> </strong><strong>     Please enter the amount of your purchase: 234.65</strong><strong>     The shipping charge on a purchase of $234.65 is $5.00.</strong><strong> </strong><strong>     Press any key to continue . . .</strong><em> </em></td>

   <td width="1"></td>

  </tr>

  <tr>

   <td width="677"><strong>Step 2: </strong>Pseudocode</td>

   <td width="1"></td>

  </tr>

  <tr>

   <td width="677">Using the pseudocode below, write the code that will meet the requirements. <strong>Display program information</strong><strong>Prompt the user for the sale amount</strong><strong>If sale amount &gt; $5,000.00</strong><strong>    shipping is $20.00</strong><strong>Else if sale amount &gt; $1,000.00</strong><strong>    shipping is $15.00</strong><strong>Else if sale amount &gt; $500.00</strong><strong>    shipping is $10.00</strong><strong>Else if sale amount &gt; $250.00</strong><strong>    shipping is $8.00</strong><strong>Else if sale amount &gt; $0.00</strong><strong>    shipping is $5.00</strong><strong>Else</strong><strong>    shipping is $0.00</strong><strong>End-If</strong><strong> </strong><strong>If shipping is $0.00</strong><strong>    Display “Error incorrect input”</strong><strong>Else</strong><strong>    Display sale amount and shipping charge</strong><strong>End-If</strong><em> </em></td>

   <td width="1"></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 3: </strong>Create a New Project</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Create a new project and name it LAB2B. Make sure you close your previous program by clicking File &gt;&gt; Close Solution. Write your code using the Processing Logic in Part B Step 2.</td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 4: </strong>Save Program</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Save your program by clicking <strong>File</strong> on the menu bar and then clicking <strong>Save Program.cpp</strong>, or by clicking the <strong>Save</strong> button on the toolbar, or <strong>Ctrl + S</strong>.<em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 5: </strong>Build Solution</td>

  </tr>

  <tr>

   <td colspan="2" width="678">To compile the program, click <strong>Debug</strong> then <strong>Build solution (F7).</strong> You should receive no error messages. If you see some error messages, check the code above to make sure you didn’t key in something wrong. Once you make your corrections to the code, go ahead and click Build &gt;&gt; Build Solution again.<em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 6: </strong>Execute the Program</td>

  </tr>

  <tr>

   <td colspan="2" width="678">Once you have no syntax errors, to execute or run your program, click <strong>Debug</strong> on the menu bar, and then click <strong>Start Debugging.  </strong><em> </em></td>

  </tr>

  <tr>

   <td colspan="2" width="678"><strong>Step 7: </strong>Capture the Output</td>

  </tr>

  <tr>

   <td colspan="2" width="678"><em> </em>1.    Capture a screen print of your output. (Do a PRINT SCREEN and paste into an MS Word document.)2.    Copy your code and paste it into the same MS Word document that contains the screen print of your output.3.    Save the Word Document as Lab02B_LastName_FirstInitial.<em> </em></td>

  </tr>

  <tr>

   <td width="677"><strong>END OF PART B</strong></td>

   <td width="1"></td>

  </tr>

  <tr>

   <td width="677"><strong>END OF LAB</strong></td>

   <td width="1"></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>




<strong> </strong>
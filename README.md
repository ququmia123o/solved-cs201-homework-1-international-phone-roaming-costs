Download Link: https://assignmentchef.com/product/solved-cs201-homework-1-international-phone-roaming-costs
<br>






<h1>Programming Language/Environment</h1>

You should prepare (or at least test) your program using MS Visual Studio 2012 C++. We will use the standard C++ compiler and libraries of the above mentioned platform while testing your homework.

<h2>Input and Output</h2>

There are nine inputs in this program:

<ul>

 <li>Name of the user (of type string),</li>

 <li>Price of outgoing call per minute in TL (of type double),</li>

 <li>Number of minutes talked as outgoing calls (of type int),</li>

 <li>Price of incoming call per minute in TL (of type double),</li>

 <li>Number of minutes talked as incoming calls (of type int),</li>

 <li>Price of internet usage per MB in TL (of type double),</li>

 <li>GBs of internet used (of type double),</li>

 <li>Price of one international SMS in TL (of type double),</li>

 <li>Number of SMS’s sent (of type int).</li>

</ul>

Seven outputs are expected in this program, all in terms of TL:

<ul>

 <li>Money spent for outgoing calls (of type double),</li>

 <li>Money spent for incoming calls (of type double),</li>

 <li>Money spent for the internet usage (of type double),</li>

 <li>Money spent for the SMS’s (of type double),</li>

 <li>Total cost of all roaming services (of type double), The tax imposed, 18% of the total cost (of type double),</li>

 <li>Total roaming bill fee including the tax (of type double).</li>

</ul>

<h2>Program Flow</h2>

At the beginning, the user will be prompted to enter his/her name as the first input. The name of the user should be displayed whenever appropriate in the prompts and the output text. See Sample Runs section for some examples.

User will first input his/her name. After that, two prompts will be received that want the user to enter the price of outgoing call per minute and the minutes talked as outgoing call. Then, your program will calculate and display the amount spent for outgoing calls while roaming. After that, two other prompts will be received that want the user to enter the price of incoming call per minute and the minutes talked as incoming call. Then, your program will calculate and display the amount spent for incoming calls while roaming. After that, another two prompts will be received that want the user to enter the price of internet usage per MB and the number of GB’s of internet used while roaming. Then, your program will calculate and display the amount spent for internet usage while roaming. Thereafter, another two prompts will be received that ask for the user to enter the price of one SMS and the number of SMS’s sent. Then, your program will calculate and display the amount spent for the SMS’s. See Sample Runs section for some examples.

Then, your program should also calculate and display the remaining expected outputs: total cost of all the used services, the tax imposed on it (18% of the total cost) and the total bill fee including the tax.

Please refer to the Sample Runs section to see the program flow.

<h2>Input Check</h2>

You do not need to perform any kind of input checks; you may assume that the user enters positive values correctly for all inputs.

<h2>Sample Runs</h2>

Below, we provide some sample runs of the program that you will develop. The italic and bold phrases are inputs taken from the user. You should follow the input order in these examples and the text your program will display must be <strong>exactly the same </strong>as in the following examples.

<strong><em>Sample Run 1</em></strong>

Please enter your name: <strong><em>Gulsen</em></strong>

Gulsen, please enter the price for outgoing call per minute: <strong><em>10</em></strong>

Gulsen, please enter how many minutes you have talked in outgoing calls: <strong><em>5</em></strong>

Gulsen, you have spent 50 TL for outgoing calls you made while you are abroad.

Gulsen, please enter the price for incoming call per minute: <strong><em>3</em></strong>

Gulsen, please enter how many minutes you have talked in incoming calls: <strong><em>12 </em></strong>Gulsen, you have spent 36 TL for incoming calls you made while you are abroad.

Gulsen, please enter the price for internet usage per MB: <strong><em>5</em></strong>

Gulsen, please enter how many GBs you have used: <strong><em>1</em></strong>

Gulsen, you have spent 5120 TL for the internet while you are abroad.

Gulsen, please enter the price for one SMS: <strong><em>1</em></strong>

Gulsen, please enter the number of SMS you have sent: <strong><em>7</em></strong>

Gulsen, you have spent 7 TL for the SMS while you are abroad.

Gulsen, total cost for all roaming services is 5213 TL.

Gulsen, tax is 938.34 TL.

Gulsen, total roaming bill fee with tax is 6151.34 TL.

<strong><em>Sample Run 2</em></strong>

Please enter your name: <strong><em>Ece</em></strong>

Ece, please enter the price for outgoing call per minute: <strong><em>4.90</em></strong>

Ece, please enter how many minutes you have talked in outgoing calls: <strong><em>17</em></strong>

Ece, you have spent 83.3 TL for outgoing calls you made while you are abroad.

Ece, please enter the price for incoming call per minute: <strong><em>2.90</em></strong>

Ece, please enter how many minutes you have talked in incoming calls: <strong><em>8 </em></strong>Ece, you have spent 23.2 TL for incoming calls you made while you are abroad.

Ece, please enter the price for internet usage per MB: <strong><em>5</em></strong>

Ece, please enter how many GBs you have used: <strong><em>0.028</em></strong>

Ece, you have spent 143.36 TL for the internet while you are abroad.

Ece, please enter the price for one SMS: <strong><em>0.95</em></strong>

Ece, please enter the number of SMS you have sent: <strong><em>5</em></strong>

Ece, you have spent 4.75 TL for the SMS while you are abroad.

Ece, total cost for all roaming services is 254.61 TL.

Ece, tax is 45.8298 TL.

Ece, total roaming bill fee with tax is 300.44 TL.



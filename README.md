Download Link: https://assignmentchef.com/product/solved-cosc2452-week5-independent-investigative-effort-5
<br>
<table width="748">

 <tbody>

  <tr>

   <td width="748">5. This week’s programming task will cover concepts required by Assignment 2. You should aim to get the help of your tutors and make further revisions.<strong>Coding exercise steps (Hint: Need help? Ask your tutor via Canvas→Discussions→”IIE05″): </strong>Follow Canvas→<a href="https://rmit.instructure.com/courses/70691/modules">Modules→Week 5</a> first. It covers topics on creating and manipulating arrays.<strong>a. </strong>Make a copy of your IIE04 Eclipse project (GTerm version that takes an entire record using one input) and rename the project to IIE05 or similar, as shown during the week 1 ‘weekly live lecture’. Ensure that your .java file is not PleaseRenameMe.java and it is something relevant to your application (avoid names such as IIE05.java; give it a personality!) but remember to follow class naming conventions (refer to IIE01). You must be able to <strong>show how your work is different to the “student manager” examples</strong> shown in the live lectures, if it can be thought of as being similar. Also note that, whenever the instructions use the term “array”, it <strong>does not refer to the array obtained by the String class’ .split method</strong>, unless otherwise stated.Ensure that your program first asks the user how many records they would like to process. Then declare an array reference of an appropriate data type for each field of your records. E.g.Instead of the variable: String name;Create an array to store many such values as:String[] names;If your code took inputs for 5 different pieces of information for each record, you must have 5 separate arrays. In other words, you will have an array reference for each column in the table but the arrays will be of different data types (whereas data in a table exist as Strings).Now create the actual arrays based on the num of records specified by the user for each of the arrays. For now, keep these two steps separate.names=new String[numRecords];Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.</td>

  </tr>

 </tbody>

</table>

<strong>Access issues:</strong> For non-programming technical issues (relating to infrastructure, passwords, etc.) please call the <a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/service-and-support-centre">RMIT IT Service and </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/service-and-support-centre">Support Centre</a> for quick help on 03-9925 8888 and remember to ask for a reference number and pass it on to your instructor.

<strong>Extensions: </strong>For all new extensions,  <a href="https://specon.rmit.edu.au/specon/"> </a><a href="https://specon.rmit.edu.au/specon/">a</a><a href="https://specon.rmit.edu.au/specon/">  </a><a href="https://specon.rmit.edu.au/specon/">pply for special consideration online</a> .  Contacting your tutors, instructors first will lead to delays.

<strong>Please follow/complete all steps below in the given sequence:</strong>

<ol>

 <li>Check your <a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">official</a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">  </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">@student.rmit.edu.au e</a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">  </a><a href="https://www.rmit.edu.au/students/support-and-facilities/it-services-for-students/email">mail account</a>  for announcements and other communication from the university. If getting in touch with your instructors, please only use this account (not Canvas inbox, messages, personal email, phone, Microsoft Teams, etc.)</li>

 <li><a href="https://rmit.instructure.com/courses/70691/pages/how-to-watch-recordings-of-live-lessons?module_item_id=2768983">Watch any unwatched recordings</a> of the <strong>Weekly Live Lecture</strong> and complete all missed tutorials <strong>before going further</strong>. For your convenience, the time stamps of recordings are sent via student email/Canvas→Announcements.</li>

 <li>Is there something that you have not fully grasped from what has been covered so far? Please have your doubts clarified via one of the relevant forums under <a href="https://rmit.instructure.com/courses/70691/discussion_topics">Canvas→Discussions</a>. Leaving gaps has shown to be severely detrimental to learning.</li>

 <li>Did you want to make any additions to the previous IIE? Please do by replying to your original post. i.e. do not edit, change the images of existing posts as it affects submission timing.</li>

</ol>




<table width="748">

 <tbody>

  <tr>

   <td width="748">b.                   When input String is split and the values are extracted/parsed and <u>before</u> they are added to the table, assign them to the arrays. i.e. if you have a names array and an ages array, names[0] and ages[0] must refer to the same student, names[1] and ages[1] should refer to the next student, etc. To achieve this, you will need to use your outer loop’s loop variable to refer to the same index across all arrays. Of course, your code must not be about students. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.c.                    After 5b, your values would be stored in the arrays. Modify your addRowToTable to add these same values to the table as you did in IIE04. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.d.                   Investigative exercise: After taking all inputs and storing them in the arrays, perform some statistical calculations on one or more of the numerical fields/columns. Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.e.                    Optional to do but must follow when solution shown: How can we make the program not ask for numRecords at the start and make it still work? Are you stuck? Please ask your friendly tutor by creating a post in the relevant IIE forum.</td>

  </tr>

 </tbody>

</table>
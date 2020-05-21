<h1>"What Do <span style="color: #ff0000;">You&nbsp;</span>Remember From Your H<span dir="ltr">igh School Matriculation Exam ? "</span></h1>
<p><strong>My name is Matan Tsour.&nbsp;</strong></p>
<p><strong>This is the title of our intro to pyscology project regarding Working Memory and Long Term Memory.</strong></p>
<h2 style="text-align: center;">&lt;Skip to the code&nbsp;<a href="https://github.com/matantsour/Core_Studies_Memory_Analysis/blob/gh-pages/Core_Studies_Memory_Analysis.ipynb" target="_blank" rel="noopener noreferrer">HERE</a>&gt;</h2>
<h2><span style="color: #003366;">Introduction</span></h2>
<p>In this project Working memory is in face, a type of&nbsp;short-term memory.<br />However, instead of all information going into one single store, there are different systems for different types of information .<br /><br />For more information, check <a href="https://www.simplypsychology.org/working%20memory.html" target="_blank" rel="noopener noreferrer">simplypsychology.org</a>.</p>
<p>In this proect,&nbsp;</p>
<p>I&nbsp;wanted to compare how the proccess of studying for those incredibly intense exams that every Israeli is familiar with from childhood, is differ between two groups:</p>
<p>Group A: Adults. mostly academic personelle after the age of 23 but less than 28<br />&nbsp;about 5 years to 10 years from completing their matriculation exams.</p>
<p>Group Y: Young. high school newest graduates.&nbsp;From the age of 18,<br />&nbsp;at least 3 month after completing their matriculation exams but no more than 20 years old.&nbsp;</p>
<p>In fact, the variable that we wanted to compare in both population is the "Quality of Memory".</p>
<p>Is there a difference in the&nbsp;Memory Quality Score (MQS)&nbsp;<br />between newly high school graduates and academic students (ages 23-28)&nbsp;<br />regarding the core-topics that were intensively learnt &nbsp;in high school .<br />did the working memory affected differently between those group in its transition to long term memory ?&nbsp;</p>
<p>However, this is not something that is easy to check.<br />For this purpose, we determined a quick test, containing 3 sections:</p>
<p>1. Class Classification:<br />we needed to know if the person asked belongs to group A or to group Y.&nbsp;</p>
<p>2. Student Classification:<br />It seemed, like it could have been better to analyse further the results if we knew the approximate level of the student and how well was his/her overall performance during the time of the exams.<br />For example, if the student has invested well in his studies, it could imply why does he remember the matirials so well, even if it is after 7 years.&nbsp;</p>
<p>3.Memory Test:</p>
<p>The test was short, maybe too short, but it represents well the potential of having a good memory vs bad one. &nbsp;The questions asked refered only to topic titles, and maybe a little bit more. The one and only mathematical question, which is not likely from a topic that most students engage in their academic studies, is the only question that required to remember a skill and not a topic's name of description.</p>
<p>more about the test is located <a href="https://github.com/matantsour/Core_Studies_Memory_Analysis/blob/gh-pages/questions.md" target="_blank" rel="noopener noreferrer">here</a></p>
<p>&nbsp;</p>
<h1><span style="text-decoration: underline;">The <span style="color: #0000ff; text-decoration: underline;">Analysis </span>Process:&nbsp;check the code&nbsp;<a href="https://github.com/matantsour/Core_Studies_Memory_Analysis/blob/gh-pages/Core_Studies_Memory_Analysis.ipynb" target="_blank" rel="noopener noreferrer">HERE</a></span></h1>
<h2 style="text-align: center;">&lt;Skip to the code&nbsp;<a href="https://github.com/matantsour/Core_Studies_Memory_Analysis/blob/gh-pages/Core_Studies_Memory_Analysis.ipynb" target="_blank" rel="noopener noreferrer">HERE</a>&gt;</h2>
<p><span style="text-decoration: underline;"><strong>1. Acquiring the data:</strong></span><br />we took the results of 99 responders to the test.<br />The raw data can be accessed from &lt;here&gt;</p>
<p><span style="text-decoration: underline;"><strong>2. Cleaning the data:</strong></span></p>
<p>We needed to clean the rows where the key parameters: Age and Education were not bar conditions were not met.<br />for example, the test didn't take into account adults whose age is between 20-23, and who didn't complete their matriculation&nbsp;exams.</p>
<p><span style="text-decoration: underline;"><strong>3. Detemine the Individual Memory Quality Score:</strong></span></p>
<p>Each responder&nbsp;was given an individual Memory Quality Score (MQS) based of his memory test answers.<br />whereas X represents the score for each category, this is how the MQS was calculated<br />Each category's score is 25% of the MQS<br /><br />A. Civil Studies: x*100/6 (6 is the maximun score, so if x=6, this category's score is 100)<br /><br />B.Litterature Studies: 10% for the first question and 15% for the second one.<br />for each question the score is X*10. (so if the subject remembered 5 pieces of litterature&nbsp; out of 10, the score will be 50.<br /><br />C. History Studies: X*100/6 ( 6 was the maximun answer given in this exam, so in fact the highest number of topics one was able to recollect out of 99 responders<br /><br />D. Math Studies: X*100/5 (if the answer was 5, than the score is 100 for this category)</p>
<p>MQS= 0.25*(A+B+C+D)</p>
<p><span style="text-decoration: underline;"><strong>4. &nbsp;Data Exploring</strong></span><br />we freely wanted to just explore the data and to draw conclusions.<br />In this section you can see many sub-tables, graphical descriptions and more.&nbsp;</p>
<p><span style="text-decoration: underline;"><strong>5.Statistical Inference:</strong></span></p>
<p>Finally, the main question was about to be answered.&nbsp;</p>
<p>Is there a difference in the&nbsp;Memory Quality Score (MQS)&nbsp;<br /><br />between newly high school graduates and academic students (ages 23-28)&nbsp;<br /><br />regarding the core-topics that were intensively learnt &nbsp;in high school .<br /><br />did the working memory affected differently between those group in its&nbsp;<br /><br />transition to long term memory ?&nbsp;</p>
<p>The answer, much to our surprise, is No.<br />Both groups showed similar performance regading their MQS, after performing Two Sampled T-Test of unequal variance.<br />we recienved definte answer that there is no difference in the group's mean MQS.&nbsp;</p>
<p>&nbsp;</p>
<h1>THANK YOU !</h1>
<h1>If you liked my project please check my <span style="color: #0000ff;">Linked_in</span> Profile&nbsp;<a href="https://www.linkedin.com/in/matan-tsour/" target="_blank" rel="noopener noreferrer">&lt;Here&gt;</a>.</h1>
<h1>&nbsp;</h1>

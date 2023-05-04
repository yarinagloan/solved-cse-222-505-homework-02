Download Link: https://assignmentchef.com/product/solved-cse-222-505-homework-02
<br>
In this homework you will create an ExperimentList class to keep track of some machine learning experiments and their results. A machine learning experiment consists of the following instance variables:




<ul>

 <li>setup (String): explains the experimental setup</li>

 <li>day(integer): represents the day of start – time(Time): represents the time of start</li>

 <li>completed(boolean): indicates whether it is completed or not</li>

 <li>accuracy(float): represents the output (not a valid value if the experiment is not completed)</li>

</ul>




Your class should implement the basics of a single linked list to keep the experiments. In order to speed up add and remove operations, an additional list structure should be defined in the level of days.










Your class should support the following functionality:




<ol>

 <li>addExp(Experiment): insert experiment to the end of the day</li>

 <li>getExp(day, index) : get the experiment with the given day and position</li>

 <li>setExp(day, index, ) set the experiment with the given day and position</li>

 <li>removeExp(day, index): remove the experiment specified as index from given day</li>

 <li>listExp(day): list all completed experiments in a given day</li>

 <li>removeDay(day): remove all experiments in a given day</li>

 <li>orderDay(day): sorts the experiments in a given day according to the accuracy, the changes will be done on the list</li>

 <li>orderExperiments(): sorts all the experiments in the list according to the accuracy, the original list should not be changed since the day list may be damage</li>

</ol>




Additional requirements are listed as follows:

<ol>

 <li>ExperimentList class should be iterable.</li>

 <li>Do not use any class from Java Collections library, each part should be written from scratch.</li>

 <li>Write a driver class (i.e. Main class) which tests all the functionality of your ExperimentList class.</li>

 <li>Include a table in your report which shows the complexity of all the functions and give details on how you calculate it.</li>

</ol>




<strong>Notes:</strong>




<ol>

 <li>Submit your homework as studentnumber.zip and which includes the following files: – intelliJ project file

  <ul>

   <li>pdf</li>

   <li>Javadoc</li>

  </ul></li>

 <li>The report must be in format “ReportFormat.doc” (moodle)</li>

 <li>The implementations will be 75 points and the report is 25 points out of 100</li>

 <li>Submit your homework until the last submission date</li>

 <li>You can ask your questions via email: <u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="533220272621323d133427267d3637267d2721">[email protected]</a></u> or by coming to office 118</li>

</ol>









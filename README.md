# ZEN-Mentos-Backend

# Mentor and Student Assigning with Database

--------------------------------------------------------------------------------------------------

Base URL https://zen-assign-mentors.herokuapp.com

# Mentor Api's

<pre>GET          <a href="https://zen-assign-mentors.herokuapp.com/Mentors">/Mentors </a></pre>

<pre>POST         <a href="https://zen-assign-mentors.herokuapp.com/Mentors">/Mentors </a></pre>

<pre>GET by ID    <a href="https://zen-assign-mentors.herokuapp.com/Mentors/get-mentor/60e7f4acd5ff5342a06652dd">/Mentors/get-mentor/:ID </a></pre>

# Student Api's

<pre>GET          <a href="https://zen-assign-mentors.herokuapp.com/Students"> /Students </a></pre>

<pre>POST         <a href="https://zen-assign-mentors.herokuapp.com/Students"> /Students </a></pre>

<b>To get list of students whose mentors weren't assigned </b>

<pre>GET          <a href="https://zen-assign-mentors.herokuapp.com/Students/no-mentors">/Students/no-mentors</a></pre>

<b>To assign or change Mentor for student</b>

<pre>PATCH        <a href="https://zen-assign-mentors.herokuapp.com/Students/assign-mentor/60e5dc9da2d09d6d581b7058">/Students/assign-mentor/:student-id</a></pre>

<b> To assign mentors for multiple Students </b>

<pre>PATCH        <a href="https://zen-assign-mentors.herokuapp.com/Students/assign-mentor-students">/Students/assign-mentor-students</a></pre>

<b> To Assign or Change Mentor for particular student </b>
  > Pass Mentor ID in request Body

<pre>PATCH        <a href="https://zen-assign-mentors.herokuapp.com/Students/assign-mentor/60e5dc9da2d09d6d581b7058">/Students/assign-mentor/:student-id</a> </pre>

<b> To Assign mentor for multiple students </b>
  > Pass Mentor ID and Student ID as list in body
 
<pre>PATCH        <a href="https://zen-assign-mentors.herokuapp.com/Students/assign-mentor-students">/Students/assign-mentor-students</a> </pre>

<b> To get all students of particular Mentor

<pre>GET          <a href="https://zen-assign-mentors.herokuapp.com/Students/mentor-students/60e7f4acd5ff5342a06652dd">/Students/mentor-students/:mentor-id </a></pre>
 







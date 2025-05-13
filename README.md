# cs112-assignment-1-students-database-solved
**TO GET THIS SOLUTION VISIT:** [CS112 Assignment 1-Students database Solved](https://www.ankitcodinghub.com/product/cs112-assignment-1-students-database-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91960&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS112 Assignment 1-Students database Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Students database

⇒ Create a student structure as follows:

1 2 3 4 5 6 7 8 9

10 11 12 13

1 2

</div>
<div class="column">
Dr. Amin Allam

</div>
</div>
<div class="layoutArea">
<div class="column">
Cairo University

Faculty of Computers and Artificial Intelligence Computer Science Department

Assignment 4

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
const int MAX_NAME=14; //Assumeanamecontainsatmost14characters enum Gender{MALE,FEMALE};

struct Date{int year; int month; int day;};

<pre>struct Student
{
</pre>
<pre>   int    id;
   char   first_name[MAX_NAME+1];
   char   last_name[MAX_NAME+1];
   Date   birth_date;
   Gender gender;
   double gpa;
</pre>
};

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
⇒ Define a function InputStudent() which takes a student data from the user and saves it into a Student object.

⇒ Define a function OutputStudent() which prints a student data in one line.

</div>
</div>
<div class="layoutArea">
<div class="column">
void InputStudent(Student* s); // s is a pointer to one object void OutputStudent(Student* s);

</div>
</div>
<div class="layoutArea">
<div class="column">
Each student data should be output in one line in the following order: id first name last name birth date gender gpa The following is an example of student data input and output:

<pre>20090111 Aly Ahmed 26/5/1992 Male 3.4
</pre>
⇒ Define a function InputAllStudents() which inputs n students from the user and saves them in a dynamic array which was previously allocated in main().

⇒ Define a function OutputAllStudents() which prints all student data, each student in one line.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 2

</div>
</div>
<div class="layoutArea">
<div class="column">
void InputAllStudent(Student* s, int n); //sisapointertodynamic void OutputAllStudent(Student* s, int n); // array of n objects

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Programming-1 CS112 Assignment 4

</div>
<div class="column">
FCI-CU

</div>
</div>
<div class="layoutArea">
<div class="column">
⇒ Define a function BirthLess() that takes 2 student pointers and returns true if the first student is born before the second student.

⇒ Define a function GpaGreater() that takes 2 student pointers and returns true if the gpa of the first student is greater than the gpa of the second student.

1 2

1 2

1 2

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>bool BirthLess(Student* a, Student* b);
bool GpaGreater(Student* a, Student* b);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
⇒ Define a function SortStudentsByBirthDate() that sorts n students by increasing birth date (the student with the earliest birth date should be first). The function should call BirthLess().

⇒ Define a function SortStudentsByGpa() that sorts n students by decreasing gpa (the student with the highest gpa should be first). The function should call GpaGreater().

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>void SortStudentsByBirthDate(Student* s, int n);
void SortStudentsByGpa(Student* s, int n);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
⇒ Define a function SearchStudentId() that takes n students and a student id as parameters and returns a pointer to a student having this id or 0 if not found.

⇒ Define a function SearchStudentFirstName() that takes n students and a C-string as parameters and returns a pointer to any student having this first name or 0 if not found.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Student* SearchStudentId(Student* s, int n, int id);
Student* SearchStudentFirstName(Student* s, int n, char* name);
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
⇒ The program should start by taking the number of students n from the user. The program should create a dynamic array of n students.

⇒ Then, the program should take the full data of each of the n students from the user.

⇒ Then, the program should output a list of choices for the user as follows:

⇒ If the user inputs 1, the program should output the full data of the n students, each student in one line, then reprints the list of choices.

⇒ If the user inputs 2, the program should sort the n students by increasing birth date then outputs all sorted students, then reprints the list of choices.

⇒ If the user inputs 3, the program should sort the n students by decreasing gpa then outputs all sorted students, then reprints the list of choices.

⇒ If the user inputs 4, the program should take integer from the user, searches for a student having this id, prints the student full data if it exists, then reprints the list of choices.

⇒ If the user inputs 5, the program should take a C-string from the user, searches for a student having this first name, prints the student full data if it exists, then reprints the list of choices.

⇒ If the user inputs 6, the program should release the dynamic array and exit.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>1) Output all students data.
2) Sort students by increasing birth date.
3) Sort students by decreasing gpa.
4) Search students by id.
5) Search students by first name.
6) Exit the program.
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>

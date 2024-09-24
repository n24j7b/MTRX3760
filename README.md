java c
MTRX3760 - Lab   3 
Refactoring and Design 
This assignment contributes   10% towards your final mark. It is to be   completed   individually, not   in   groups. Total Marks:   100.
This assignment is due before the start of your allocated lab session in two weeks, i.e. before the start of the Week 6 lab session for Weds/Fri labs, and before the start of the Week 7 lab session for Monday labs. Late assignments will be subjected to the University’s late   submission policy unless accompanied   by   a   valid   special   consideration   form. Plagiarism   will   be   dealt   within   accordance   with   the University of Sydney plagiarism policy. Lab submissions will not be accepted more than a week after the due date. 
Assignments will be assessed based on the following components. Incomplete submissions   will   have   severely reduced marks:
● Report:   Submit a   .pdf   report using the class Canvas site. The report   can be very   simple,   and   needs only directly address the questions laid out   in   the   assignment.
The cover page for your report should include your SID   and tutorial   section, but   do   not   include   your name to comply with the University’s anonymous marking policy.Code appendix: The   appendix   ofyour   report must contain   a printout (in   text   format)   of   all source code written for the assignment. File header comments and proper   formatting will be critical to making this section readable. Unintelligible code attachments will result in loss   of marks.
● Code:   Submit your code (code only, no binaries) in a   .zip   file via   the   canvas   site.
Please see Lab   1 for hints on preparing your report, including how to   format   code   for   inclusion   in the   appendix.
Logic   Simulator Redesign 
This lab has the following   goals:
1.       To allow you to   revisit   a   familiar   design problem   with   new   learnings   covered   over   the   first   four   weeks   of   the   unit,
2.       To simulate   and build your understanding   of   a   system   of   moderate   complexity,   and
3.       To exercise   design thinking   and   decision-making when   faced with   the   many   open   design   choices   typical   of   a   real-world   engineering   problem.
In the circuit simulator from Lab 2 we used hard-coded circuit   designs.   For this   lab you   will   redesign   the   circuit simulator to load the description of   the circuit from   a   circuit   description   file.   This   means   your program should build the circuit dynamically at runtime rather than in   a hard-coded manner.
You may design the circuit description language yourself, though an   example   of   a   suitable   format   and   a   means of   reading it are provided in the code accompanying this   lab handout.
As part of   the refactor, we will lift a few simplifications   applied   in previous   labs. We   have previously   allowed global constants and single-file submissions. These   are   not   applicable   to   this   lab:
1.       Employ the “encapsulate   everything”   strategy   of   object-oriented   design taught   in   lecture,   such   that there are no global constants or floating   functions   or   data,
2.       Build your solution   as   a mult代 写MTRX3760 - Lab 3 Refactoring and DesignC/C++
代做程序编程语言i-file project,   following the   guiding principle   that   each   class   should   generally have its own header and implementation files,   and
3.       In general there   should be very   few   constants   or hard-coded   circuitry,   as   the   goal   is   to   move   those   aspects   of   the   program   into   the   input   files.
To make this lab more tractable the following new simplifications may be applied:
1.         Support for subcircuits is not required,
2.       You may limit the   logic   gates   supported to AND,   OR, XOR   and NOT   gates.
You may choose to start from your own Lab   2   solution   or you may   choose   to   start   from   scratch.
Regardless, your submission should demonstrate the principles of   object-oriented   design   and   C++   coding   best practices taught in lecture.
Use your redesigned program to implement at least two different logic circuits,   one   of   which   is   a   1-bit   comparator.
[20 Marks] Functionality: In your report show the content ofyour   1-bit comparator,   and   copy/pasted   text   from the terminal showing your program simulating it correctly. Note: copy/paste the text, screenshots are unacceptable. The program output and the code in your attached   .zip   file will be   assessed   for correct functionality.
[20 Marks] Comparing containers: In Week 3 we learned   about   the   C++   Standard   Library   and   the standard types of   containers it comes with. In your report, compare the two best   choices   for containers   that you could have used in your program to keep track of   the components in your circuit: 
● List the names of   the two best choices of   container as they appear in   the   standard   library,
● List which underlying data structure each of   those two containers uses,
● List the two main advantages and disadvantages of   each container,   and
● State which factor was most important in driving your choice of   container.
[30 Marks] Design: In your report provide a UML class diagram for your   design.   Do not   include   member   variables and functions. This diagram and your code will be   assessed based   on   appropriate use   of   the design principles taught   in lecture.
[30 Marks] Code Quality and Development Process: Include   in your report your   git   commit   history   as   reported by:
git   log   --oneline
Note: copy/paste the text, screenshots are unacceptable 
Your code and commit history will be assessed based on style and coding and development best practices as taught in   lecture.
Self-Assessment [+5 Bonus] In your report estimate the level of   achievement ofyour submission.   Show   estimates   for   all component grades as well as the total. If   your estimated total is within   5   marks   of   the   correct   score   you   will be awarded 5 bonus marks. Ignore late penalties when estimating.
/20 Functionality
/40 Code   quality
/40 Design
/   100   Total
ROS Tutorials 
Complete the ROS 2 tutorials here: https://docs.ros.org/en/humble/Tutorials.html . Complete up to and      including the Beginner: Client Libraries sections. Be sure to   complete the   C++ versions   of   the   tutorials.





         
加QQ：99515681  WX：codinghelp

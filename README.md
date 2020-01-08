# General-course-info

We are going to be using github to manage up/download of exercises and assignments. We encourage the use of R as a coding language for this course. Some details of how to install R and github can be found below. Please install these before hte first class if you can. If you run into any problems, we can help you with them at the start of class.

1. The home page for the R project is: http://www.r-project.org/
Please follow the link downloadR in the box Getting Started.
Then download and install the most recent release: ver3.6.0 released 2019-04-26.
Older machines might require an older version.

2. We will be running R using the R Studio integrated development environment (IDE).
Please download and install RStudio Desktop Open Source License from the following
website: http://www.rstudio.com/

3. Please create a GitHub account at https://github.com if you do not have one.

4. You will need the software Git to talk between GitHub and RStudio. Please install Git
from https://git-scm.com/downloads. Now we want to set our Git username and email.
We do this by opening a Terminal (cmd) Window and typing (using "Mona Lisa" as an example username):
>git config --global user.name "Mona Lisa"

confirm that the user name is set by typing
>git config --global user.name
>Mona Lisa

Setting the email is very similar. Do this by typing
>git config --global user.email "email@example.com"

And confirm that you have set the email address by typing:
>git config --global user.email
>email@example.com

Directions to follow are found here, under Setting up Git:
https://help.github.com/articles/set-up-git/


In-class exercises and examinable assignments can be found at the following website:
https://classroom.github.com/classrooms/58991550-pm520-spring-2020-classroom-1/

In order to access the exercise/assignment details, pseudocode, etc., and then be able to push your solutions so that I can see them, you need to accept the invitation you will receive via email for each exercise.

When you start work on an exercises or assignment, you will need to complete the following steps:
1. Accept the invitation to the assignment that you will receive (by email, I think)
2. Link the assignment to your Github ID (github will automatically ask you to do this and help you get it done).
3. Downoad the pseudocode (if there is any for that problem). The simplest way to do this using RStudio is...
4. As you are working on the problem, regularly "commit" your work. I will not be able to see what you are doing, and comment on it, until you "push" the work back to Github. Get into the habit of committing regularly.
5. Once you have completed your work on that problem you need to "commit" you work and then push it to github one final time.


## Here is the Course Syllabus:

Instructor:	Paul Marjoram, Ph.D.        
		Soto Bldg 202V, HSC 
           	Phone: (323) 442-0111
                          Email: pmarjora@usc.edu
 
Teaching Assistants: TBD

Office Hours : Mondays 10am-11am.

Class Meets:  Monday, 1pm-4pm.

Course Objective:
The objective of the course is to give you the skills to enable you to both be able to program, and better understand, statistical machinery using the R programming language. Note that this is not really a course about R, as such. Instead, we use R as a way of illustrating how to write code to perform a number of probabilistic and statistical procedures. We will introduce the R details as we go, but students will be expected to invest some time of their own each week, outside class, in which they improve their R programming skills if necessary.

Each week’s lecture (60-90 minutes) will focus on one or more areas in probability and statistics, describing how those procedures are performed. The rest of the class (90-120 minutes) will be a lab in which students will sit down and start to code those procedures in class. Students will be encouraged to show their work “in progress”. For example, you’ve written 30 lines of code and it isn’t working properly: we will put the code on the screen and we will all try to work out what is wrong. In other words, we will learn by doing, and by learning from our mistakes, rather than relying upon the traditional method of listening to a member of faculty drone on for 3 hours. In doing so we hope to make the course more interactive. As the saying goes: turn-about is fair play. So, as the instructor, I will also display bugged code of my own to the rest of the class, so that we can learn from my mistakes as well.

The course will be examined by a number of projects during the course. These projects will involve writing R code to perform a particular task (optimize a function, fit a regression, simulate a stochastic process,…). That code will be turned in to me and I will run it on some test problems to see how it does. In addition, the final exam will consist of your giving small group (2-3 people) presentations regarding statistical computing methods.


Recommended Textbook: “Scientific Programming and Simulation Using R” – Owen Jones, Robert Maillardet and Andrew Robinson, CRC Press. This book will (I think) be available from the USC bookstore, but can also ordered from Amazon ($70 to buy; $50 to rent).
Please note that each student will also be required to bring a laptop to each class so that they can actively write code during the lab. 

Other Material: Copies of slides will be posted, as will example bits of code. But there are a host of free online resources for R:
•	Mastering Software Development in R, 2017. Roger Peng, Sean Kross, Brooke Anderson. https://bookdown.org/rdpeng/RProgDA/
•	R for Data Science, 2017 Garrett Grolemund and Hadley Wickham. http://r4ds.had.co.nz/
•	Advanced R, 2014, Hadley Wickham, CRC press. http://adv-r.had.co.nz/ (Second edition is avalaible in print on June 28 https://www.amazon.com/gp/product/0815384572/, online here: https://adv-r.hadley.nz/)
•	R Packages, 2015, Hadley Wickham, O’Reilly. http://r-pkgs.had.co.nz/ (work on a second edition is in development here https://r-pkgs.org/ starting as of 2019-02)
•	Advanced Statistical Computing, 2018 Roger Peng (https://bookdown.org/rdpeng/advstatcomp/) 

Grading:  70% projects + 20% final presentation + 10% participation. 

Pre-requisites: None, but you will need to have some basic statistics and probability. If you are not sure, come and see me to talk about it.


### PROPOSED COURSE OUTLINE:
Most weeks will be based upon one of the chapters from the course text, but some of the latter weeks will digress from the text and use material that will be distributed or described in class [labeled “(external material)”].

Week 1: Introduction – Using Github; Random number generation and Monte Carlo Estimation. How to estimate things that you cannot calculate. Coin-tossing. Occupancy problems. Hypercubes. Golf balls. 
Week 2: More Monte Carlo Estimation: Estimating pi, Random variable simulation, Likelihood Estimation. Bayesian methods. Accept/Reject Algorithms (external material).
Week 3: Methods for finding function roots and fixed points. Math as art. (Chapter 10 of course text).
Week 4: Probability and Stochastic Simulation – Urn Models and Chinese Restaurants (Chapter 18 vol 1; or Chapter 20, in the 2nd ed.).
Week 5: Optimization and Regression (chapter 12)
Week 6-8: Markov Chain Monte Carlo [MCMC] Methods. Adaptive MCMC, Parallel Tempered-MCMC, Code-breaking (external material).
Week 9: Gibbs Sampling, Accept/Reject Algorithms (external material).
Week 10: Permutation tests, Numerical Integration and Importance Sampling (Chapters 19 and 22; chaps. 21 and 24 in the 2nd ed.).
Week 11: Approximate Bayesian Computation, ABC-Rejection, ABC-MCMC (external material).
Week 12: Sequential Monte Carlo Methods, Regression-adjusted ABC (external material)
Week 13: Hidden Markov Models, Genetic Algorithms. (external material)

Closing Project: Short presentation from a topic we haven’t covered in the course: e.g. E-M algorithms, fancy MCMC version, (e.g. Hamiltonian MCMC, Empirical Bayes methods, Boot-strapping,…), or a related project from your own research.



STATEMENT FOR STUDENTS WITH DISABILITIES:
Any student requesting academic accommodations based on a disability is required to register with Disability Services and Programs (DSP) each semester. A letter of verification for approved accommodations can be obtained from DSP. Please be sure the letter is delivered to me (or to TA) as early in the semester as possible. DSP is located in STU 301 and is open 8:30 a.m.–5:00 p.m., Monday through Friday. The phone number for DSP is (213) 740-0776.

	STATEMENT ON ACADEMIC CONDUCT AND SUPPORT SYSTEMS

Academic Conduct:

Plagiarism – presenting someone else’s ideas as your own, either verbatim or recast in your own words – is a serious academic offense with serious consequences. Please familiarize yourself with the discussion of plagiarism in SCampus in Part B, Section 11, “Behavior Violating University Standards” policy.usc.edu/scampus-part-b. Other forms of academic dishonesty are equally unacceptable. See additional information in SCampus and university policies on scientific misconduct, policy.usc.edu/scientific-misconduct.

Support Systems: 

Student Health Counseling Services - (213) 740-7711 – 24/7 on call
engemannshc.usc.edu/counseling
Free and confidential mental health treatment for students, including short-term psychotherapy, group counseling, stress fitness workshops, and crisis intervention. 

National Suicide Prevention Lifeline - 1 (800) 273-8255 – 24/7 on call
suicidepreventionlifeline.org
Free and confidential emotional support to people in suicidal crisis or emotional distress 24 hours a day, 7 days a week.

Relationship and Sexual Violence Prevention Services (RSVP) - (213) 740-4900 – 24/7 on call
engemannshc.usc.edu/rsvp
Free and confidential therapy services, workshops, and training for situations related to gender-based harm.

Office of Equity and Diversity (OED) | Title IX - (213) 740-5086
equity.usc.edu, titleix.usc.edu
Information about how to get help or help a survivor of harassment or discrimination, rights of protected classes, reporting options, and additional resources for students, faculty, staff, visitors, and applicants. The university prohibits discrimination or harassment based on the following protected characteristics: race, color, national origin, ancestry, religion, sex, gender, gender identity, gender expression, sexual orientation, age, physical disability, medical condition, mental disability, marital status, pregnancy, veteran status, genetic information, and any other characteristic which may be specified in applicable laws and governmental regulations.

Bias Assessment Response and Support - (213) 740-2421
studentaffairs.usc.edu/bias-assessment-response-support
Avenue to report incidents of bias, hate crimes, and microaggressions for appropriate investigation and response.

The Office of Disability Services and Programs - (213) 740-0776
dsp.usc.edu
Support and accommodations for students with disabilities. Services include assistance in providing readers/notetakers/interpreters, special accommodations for test taking needs, assistance with architectural barriers, assistive technology, and support for individual needs.

USC Support and Advocacy - (213) 821-4710
studentaffairs.usc.edu/ssa
Assists students and families in resolving complex personal, financial, and academic issues adversely affecting their success as a student.

Diversity at USC - (213) 740-2101
diversity.usc.edu
Information on events, programs and training, the Provost’s Diversity and Inclusion Council, Diversity Liaisons for each academic school, chronology, participation, and various resources for students. 

USC Emergency - UPC: (213) 740-4321, HSC: (323) 442-1000 – 24/7 on call 
dps.usc.edu, emergency.usc.edu
Emergency assistance and avenue to report a crime. Latest updates regarding safety, including ways in which instruction will be continued if an officially declared emergency makes travel to campus infeasible.

USC Department of Public Safety - UPC: (213) 740-6000, HSC: (323) 442-120 – 24/7 on call 
dps.usc.edu
Non-emergency assistance or information.

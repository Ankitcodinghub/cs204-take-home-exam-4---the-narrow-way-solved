# cs204-take-home-exam-4---the-narrow-way-solved
**TO GET THIS SOLUTION VISIT:** [CS204 Take Home Exam 4 – The Narrow Way Solved](https://www.ankitcodinghub.com/product/cs204-the-4-the-narrow-way-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109400&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS204 Take Home Exam 4 – The Narrow Way Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
DISCLAIMER:

Introduction

The aim of this assignment is to practice on operator overloading. In this assignment, you will implement a well-structured dynamic 2D matrix class with several operators overloaded.

Main is Given (yeey!)

What does Main do?

The main function reads two different file names from the console and opens them. Later, by using the extraction operator (&gt;&gt;) that you will overload, it will read the contents of each file into a dynamic 2D matrix object of type integer. Later, it does several operations with this constructed 2D matrix and displays them on the console using the insertion operator (&lt;&lt;) that you will overload. You can inspect the main file for details, as it is quite short.

Class to Implement

We have given you an implementation of the Matrix2D class as a basis. This basis class:

1) Does not implement default constructor,

2) Does not implement deep copy constructor,

3) Does not implement destructor, and

4) Lacks several other operators that the main function uses.

The definitive tasks of the assignment can be ordered like this:

– Implement isEmpty member function,

– Implement the destructor (deallocate the 2D dynamic array held within the object),

– Implement &lt;&lt; operator,

– Implement += and = operators for the class,

– Implement the copy constructor (you will need this for + operator. Do not make shallow copy, it will change outputs in the main and make your program fail test cases), and – Finally, implement + operator which will return a new Matrix2D object.

Format of the Input Files

There are very good assumptions that you can make on the format of the input files. These input files are the ones from which you will read the elements of the matrices. First of all, each row of the file represents a row of the matrix. The elements in a line can be separated by spaces, tabs or a combination of them, but this does not matter as you are already familiar with string streams.

The other assumption that you can make is that there will be an equal number of elements in each line of the file. Therefore, you do not need to check against this. Also, the number of lines in the file or the number of elements in a line will not ever be zero!

Lastly, the elements in the file will be whole numbers so that they can be parsed as integers.

In order to have pretty and neat outputs like we have in the sample runs, you will use setw(5) from the iomanip library.

Rules

In this assignment, the existence of main.cpp already narrows down the kind of implementation that you can follow. On top of this, there are other limitations as well.

First of all, you are not allowed to use vectors or other data structures inside your class to hold the data. It must be a 2D dynamic array as it is in the basis class. These restrictions follow the fact that implementing the assignment operator, destructor and copy constructor would be meaningless with a vector field in the class (as these would be done automatically). We want you to get experience on implementing these methods, hence we restrict such usages.

Sample Runs

Below, we provide some sample runs of the program that you will develop. The italic and bold phrases are the standard inputs (cin) taken from the user (i.e., like this). You have to display the required information in the same order and with the same words as here. Please refer to the submission page on SUCourse for additional sample runs.

Sample Run 1

file1.txt file2.txt

2 4 6 3 10

4 6 8 7 12

6 8 -4 9 14

8 10 20 14 16

10 12 12 10 18

2 4 6 3 10

4 6 8 7 12

6 8 -4 9 14

8 10 20 14 16

10 12 12 10 18

3 6 9 2 15

6 9 12 9 18

9 12 -13 12 21 12 15 34 21 24

15 18 17 12 27

10000 6 9 2 15 6 9 12 9 18

9 12 -13 12 21

12 15 34 21 24

15 18 17 12 27

3

Sample Run 2 file3.txt file4.txt

3 23 18 -3 3 14 1

8 7 6 5 4 3 2

10 51 8 17 -48 5 64 6 16 6 12 4 8 0

5 27 30 -5 4 17 9

5 4 3 1 -1 -3 -5

6 44 11 23 -41 4 56

-2 9 4 10 10 9 8

3 23 18 -3 3 14 1

8 7 6 5 4 3 2

10 51 8 17 -48 5 64 6 16 6 12 4 8 0

5 27 30 -5 4 17 9

5 4 3 1 -1 -3 -5

6 44 11 23 -41 4 56

-2 9 4 10 10 9 8

3 44 41 -13 1 24 2 15 13 11 9 7 5 3

15 94 18 39 -90 8 119

10 25 8 16 9 14 0

5 48 53 -15 2 27 10 12 10 8 5 2 -1 -4

11 87 21 45 -83 7 111

2 18 6 14 15 15 8

10000 44 41 -13 1 24 2 15 13 11 9 7 5 3

15 94 18 39 -90 8 119

10 25 8 16 9 14 0

5 48 53 -15 2 27 10 12 10 8 5 2 -1 -4

11 87 21 45 -83 7 111

2 18 6 14 15 15 8

3

Some Important Rules

Submit via SUCourse ONLY! Paper, e-mail or any other methods are not acceptable.

The internal clock of SUCourse might be a couple of minutes skewed, so make sure you do not leave the submission to the last minute. In the case of failing to submit your THE on time: “No successful submission on SUCourse on time = A grade of zero (0) directly.”

What and where to submit (PLEASE READ, IMPORTANT)

It’d be a good idea to write your name and last name in the program (as a comment line of course). Do not use any Turkish characters anywhere in your code (not even in comment parts). If your full name is “Duygu Karaoğlan Altop”, and if you want to write it as comment; then you must type it as follows:

// Duygu Karaoglan Altop

You should update the attached header file and upload it into the attachment section under the “Answer” area in the relevant assignment submission page on SUCourse. The name of the header file must be (“”myUpdatedMatrixClass.h”).

Since the grading process will be automatic, you are expected to strictly follow these guidelines. If you do not follow these guidelines, your grade will be zero (0). Any tiny change in the output format will result in your grade being zero (0), so please test your programs yourself, and against the sample runs that are available at the relevant assignment submission page on SUCourse.

In the CodeRunner, there are some visible and invisible (hidden) test cases. You will see your final grade (including hidden test cases) before submitting your code. There is no re-submission. You don’t have to complete your task in one time, you can continue from where you left last time but you should not press submit before finalizing it. Therefore, you should make sure that it’s your final solution version before you submit it. Also, we still do not suggest that you develop your solution on CodeRunner but rather on your IDE on your computer.

How to get help?

Good Luck!

Ahmed Salem, Duygu Karaoğlan Altop

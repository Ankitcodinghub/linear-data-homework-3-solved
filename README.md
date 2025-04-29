# linear-data-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [Linear Data Homework 3 Solved](https://www.ankitcodinghub.com/product/data-structure-2021_ds_fall_hw3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110155&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Linear Data Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
homework 21: B-heap (441, 6) homework 22: F-heap (449, 6) homework 23: SMMH (469, 5) homework 24: AVL tree and Red-black tree (518, 14) homework 25: B-tree? (550, 12) homework 26: B+-tree (560, 8)

Program Requirement

Programming Language: C

Execution Environment

CPU core: 1

Memory: 2 GB

Execution time limit: 1 second

C Compiler: GCC

Compiled with -O2 -std=c11 -Wall C Standard: C 11

Read input from stdin and write your output to stdout.

Use header files from C Standard Library only.

Submit your answer as a C source code file, no executable file.

Your program will be compiled by us.

Homework #21 *

Compare the performance of leftist trees and B-heaps under the assumption that the only permissible operations are insert and delete min. For this, do the following:

1. Create a random list of elements and a random sequence of insert and delete min operations of length . The number of delete mins and inserts should be approximately equal. Initialize a min-leftist tree and a B-heap to contain the elements in the first random list. Now, measure the time to perform the operations using the min-leftist tree as well as the B-heap. Divide the time by to get the average time per operation. Do this for

. Let be . Tabulate your computing times. 2. Based on your experiments, make some statements about the relative merits of the two data structures?

Technical Specification

Perform the experiment. Tabulate the computing times in your homework report.

Based on your experiments, make some statements about the relative merits of the two data structures.

Homework #22

Write C functions to do the following:

1. Create an empty F-heap

2. Insert element into an F-heap

3. Perform a delete min from an F-heap. The deleted element is to be returned to the invoking function.

4. Delete the element in node of an F-heap . The deleted element is to be returned to the invoking function.

5. Decrease the key in the node of an F-heap by some positive amount .

Note that all operations must leave behind properly structured F-heaps. Your functions for (4) and (5) must perform cascading cuts. Test the correctness of your procedures by running them on a computer using suitable test data.

Input Format

There are instructions in each line:

1. insert x val : Insert an element with key x

2. extract : Print out the minimum in the heap, and delete it from the heap.

3. delete x val : Delete the node with key x and value val . It is guaranteed that there will be at most 1 node matching the key and value.

4. decrease x val y : Decrease the key by y on the node that has key x and value y . It is guaranteed that there will be at most 1 node matching the key and value.

5. quit : Terminate your program.

Output Format

Print out (&lt;key&gt;)&lt;value&gt; , if you encounter extract and the F-heap is not empty.

Technical Specification

The key after decreasing will not exceed the bound of 32-bit signed integer.

Sample Input

Sample Output

Homework #23

Develop the code for all SMMH operations. Test all functions using your own test data.

Input Format

1. insert x : Add an integer x into the SMMH tree.

2. delete min : Delete the minimum element in the tree.

3. delete max : Delete the maximum element in the tree.

4. show : Show your tree.

5. quit : Terminate your program.

Output Format

Print your tree level by level.

Technical Specification

Sample Input

Sample Output

Homework #24 *

Program the search, insert and delete operations for AVL trees and red-black trees.

(a) Test the correctness of your functions.

(b) Generate a random sequence of inserts of distinct values. Use this sequence to initialize each of the data structures. Next, generate a random sequence searches, inserts, and deletes. In this sequence, the probability of a search should be 0.5, that of an insert 0.25, and that of a delete 0.25. The sequence length is . Measure the time needed to perform the operations in the sequence using each of the above data structures.

(c) Do part (b) for = 100, 1000, 10,000, and 100,000 and .

(d) What can you say about the relative performance of these data structures.

Input Format

There are lines of input. The first line is AVL or red_black . AVL means implement the

“instructions” by AVL-tree. red_black means implement the “instructions” by red-black tree. The instructions are:

1. insert x : Add an integer x to the red-black/avl tree. If x already exists, do nothing.

2. search x : Print out the (or ) of the tree node if the element x exists.

If the element x does not exist, print out Not found .

3. delete x : Delete the element x in the tree if the element x exists.

4. exist x : Print out exist if the element x is in the tree. If the element x does not in the tree, print out Not exist .

5. quit : Terminate your program.

(Note: The text book did not describe how to implement delete on AVL or red-black tree. Students can write your own delete to satisfy the constraint of the AVL or red-black tree. It is guaranteed that there is no search y after delete x in the testcase.)

Output Format

Print out the (or ) or Not found in a line, if you encounter an instruction search x .

Print out exist or Not exist , if you encounter an instruction exist x .

Technical Specification

Upload your report. In your report, you must

1. Tabulate the time you measured from (c).

2. Try to say about the relative performance of these data structures.

Sample Input

Sample Output

Homework #25 *

Write algorithms to search and delete keys from a B-tree by position; that is, get(k) finds the kth smallest key, and delete(k) deletes the kth smallest key in the tree (Hint: To do this efficiently, additional information must be kept in each node. Write each pair keep

.) What are the worst-case

computing times of your algorithm?

Input Format

The input consists of lines.

The first line contains one integer . It indicates how many B-tree operations in the following input.

The next lines declare B-tree operation. For every line , it consists of a string and an integer ; each separated by one whitespace. The can be add , get , getk , remove or removek . Each corresponds to one B-tree operation.

: add an integer into the B-tree. : find any integer in the B-tree.

: find the item in the B-tree.

: remove a integer from the B-tree.

: remove the item from the B-tree.

Usually we use B-tree as a key-value store where keys can be duplicated. But in this homework we doesn’t store any value(or key equals to the value). Doing so avoid tying the answer to specific implementation detail or increase the burden of evaluate the correctness of B-tree implementation.

Output Format

The output consists of lines. Each line corresponding to the result of B-tree operation

:

Output add(x) = ok

:

Output get(x) = x if x exists in the B-tree.

Output get(x) = not found if x doesn’t exists in the B-tree.

:

Output getk(k) = x where x is the item in the B-tree.

Output getk(k) = not found if k is an illegal position (exceeded the size of the Btree).

:

Output remove(x) = x if a x is removed from the B-tree successfully.

Output remove(x) = not found if x is not in the B-tree.

:

Output removek(k) = x where x is the item in the B-tree.

Output removek(k) = not found if k is an illegal position (exceeded the size of the Btree).

Technical Specification

Sample Input

Sample Output

Homework #26

Program B+-tree functions for exact the range search as well as for insert and delete. Test all functions using your own test data.

Input Format

The input consists of lines.

The first line consists of one integer . It indicates how many B+-tree operations are in the following input.

The rest of the lines input; each line declares a B+-tree operation. Line consists of a string and one to two integers. can be add , remove or range-search . The operation comes with 1 to 2 integers as arguments.

add x : add an integer x into the B+-tree.

remove x : remove an integer x from the B+-tree. range-search l r : Search for all the integers in the B+-tree that are within the range .

That is, given all the integers in the B+-tree . Search for all the that satisfied

.

Output Format

For each range-search operation, your program should output one line of text range [l,r) = [x0,x1,x2,…] . Where l and r is the argument specified in the given range-search operation. And x0,x1,x2,… are the integers that are in the B+-tree and within the range l and r.

You can refer to the sample output section for a more specific output format.

Technical Specification

.

Sample Input

Sample Output

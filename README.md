# cse220-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CSE220 Homework 4 Solved](https://www.ankitcodinghub.com/product/cse220-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93845&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE220 Homework 4  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
&nbsp;

&nbsp;

For this homework assignment you will be writing functions in assembly language. The functions will be tested independently of each other. This is very important to note, as you must take care that no function you write ever has<u> side-effects</u> or requires that other functions be called before the function in question is called. Both of these are generally considered bad practice in programming.

Some other items you should be aware of:

<ul>
<li>Each test case must execute in 1,000,000 instructions or fewer. Efficiency is an important aspect of programming. This maximum instruction count will be increased in cases where a complicated algorithm might be necessary, or a large data structure must be traversed. To find the instruction count of your code in MARS, go to the <strong>Tools</strong> menu and select <strong>Instruction Statistics</strong>. Press the button marked <strong>Connect to MIPS</strong>. Then assemble and run your code as</li>
<li>Any excess output from your program (debugging notes, etc.) will impact grading. Do not leave erroneous print-outs in your code.</li>
<li>We will provide you with a small set of test cases for each assignment to give you a sense of how your work will be graded. It is your responsibility to test your code thoroughly by creating your own test cases.</li>
<li>The testing framework we use for grading your work will not be released, but the test cases and expected results used for testing will be released.</li>
</ul>
<strong>Register Conventions</strong>

You must follow the register conventions taught in lecture and reviewed in recitation. Failure to follow them will result in loss of credit when we grade your work. Here is a brief summary of the register conventions and how your use of them will impact grading:

<ul>
<li>It is the callee’s responsibility to save any $s registers it overwrites by saving copies of those registers on the stack and restoring them before returning.</li>
<li>If a function calls a secondary function, the caller must save $ra before calling the callee. In addition, if the caller wants a particular $a, $t or $v register’s value to be preserved across the secondary function call, the best practice would be to place a copy of that register in an $s register before making the function call.</li>
<li>A function which allocates stack space by adjusting $sp must restore $sp to its original value before returning.</li>
<li>Registers $fp and $gp are treated as preserved registers for the purposes of this course. If a function modifies one or both, the function must restore them before returning to the caller. There really is no reason for your code to touch the $gp register, so leave it alone.</li>
</ul>
The following practices will result in loss of credit:

&nbsp;

<ul>
<li>“Brute-force” saving of all $s registers in a function or otherwise saving $s registers that are not overwritten by a function.</li>
<li>Callee-saving of $a, $t or $v registers as a means of “helping” the caller.</li>
<li>“Hiding” values in the $k, $f and $at registers or storing values in main memory by way of offsets to $gp. This is basically cheating or at best, a form of laziness, so don’t do it. We will comment out any such code we find.</li>
</ul>
<strong>How to Test Your Functions</strong>

To test your implemented functions, open the provided “main” files in MARS. Next, assemble the main file and run it. MARS will include the contents of any .asm files referenced with the .include directive(s) at the end of the file and then append the contents of your hwk4.asm file before assembling the program.

Each main file calls a single function with one of the sample test cases and prints any return value(s). You will need to change the arguments passed to the functions to test your functions with the other cases. To test each of your functions thoroughly, create your own test cases in those main files. Your submission will not be graded using the examples provided in this document or using the provided main file(s). Do not submit your main files with your hwk4.asm file – we will delete them. Also please note that these testing main files will not be used in grading.

Again, any modifications to the main files will not be graded. You will submit only your hwk4.asm for grading. Make sure that all code required for implementing your functions is included in the hwk4.asm file. To make sure that your code is self-contained, try assembling your hwk4.asm file by itself in MARS. If you get any errors (such as a missing label), this means that your hwk4.asm file is attempting to reference labels in the main file, which will not have the same names during grading!

<strong>A Final Reminder on How Your Work Will be Graded</strong>

It is imperative (crucial, essential, necessary, critically important) that you implement the functions below exactly as specified. Do not deviate from the specifications, even if you think you are implementing the program in a better way. Modify the contents of memory only as described in the function specifications!

<strong>Preliminaries</strong>

For this assignment you will be implementing a hash table data structure for storing different types of structs. The context of the assignment is a simulated book store that will track its books for sale and the actual sales themselves through two different hash tables. Towards the end of the assignment we will also explore a (sorta related) interesting computational problem we will solve using a simple, non-recursive brute-force algorithm. Perhaps in your Algorithms course you will study it (or a similar problem) using a more efficient, recursive algorithm.

&nbsp;

<strong>Data Structures</strong>

The assignment relies on three data structures given as structs:

<table>
<tbody>
<tr>
<td width="172">struct Book ~ string isbn;</td>
<td width="32">//</td>
<td width="131">13-character,</td>
<td colspan="2" width="338">null-terminated string [14 bytes]</td>
</tr>
<tr>
<td width="172">string title;</td>
<td width="32">//</td>
<td width="131">25-byte buffer</td>
<td width="36">to</td>
<td width="301">store the null-terminated title</td>
</tr>
<tr>
<td width="172">string author;</td>
<td width="32">//</td>
<td width="131">25-byte buffer</td>
<td width="36">to</td>
<td width="301">store the null-terminated author</td>
</tr>
<tr>
<td width="172">int times_sold;</td>
<td width="32">//</td>
<td width="131">4-byte integer</td>
<td width="36">the</td>
<td width="301">stores # of sales of this book</td>
</tr>
</tbody>
</table>
~

Note that a Book struct requires 14 + 25 + 25 + 4 = 68 bytes. We will assume that the entire struct is word-aligned, which guarantees that times_sold will also be word-aligned. In this assignment we will also assume that a string containing an ISBN consists only of the digit characters (no dashes, spaces, X’s, etc.)

struct BookSale ~

string isbn;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; // 13-character, null-terminated string [14 bytes]

byte[2] padding; // 2 bytes of zeros

int customer_id; // 4-byte customer ID#

int sale_date;&nbsp;&nbsp;&nbsp;&nbsp; // date of sale as # of days since 1/1/1600 [4 bytes]

int sale_price;&nbsp;&nbsp; // 4 bytes

~

Note that a BookSale struct requires 14 + 2 + 4 + 4 + 4 = 28 bytes. The date of the sale is encoded as a 4-byte integer that provides the number of days that have passed since January 1, 1600. For example, January 5, 1600 would be represented by the number 4. January 1, 1600 itself would be represented by the number 0. November 8, 2020 would be represented by the number 153,714. You will write functions to convert a date-string in the form YYYY-MM-DD (e.g., “2020-11-08”) to this numerical encoding. The inspiration for this time format is the<u> UNIX timestamp</u> system.

Instances of the above structs will be stored in two separate hash table data structures, as defined below. The hash table itself will be word-aligned.

<table>
<tbody>
<tr>
<td width="60">struct</td>
<td width="139">Hashtable ~</td>
<td width="31">&nbsp;</td>
<td width="442">&nbsp;</td>
</tr>
<tr>
<td width="60">int</td>
<td width="139">capacity;</td>
<td width="31">//</td>
<td width="442">maximum # of elements in hashtable [4 bytes]</td>
</tr>
<tr>
<td width="60">int</td>
<td width="139">size;</td>
<td width="31">//</td>
<td width="442"># of elements in hashtable [4 bytes]</td>
</tr>
<tr>
<td width="60">int</td>
<td width="139">element_size;</td>
<td width="31">//</td>
<td width="442">size of one element in the hashtable [4 bytes]</td>
</tr>
<tr>
<td colspan="2" width="199">object[]&nbsp;&nbsp;&nbsp;&nbsp; elements;</td>
<td width="31">//

//</td>
<td width="442">objects stored in the hashtable consumes&nbsp; (capacity*element_size)&nbsp;&nbsp; bytes</td>
</tr>
</tbody>
</table>
~

A hash table in this assignment consists of an array of structs, <strong>not </strong>an array of pointers to structs. Note how this differs from Java, wherein what we call “an array of objects” is really an array of <em>references </em>to objects. In C and MIPS it <em>is </em>possible to create an array of pointers to objects, and we will explore that

&nbsp;

option in the last function of the assignment. But for the functions in the current assignment, we will store the structs directly in the arrays themselves, the reason being that one of the purposes of this assignment is to deal with arrays of varying element sizes.

In the elements array, an <em>empty</em> entry, i.e., an entry in the array that has never stored a struct, is filled entirely with zeros. A <em>deleted</em> (sometimes called <em>available</em>) entry is one that once stored an object that has since been deleted (removed) from the hash table. A deleted element is represented by (capacmty*element_smze) , one-byte, two’s complement representations of -1 (i.e., 0xFF). That is, the entire entry in the array consists of one-byte -1s. Due to a quirk of how we will be using the hash table for this assignment, it will be sufficient to load the first byte of an entry in the elements array and check if that byte equals 0xFF. If so, that entry can be assumed to be <em>deleted</em>. Similarly, to check if an entry in elements is <em>empty</em>, it will be sufficient to load the first byte and check if it equals zero. Every 13-character ISBN must start with ‘9’, so the first character of a non-empty, non-deleted object in elements cannot be’ ‘0’. In sum, the first byte of a Book struct or a BookSale struct must be the number 0, the number -1, or the ASCII code for the character ‘9’.

<strong>Part 1: Copy a Memory Buffer</strong>

mnt memcpy(byte[] dest, byte[] src, mnt n)

The memcpy function copies n bytes of data from address src to address dest. You may assume that the dest buffer is at least n bytes in size. This function will be used in later functions to copy structs from one place in memory to another. Therefore, you should code for generality and not be concerned about the significance of the bytes that the function copies. For this reason, your code should use lbu to read the bytes from memory.

The function takes the following arguments, in this order:

<ul>
<li>dest: the address to copy bytes to</li>
<li>src: the address to copy bytes from</li>
<li>n : the number of bytes to copy (must be greater than 0)</li>
</ul>
Note that src and dest are not necessarily word-aligned.

Returns in $v0:

<ul>
<li>n if n &gt; 0, or</li>
<li>-1 if n : 0</li>
</ul>
Additional requirements:

<ul>
<li>The function may only change the contents of the dest buffer and no other parts of main</li>
<li>Only the first n bytes memory starting at dest may be changed. All other bytes in dest must be left unchanged.</li>
</ul>
Examples:

&nbsp;

<table>
<tbody>
<tr>
<td colspan="2" width="226"><strong>Function Arguments</strong></td>
<td width="60">&nbsp;</td>
<td width="115"><strong>Return Value</strong></td>
<td width="120"><strong>Updated </strong><strong>dest</strong></td>
</tr>
<tr>
<td width="100">“XXXXXXX”,</td>
<td width="126">“ABCDEFGHIJ”,</td>
<td width="60">3</td>
<td width="115">3</td>
<td width="120">“ABCXXXX”</td>
</tr>
<tr>
<td width="100">“XXXXXXX”,</td>
<td width="126">“ABCDEFGHIJ”,</td>
<td width="60">7</td>
<td width="115">7</td>
<td width="120">“ABCDEFG”</td>
</tr>
<tr>
<td width="100">“XXXXXXX”,</td>
<td width="126">“ABCDEFGHIJ”,</td>
<td width="60">-3</td>
<td width="115">-1</td>
<td width="120">“XXXXXXX”</td>
</tr>
<tr>
<td width="100">“XXXXXXX”,</td>
<td width="126">“ABCDEFGHIJ”,</td>
<td width="60">0</td>
<td width="115">-1</td>
<td width="120">“XXXXXXX”</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Part 2: Compare Two Strings</strong>

int strcmp(string str1, string str2)

The strcmp function takes two null-terminated strings (either or both of which could be empty) and returns an integer that indicates the<u> lexicographic order</u> of the strings. The function begins by comparing the first character of each string. If they are equal to each other, it continues with the following pairs until the characters differ or until a terminating null-character is reached. Note that the strings can be of different lengths.

The function takes the following arguments, in this order:

<ul>
<li>str1 : the starting address of the first string</li>
<li>str2 : the starting address of the second string</li>
</ul>
Returns in $v0:

<ul>
<li>the difference between the ASCII values of the first mismatch, if any: str1[n] – str2[n] , where n is the index of the first mismatch; or</li>
<li>0 if the contents of both strings are identical (including the case where they are both empty strings); or</li>
<li>length of str1 if str2 is an empty string but str1 is non-empty; or</li>
<li>negated length of str2 if str1 is an empty string but str2 is non-empty</li>
</ul>
Additional requirements:

<ul>
<li>The function must not write any changes to main memory.</li>
</ul>
Examples:

<table>
<tbody>
<tr>
<td width="418"><strong>Function Arguments</strong></td>
<td width="128"><strong>Return Value</strong></td>
</tr>
<tr>
<td width="418">“ABCD”,&nbsp; “ABCGG”</td>
<td width="128">-3</td>
</tr>
<tr>
<td width="418">“WHOOP!”,&nbsp; “WHOA”</td>
<td width="128">14</td>
</tr>
<tr>
<td width="418">“Intel”,&nbsp; “pentium”</td>
<td width="128">-39</td>
</tr>
<tr>
<td width="418">“STONY”,&nbsp; “BROOK”</td>
<td width="128">17</td>
</tr>
</tbody>
</table>
&nbsp;

<table>
<tbody>
<tr>
<td width="418">“”,&nbsp; “mouse”</td>
<td width="128">-5</td>
</tr>
<tr>
<td width="418">“lonely guy”,&nbsp; “”</td>
<td width="128">10</td>
</tr>
<tr>
<td width="418">“Wolfie”,&nbsp; “Wolfie”</td>
<td width="128">0</td>
</tr>
<tr>
<td width="418">“”,&nbsp; “”</td>
<td width="128">0</td>
</tr>
<tr>
<td width="418">“happy”,&nbsp; “Z”</td>
<td width="128">14</td>
</tr>
<tr>
<td width="418">“WOLF”,&nbsp; “WOLFIE”</td>
<td width="128">-73</td>
</tr>
<tr>
<td width="418">“StonyBrook”,&nbsp;&nbsp; “Stony”</td>
<td width="128">66</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Part 3: Initialize a Hash Table</strong>

int initialize_hashtable(Hashtable* hashtable, int capacity,

int element_size)

The initialize_hashtable function takes a pointer to (i.e., address of) an uninitialized Hashtable struct and performs the following steps:

<ol>
<li>sets the struct’s capacity field to the capacity argument</li>
<li>sets the struct’s size field to 0</li>
<li>sets the struct element_size field to the element_size argument</li>
<li>fills the entirety of the struct’s elements field to 0 (i.e., all capacity * element_size bytes)</li>
</ol>
Assume that the uninitialized block of memory referenced by hashtable is large enough to store a hash table of the required size in bytes.

The function takes the following arguments, in this order:

<ul>
<li>hashtable: a pointer to an uninitialized block of memory</li>
<li>capacity: the number of elements in the hash table’s elements array</li>
<li>element_size : the size of a single struct stored in one element of the hash table’s elements</li>
</ul>
Returns in $v0:

<ul>
<li>-1 if capacity is less than 1 or element_size is less than 1; or</li>
<li>0 otherwise</li>
</ul>
Additional requirements:

<ul>
<li>The function may only change the contents of the hashtable buffer and no other parts of</li>
</ul>
Example #1: initializing a hash table to store Book structs.

&nbsp;

hashtable = pointer to buffer of 352 <sup>(12+5*68)</sup> uninitialized bytes of memory capacity = 5

element_size = 68

Return value in $v0: 0

Resulting contents of hashtable:

5 0 68 (capacity, size, element_size)

elements[] array contents in hexadecimal, truncated:

<table>
<tbody>
<tr>
<td width="21">0:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">1:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">2:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">3:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">4:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
</tbody>
</table>
Example #2: initializing a hash table to store BookSale structs.

hashtable = pointer to buffer of 320 <sup>(12+11*28)</sup> uninitialized bytes of memory capacity = 11

element_size = 28

Return value in $v0: 0

Resulting contents of hashtable:

11 0 28 (capacity, size, element_size)

elements[] array contents in hexadecimal, truncated:

<table>
<tbody>
<tr>
<td width="21">0:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">1:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">2:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">3:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
<tr>
<td width="21">4:</td>
<td width="28">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="27">00</td>
<td width="30">00</td>
</tr>
</tbody>
</table>
&nbsp;

. . . 10: 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ~

Example #3: failed attempt to initialize a hash table to store BookSale structs. hashtable = pointer to buffer of some unknown number of uninitialized bytes of memory capacity = -3

element_size = 28

Return value in $v0: -1

Contents of hashtable are the same as before the function call.

<strong>Part 4: Compute the Hash Code for an ISBN in a Given Hash Table</strong>

&nbsp;

int hash_book(Hashtable* books, string isbn)

&nbsp;

The hash_book function takes a pointer to a valid Hashtable struct named books and an ISBN-13 value called isbn for which we want to compute the hash function. The hash function itself is very simple: sum the ASCII codes of the 13 characters in isbn and take the modulus of dividing that sum by the capacity of the books hash table (e.g., sum of the ASCII codes <em>mod</em> the capacity).

The function takes the following arguments, in this order:

<ul>
<li>books: the starting address of a valid Hashtable struct</li>
<li>isbn: a 13-character, null-terminated string that represents a valid ISBN</li>
</ul>
Returns in $v0:

. The value of the hash function when evaluated for the provided ISBN.

Additional requirements:

. The function may not write any changes to main memory.

Example #1:

hashtable = pointer to a valid hash table with capacity = 9 isbn = “9780671028370”

Return value in $v0: 7

Example #2:

hashtable = pointer to a valid hash table with capacity = 17 isbn = “9780071401940”

Return value in $v0: 11

Example #3:

hashtable = pointer to a valid hash table with capacity = 13 isbn = “1123121401940”

Return value in $v0: 3

<strong>Part 5: Retrieve a Book from a Hashtable of </strong><strong>Book</strong><strong> Structs</strong>

int, int get_book(Hashtable* books, string isbn) -&gt; (int, int)

The get_book function attempts to find a struct inside books with the given ISBN and returns the index of that struct, as well as the number of entries in books.elements that needed to be inspected to find that struct by way of linear probing. If an <em>empty</em> entry is encountered during probing, this means that no book of the given ISBN is in the hash table. If a <em>deleted</em> entry is encountered during probing, the linear probing must continue. If no struct has the given ISBN, the function returns -1 in $v0 and the number of inspected entries of elements in $v1.

&nbsp;

The function takes the following arguments, in this order:

<ul>
<li>books: the starting address of a valid Hashtable struct</li>
<li>isbn : a 13-character null-terminated string that represents a valid ISBN</li>
</ul>
Returns in $v0:

<ul>
<li>The index in elements where the book was found; or</li>
<li>-1 if the hash table does not contain a book with the given ISBN</li>
</ul>
Returns in $v1:

<ul>
<li>The number of entries in the elements array that were accessed before a book of the given ISBN was found or was determined not to be in the elements</li>
</ul>
Additional requirements:

<ul>
<li>The function may not write any changes to main memory.</li>
<li>The function must call hash_book and strcmp .</li>
</ul>
<strong><em>The examples in this document are not comprehensive nor cover all possible classes of inputs! </em></strong>Example #1: Attempt to get a book from an empty hash table

isbn = “9780553214830” Contents of books hash table:

<table>
<tbody>
<tr>
<td width="29">9 0</td>
<td width="130">68&nbsp; (capacity,</td>
<td width="54">size,</td>
<td width="461">element_size)</td>
</tr>
<tr>
<td width="29">0:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">1:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">2:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">3:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">4:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">5:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">6:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">7:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
<tr>
<td width="29">8:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="461">&nbsp;</td>
</tr>
</tbody>
</table>
Return value in $v0: -1 Return value in $v1: 1

Example #2: Get a book that is present in the hash table at the expected index

isbn = “9780440060670”

Contents of books hash table:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney</li>
</ul>
&nbsp;

Sheldon\0\0\0\0\0\0\0\0\0\0\00

<ul>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>deleted</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: 3

Return value in $v1: 1

Example #3: Attempt to get a book that is not present in the hash table; expected location is empt~

isbn = “9780007201780”

Contents of books hash table:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney Sheldon\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>deleted</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: -1

Return value in $v1: 1

Example #4: Get a book that is not present in the hash table; expected location is deleted (hash table not full); probing required

isbn = “9780060182980”

Contents of books hash table:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney Sheldon\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>deleted</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
&nbsp;

Return value in $v0: -1 Return value in $v1: 6

Example #5: Get a book that is present in a full hash table

isbn = “9780064408330”

Contents of books hash table:

7 7 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>9780345419580\0Moreta: Dragonlady of Pe\0Anne McCaffrey\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney Sheldon\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780140168130\0Big Sur\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Jack Kerouac, Aram Saroy\00</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: 4

Return value in $v1: 1

Example #6: Get a book that is present in the hash table at a probed index; one or more deleted slots encountered during probing

isbn = “9780140168130”

Contents of books hash table:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>9780345419580\0Moreta: Dragonlady of Pe\0Anne McCaffrey\0\0\0\0\0\0\0\0\0\0\00</li>
<li>deleted</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney Sheldon\0\0\0\0\0\0\0\0\0\0\00</li>
<li>deleted</li>
<li>9780140168130\0Big Sur\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Jack Kerouac, Aram Saroy\00</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: 5

Return value in $v1: 6

Example #7: Attempt to get a book that is not present in the hash table; hash table is full

&nbsp;

isbn = “9780316905750”

Contents of books hash table:

7 7 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>9780345419580\0Moreta: Dragonlady of Pe\0Anne McCaffrey\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9781516865870\0Beacon 23: The Complete \0Hugh Howey\0\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780440060670\0The Other Side of Midnig\0Sidney Sheldon\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9781573451990\0Rumors of War (Children \0Dean Hughes\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780140168130\0Big Sur\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Jack Kerouac, Aram Saroy\00</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00 Return value in $v0: -1</li>
</ul>
Return value in $v1: 7

<strong>Part 6: Insert a </strong><strong>Book</strong><strong> Struct into a Hashtable of Books</strong>

int, int add_book(Hashtable* books, string isbn, string title, string author)

The add_book function attempts to insert a new Book struct into a given hash table by initializing the contents of the struct with the provided ISBN, title and author. It also sets the times_sold field of the struct to 0. It begins by checking if the hash table is full. If so, the function returns (-1, -1) and makes no changes to the hash table’s contents. Next, it checks if a book of the given ISBN is already in the hash table. If so, the function returns the return values of get_book(books, isbn) as its own return values. Otherwise, the function attempts to insert the struct at books.elements[hash_book(isbn)] . Failing that, it performs linear probing to find the next <em>empty</em>or <em>deleted</em> entry in the elements array and inserts the struct at that location. If needed, probing wraps-around from the last entry in elements to the first. The function returns in $v0 the index where the struct was inserted. It returns in $v1 the number of entries in elements it had to read before finding an empty or deleted entry. For example, if it must skip over 3 occupied slots before finding an empty one, $v1 would be 4 in that case. If a book is successfully added to the hash table, books.size is incremented by 1.

Note that at most 24 characters of a book’s title or author can be stored in a Book struct. Therefore, any characters in title or author beyond the 24th character are dropped. The function must then write a null-terminator for the truncated string.

&nbsp;

When writing the title and author string arguments into the Book struct, if the string is shorter than 24 characters in length, the function pads out the remainder of the 25 bytes of the title or author field by appending null-terminators. For instance, if title were “MIPS Rocks”, which is only 10 characters in length, the function would write the following as the title field in the new Book struct:

MIPS Rocks\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0

The function takes the following arguments, in this order:

<ul>
<li>books : the starting address of a valid Hashtable of Book structs</li>
<li>isbn : a 13-character null-terminated string that represents a valid ISBN</li>
<li>title: a non-empty, null-terminated string that represents a book’s title</li>
<li>author: a non-empty, null-terminated string that represents a book’s author</li>
</ul>
Returns in $v0:

<ul>
<li>The index in elements where the new book was added (or found, if the book was already in the hash table); or</li>
<li>-1 if the hash table was full before the function call.</li>
</ul>
Returns in $v1:

<ul>
<li>The number of entries in the elements array that were accessed before the book was added to the hash table; or</li>
<li>-1 if the hash table was full before the function call.</li>
</ul>
Additional requirements:

<ul>
<li>The function may only change the contents of the books hash table and no other parts of</li>
<li>The function must call get_book , hash_book and memcpy .</li>
</ul>
Example #1: Add a book to an empty hash table.

isbn = “9780553214830”

title = “The Declaration of Independence”

author = “Founding Fathers”

Return value in $v0: 4

Return value in $v1: 1

Resulting books contents:

9 1 68 (capacity, size, element_size)

0: empty

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>9780553214830\0The Declaration of Indep\0Founding Fathers\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
<li>empty</li>
</ul>
&nbsp;

<ul>
<li>empty</li>
<li>empty</li>
</ul>
(Note: null-terminators are appended as needed to pad the title and author fields to 25 bytes each. The final 4-byte word in each struct is the times_sold field, which is 0 in this case.)

Example #2: Add a book to a hash table with existing values; no collisions

isbn = “9781620610090”

title = “Opal (Lux, #3)”

author = “Jennifer L. Armentrout”

books contents before function call:

9 4 68 (capacity, size, element_size)

0: empty

<ul>
<li>9780446695660\0Double Whammy\0\0\0\0\0\0\0\0\0\0\0\0Carl Hiaasen\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
<li>empty</li>
<li>9780553214830\0The Declaration of Indep\0Founding Fathers\0\0\0\0\0\0\0\0\014</li>
<li>9788433914260\0Hollywood\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Charles Bukowski\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet</li>
</ul>
Evanovich\0\0\0\0\0\0\0\0\0\00

<ul>
<li>empty</li>
<li>empty Return value in $v0: 7</li>
</ul>
Return value in $v1: 1

Resulting books contents:

9 5 68 (capacity, size, element_size)

0: empty

<ul>
<li>9780446695660\0Double Whammy\0\0\0\0\0\0\0\0\0\0\0\0Carl Hiaasen\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
<li>empty</li>
<li>9780553214830\0The Declaration of Indep\0Founding Fathers\0\0\0\0\0\0\0\0\014</li>
<li>9788433914260\0Hollywood\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Charles Bukowski\0\0\0\0\0\0\0\0\00</li>
</ul>
<table>
<tbody>
<tr>
<td width="22">6:</td>
<td width="420">9780345527780\0Wicked Business&nbsp; (Lizzy &amp;\0Janet</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="177">&nbsp;</td>
</tr>
<tr>
<td width="22">&nbsp;</td>
<td width="420">Evanovich\0\0\0\0\0\0\</td>
<td width="17">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="177">00</td>
</tr>
<tr>
<td width="22"><strong>7:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></td>
<td colspan="5" width="650"><strong>9781620610090\0Opal&nbsp;&nbsp;&nbsp; </strong><strong>(Lux, #3)\0\0\0\0\0\0\0\0\0\0\0Jennifer L.</strong>

<strong>Arinentrout\0\0\00</strong>
</td>
</tr>
<tr>
<td width="22"><strong>8:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong></td>
<td width="420">empty</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="177">&nbsp;</td>
</tr>
</tbody>
</table>
&nbsp;

Note that the Declaration of Independence was sold 14 times.

Example #3: Add a book to a hash table with existing values; collision with one probe required

isbn = “9781416971700”

title = “Out of My Mind”

author = “Sharon M. Draper”

books contents before function call:

7 3 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty Return value in $v0: 6</li>
</ul>
Return value in $v1: 2

Resulting books contents:

7 4 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li><strong>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. </strong><strong>Draper\0\0\0\0\0\0\0\0\00</strong></li>
</ul>
Example #4: Add a book to a hash table with existing values; collisions with multiple probes required

isbn = “9781455525930”

title = “Crimson Shore (Pendergast, #15)” author = “Douglas Preston, Lincoln Child” books contents before function call:

11 7 68 (capacity, size, element_size) 0: empty

<ul>
<li>9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\0251</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
&nbsp;

<table>
<tbody>
<tr>
<td width="25">3:

4:
</td>
<td colspan="6" width="647">9780156948780\0The Waste Land and Other\0T.S.

Eliot\0\0\0\0\0\0\0\0\0\0\0\0\0\0\00

9780670032080\0Financial Peace Revisite\0Dave
</td>
</tr>
<tr>
<td width="25">&nbsp;</td>
<td width="176">&nbsp;</td>
<td width="269">Ramsey\0\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="37">0\0\</td>
<td width="17">0\</td>
<td width="130">0422</td>
</tr>
<tr>
<td width="25">5:</td>
<td width="176">9780064408330\0Joey</td>
<td width="269">Pigza Swallowed the\0Jack</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="17">&nbsp;</td>
<td width="130">&nbsp;</td>
</tr>
<tr>
<td width="25">&nbsp;</td>
<td width="176">&nbsp;</td>
<td width="269">Gantos\0\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="37">0\0\</td>
<td width="17">0\</td>
<td width="130">01251</td>
</tr>
<tr>
<td width="25">6:</td>
<td width="176">9780312577220\0Fly</td>
<td width="269">Away&nbsp;&nbsp; (Firefly Lane, \0Kristin</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="17">&nbsp;</td>
<td width="130">&nbsp;</td>
</tr>
<tr>
<td width="25">&nbsp;</td>
<td width="176">&nbsp;</td>
<td width="269">Hannah\0\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="37">0734</td>
<td width="17">&nbsp;</td>
<td width="130">&nbsp;</td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: 7

Return value in $v1: 3

Resulting books contents:

11 8 68 (capacity, size, element_size)

0: empty

<ul>
<li>9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\0251</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
<li>9780156948780\0The Waste Land and Other\0T.S.</li>
</ul>
<table>
<tbody>
<tr>
<td width="30">4:</td>
<td colspan="5" width="511">Eliot\0\0\0\0\0\0\0\0\0\0\0\0\0\0\

9780670032080\0Financial Peace Revisite\0Dave
</td>
<td width="132">00</td>
</tr>
<tr>
<td width="30">&nbsp;</td>
<td width="424">Ramsey\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="37">0\0\</td>
<td width="15">0\</td>
<td width="132">0422</td>
</tr>
<tr>
<td width="30">5:</td>
<td width="424">9780064408330\0Joey Pigza Swallowed the\0Jack</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
<tr>
<td width="30">&nbsp;</td>
<td width="424">Gantos\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="37">0\0\</td>
<td width="15">0\</td>
<td width="132">01251</td>
</tr>
<tr>
<td width="30">6:</td>
<td colspan="2" width="441">9780312577220\0Fly Away&nbsp;&nbsp; (Firefly Lane, \0Kristin</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
<tr>
<td width="30">&nbsp;</td>
<td width="424">Hannah\0\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="37">0734</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
<tr>
<td width="30"><strong>7:&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong></td>
<td width="424"><strong>9781455525930\0Crimson Shore (Pendergas\0Douglas</strong></td>
<td colspan="3" width="73"><strong>Preston,</strong></td>
<td width="15">&nbsp;</td>
<td width="132"><strong>Lincoln\00</strong></td>
</tr>
<tr>
<td width="30">8:</td>
<td width="424">empty</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
<tr>
<td width="30">9:</td>
<td width="424">empty</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
<tr>
<td width="30">10:</td>
<td width="424">97800608550\0Equal Rites&nbsp;&nbsp;&nbsp; (Discworld,&nbsp;&nbsp; \0Terry</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="37">&nbsp;</td>
<td width="15">&nbsp;</td>
<td width="132">&nbsp;</td>
</tr>
</tbody>
</table>
Pratchett\0\0\0\0\0\0\0\0\0\00

Note how the title and author were truncated when stored in the hash table.

Example #5: Add a book to a hash table with existing values; collisions with multiple probes required

isbn = “9780451230230”

title = “The Pacific”

author = “Hugh Ambrose”

books contents before function call:

7 4 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\07777

&nbsp;

<table>
<tbody>
<tr>
<td width="26">1:</td>
<td width="411">0</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="129">&nbsp;</td>
</tr>
<tr>
<td width="26">2:</td>
<td width="411">-1</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="129">&nbsp;</td>
</tr>
<tr>
<td width="26">3:</td>
<td width="411">9780670032080\0Financial Peace Revisite\0Dave</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="129">&nbsp;</td>
</tr>
<tr>
<td width="26">&nbsp;</td>
<td width="411">Ramsey\0\0\0\0\0\0\0\</td>
<td width="17">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="129">0222</td>
</tr>
<tr>
<td width="26">4:</td>
<td width="411">9780064408330\0Joey Pigza Swallowed the\0Jack</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="129">&nbsp;</td>
</tr>
<tr>
<td width="26">&nbsp;</td>
<td width="411">Gantos\0\0\0\0\0\0\0\</td>
<td width="17">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="129">0333</td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>-1</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
Return value in $v0: 5

Return value in $v1: 3

Resulting books contents:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\07777

<ul>
<li>0</li>
<li>-1</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\0222</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\0333</li>
<li><strong>9780451230230\0The Pacific\0\0\0\0\0\0\0\0\0\0\0\0\0\0Hug~ </strong><strong>Axnbrose\0\0\0\0\0\0\0\0\0\0\0\0\00</strong></li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\00</li>
</ul>
<strong>Part 7: Delete a </strong><strong>Book</strong><strong> Struct from a Hash Table of Books</strong> int delete_book(Hashtable* books, string isbn)

The delete_book function attempts to delete the Book struct from the hash table with the given ISBN. If the book exists, then its entire struct is filled with the value -1 (8-bit, two’s complement format) and the function returns the index in books.elements where the book was found. If a book is successfully deleted from the hash table, books.size is decremented by 1. If the book is not found, the function returns -1 and makes no changes to the contents of books.

The function takes the following arguments, in this order:

<ul>
<li>books: the starting address of a valid Hashtable struct</li>
<li>isbn: a 13-character null-terminated string that represents a valid ISBN</li>
</ul>
Returns in $v0:

<ul>
<li>The index where the deleted book had been located; or</li>
<li>-1 if no book with the given ISBN was found in the hash table</li>
</ul>
Additional requirements:

&nbsp;

<ul>
<li>The function may only change the contents of the books hash table and no other parts of memory.</li>
<li>The function must call get_book.</li>
</ul>
Example #1: Attempt to delete a book from an empty hash table

isbn = “9780553214830”

books contents before function call:

7 0 68 (capacity, size, element_size)

0: empty

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty Return value in $v0: -1</li>
</ul>
Resulting books contents:

7 0 68 (capacity, size, element_size)

0: empty

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
</ul>
Example #2: Delete a book that is present in the hash table at the expected index

isbn = “9780060855900”

books contents before function call:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
</ul>
Return value in $v0: 2

Resulting books contents:

&nbsp;

7 4 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li><strong>deleted</strong></li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
</ul>
Example #3: Attempt to delete a book that is not present in the hash table; expected location is empt~

isbn = “9781439164630”

books contents before function call:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
</ul>
Return value in $v0: -1

Resulting books contents:

7 5 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
</ul>
Example #4: Delete a book that is not present in the hash table; expected location is deleted

&nbsp;

<table>
<tbody>
<tr>
<td colspan="2" width="441">isbn = “9780064410150” books contents before function call:</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">7 3</td>
<td width="415">68&nbsp; (capacity,&nbsp; size,&nbsp;&nbsp; element_size)</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">0:</td>
<td width="415">empty</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">1:</td>
<td width="415">deleted</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">2:</td>
<td width="415">9780060855900\0Equal Rites&nbsp; (Discworld,&nbsp; \0Terry</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">&nbsp;</td>
<td width="415">Pratchett\0\0\0\0\0\0\</td>
<td width="17">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="106">00</td>
</tr>
<tr>
<td width="26">3:</td>
<td width="415">9780345527780\0Wicked Business&nbsp; (Lizzy &amp;\0Janet</td>
<td width="17">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td width="26">&nbsp;</td>
<td width="415">Evanovich\0\0\0\0\0\0\</td>
<td width="17">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="106">00</td>
</tr>
<tr>
<td colspan="6" width="600">4: deleted

5: 9780312577220\0Fly Away&nbsp; (Firefly Lane,&nbsp;&nbsp; \0Kristin

Hannah\0\0\0\0\0\0\0\0\0\0\00

6: empty
</td>
</tr>
<tr>
<td colspan="3" width="458">Return value in $v0: -1</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">Resulting books contents:</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">7 3&nbsp;&nbsp; 68&nbsp;&nbsp; (capacity,&nbsp; size,&nbsp;&nbsp; element_size)</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">0:&nbsp;&nbsp; empty</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">1:&nbsp; deleted</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">2:&nbsp; 9780060855900\0Equal Rites&nbsp;&nbsp; (Discworld,&nbsp;&nbsp; \0Terry</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">Pratchett\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="106">00</td>
</tr>
<tr>
<td colspan="3" width="458">3:&nbsp;&nbsp; 9780345527780\0Wicked Business&nbsp;&nbsp;&nbsp;&nbsp; (Lizzy &amp;\0Janet</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="106">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="458">Evanovich\0\0\0\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="106">00</td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>deleted</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>empty</li>
</ul>
Example #5: Attempt to delete a book not present in the hash table; hash table is full

isbn = “9780802122550”

books contents before function call:

7 7 68 (capacity, size, element_size)

0: 9780553214830\0The Declaration of Indep\0Founding

Fathers\0\0\0\0\0\0\0\0\00

<ul>
<li>9780446695660\0Double Whammy\0\0\0\0\0\0\0\0\0\0\0\0Carl Hiaasen\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9788433914260\0Hollywood\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Charles Bukowski\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
</ul>
&nbsp;

6: 9781620610090\0Opal (Lux, #3)\0\0\0\0\0\0\0\0\0\0\0Jennifer L. Armentrout\0\0\00

Return value in $v0: -1

Resulting books contents:

7 7 68 (capacity, size, element_size)

0: 9780553214830\0The Declaration of Indep\0Founding Fathers\0\0\0\0\0\0\0\0\00

<ul>
<li>9780446695660\0Double Whammy\0\0\0\0\0\0\0\0\0\0\0\0Carl Hiaasen\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780345527780\0Wicked Business (Lizzy &amp;\0Janet Evanovich\0\0\0\0\0\0\0\0\0\00</li>
<li>9788433914260\0Hollywood\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0\0Charles Bukowski\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9781620610090\0Opal (Lux, #3)\0\0\0\0\0\0\0\0\0\0\0Jennifer L. Armentrout\0\0\00</li>
</ul>
<strong>Part 8: Compute the Hash Code for an (ISBN, Customer ID #) Pair in a Given Hash Table</strong> int hash_booksale(Hashtable* sales, string isbn, int customer_id)

The hash_booksale function takes a pointer to a valid Hashtable struct named sales, and an ISBN-13 value called isbn and customer ID # called customer_id for which we want to compute the hash function. The hash function itself is very simple: sum the ASCII codes of the 13 characters in isbn and the digits of customer_id , and then take the modulus of dividing the grand total by the capacity of the sales hash table (e.g., sum of all the ASCII codes from isbn and the digits from customer_id<em> mod</em> the capacity).

The function takes the following arguments, in this order:

<ul>
<li>books: the starting address of a valid Hashtable of Book structs</li>
<li>isbn: a 13-character, null-terminated string that represents a valid ISBN</li>
<li>customer_id : an integer providing the customer ID#</li>
</ul>
Returns in $v0:

<ul>
<li>The value of the hash function when evaluated for the provided ISBN and customer ID#.</li>
</ul>
Additional requirements:

<ul>
<li>The function may not write any changes to main memory.</li>
</ul>
Example #1:

&nbsp;

hashtable = pointer to a valid hash table with capacity = 11 isbn = “9780671028370”

customer_id = 829273

Return value in $v0: 9

Example #2:

hashtable = pointer to a valid hash table with capacity = 13

isbn = “9780071401940”

customer id = 93730282

_

Return value in $v0: 6

Example #3:

hashtable = pointer to a valid hash table with capacity = 19 isbn = “9712312301940”

customer id = 512312

_

Return value in $v0: 15

<strong>Part 9: Determine if a Year is a Leap Year</strong> int is_leap_year(int year)

The is_leap_year function does what it sounds like – it determines if a given year is a leap year. A year is a leap year if it is after 1582 and it is divisible by 4, except centenary years not divisible by 400 (1700, 1800, 1900, 2100, etc.) Feel free to adapt the sample code given in the lecture slides and course materials that implements the logic needed for this function

The function takes one argument:

<ul>
<li>year: an integer representing…a year</li>
</ul>
Returns in $v0:

<ul>
<li>0 if year is &lt; 1582; or</li>
<li>1 if year is a leap year; or</li>
<li>the number of years<em> negated</em> until the next leap year if year is not a leap year</li>
</ul>
Additional requirements:

<ul>
<li>The function may not make any changes to main memory.</li>
</ul>
<table>
<tbody>
<tr>
<td width="166"><strong>Function Argument</strong></td>
<td width="113"><strong>Return Value</strong></td>
</tr>
<tr>
<td width="166">1244</td>
<td width="113">0</td>
</tr>
</tbody>
</table>
&nbsp;

<table>
<tbody>
<tr>
<td width="166">1900</td>
<td width="113">-4</td>
</tr>
<tr>
<td width="166">2000</td>
<td width="113">1</td>
</tr>
<tr>
<td width="166">5602</td>
<td width="113">-2</td>
</tr>
<tr>
<td width="166">2997</td>
<td width="113">-7</td>
</tr>
<tr>
<td width="166">3997</td>
<td width="113">-3</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Part 10: Convert a String Representation of a Time Interval to an Integer Number of Days</strong> int datestring_to_num_days(string start_date, string end_date)

The datestring_to_num_days function takes two dates given as strings, in the format YYYY-MM-DD, and returns the number of days that elapse from start_date to end_date . For example, if start_date = “2020-10-01” and end_date = “2020-10-10” , the return value

will be 9. Note that start_date itself is not included in the number of days elapsed. The function must account for leap years by calling the is_leap_year function. You may assume that both arguments are valid.

The function takes the following arguments, in this order:

<ul>
<li>start_date : a date given in the format YYYY-MM-DD that is 1600-01-01 or later</li>
<li>end_date : a date given in the format YYYY-MM-DD that is 1600-01-01 or later</li>
</ul>
Returns in $v0:

<ul>
<li>The number of days elapsed between start_date and end_date , including end_date , but excluding start_date ; or</li>
<li>-1 if end_date is before start_date</li>
</ul>
Additional requirements:

<ul>
<li>The function may not write any changes to main memory.</li>
<li>The function must call is_lea~_year . Not required because at least one student is using the Julian calendar to calculate this!</li>
</ul>
<table>
<tbody>
<tr>
<td colspan="2" width="287"><strong>Function Arguments</strong></td>
<td width="144"><strong>Return Value</strong></td>
</tr>
<tr>
<td width="127">“2020-10-12”,</td>
<td width="160">“2020-10-25”</td>
<td width="144">13</td>
</tr>
<tr>
<td width="127">“2020-10-25”,</td>
<td width="160">“2020-10-12”</td>
<td width="144">-1</td>
</tr>
<tr>
<td width="127">“2019-10-25”,</td>
<td width="160">“2020-10-25”</td>
<td width="144">366</td>
</tr>
<tr>
<td width="127">“1692-11-28”,</td>
<td width="160">“2602-09-13”</td>
<td width="144">332293</td>
</tr>
<tr>
<td width="127">“2019-01-08”,</td>
<td width="160">“8410-09-08”</td>
<td width="144">2334508</td>
</tr>
</tbody>
</table>
&nbsp;

<table>
<tbody>
<tr>
<td width="287">“3156-05-08”, “3156-05-08”</td>
<td width="143">0</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Part 11: Record the Sale a Boo~</strong>

int, int sell_book(Hashtable* sales, <sup>Hashtable*</sup> books, string isbn, int customer_id, string sale_date, int sale_price)

The sell_book function records the sale of a book by adding an entry into the hash table sales of BookSale objects and updating the times_sold count of the sold book. We will make the following assumptions for this function:

<ul>
<li>Deletions from the sales hash table never take place. Therefore, every entry in elements is either all zeros (indicating an <em>empty</em> entry) or a valid BookSale struct.</li>
<li>No customer ever buys the same book twice.</li>
<li>The store has an infinite number of copies of every book.</li>
</ul>
Note that sell_book is similar in spirit to the add_book function from earlier in the assignment. The sell_book function attempts to insert a new BookSale struct into a given sales hash table by initializing the contents of the struct with the provided ISBN, customer ID# and sale price. The value stored in the struct for sale_date is provided by the return value of datestring_to_num_days(“1600-01-01”, sale_date) . sell_book begins by checking if the sales hash table is full. If so, the function returns (-1, -1) and makes no changes to the hash table’s contents. It also checks if a book with the given ISBN exists in the books hash table. If not, the function returns (-2, -2). Otherwise, the function attempts to insert the struct at sales.elements[hash_booksale(sales, isbn, customer_id)] . Failing that, it performs linear probing to find the next <em>empty</em> entry in the sales.elements array and inserts the struct at that location. If needed, probing wraps-around from the last entry in elements to the first. The value of the times_sold field of the corresponding book in the books hash table must be incremented by 1. The function returns in $v0 the index where the struct was inserted. It returns in $v1 the number of entries in elements it had to read before finding an empty entry. For example, if it must skip over 3 occupied slots before finding an empty one, $v1 would be 4 in that case. If a sale is successfully added to the hash table, sales .size is incremented by 1.

The function takes the following arguments, in this order:

<ul>
<li>sales: the starting address of a valid Hashtable of BookSale structs</li>
<li>books: the starting address of a valid Hashtable of Book structs</li>
<li>isbn: a 13-character, null-terminated string that represents a valid ISBN</li>
<li>customer_id : an integer that represents a customer’s ID#</li>
<li>sale_date : a 10-character, null-terminated string that represents a valid date on or after January 1, 1600. Available at 0($sp). Assume the date string is value and represents a date on or after January 1, 1600.</li>
<li>sale_price : an integer that represents the price paid for the book. Available at 4($sp).</li>
</ul>
Returns in $v0:

&nbsp;

<ul>
<li>The index in elements where the new BookSale struct was added to the sales hash table; or</li>
<li>-1 if the hash table was full before the function call or</li>
<li>-2 if no book of the given ISBN exists in the books hash table.</li>
</ul>
Returns in $v1:

<ul>
<li>The number of entries in the elements array that were accessed before the BookSale struct was added to the sales hash table; or</li>
<li>-1 if the hash table was full before the function call; or</li>
<li>-2 if no book of the given ISBN exists in the books hash table.</li>
</ul>
Additional requirements:

<ul>
<li>The function may only change the contents of the books and sales hash tables and no other parts of memory.</li>
<li>The function must call get_book , datestring_to_num_days , hash_booksale , and memcpy .</li>
</ul>
Example #1: sales hash table is empty

isbn = “9780670032080” customer_id = 12345

sale_date = “2020-09-14” sale_price = 50

Contents of sales hash table:

<table>
<tbody>
<tr>
<td width="32">9 0</td>
<td width="130">28&nbsp; (capacity,</td>
<td width="54">size,</td>
<td width="457">element_size)</td>
</tr>
<tr>
<td width="32">0:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">1:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">2:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">3:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">4:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">5:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">6:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">7:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
<tr>
<td width="32">8:</td>
<td width="130">empty</td>
<td width="54">&nbsp;</td>
<td width="457">&nbsp;</td>
</tr>
</tbody>
</table>
Contents of books hash table:

7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780670032080\0Financial Peace Revisite\0Dave</li>
</ul>
<table>
<tbody>
<tr>
<td width="27">&nbsp;</td>
<td width="176">&nbsp;</td>
<td width="272">Ramsey\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="35">00</td>
</tr>
<tr>
<td width="27">4:</td>
<td width="176">9780064408330\0Joey</td>
<td width="272">Pigza Swallowed the\0Jack</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="35">&nbsp;</td>
</tr>
<tr>
<td width="27">&nbsp;</td>
<td width="176">&nbsp;</td>
<td width="272">Gantos\0\0\0\0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="18">0\</td>
<td width="35">00</td>
</tr>
<tr>
<td width="27">5:</td>
<td width="176">9780312577220\0Fly</td>
<td width="272">Away&nbsp;&nbsp; (Firefly Lane, \0Kristin</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="18">&nbsp;</td>
<td width="35">&nbsp;</td>
</tr>
</tbody>
</table>
&nbsp;

Hannah\0\0\0\0\0\0\0\0\0\0\00

6: 9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M.

Draper\0\0\0\0\0\0\0\0\00

Return value in $v0: 5

Return value in $v1: 1

Resulting sales contents:

9 1 28 (capacity, size, element_size)

0: empty

<ul>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li>empty</li>
<li><strong>9780670032080\0 0 0 12345 153659 50</strong></li>
<li>empty</li>
<li>empty</li>
<li>empty Resulting books contents:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\00

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\00</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\0 <strong>1</strong></li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\00</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M.</li>
</ul>
Draper\0\0\0\0\0\0\0\0\00

Example #2: sales hash table contains some entries; a few steps of linear probing required to insert the BookSale struct

isbn = “9780670032080”

customer_id = 6123

sale_date = “2019-11-04”

sale_price = 1032

Contents of sales hash table:

9 4 28 (capacity, size, element_size) 0: empty

<ul>
<li>9781416971700\0 0 0 2323432 155136 22</li>
<li>9780060855900\0 0 0 920192 158715 61</li>
<li>9780345501330\0 0 0 81321 151369 192</li>
</ul>
&nbsp;

<ul>
<li>empty</li>
<li>9780312577220\0 0 0 2424 152013 125</li>
<li>empty</li>
<li>empty</li>
<li>empty Contents of books hash table:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\01

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\061</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\044</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\0812</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\01</li>
</ul>
Return value in $v0: 4

Return value in $v1: 3

Resulting sales contents:

9 5 28 (capacity, size, element_size)

0: empty

<ul>
<li>9781416971700\0 0 0 2323432 155033 22</li>
<li>9780060855900\0 0 0 920192 158610 61</li>
<li>9780345501330\0 0 0 81321 151269 192</li>
<li>9780670032080\0 0 0 6123 153344 1032</li>
<li>9780312577220\0 0 0 2424 151912 125</li>
<li>empty</li>
<li>empty</li>
<li>empty Resulting books contents:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\01

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\0 <strong>62</strong></li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\044</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\0812</li>
</ul>
&nbsp;

6: 9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M.

Draper\0\0\0\0\0\0\0\0\01

Example #3: provided ISBN does not exist in the books hash table

isbn = “9780679744400”

customer_id = 5123

sale_date = “2029-11-04”

sale_price = 987

Contents of sales hash table:

9 4 28 (capacity, size, element_size)

0: empty

<ul>
<li>9781416971700\0 0 0 2323432 155136 22</li>
<li>9780060855900\0 0 0 920192 158715 61</li>
<li>9780345501330\0 0 0 81321 151369 192</li>
<li>empty</li>
<li>9780312577220\0 0 0 2424 152013 125</li>
<li>empty</li>
<li>empty</li>
<li>empty Contents of books hash table:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\01

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\061</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\044</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\0812</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\01</li>
</ul>
Return value in $v0: -2 Return value in $v1: -2 Resulting sales contents:

Resulting sales contents:

9 4 28 (capacity, size, element_size)

0: empty

<ul>
<li>9781416971700\0 0 0 2323432 155033 22</li>
<li>9780060855900\0 0 0 920192 158610 61</li>
<li>9780345501330\0 0 0 81321 151269 192</li>
<li>empty</li>
<li>9780312577220\0 0 0 2424 151912 125</li>
<li>empty</li>
<li>empty</li>
<li>empty Resulting books contents:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\01

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\061</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\044</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\0812</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\01</li>
</ul>
Example #4: the sales hash table is full

isbn = “9781416971700”

customer_id = 1523

sale_date = “2022-10-14”

sale_price = 323

Contents of sales hash table:

9 9 28 (capacity, size, element_size)

0: 9780345501330\0 0 0 723341 155332 55

<ul>
<li>9781416971700\0 0 0 2323432 155136 22</li>
<li>9780060855900\0 0 0 920192 158715 61</li>
<li>9780345501330\0 0 0 81321 151369 192</li>
<li>9780312577220\0 0 0 777233 155332 55</li>
<li>9780312577220\0 0 0 2424 152013 125</li>
<li>9780345501330\0 0 0 26234 155332 55</li>
<li>9780312577220\0 0 0 12312 155332 55</li>
<li>9780064408330\0 0 0 73123 155332 55 Contents of books hash table:</li>
</ul>
7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\03

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\0\0\0\0\0\0\0\061</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack</li>
</ul>
Gantos\0\0\0\0\0\0\0\0\0\0\0\0\0\045

<ul>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\0\0\0\0\0814</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\01</li>
</ul>
Return value in $v0: -1 Return value in $v1: -1 Resulting sales contents:

<table>
<tbody>
<tr>
<td width="20">9</td>
<td width="144">9 28&nbsp;&nbsp; (capacity,</td>
<td colspan="2" width="44">size,</td>
<td width="465">element_size)</td>
</tr>
<tr>
<td width="20">0:</td>
<td width="144">9780345501330\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">723341&nbsp;&nbsp; 155229 55</td>
</tr>
<tr>
<td width="20">1:</td>
<td width="144">9781416971700\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">2323432&nbsp;&nbsp; 155033 22</td>
</tr>
<tr>
<td width="20">2:</td>
<td width="144">9780060855900\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">920192&nbsp; 158610&nbsp;&nbsp; 61</td>
</tr>
<tr>
<td width="20">3:</td>
<td width="144">9780345501330\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">81321&nbsp;&nbsp; 151269&nbsp; 192</td>
</tr>
<tr>
<td width="20">4:</td>
<td width="144">9780312577220\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">777233&nbsp;&nbsp; 155229 55</td>
</tr>
<tr>
<td width="20">5:</td>
<td width="144">9780312577220\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">2424&nbsp;&nbsp; 151912&nbsp;&nbsp; 125</td>
</tr>
<tr>
<td width="20">6:</td>
<td width="144">9780345501330\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">26234&nbsp;&nbsp; 155229 55</td>
</tr>
<tr>
<td width="20">7:</td>
<td width="144">9780312577220\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">12312&nbsp;&nbsp; 155229 55</td>
</tr>
<tr>
<td width="20">8:</td>
<td width="144">9780064408330\0</td>
<td width="23">0</td>
<td width="21">0</td>
<td width="465">73123&nbsp;&nbsp; 155229 55</td>
</tr>
</tbody>
</table>
Resulting books contents:

7 6 68 (capacity, size, element_size)

0: 9780345501330\0Fairy Tail, Vol. 1 (Fair\0Hiro Mashima, William Fl\03

<ul>
<li>empty</li>
<li>9780060855900\0Equal Rites (Discworld, \0Terry Pratchett\0\0\0\0\0\0\0\0\0\0103</li>
<li>9780670032080\0Financial Peace Revisite\0Dave Ramsey\0\0\0\0\0\0\</li>
<li>9780064408330\0Joey Pigza Swallowed the\0Jack Gantos\0\0\0\0\0\0\</li>
<li>9780312577220\0Fly Away (Firefly Lane, \0Kristin Hannah\0\0\0\0\0\0\</li>
<li>9781416971700\0Out of My Mind\0\0\0\0\0\0\0\0\0\0\0Sharon M. Draper\0\0\0\0\0\0\0\0\01</li>
</ul>
In the remainder of the assignment we will explore an interesting computational problem described on <a href="http://geeksforgeeks.com">geeksforgeeks.com</a><u>.</u> In our case, we will optimize the sale of books, rather than wines, which is used in the geeksforgeeks problem

<strong>Part 12: Compute the Total Sales for a Given Ordering of Books</strong>

&nbsp;

int compute_scenario_revenue(BookSale[] sales_list, int num_sales,

int scenario)

The compute_scenario_revenue function takes an array of at most 32 BookSale structs and, according to the bitstring scenario, computes the total revenue generated by selling the given books in that order, with the small twist that as time goes on, the revenue realized from the sale of a book actually increases. The integer scenario encodes the order in which the books are sold. <strong>Note: </strong>for the purposes of this function we will ignore the sale_date field in each BookSale struct. For instance, suppose 5 BookSale structs are stored in the sales_list array, and int scenario = 12 . The scenario bitstring 01100, read left-to-right, would mean: sell the leftmost book (and remove it), then sell the rightmost book (and remove it), then sell the rightmost book (and remove it), then sell the leftmost book (and remove), and then sell the leftmost book.

As an example, suppose our list of BookSale structs had the following corresponding ISBNs: sales_list[0]: 0000000000000

sales_list[1]: 1111111111111 sales_list[2]: 2222222222222 sales_list[3]: 3333333333333 sales_list[4]: 4444444444444

The bitstring 01100 indicates that the books would be sold in the following order:

<table>
<tbody>
<tr>
<td width="45">1.</td>
<td width="136">0000000000000</td>
<td width="147">(leftmost book)</td>
<td width="344">&nbsp;</td>
</tr>
<tr>
<td width="45">2.</td>
<td width="136">4444444444444</td>
<td width="147">(rightmost book</td>
<td width="344">remaining)</td>
</tr>
<tr>
<td width="45">3.</td>
<td width="136">3333333333333</td>
<td width="147">(rightmost book</td>
<td width="344">remaining)</td>
</tr>
<tr>
<td width="45">4.</td>
<td width="136">1111111111111</td>
<td width="147">(leftmost book</td>
<td width="344">remaining)</td>
</tr>
<tr>
<td width="45">5.</td>
<td width="136">2222222222222</td>
<td width="147">(final book)</td>
<td width="344">&nbsp;</td>
</tr>
</tbody>
</table>
&nbsp;

Note that we are reading the bitstring from left-to-right, not right-to-left!

Now, the significance of this order becomes apparent when we see what happens when we sell a book. Imagine that each book is sold on a different day (again, remember that we are ignoring the sale_date field of the BookSale structs for this problem). On Day 1, the chosen book is sold at its normal price, as given by its sale_price. On Day 2, the next book is sold at 2x its sale_price. On Day 3, the next book is sold at 3x its sale_price, and so on. The n-th book is sold at n times its sale_price .

Let’s go back to our example. Suppose the books have the indicated prices: stored in the sale_price field of each struct.

<table>
<tbody>
<tr>
<td width="117">sales_list[0]</td>
<td width="14">:</td>
<td width="132">0000000000000</td>
<td width="410">$2</td>
</tr>
<tr>
<td width="117">sales_list[1]</td>
<td width="14">:</td>
<td width="132">1111111111111</td>
<td width="410">$4</td>
</tr>
<tr>
<td width="117">sales_list[2]</td>
<td width="14">:</td>
<td width="132">2222222222222</td>
<td width="410">$6</td>
</tr>
<tr>
<td colspan="2" width="131">sales&nbsp; list[3]:

_
</td>
<td width="132">3333333333333</td>
<td width="410">$2</td>
</tr>
<tr>
<td width="117">sales_list[4]</td>
<td width="14">:</td>
<td width="132">4444444444444</td>
<td width="410">$5</td>
</tr>
</tbody>
</table>
&nbsp;

We have our bitstring 01100 that indicates the selling order. As time goes on, we can see how the total revenue of selling the books in that order is realized:

<table>
<tbody>
<tr>
<td width="46">1.</td>
<td width="161">Sell 0000000000000</td>
<td width="40">&nbsp;</td>
<td colspan="3" width="166">$2&nbsp;&nbsp;&nbsp;&nbsp; Total:&nbsp; 1*$2</td>
<td width="19">=</td>
<td width="240">$2</td>
</tr>
<tr>
<td width="46">2.</td>
<td width="161">Sell 4444444444444</td>
<td width="40">$5</td>
<td width="71">Total:</td>
<td width="32">$2</td>
<td width="63">+ 2*$5</td>
<td width="19">=</td>
<td width="240">$12</td>
</tr>
<tr>
<td width="46">3.</td>
<td width="161">Sell 3333333333333</td>
<td width="40">$2</td>
<td width="71">Total:</td>
<td width="32">$12</td>
<td width="63">+ 3*$2</td>
<td width="19">=</td>
<td width="240">$18</td>
</tr>
<tr>
<td width="46">4.</td>
<td width="161">Sell 1111111111111</td>
<td width="40">$4</td>
<td width="71">Total:</td>
<td width="32">$18</td>
<td width="63">+ 4*$4</td>
<td width="19">=</td>
<td width="240">$34</td>
</tr>
<tr>
<td width="46">5.</td>
<td width="161">Sell 2222222222222</td>
<td width="40">$6</td>
<td width="71">Total:</td>
<td width="32">$34</td>
<td width="63">+ 5*$6</td>
<td width="19">=</td>
<td width="240">$64</td>
</tr>
</tbody>
</table>
&nbsp;

For this particular selling scenario, the total revenue is $64.

The function takes the following arguments, in this order:

<ul>
<li>sales_list : a completely filled array of BookSale structs</li>
<li>num_sales: the number of BookSale structs in sales_list</li>
<li>scenario: a 32-bit integer that encodes the order in which to sell the books in sales_list</li>
</ul>
Returns in $v0:

<ul>
<li>The total revenue produced by selling the books in the order specified by scenario.</li>
</ul>
Additional requirements:

<ul>
<li>The function may not write any changes to main memory.</li>
</ul>
Example #1:

<table>
<tbody>
<tr>
<td colspan="6" width="673">num_sales = 5

scenario = 000000000000000000000000000 <strong>01100 </strong>Contents of sales_list:
</td>
</tr>
<tr>
<td width="144">0000000000000\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12345</td>
<td width="63">153789</td>
<td width="376">2</td>
</tr>
<tr>
<td width="144">1111111111111\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">52321</td>
<td width="63">153789</td>
<td width="376">4</td>
</tr>
<tr>
<td width="144">2222222222222\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">41231</td>
<td width="63">153789</td>
<td width="376">6</td>
</tr>
<tr>
<td width="144">3333333333333\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12523</td>
<td width="63">153789</td>
<td width="376">2</td>
</tr>
<tr>
<td width="144">4444444444444\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">51231</td>
<td width="63">153789</td>
<td width="376">5</td>
</tr>
</tbody>
</table>
Return value in $v0: 64 Example #2:

<table>
<tbody>
<tr>
<td colspan="6" width="673">num_sales = 9

scenario = 00000000000000000000000 <strong>011001101 </strong>Contents of sales_list:
</td>
</tr>
<tr>
<td width="144">5688198170802\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">69170</td>
<td width="45">1836</td>
<td width="394">54</td>
</tr>
<tr>
<td width="144">8174611363470\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">42817</td>
<td width="45">1416</td>
<td width="394">472</td>
</tr>
<tr>
<td width="144">6771105776755\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">73451</td>
<td width="45">1537</td>
<td width="394">296</td>
</tr>
<tr>
<td width="144">9694257705423\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">89692</td>
<td width="45">1796</td>
<td width="394">348</td>
</tr>
<tr>
<td width="144">8148291072965\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">93505</td>
<td width="45">1860</td>
<td width="394">115</td>
</tr>
<tr>
<td width="144">1537177706509\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">25366</td>
<td width="45">1488</td>
<td width="394">433</td>
</tr>
</tbody>
</table>
&nbsp;

<table>
<tbody>
<tr>
<td width="155">3918738489597\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">52178</td>
<td width="45">1247</td>
<td width="148">303</td>
</tr>
<tr>
<td width="155">1856189180494\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">69428</td>
<td width="45">1731</td>
<td width="148">118</td>
</tr>
<tr>
<td width="155">4206531586624\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">99857</td>
<td width="45">1083</td>
<td width="148">190</td>
</tr>
</tbody>
</table>
Return value in $v0: 12824 Example #3:

<table>
<tbody>
<tr>
<td colspan="6" width="437">num_sales = 11

scenario = 000000000000000000000 <strong>01101001101 </strong>Contents of sales_list :
</td>
</tr>
<tr>
<td width="155">0043444591466\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">56274</td>
<td width="45">1935</td>
<td width="148">12</td>
</tr>
<tr>
<td width="155">0912549927792\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">20150</td>
<td width="45">1615</td>
<td width="148">341</td>
</tr>
<tr>
<td width="155">8208666153502\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">13570</td>
<td width="45">1727</td>
<td width="148">275</td>
</tr>
<tr>
<td width="155">7891835066590\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">89612</td>
<td width="45">1679</td>
<td width="148">405</td>
</tr>
<tr>
<td width="155">7850924139905\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">56805</td>
<td width="45">1379</td>
<td width="148">227</td>
</tr>
<tr>
<td width="155">7172692040044\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">14473</td>
<td width="45">1609</td>
<td width="148">306</td>
</tr>
<tr>
<td width="155">8881948157382\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">35983</td>
<td width="45">1662</td>
<td width="148">38</td>
</tr>
<tr>
<td width="155">6319285981025\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">61086</td>
<td width="45">1664</td>
<td width="148">411</td>
</tr>
<tr>
<td width="155">5218182478429\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">34089</td>
<td width="45">1400</td>
<td width="148">484</td>
</tr>
<tr>
<td width="155">9545006833495\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12400</td>
<td width="45">1382</td>
<td width="148">458</td>
</tr>
<tr>
<td width="155">6178171431772\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">40266</td>
<td width="45">1773</td>
<td width="148">330</td>
</tr>
</tbody>
</table>
Return value in $v0: 19581 Example #4:

<table>
<tbody>
<tr>
<td colspan="6" width="437">num_sales = 13

scenario = 00000000000000000001101101001101 Contents of sales_list :
</td>
</tr>
<tr>
<td width="155">3318220944005\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">68169</td>
<td width="45">1310</td>
<td width="148">429</td>
</tr>
<tr>
<td width="155">1790274371133\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12055</td>
<td width="45">1911</td>
<td width="148">67</td>
</tr>
<tr>
<td width="155">2323508691228\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">25027</td>
<td width="45">1950</td>
<td width="148">382</td>
</tr>
<tr>
<td width="155">6580406620516\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">14457</td>
<td width="45">1160</td>
<td width="148">390</td>
</tr>
<tr>
<td width="155">1220293838689\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">26212</td>
<td width="45">1181</td>
<td width="148">79</td>
</tr>
<tr>
<td width="155">8838065641525\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">38406</td>
<td width="45">1406</td>
<td width="148">239</td>
</tr>
<tr>
<td width="155">4140073652158\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">91560</td>
<td width="45">1707</td>
<td width="148">231</td>
</tr>
<tr>
<td width="155">0358003692171\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">97221</td>
<td width="45">1131</td>
<td width="148">492</td>
</tr>
<tr>
<td width="155">8102823570747\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">64311</td>
<td width="45">1671</td>
<td width="148">147</td>
</tr>
<tr>
<td width="155">2694841805861\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">81769</td>
<td width="45">1342</td>
<td width="148">380</td>
</tr>
<tr>
<td width="155">8985832671846\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">33475</td>
<td width="45">1157</td>
<td width="148">455</td>
</tr>
<tr>
<td width="155">9649316844603\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">74921</td>
<td width="45">1199</td>
<td width="148">446</td>
</tr>
<tr>
<td width="155">2768474273172\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">48218</td>
<td width="45">1291</td>
<td width="148">474</td>
</tr>
</tbody>
</table>
Return value in $v0: 25886

<strong>Part 13: Find the Optimal Selling Order to Maximize Revenue</strong>

&nbsp;

int maximize_revenue(BookSale[] sales_list, int num_sales)

The maximize_revenue function takes an array of BookSale objects and determines in which order to sell the books to maximize the revenue. As laid out in the previous part of the assignment, we imagine a situation in which each day we select one book from the list of books and sell it. However, the next book to sell may be taken only from the front or the rear of the array.

Although the geeksforgeeks web page recommends using recursion to solve this problem, you are not expected or required to do so. In fact, a simple, iterative brute-force algorithm can be applied to solve this problem. Suppose n is the number of BookSale structs in sales_list . We can simply

n

enumerate all 2 possible bitstrings from 0 to 2 -1 and compute the revenues realized by selling the books in every possible order. In other words, we call

compute_scenario_revenue(sales_list, num_sales, bitstring) for each of the 2 <sup>n</sup> possible bitstrings and choose the maximum returned value. That’s it!

n

Enumerating the 2 possible bitstrings is very simple: in a for-loop, just count from 0 to 2 -1 and pass each of those values as scenario to the compute_scenario_revenue function. For large test cases, the maximum MIPS instruction count will be appropriately increased.

The function takes the following arguments, in this order:

<ul>
<li>sales_list: a completely filled array of BookSale structs</li>
<li>num_sales: the number of BookSale structs in sales_list</li>
</ul>
Returns in $v0:

<ul>
<li>The maximum revenue that can be realized by selling the books in sales_list as described in this part and the previous part of the assignment.</li>
</ul>
Additional requirements:

<ul>
<li>The function may not write any changes to main memory.</li>
<li>The function must call compute_scenario_revenue .</li>
</ul>
Example #1:

<table>
<tbody>
<tr>
<td colspan="3" width="177">num_sales = 5 Contents of sales_list:</td>
<td width="54">&nbsp;</td>
<td width="63">&nbsp;</td>
<td width="378">&nbsp;</td>
</tr>
<tr>
<td width="141">0000000000000\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12345</td>
<td width="63">153789</td>
<td width="378">2</td>
</tr>
<tr>
<td width="141">1111111111111\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">52321</td>
<td width="63">153789</td>
<td width="378">4</td>
</tr>
<tr>
<td width="141">2222222222222\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">41231</td>
<td width="63">153789</td>
<td width="378">6</td>
</tr>
<tr>
<td width="141">3333333333333\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">12523</td>
<td width="63">153789</td>
<td width="378">2</td>
</tr>
<tr>
<td width="141">4444444444444\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">51231</td>
<td width="63">153789</td>
<td width="378">5</td>
</tr>
</tbody>
</table>
Return value in $v0: 64

Example #2:

&nbsp;

<table>
<tbody>
<tr>
<td colspan="3" width="193">num_sales = 9 Contents of sales_list:</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td width="155">0845558347906\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">65818</td>
<td width="45">1620</td>
<td width="46">82</td>
</tr>
<tr>
<td width="155">5577045702462\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">91689</td>
<td width="45">1951</td>
<td width="46">154</td>
</tr>
<tr>
<td width="155">6354780489355\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">94530</td>
<td width="45">1579</td>
<td width="46">60</td>
</tr>
<tr>
<td width="155">1999320995468\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">93964</td>
<td width="45">1715</td>
<td width="46">225</td>
</tr>
<tr>
<td width="155">0145174318443\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">41570</td>
<td width="45">1195</td>
<td width="46">232</td>
</tr>
<tr>
<td width="155">5871544817889\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">57193</td>
<td width="45">1139</td>
<td width="46">387</td>
</tr>
<tr>
<td width="155">7106045480035\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">48631</td>
<td width="45">1282</td>
<td width="46">414</td>
</tr>
<tr>
<td width="155">1730871923235\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">39311</td>
<td width="45">1399</td>
<td width="46">78</td>
</tr>
<tr>
<td width="155">8122589552824\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">60637</td>
<td width="45">1888</td>
<td width="46">497</td>
</tr>
<tr>
<td colspan="3" width="193">Return value in $v0: 12980</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="193">Example #3:</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td width="155">num_sales = 11</td>
<td width="18">&nbsp;</td>
<td width="20">&nbsp;</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="193">Contents of sales_list :</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td width="155">5289996563210\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">50402</td>
<td width="45">1912</td>
<td width="46">114</td>
</tr>
<tr>
<td width="155">4878656880115\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">14181</td>
<td width="45">1025</td>
<td width="46">40</td>
</tr>
<tr>
<td width="155">1545953167947\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">74773</td>
<td width="45">1453</td>
<td width="46">419</td>
</tr>
<tr>
<td width="155">4163887205026\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">11881</td>
<td width="45">1088</td>
<td width="46">316</td>
</tr>
<tr>
<td width="155">3994954632401\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">25708</td>
<td width="45">1418</td>
<td width="46">346</td>
</tr>
<tr>
<td width="155">2840757350273\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">79850</td>
<td width="45">1501</td>
<td width="46">89</td>
</tr>
<tr>
<td width="155">2690573805693\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">75967</td>
<td width="45">1093</td>
<td width="46">147</td>
</tr>
<tr>
<td width="155">6412500793328\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">20379</td>
<td width="45">1997</td>
<td width="46">380</td>
</tr>
<tr>
<td width="155">1956670228687\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">95494</td>
<td width="45">1343</td>
<td width="46">275</td>
</tr>
<tr>
<td width="155">4719224196873\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">30863</td>
<td width="45">1956</td>
<td width="46">194</td>
</tr>
<tr>
<td width="155">1049903854879\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">40347</td>
<td width="45">1980</td>
<td width="46">281</td>
</tr>
<tr>
<td colspan="3" width="193">Return value in $v0: 18092</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="193">Example #4:</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td width="155">num_sales = 13</td>
<td width="18">&nbsp;</td>
<td width="20">&nbsp;</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td colspan="3" width="193">Contents of sales_list :</td>
<td width="52">&nbsp;</td>
<td width="45">&nbsp;</td>
<td width="46">&nbsp;</td>
</tr>
<tr>
<td width="155">0969867337768\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">91339</td>
<td width="45">1799</td>
<td width="46">274</td>
</tr>
<tr>
<td width="155">7167926219358\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">87431</td>
<td width="45">1648</td>
<td width="46">149</td>
</tr>
<tr>
<td width="155">5856271181125\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">38069</td>
<td width="45">1171</td>
<td width="46">135</td>
</tr>
<tr>
<td width="155">1739956344089\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">24120</td>
<td width="45">1716</td>
<td width="46">401</td>
</tr>
<tr>
<td width="155">2423634816035\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">44091</td>
<td width="45">1735</td>
<td width="46">429</td>
</tr>
<tr>
<td width="155">7323738407143\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">33518</td>
<td width="45">1687</td>
<td width="46">357</td>
</tr>
<tr>
<td width="155">0790885414601\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">49219</td>
<td width="45">1389</td>
<td width="46">468</td>
</tr>
<tr>
<td width="155">2095877382616\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">89257</td>
<td width="45">1679</td>
<td width="46">325</td>
</tr>
<tr>
<td width="155">7788346465697\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">76118</td>
<td width="45">1374</td>
<td width="46">364</td>
</tr>
<tr>
<td width="155">7903951955477\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">45362</td>
<td width="45">1032</td>
<td width="46">44</td>
</tr>
<tr>
<td width="155">2668430009430\0</td>
<td width="18">0</td>
<td width="20">0</td>
<td width="52">26427</td>
<td width="45">1969</td>
<td width="46">245</td>
</tr>
</tbody>
</table>
&nbsp;

<table>
<tbody>
<tr>
<td width="143">5802412331328\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">94001</td>
<td width="45">1133</td>
<td width="395">62</td>
</tr>
<tr>
<td width="143">0689148237261\0</td>
<td width="18">0</td>
<td width="18">0</td>
<td width="54">28651</td>
<td width="45">1412</td>
<td width="395">265</td>
</tr>
</tbody>
</table>
&nbsp;

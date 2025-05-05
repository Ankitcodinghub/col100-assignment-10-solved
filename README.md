# col100-assignment-10-solved
**TO GET THIS SOLUTION VISIT:** [COL100 Assignment 10 Solved](https://www.ankitcodinghub.com/product/col100-assignment-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101487&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COL100 Assignment 10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1 Python Lists in C

In this assignment you will be implementing Python List Data structure and the APIs associated with it, but in C programming language. One way to achieve this is to use pointers to handle this dynamic nature of the Python Lists (since arrays in C are static). In this way, a list is made up of some “nodes” that contain pointers of the next node; therefore you can move or “traverse” the list by moving through the pointers stored in each node. Therefore, we only need to store the “location” of the first node i.e. the head (of course, we store this location using a pointer). A “Node” is then a collection of 2 things: the first one is the data which it stores and second is the pointer that points to the next node of the list, that is how they are linked. Observe that you can only traverse in a single direction as only pointer to the next node is present. Note that initially, when the list is empty, HEAD would be NULL. Also, the last node always points to NULL marking the end of the list.

There are a couple of benefits of having this pointer containing list over an array. An array has fixed size, you have to copy the whole array if you want to add an element and the array is filled. Here you have dynamic size and can easily add and remove elements. Again as mentioned above, you will be mimicking a list in Python and implementing the functions present in lists in Python.

You are given a global pointer PythonListHead that always points to the head of the Python List and some helper function to create, print and delete the nodes. You are not allowed to change these helper functions that are already there since any changes might interfere with the autograder. Also, make sure that PythonListHead points to the head of the list always. Not following this invariant might result in malfunctioning of the autograder.

Some descrption of the helper functions provided to you:

create_new_node(int x): This function would create a new Node with the data attribute as x

and the next attribute as NULL and return a pointer to it.

delete_node(struct Node* ptr): This function would delete the node present at the ptr loca- tion and free the memory associated with it. Make sure ptr actually contains a valid Node, otherwise the function may throw a segmentation fault.

You have to implement the functions mentioned below and are also provided with the main func- tion. Again, as above, do not change the main function. You can change the inputs given to the program to check your code, you may also add print statements in your functions but make sure before

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
submitting, you comment all such print statements.

Please download the skeleton code from the gradescope. Please read the comments of the Skele- ton code for more clarity on the functions. You only need to fill the functions in the skeleton code and change nothing else. You can’t change the parameters and the return types of the functions in the skeleton code. You just have to return the values in the functions and rest will be handled by the main given to you.

Functions to be implemented are as below:

FUNCTIONS:

<ol>
<li>void append(int x): In-Lab Component

This function takes an integer parameter x and appends a Node with data x at the end of the list. Level: Medium</li>
<li>void insert(int position, int x):

This function takes two parameters position and interger x and will return insert a Node with data x at the given position in the list. If position doesn’t exists then do nothing.

Level: Medium</li>
<li>void pop():

This function deletes the Node from the end of the list. If the list is empty, do nothing. Level: Easy</li>
<li>void clear():

This function deletes all the elements from the list. Level: Easy</li>
<li>int count(int x): In-Lab Component

This function takes an integer argument x and then returns the count of the number of Nodes that contain the data as x in the list.

Level: Easy</li>
<li>void reverse():

This function in place reverses the list at the current state. i.e. You cannot use extra space while reversing the list. Make sure you change the PythonListHead accordingly.

Level: Hard</li>
<li>int len():

This function returns the number of Nodes in the list. Level: Easy</li>
<li>void setitem(int position, int x):

This function returns takes position and integer x as the parameters and sets the data of the Node at the given position as x.

Level: Easy</li>
<li>int getitem(int position):

This function takes the position as parameter and returns the data of the Node at the given position. If no such position exists in the list return −1.

Level: Easy</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ol start="10">
<li>void erase(int position):

This function takes parameter position and removes the Node at the given position. Level: Medium</li>
<li>void swap(int position):

This function takes parameter position and swaps the Nodes present at position and position + 1. If no such position or position + 1 exists, do nothing.

Level: Medium</li>
<li>void index_into(int *positions, int n):

Returns the head of the newly formed Python List containing elements present in positions in the original List. Note that you have to create new Python List and return its head. Here positions is an array of size n. eg. if positions = [2, 3, 5], you need to return a newly formed list having nodes that were at position 2, 3 and 5 in the original list.

Level: Hard</li>
<li>void sort():

This function sorts the Python List in-place. You might use the swap function defined above to implement Bubble Sort (Wiki). But you are free to implement any algorithm that achieves this. Note that PythonListHead might change at the end of this function.

Level: Hard</li>
</ol>
NOTE: You should never change the data attribute of an instance of a Node (except in setitem func- tion) i.e. your solution should not contain the code of the following form: node-&gt;data = some_value;. All the above functions should be implemented by manipulating the next attribute of the Node instance. If we discover a case that violates the above, we will NOT consider that submission.

Below we provide a description of the input.txt file that is given to you along with starter-code for more clarity. You may change the file to test your code on various other inputs. We have also provided a Makefile that enables you to compile your code and then run it on the given input.txt file. Just use the command make on the terminal. For more information on makefiles, refer here and here.

INPUT:

1 2 3 4 5 6 7 8 9

10 11 12 13 14 15 16 17

OUTPUT:

1 2 3 4

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>16
print
append 1
append 2
append 3
print
getitem 0
getitem 1
getitem 100
setitem 0 100
print
reverse
print
erase 0
print
erase 5
print
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
123 1

2

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>-1
100 2 3
3 2 100
2 100
2 100
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
5 6 7 8 9

</div>
</div>
<div class="layoutArea">
<div class="column">
EXPLANATION

1. The first line indicates the number of queries that we will be making. In this case, it is 16. 2. Initially the list is empty.

3. We append 1 to the list, so the list becomes 1.

4. We append 2, 3 as well to the list. The list now is 1,2,3.

5. We call print and it prints the list 1 2 3.

6. Now we call getitem 0 which means get the item at position 0 and it will return 1.

7. Now we call getitem 1 which means get the item at position 1 and it will return 2.

8. Calling getitem 100 will yield us -1 now, since there is no Node at position 100.

9. Then setitem 0 100 is called which sets the data as 100 at position 0 so the list now becomes 100 2 3.

<ol start="10">
<li>Then print is called that will print the current list.</li>
<li>Now we call reverse and it will reverse the list. The list now is 3 2 100</li>
<li>Then print is called that will print the current list.</li>
<li>Then we call erase 0 and it will erase the element at position 0. Now list becomes 2 100.</li>
<li>Then print is called that will print the current list.</li>
<li>Then we call erase 5 and it will erase the element at position 5. Since 5 is not the position of any Node in the list, so it will do nothing. Now list becomes 2 100.</li>
<li>Then print is called that will print the current list.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>

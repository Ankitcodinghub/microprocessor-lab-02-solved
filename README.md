# microprocessor-lab-02-solved
**TO GET THIS SOLUTION VISIT:** [Microprocessor Lab 02 Solved](https://www.ankitcodinghub.com/product/microprocessor-lab-02-requirement-description-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110216&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Microprocessor  Lab 02 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Merge two sorted arrays:

Source: Merge two sorted arrays – GeeksforGeeks 裡的 Method 3

Time complexity: O(n1 + n2)

Lab 02: Requirement Description

• Addressing Mode Guideline video: https://www.youtube.com/watch?v=NuTuCi2JEw8 hackmd: https://hackmd.io/S9oYQa4NSBqPdQWdMRJpFQ?view

• Basic

Description:

Please store 0x01 at Data Memory address 0x100, and store 0x01 at Data Memory address 0x101. Next, please use at least one indirect addressing register, so that the values of the Data Memory addresses 0x102~0x108 are the sum of the values of the previous two addresses.

For example: The value of Data Memory address 0x102 is the sum of the

value of Data Memory address 0x100 and the value of Data

Memory address 0x101,

the value of Data Memory address 0x103 is the sum of the

value of Data Memory address 0x101 and the value of Data

Memory address 0x102,

and so on, until the Data memory address 0x108.

Grading Criteria:

1. The data memory address 0x100~0x108 should be 0x01, 0x01, 0x02, 0x03, 0x05, 0x08, 0x0D, 0x15, 0x22 in sequence.

2. Please use at least one indirect addressing register.

• Advanced (30%):

Description:

Initialize the following 9 numbers (0x0B、0x05、0x40、0x07、0x0D、 0x7F、0x0A、0x01、0xFE) at 0x010 ~ 0x018 in Data Memory. Then, implement any sorting algorithm to sort the values and store the results at 0x010 ~ 0x018 in ascending order.

Standard of grading:

1. You must make sure that the values are sorted properly (as Figure).

2. You should use at least one indirect addressing register.

Hint: The number of the values is fixed. You do not have to consider the situation when the number of the values is changed.

• Bonus (20%):

Description:

In Data Memory address 0x100 ~ 0x104, store an array of 5 elements in sequence 0xa1, 0xb2, 0xc3, 0xd4, 0xe5, and in Data Memory address 0x110 ~ 0x113, store another array with 4 values in sequence 0xa7, 0xb3, 0xc9, 0xf6.

Next, please merge the two arrays into the data memory address 0x120 ~ 0x128 by means of merge two sorted arrays. The merged array is an increasing array with 9 elements.

Standard of grading:

1. You need to open File Registers in the video, and display the values in the three columns of 0x100, 0x110, and 0x120 on the screen.

2. The value of column 0x120 should be 0xa1, 0xa7, 0xb2, 0xb3, 0xc3, 0xc9, 0xd4, 0xe5, 0xf6.

3. Use at least one indirect addressing register.

Merge two sorted arrays:

Source: Method 3 in Merge two sorted arrays – GeeksforGeeks

Time complexity: O(n1 + n2)

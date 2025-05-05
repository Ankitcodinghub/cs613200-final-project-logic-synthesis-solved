# cs613200-final-project-logic-synthesis-solved
**TO GET THIS SOLUTION VISIT:** [CS613200 Final Project-Logic Synthesis Solved](https://www.ankitcodinghub.com/product/cs613200-final-project-logic-synthesis-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94605&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS613200 Final Project-Logic Synthesis Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This project will implement a two-stage algorithm for technology mapping in FPGA design on a Linux environment.

Stage1: Minimum Level Two-input Decomposition

A Boolean circuit is a network of Boolean gates, e.g., AND, OR, and NOT gates. The level of a circuit indicates the maximum number of gates from primary inputs to primary outputs. So, the circuit level further relates to the circuit delay.

A general circuit may consist of Boolean gates with more than two inputs. Replacing the multiple-input gates with smaller gates is widely adopted before the technology mapping, i.e., the decomposition. In the first stage, you will have a Boolean circuit that contains multiple-input gates. Your task is to decompose those gates into several two-input Boolean.

BLIF Example: test01.blif

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>.model sample01
.inputs a b c d e
.outputs h j
.names a b c d f
1--- 1
</pre>
<pre>-1-- 1
--1- 1
---1 1
.names b d g
1- 1
</pre>
-1 1

.names a f h

1- 1

-1 1

.names d e f g i 1111 1

.names i j

01

.end

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Output BLIF Example: output.blif

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>.model sample01
.inputs a b c d e
.outputs h j
.names a b f1
</pre>
1- 1

-1 1

.names c d f2 1- 1

-1 1

.names f1 f2 f 1- 1

-1 1

.names b d g 1- 1

-1 1

.names a f h 1- 1

-1 1

.names d e i2 11 1

.names g i2 i1 11 1

.names f i1 i 11 1

.names i j

01

.end

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Stage2: Delay Optimal FPGA Technology Mapping

The FPGA comprises K-input lookup tables (LUTs) and Flip-Flops (FFs), which can simulate any circuit’s functionality. The technology mapping is the step to map a circuit’s functionality with the FPGA’s LUTs and FFs. Since the LUTs are limited hardware resources on the FPGA, a good mapping uses fewer FPGA LUTs to achieve the functionality. (In this project, we only consider the K-input LUTs.)

With the decomposed circuit from the first stage, this stage’s task is to map the circuit to a K-input LUT FPGA. You will write a program to perform LUT technology mapping on FPGA with a minimized circuit level and number of LUTs.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Input/output Format:

<ul>
<li>Input file: A BLIF format file with 3 types of Boolean operations, i.e., AND, OR, and NOT.</li>
<li>Standard output: The circuit level and number of LUT of your circuit.</li>
<li>Output file: A BLIF format file of your circuit.
Input file example: map01.blif
</li>
</ul>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>.model map01
.inputs a b c d e f g h i j k l m n
.outputs o
.names [25] [26] o
11 1
.names k x1 x2
1- 1
-1 1
.names [19] [20] x3
1- 1
-1 1
.names n [18] x1
11 1
.names m l [18]
11 1
.names h g [19]
1- 1
-1 1
.names j i [20]
1- 1
-1 1
.names b a [21]
11 1
.names d c [22]
11 1
.names f e [23]
11 1
.names [22] [21] [24]
11 1
.names x3 [23] [25]
11 1
.names x2 [24] [26]
11 1
.end
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Run-time Example:

Output file example: output.blif

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>%&gt; ./map –k 4 map01.blif output.blif # map circuit by 4-input LUT
The circuit level is 2.
The number of LUTs is 5.
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>.model map01
.inputs a b c d e f g h i j k l m n
.outputs o
.names x2 x3 [23] [24] o
1111 1
.names k l m n x2
1--- 1
-111 1
.names g h i j x3
1--- 1
-1-- 1
--1- 1
---1 1
.names f e [23]
11 1
.names a b c d [24]
1111 1
.end
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Notice:

<ol>
<li>The score considers the circuit level (primarily) and the number of LUT (secondary).</li>
<li>The output circuit’s functionality must be equivalent to the input circuit. You may use
the ABC command (i.e., cec) for equivalent checking!
</li>
<li>LEDA is a C++ library for efficient data types and algorithms. You can download the static
library file of LEDA from the course website and use the graph algorithm (e.g., min_cut) provided by LEDA API in your code. (http://www.algorithmic-solutions.info/leda_guide/graph_algorithms/mincut.html)
</li>
<li>Please follow the format of run-time example:
<pre>     %&gt; ./map –k 4 map01.blif output.blif
</pre>
</li>
<li>TA will test your program with different k-input sizes.</li>
<li>Please submit your source code, makefile, and a readme that describes how to compile
your code.
</li>
<li>A report is required (10%), which includes your data structure, algorithm, and results.</li>
<li>You must demo your code to TA orally. You get zero score for skipping demo.</li>
</ol>
Reference

[1] J. Cong, Y. Ding, An Optimal Technology Mapping Algorithm for Delay Optimization in Lookup-Table based FPGA Designs, IEEE Trans. on CAD, Vol. 13, No. 1, Jan. 1994, pp. 1-12

[2] Leda, http://www.algorithmic-solutions.info/leda_guide/Index.html

</div>
</div>
</div>

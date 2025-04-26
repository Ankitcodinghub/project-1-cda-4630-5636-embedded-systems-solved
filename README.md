# project-1-cda-4630-5636-embedded-systems-solved
**TO GET THIS SOLUTION VISIT:** [Project 1 CDA 4630/5636: Embedded Systems Solved](https://www.ankitcodinghub.com/product/project-1-cda-4630-5636-embedded-systems-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;39532&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Project 1  CDA 4630\/5636: Embedded Systems Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
This is an <strong>individual</strong> assignment. You are not allowed to take or give any help in completing this project. Please <strong>strictly</strong> <strong>follow the submission instructions</strong> (outlined at the end of this document) and submit your source code in eLearning (https://elearning.ufl.edu/) website before the deadline. Please include the following sentence on top of your submission: “<strong>I have neither given nor received any unauthorized aid on this assignment</strong>”.

<strong>Petri Net Simulator for a Simplified MIPS Processor: </strong>In this project, you will create a Petri Net simulator for a simplified MIPS Processor. The model will use colored tokens (token with values) rather than the default Petri net. Your simulator should generate step-by-step simulation of the Petri net model of the MIPS processor described below. You can use <strong>C</strong>, <strong>C++</strong> or <strong>Java</strong> to implement this project. Please go through this document first, and the view the sample input/output files in the class assignments page.

<strong><img data-recalc-dims="1" decoding="async" class="aligncenter lazyloading" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/12/526.png?w=980&amp;ssl=1" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2019/12/526.png?w=980&amp;ssl=1">&nbsp;</strong>

We first describe three important places (instruction memory, register file, and data memory) of the Petri net model. Next we describe eight transitions. The remaining places can be viewed as buffers. Each arc carries (consumes) 1 token unless marked otherwise. <strong>You do not have to worry about any hazards. We will not provide testcases that produces any hazards or exceptions. </strong>

<strong>&nbsp;</strong><strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h1>THREE IMPORTANT PLACES</h1>
<ol>
<li><strong> Instruction Memory (INM):</strong></li>
</ol>
The processor to be simulated only supports five types of instructions: <em>add</em> (ADD), <em>subtract</em> (SUB), <em>logical and</em> (AND), <em>logical or</em> (OR), and <em>load</em> (LD). At a time step, the place denoted as Instruction Memory (INM) can have up to 16 instruction tokens. This is shown as <strong>Ii</strong> in Figure 1. We will provide an input file (instructions.txt) with up to 16 instruction tokens. It supports the following instruction format. Please note that both source operands are always registers.

&lt;Opcode&gt;, &lt;Destination Register&gt;, &lt;First Source Operand&gt;, &lt;Second Source Operand&gt;

Sample instruction tokens and equivalent functionality are shown below:

&lt;ADD, R1, R2, R3&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; è R1 = R2 + R3

&lt;SUB, R1, R2, R3&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; è R1 = R2 – R3

&lt;AND, R1, R2, R3&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; è R1 = R2 &amp; R3

&lt;OR, R1, R2, R3&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; è R1 = R2 | R3

&lt;LD, R1, R2, R3&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; è R1 = DataMemory[R2+R3]

&nbsp;

<ol start="2">
<li><strong>Register File (RGF):</strong></li>
</ol>
This MIPS processor supports up to 8 registers (R0 through R7). At a time step it can have up to 8 tokens. The token format is &lt;registername, registervalue&gt;, e.g., &lt;R1, 5&gt;. This is shown as <strong>Xi</strong> in Figure 1. We will provide an input file (registers.txt) with 8 register tokens that you can use to initialize the registers. You can assume that the content of a register can vary between 0 – 63.

<ol start="3">
<li><strong>Data Memory (DAM):</strong></li>
</ol>
This MIPS processor supports up to 8 locations (0 – 7) in the data memory. At a time step it can have up to 8 tokens. The token format is &lt;address, value&gt;, e.g., &lt;6, 5&gt; implies that memory address 6 has value 5. This is shown as <strong>Di</strong> in Figure 1. We will provide an input file (datamemory.txt) with 8 data tokens that you can use to initialize the data memory locations. You can assume that the content of a data memory location can vary between 0 – 63.

&nbsp;

<h1>EIGHT TRANSITIONS</h1>
<ol>
<li><strong>READ: </strong></li>
</ol>
The READ transition is a slight deviation from traditional Petri net semantics since it does not have any direct access to instruction tokens. Assume that it knows the top (in-order) instruction in the Instruction Memory (INM). It checks for the availability of the source operands in the Register File (RGF) for the top instruction token and passes them to Instruction Buffer (INB) by replacing the source operands with the respective values. For example, if the top instruction token in INM is &lt;ADD, R1, R2, R3&gt; and there are two tokens in RGF as &lt;R2,5&gt; and &lt;R3,7&gt;, then the instruction token in INB would be &lt;ADD,R1,5,7&gt; once both READ and DECODE transitions are activated. Both READ and DECODE transitions are executed together. Please note that when READ consumes two register tokens, it also returns them to RGF in the same time step (no change in RGF due to READ).

&nbsp;

&nbsp;

&nbsp;

<ol start="2">
<li><strong>DECODE:</strong></li>
</ol>
The DECODE transition consumes the top (in-order) instruction (one token) from INM and updates the values of the source registers with the values from RGF (with the help of READ transition, as described above), and places the modified instruction token in INB.

&nbsp;

<ol start="3">
<li><strong>ISSUE1:</strong></li>
</ol>
ISSUE1 transition consumes one arithmetic/logical (ADD, SUB, AND, OR) instruction token (if any) from INB and places it in the Arithmetic Instruction Buffer (AIB).

&nbsp;

<ol start="4">
<li><strong>ISSUE2:</strong></li>
</ol>
ISSUE2 transition consumes one load (LD) instruction token (if any) from INB and places it in the Load Instruction Buffer (LIB).

&nbsp;

<ol start="5">
<li><strong>Arithmetic Logic Unit (ALU) </strong></li>
</ol>
ALU transition performs arithmetic/logical computations as per the instruction token from AIB, and places the result in the result buffer (REB). The format of the token in result buffer is same as a token in RGF i.e., &lt;destination-register-name, value&gt;.

&nbsp;

<ol start="6">
<li><strong>Address Calculation (ADDR)</strong></li>
</ol>
ADDR transition performs effective (data memory) address calculation for the load instruction by adding the contents of two source registers. It produces a token as &lt;destination-register-name, data memory address&gt; and places it in the address buffer (ADB).

&nbsp;

<ol start="7">
<li><strong>LOAD: </strong></li>
</ol>
The LOAD transition consumes a token from ADB and gets the data from the data memory for the corresponding address. Assume that you will always have the data for the respective address in the data memory in the same time step. It places the data value (result of load) in the result buffer (REB). The format of the token in result buffer is same as a token in RGF i.e., &lt;destination-register-name, data value&gt;.

&nbsp;

<ol start="8">
<li><strong>WRITE</strong></li>
</ol>
Transfers the result (one token) from the Result Buffer (REB) to the register file (RGF). If there are more than one token in REB in a time step, the WRITE transition writes the token that belongs to the in-order first instruction.

&nbsp;

<strong><u>Command Line and Input/Output Formats</u></strong><strong>: </strong>

<strong>Command Line:</strong>

The simulator should be executed with the following command line:

<strong>./MIPSsim</strong>&nbsp;&nbsp; or&nbsp; <strong>java MIPSsim</strong>

Please hardcode the input and output files as follows: Instructions (input):&nbsp; instructions.txt

Registers (input): registers.txt

Data Memory (input): datamemory.txt

Simulation (output): simulation.txt

<strong>&nbsp;</strong>

<strong>File Formats:</strong>

<em>We will provide inputs in the specific format as listed below:</em>

<h2>Input Register File Format: (see registers.txt for example)</h2>
&lt;register name,value&gt;

…

&nbsp;

<h2>Input Data Memory File Format: (see datamemory.txt for example)</h2>
&lt;memory address,data value&gt;

…

&nbsp;

<u>Input Instruction Memory File Format (see instructions.txt for example):</u>

&lt;opcode,dest,src1,src2&gt;

…

<u>Step-by-step Snapshot Output File Format&nbsp; </u>(see simulation.txt for example): <strong>Please note the following comments are not part of the output format</strong>.

&nbsp;

STEP 0:

INM: I1,I2,I3,…&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Where Ii are comma separated instruction tokens.&nbsp;&nbsp; INB:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma separated tokens with source values.

AIB:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma separated arithmetic instruction tokens

LIB:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma separated load instruction tokens

ADB:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma separated address tokens

REB:&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Comma separated result buffer tokens

RGF:RF1,RF2,…&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma Separated register file tokens.

DAM:D1,D2,…&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # Comma Separated data memory tokens. &lt;blank_line&gt;

STEP 1: …

Continue until the end of simulation. End of simulation is determined when none of the transitions can be fired in a time step.

&nbsp;

Additional Notes: (refer to sample input and output files for ease of understanding)

<ul>
<li>STEP 0 values represent initial states of all the places. STEP 1 represents the tokens of all the places at the end of first time step. In general, STEP <strong>i</strong> values should reflect the tokens of all the places at the end of time step <strong>i</strong>. In each time step, you are supposed to execute each transition exactly once (if it has required input tokens at the beginning of that cycle).</li>
<li>When there are more than one tokens in a place, please print them in instruction order (<strong>in-order</strong>) except for DAM and RGF. The token for DAM and RGF should be printed in the sorted order based on memory address or register name (starting with the smallest), respectively.</li>
</ul>
<strong>&nbsp;</strong>

<strong><u>Submission Policy</u>: </strong>

Please follow the submission policy outlined below. There will be up to 10% <strong>score penalty</strong> based on the nature of submission policy violations.

<ol>
<li>Please submit only one source file. <strong>Please add “.txt” at the end of your filename</strong>. Your file name must be MIPSsim (e.g., MIPSsim.c.txt <strong>or</strong>cpp.txt <strong>or</strong> MIPSsim.java.txt). On top of the source file, please include the sentence: “/* On my honor, I have neither given nor received unauthorized aid on this assignment */”.</li>
<li>Please test your submission. These are the exact steps we will follow too. o Download your submission from eLearning (ensures your upload was successful).
<ul>
<li>Remove “.txt” extension (e.g., MIPSsim.c.txt should be renamed to MIPSsim.c)</li>
<li>Login to thunder.cise.ufl.edu or storm.cise.ufl.edu. If you don’t have a CISE account, go to http://cise.ufl.edu/help/account.shtml and apply for one CISE class account. Then you use <strong>putty</strong> and <strong>winscp</strong> or other tools to login and transfer files.</li>
<li>Please compile to produce an executable named <strong>MIPSsim</strong>.
<ul>
<li>gcc MIPSsim.c –o MIPSsim<strong> or</strong>&nbsp; javac MIPSsim.java&nbsp; <strong>or</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; g++ MIPSsim.cpp –o MIPSsim&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>or </strong>&nbsp;g++ -std=c++0x MIPSsim.cpp -o MIPSsim</li>
</ul>
</li>
<li>Please do not print anything on screen.</li>
<li>Execute to generate simulation file and test with the correct one
<ul>
<li>./MIPSsim <strong>or</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; java&nbsp; MIPSsim</li>
<li>diff –w –b –B simulation.txt txt</li>
</ul>
</li>
</ul>
</li>
</ol>
<ol start="3">
<li><em>In previous years, there were many cases where output format was different, filename was different, command line arguments were different, or e-Learning submission was missing. All of these led to unnecessary frustration and waste of time for TA, instructor and students. </em><strong>Please use the exactly same commands as outlined above to avoid 10% score penalty.</strong></li>
<li><strong>You are not allowed to take or give any help in completing this project</strong>. <em>In previous years, some students violated academic honesty (giving help or taking help in completing this project). We were able to establish cheating in several cases – those students received “0” in the project and their names were reported to UF Ethics office. This year we would also impose one additional letter grade penalty. </em></li>
</ol>
<em>Someone could potentially lose two letter grade points (e.g., “A-” grade to “B” grade) – one for getting 0 score in the project and then another grade point penalty on top of it. Moreover, the names of the students will also be reported to UF Dean of Students Office (DSO). If your name is already in DSO for violation in another course, the penalty for the second offence is determined by DSO. In the past, two students from my class were suspended for a semester due to repeated academic honesty violation (implies deportation for international students). </em>

<strong><u>Grading Policy</u> </strong>

The class assignments webpage has the sample input and output files. Correct handling of the sample input (with possible changes of register and data values) will be used to determine 60% of credit awarded. <strong>The register and data memory values will be between 0 and 63</strong>. The remaining 40% will be determined from other input test cases that you will not have access prior to grading. The other test cases can have different number or order of instructions as well as different register and data memory tokens. It is recommended that you construct your own sample input files with which to further test your simulator. <strong>Note that the new test case will NOT test any hazards, exceptions or scenarios that are not described in this document</strong>.

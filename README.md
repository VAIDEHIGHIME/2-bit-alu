INTRODUCTION

A computer is an electronic device that manipulates information, or data. It has the ability to store, retrieve, and process data. It is a device that can be instructed to carry out an arbitrary set of arithmetic or logical operations automatically. The ability of computers to follow a sequence of operations, called a program, make computers very applicable to a wide range of tasks.
Since ancient times, simple manual devices like the abacus, aided people in doing calculations. Early in the Industrial Revolution, some mechanical devices were built to automate long tedious tasks, such as guiding patterns for looms. More sophisticated electrical machines did specialized analogue calculations in the early 20th century. The first digital electronic calculating machines were developed during World War II. The speed, power, and versatility of computers have increased continuously and dramatically since then.
Conventionally, a modern computer consists of at least one processing element, typically a central processing unit (CPU), and some form of memory. The processing element carries out arithmetic and logical operations, and a sequencing and control unit can change the order of operations in response to stored information.

CENTRAL PROCESSING UNIT (CPU)
The control unit, ALU, and registers are collectively known as a central processing unit (CPU). Early CPUs were composed of many separate components but since the mid-1970s CPUs have typically been constructed on a single integrated circuit called a microprocessor.

ARITHMETIC LOGIC UNIT (ALU)
The ALU is capable of performing two classes of operations: arithmetic and logic. The set of arithmetic operations that a particular ALU supports may be limited to addition and subtraction, or might include multiplication, division, trigonometry functions such as sine, cosine, etc., and square roots. Some can only operate on whole numbers (integers) whilst others use floating point to represent real numbers, albeit with limited precision. However, any computer that is capable of performing just the simplest operations can be programmed to break down the more complex operations into simple steps that it can perform. Therefore, any computer can be programmed to perform any arithmetic operation—although it will take more time to do so if its ALU does not directly support the operation. An ALU may also compare numbers and return Boolean truth values (true or false) depending on whether one is equal to, greater than or less than the other ("is 64 greater than 65?"). Logic operations involve Boolean logic: AND, OR, XOR, and NOT. These can be useful for creating complicated conditional statements and processing Boolean logic.
  
In our mini-project, we have attempted to design and realise a 2-bit computer whose ALU performs specific calculations and operations, namely:
Addition 
Subtraction  
Multiplication 
Division 
Comparison

 In a nutshell, firstly, we thought of a particular logic for each operation and then by using our knowledge of the Karnaugh Maps, we realised all the combinational circuits) using the basic gates (AND, OR, NOT).
 
SOFTWARE IMPLEMENTATION
We implemented our logics on the Multisim 14.0.0. 
Firstly, each operation was performed successfully on different sheets, using the truth tables mentioned above. 
The inputs to the gates were given from the Word Generator while the outputs were obtained on the DCD hex display. 
Then came the difficult task of combining all the operations and creating the final ALU having all the operations at one place. 
So, we put each operation into a specific box, assuming it to be a black box where only the inputs and outputs are shown by following the procedure as given: 
Go to “place” situated on the toolbar in the Multisim desktop.
Select “New Hierarchical Block” from the dropdown menu. A dialog box appears. 
Input your block “name”, number of “input pins”, and number of “output pins” into the desired labels. Click “Ok”.
A hierarchical block would be created. Double click on the block and select “open sub sheet”.
Copy the sheet whose circuit is required to be put into the black box, give the respective inputs and outputs to the terminals and you are done.
Place > New Hierarchical Block > Open Sub Sheet 
Now, each black box (containing a particular operation) is given same inputs from the word generator (2 – bit numbers: A, B as inputs) and separate outputs connected to the DCD hex display. 
Hence, the desired ALU of our 2-bit Computer was obtained. 

CONCLUSION
Our ALU has five operations. These five operations are carried out for 2-bit inputs.
This mini-project helped us to learn many new aspects and internal concepts of combinational circuits. 
We were able to gain more information about the various features of Multisim. 
To conclude, we were successful in designing a logic that could help us in performing calculations, similar to what any other computational machine would do!

# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean function minimization is the process of simplifying Boolean algebraic expressions to reduce the number of logic gates and complexity in a digital circuit, leading to more efficient, faster, and less costly hardware For minimizing Boolean expressions,we can use a set of rules and laws (like distributive, associative, and complement laws) to simplify Boolean expressions. This method focuses on applying algebraic manipulations to reduce the complexity of the expression by eliminating redundant terms.

Identity Law A ⋅ 1 = A, A + 0 = A

Null Law A ⋅ 0 = 0, A + 1 =1

Idempotent Law A ⋅ A = A, A + A = A

Complement Law A ⋅ A′ = 0, A + A' = 1

Distributive Law A ⋅ (B + C) = A ⋅ B + A ⋅ C

De Morgan’s Law (A ⋅ B)′ = A′ + B', (A + B)′ = A′ ⋅ B′

Absorption Law A ⋅ (A + B) = A, A + (A ⋅ B) = A

Associative Law A + (B + C) = (A + B) + C, A.(B.C) = (A.B).C

Commutative law A B = B A,A + B = B + A

**Logic Diagram**

**Procedure:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

(i) <img width="1920" height="1080" alt="Screenshot (122)" src="https://github.com/user-attachments/assets/516ea217-b878-41fd-ac81-79f990a82203" />

(ii) <img width="1920" height="1080" alt="Screenshot (125)" src="https://github.com/user-attachments/assets/2153a1e3-1cec-49c4-a021-fa032d5fcf7c" />

Developed by: RAAGHAVI S  RegisterNumber: 212225040321 */

**Truth Table:**
(i) <img width="805" height="442" alt="image" src="https://github.com/user-attachments/assets/524317d3-9337-4ff3-a654-222afff3e326" />

(ii) <img width="797" height="421" alt="image" src="https://github.com/user-attachments/assets/b71193ee-d7f1-4af4-80d4-1d2793293431" />

**RTL realization**

(i) <img width="1920" height="1080" alt="Screenshot (123)" src="https://github.com/user-attachments/assets/ac387f78-2462-47d7-b419-0bc4d0753e37" />

(ii) <img width="1920" height="1080" alt="Screenshot (126)" src="https://github.com/user-attachments/assets/15ac6ac1-31ae-419b-a282-ff39b9ccc6a9" />

**Output:**
**Timing Diagram**

(i) <img width="1920" height="1080" alt="Screenshot (121)" src="https://github.com/user-attachments/assets/5b899d8c-8c78-4b7c-ab8a-e9ff9418cc99" />

(ii) <img width="1920" height="1080" alt="Screenshot (124)" src="https://github.com/user-attachments/assets/e67527d0-4643-469c-8459-fe788ebeb6b8" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


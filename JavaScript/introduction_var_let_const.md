Part a — 4 Questions
1. Personal Information Declare variables for name, age, and city using appropriate variable keywords. Assign values and print all three variables.

2. Change the Score Create a variable score with the value 50. Change its value to 80 and print the final value. Use the appropriate keyword for a value that can change.

3. Constant Value Create a constant variable PI with the value 3.14. Print its value. Do not try to change the value.

4. Uninitialized Variables Declare one variable having name num1 using var and one having name num2 using let without assigning values. Print both variables. Then assign values to them and print the values again.
Answer:
<img width="250" height="117" alt="Screenshot 2026-09-30 181334" src="https://github.com/user-attachments/assets/37b97b8f-a4f5-4f90-aacc-acc9255809a1" />
<img width="217" height="52" alt="Screenshot 2026-09-30 181021" src="https://github.com/user-attachments/assets/ce980972-1cd6-407e-8c06-a21eb09f9182" />
<img width="328" height="105" alt="Screenshot 2026-09-30 180839" src="https://github.com/user-attachments/assets/f8ee89db-7a97-48d6-a7c0-07d37c637984" />
<img width="330" height="187" alt="Screenshot 2026-09-30 180447" src="https://github.com/user-attachments/assets/8bfc4c48-f0ff-4c71-8a67-afe585cfea94" />

 Question.5.
 Choose the Correct Keyword Create the following variables using the most appropriate keyword:

studentName — the value will not change
marks — the value may change
schoolName — the value will not change
Assign values to all three variables. Change marks and print all variables.
Answer:
<img width="632" height="97" alt="image" src="https://github.com/user-attachments/assets/64759f15-5ad3-4a3c-b07a-d4e0bafe02f4" />
<img width="843" height="182" alt="Screenshot 2026-09-30 183748" src="https://github.com/user-attachments/assets/1e422520-daab-4ec4-af09-3a52c384eecf" />

Question.6.Understand Scope Write a program where var, let, and const variables are declared inside an if block. Try to access all three variables outside the block. Observe and identify which variables can be accessed.
Answer:
<img width="266" height="247" alt="Screenshot 2026-09-30 192054" src="https://github.com/user-attachments/assets/e9d3b9ec-140e-4043-ac9a-735fc8d91c03" />
<img width="62" height="102" alt="Screenshot 2026-09-30 192059" src="https://github.com/user-attachments/assets/65a4993e-b8df-486b-a1b9-0fdb5ac1d5bc" />
<img width="310" height="271" alt="Screenshot 2026-09-30 192153" src="https://github.com/user-attachments/assets/a9ef094a-ad05-4be9-b64a-d3692fd20471" />
<img width="692" height="510" alt="Screenshot 2026-09-30 192216" src="https://github.com/user-attachments/assets/7ebb02c7-d3d8-401f-b115-cbc002b6cab1" />
<img width="293" height="327" alt="Screenshot 2026-09-30 192240" src="https://github.com/user-attachments/assets/c9c6715d-0c01-421e-b614-857f5ee2e29c" />
<img width="77" height="107" alt="Screenshot 2026-09-30 192245" src="https://github.com/user-attachments/assets/cf470225-ec1c-4e75-b488-550363f1b40f" />


Question. 7. Test Re-declaration Declare a variable named user using var and declare it again with a different value. Then perform the same experiment using let. Observe what happens and identify which declaration allows re-declaration.
Answer:
<img width="47" height="47" alt="Screenshot 2026-09-30 193759" src="https://github.com/user-attachments/assets/9abb7980-daef-4c70-860b-3bb9e0483feb" />
<img width="200" height="97" alt="Screenshot 2026-09-30 193746" src="https://github.com/user-attachments/assets/733b186a-6537-4df3-9f1d-b47d020e2c85" />
<img width="47" height="47" alt="Screenshot 2026-09-30 193759" src="https://github.com/user-attachments/assets/aceb0585-102c-4f5f-a9c1-3945a11c5ea8" />
<img width="198" height="90" alt="Screenshot 2026-09-30 193816" src="https://github.com/user-attachments/assets/b3ff382d-6d99-48ef-88ff-4ba32108b051" />
<img width="207" height="118" alt="Screenshot 2026-09-30 193837" src="https://github.com/user-attachments/assets/db3c1cdb-3c87-460e-8956-8a41b1dff25f" />
<img width="746" height="595" alt="Screenshot 2026-09-30 193848" src="https://github.com/user-attachments/assets/e4be1d12-5bb6-4cdc-951c-ce4a23b3807e" />


8. Test Re-assignment Create three variables using var, let, and const. Assign an initial value to each. Try to change the value of all three variables. Observe which variables allow re-assignment and which one produces an error.
Answer:
<img width="323" height="77" alt="Screenshot 2026-09-30 193356" src="https://github.com/user-attachments/assets/cfd28cc1-4c2d-480f-bfd0-e53cd747c523" />
<img width="288" height="98" alt="Screenshot 2026-09-30 193416" src="https://github.com/user-attachments/assets/ed079ff4-5348-419f-84e1-61be80900b73" />
<img width="680" height="497" alt="Screenshot 2026-09-30 193428" src="https://github.com/user-attachments/assets/11896a98-2796-4bf7-aff8-88cf234df83b" />
<img width="320" height="80" alt="Screenshot 2026-09-30 194529" src="https://github.com/user-attachments/assets/436ff797-d1b5-4f5f-a22b-7edee3415ad6" />
<img width="738" height="441" alt="Screenshot 2026-09-30 194544" src="https://github.com/user-attachments/assets/67932e96-df85-42e0-98dc-ea52861f1725" />

9. Predict and Explain Without running the code, predict the output of each console.log() and identify which lines cause errors. Explain your answer using the rules of scope, re-assignment, and variable declaration.
```Javascript
var x = 10;

if (true) {
    var x = 20;
    let y = 30;
    const z = 40;
}

console.log(x);
console.log(y);
console.log(z);
```
Answer:
only x is print because var is a functional keyword or variable.
And y and z show error because they are block scope keyword of variable.

10. Fix the Program The following program contains multiple errors. Fix the code so that it runs correctly. Make sure your solution follows the rules for initialization, re-declaration, re-assignment, and scope.
```JavaScript
const name;

let age = 20;
let age = 25;

if (true) {
    var city = "Delhi";
    let country = "India";
}

console.log(country);

const score = 50;
score = 80;
```
Answer:
```JavaScript
var name;

let age = 20;
let age = 25;

if (true){
     var city = "Delhi";
     let country = "India"
     console.log(country);
     }
var score = 50;
score = 80;
```












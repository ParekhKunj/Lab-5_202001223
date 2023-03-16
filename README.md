# Lab-5_202001223
**Static Analysis Tool:**  Pytlint

I have taken two example codes in python for static analysis

**Example 1:**


**For first Example error detected-**

![image](https://user-images.githubusercontent.com/124246644/225582078-788b1915-a2b5-440d-a090-270f0d617528.png)


**Codelines in which errors are detected :**

![image](https://user-images.githubusercontent.com/124246644/225582318-f70bec90-6a08-4d24-885b-35123a07666e.png)

![image](https://user-images.githubusercontent.com/124246644/225582459-5e1701c0-ed23-487c-919d-17e9f9387eb7.png)

![image](https://user-images.githubusercontent.com/124246644/225582940-5129a6f5-2f5a-48d7-a240-7005c6fb495a.png)

![image](https://user-images.githubusercontent.com/124246644/225582585-03123da7-cd03-4455-96c8-6ed7fdcfdea1.png)

![image](https://user-images.githubusercontent.com/124246644/225582834-4014a860-9394-497e-9e32-72ab5189f587.png)



**Discription of errors:**

     1st error shows error about extra newline

     2nd error is about more number of characters in comments compare to desired number of Errors.
     
     4th error showing that file name does not follow the naming style.
     
     3rd, 5th and 6th error is about missing docstring.
     
     7th and 10th errors are about having unnecessary statements/lines.

Basically this all errors are just warnings not compulsory errors , so the developer can remove these errors if he/she wishes to. Thus these are false positive errors.

The 8th error shows unnecessary use of else as we have to return only then it doesn't require the else statement.But here actually else is working when len of array is greater than 1 so this is false negative error as a warning.

**Example 2:**



**For first Example 2 error detected-**

![image](https://user-images.githubusercontent.com/124246644/225584508-5e2608e4-56e2-4f27-a7b5-bb3f3128eb8d.png)

**Codelines in which errors are detected :**

![image](https://user-images.githubusercontent.com/124246644/225584906-4a8828ab-b633-4090-86fc-d9032e54473f.png)

![image](https://user-images.githubusercontent.com/124246644/225584994-0ad4dbef-1ac1-44e3-a4c0-787c329d099d.png)

**Discription of errors:**

     1st error shows error about unnecessaary line

     2nd error is about identation that the import statement should be at the top of the file. 

This both errors are as a warning so these are false positive error which developer can remove if he/sher wishes. 

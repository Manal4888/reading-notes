## [Link of the Duckett JS book:](https://alqudscollege-my.sharepoint.com/:B:/g/personal/advtech_ltuc_com/Ecix8R_amQVPhRpnPyJaSmoBleNloBxgtjgnbXS7T9MgoA?e=PPfTVl )

JavaScript book, Ch. 10, “Error Handling & Debugging”

The JavaScript interpreter uses the concept of **execution contexts**. There is  one global execution context; plus, each function creates a new new execution context. They correspond to **variable scope**. 

Summary:

- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 

- Debugging is the process of finding errors. It involves a process of deduction. ;

- The console helps narrow down the area in  which the error is located, so you can try to find the exact error. ;

- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. ;

- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 
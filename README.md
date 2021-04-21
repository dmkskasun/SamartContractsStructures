# SamartContractsStructures
----
![Supply Image](Images/ethereum_solidity.jpg)

### My First Contract
Still pending........

I am trying to simplify solidity and show how to build it step by step. 
I am using Dapp University and freeCodeCamp.org to build the building blocks step by step. 

----
### How to find errors and how to solve them?

![Supply Image](Images/one.gif)

The above Gif Image shows once you compile the above simple, smart contract, you get errors in lines 7 and 8. Line 7 says 

#### " Did you intend to add "public" ? function get() 

This means we need to add "public." or if it is private we can add "private" after the get().

But its still give an error on line 8.

![image](https://user-images.githubusercontent.com/71329902/115631370-8a217f80-a2ba-11eb-832f-891210421384.png)

The error says,

![image](https://user-images.githubusercontent.com/71329902/115631491-c7860d00-a2ba-11eb-995f-6142467fef61.png)

The above error means there are many arguments, which means the solidity compiler didn't know the return value is a string, integer, etc.( VAR), So we need to change that public returns(string) as show below, but still it gives an warning.

![image](https://user-images.githubusercontent.com/71329902/115632272-36179a80-a2bc-11eb-8355-8aa7aedd5e53.png) 

and the warning says,

![image](https://user-images.githubusercontent.com/71329902/115632313-49c30100-a2bc-11eb-8af8-3d9399959d2f.png)

This simply means we cant view the string value after we deply it, so we add ##view 







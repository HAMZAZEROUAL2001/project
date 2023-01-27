# project

#### introduction :


hello guys , to day I will try to build File-Integrity-Monitor with python programming language, but before I get started. we need to know what is 

#### 3 Pillars of Data Security: Confidentiality, Integrity & Availability

    Confidentiality — You need to know your data is protected from unauthorized access.
    Integrity — You have to be able to trust your data.
    Availability — You need to be able to access your data.

#### let it focus on the Intergrity :


### Integrity 
is maintaining the consistency and trustworthiness of data, making sure it doesn’t change if it’s not supposed to and if it does, the user knows about it. This is what we will cover in this tutorial. We will build a simple FIM (File Integrity Monitor) using hashing algorithms to monitor data and keep tabs on changes made on it (writing) and implement a warning that is triggered when said changes happen so that the user may take the necessary precautions.




what is File-Integrity-Monitor ?





why we need it ?

#### Hashing Algorithms :

 Or a cryptographic hash function is an algorithm that takes an arbitrary amount of data input and produces a fixed-size output of enciphered text called a hash value, or just “hash.” That enciphered text can then be stored instead of the password itself, and later used to verify the user in the most basic cases.
 
 1- Hashes are non-reversible. it is very hard to find the original password from the output r hash
 2- Diffusion, the slightest ofr changes to the input will produce an entirely different output, this making it harder 
 3- Determinism, a given input must always  produce the samen hash value 
 4- Collision resistance. it should be hard to find two different passwords that hash to the same enciphered text 
 5- Non predictable, the hash value should not be predictable from the input .
 
 There are many hashing algorithm,I will use the MD5 OR sha256 even if its collision resistance is weak and not secure or (sha256 if I sdudy its because it more secure)
 


    
   


 

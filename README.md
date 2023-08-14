# Blockchain-summer-course
This repository contains the materials of Blockchain &amp; Web3 course at the University of Tehran ACM Chapter Summer School 2023.

## Phase 1: Introduction to cryptography
The objective of this assignment is to gain practical experience in implementing symmetric and asymmetric cryptography techniques, as well as hash functions, using Python programming.      
     
### StoryLine:
We have **TinTin** and **Haddock** on two seperate islands and they want to send messages to each other using morse codes!!   
However, there is a problem over there. **Roberto Rastapopoulos** (Their enemy!) is listening to their conversation to figure out what they are saying to each other!

![logo-tintin-1 (2)](https://github.com/UT-ACM-Student-Chapter/Blockchain-summer-course/assets/88896798/17b925b5-5fdf-4992-a927-2109663e1180)

Now TinTin wants to use some encryption and decryption techniques to ensure that Roberto couldn't understand what they are saying. Help TinTin to acheive his goal! 


### Part 1: Symmetric Cryptography
TinTin decided to design a symmetirc encryption scheme for his connection with haddock. He asked you to design it for him using these steps:     

In all steps, use AES-128 encryption method for encryption/decryption. You can use python cryptography libraries for this purpose.    
1. Write a function to which gives an input message and a secret key for encryption.     
2. Encrypt this [confidential message](https://github.com/UT-ACM-Student-Chapter/Blockchain-summer-course/blob/main/CA1/Confidential-Message.txt) using a random key and display the encrypted result.     
3. Implement a decryption function that takes the encrypted message and the secret key as input and decrypts the message.     
4. Verify the correctness of the decryption process by comparing the original message with the decrypted message.


### Part 2: Asymmetric Cryptography
After TinTin found how to use symmetric encryption using a key, he faced another problem! How to share a key with haddock without letting Roberto finds it? Therefore, he decides to use an asymmetric crypto system. help him to acheive his goal by writing a program which:   

1. Generate a pair of RSA keys using a cryptography library.
2. Implement a program to encrypt a message using the public key and decrypt the message using the private key.
3. Allow the user to input a message and encrypt it using the public key.
4. Implement a decryption function that takes the encrypted message and decrypts it using the private key.
5. Verify the correctness of the decryption process by comparing the original message with the decrypted message.

### Part 3: Digital Signature
Now TinTin wants to send a message without encryption to haddock, to trick roberto :)    
However, he wants to show haddack that the sender of thsese tricky messages is TinTin, and inform haddock to ignore this type of messages. In order to capture this goal, TinTin wants to sign these messages and send the signs beside each message. Help him to do that by coding:     

1. Write a function to sign a given message in the text file (Confidentail message) using private key which was made in the part 2.     
   You have to **sign the hash of the message**, not the whole message (why?). (Use SHA-256 for hashing)
2. Write a function to verify a message with its signature.


## Submission Guidelines:
- Donwload the [notebook](https://github.com/UT-ACM-Student-Chapter/Blockchain-summer-course/blob/main/CA1/CryptoGraphy-CA.ipynb) file from this link, and complete your code on this notebook. You have to install [jupyter notebook](https://jupyter.org/install) and [python](https://www.python.org/downloads/) on your system.     
- Provide well-commented Python code for each part of the assignment.
- Include explanations for the design choices you made in terms of algorithms and libraries.
- Write a report summarizing the concepts of symmetric and asymmetric cryptography, hash functions, and their practical applications.
- Include screenshots or examples of the program in action for each part.

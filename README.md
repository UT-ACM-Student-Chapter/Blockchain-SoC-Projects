# Blockchain-summer-course
This repository contains the materials of Blockchain &amp; Web3 course at the University of Tehran ACM Chapter Summer School 2023.

Designers & Instructors:    
* [Alireza Arbabi](https://github.com/Alireza-Zwolf)       
* [AmirPasha Motamed](https://github.com/aamirpashaa)     
     

## Phase 1: Introduction to cryptography
The objective of this assignment is to gain practical experience in implementing symmetric and asymmetric cryptography techniques, as well as hash functions, using Python programming.      

     
### StoryLine:
We have **TinTin** and **Haddock** on two seperate islands and they want to send messages to each other using morse codes!!   
However, there is a problem over there. **Roberto Rastapopoulos** (Their enemy!) is listening to their conversation to figure out what they are saying to each other!

![logo-tintin-1 (2)](https://github.com/UT-ACM-Student-Chapter/Blockchain-summer-course/assets/88896798/17b925b5-5fdf-4992-a927-2109663e1180)

Now TinTin wants to use some encryption and decryption techniques to ensure that Roberto couldn't understand what they are saying. Help TinTin to achieve his goal! 


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

1. Write a function to sign the given message in the text file (confidentail message) using private key which was made in the part 2.     
   You have to **sign the hash of the message**, not the whole message (why?). (Use SHA-256 for hashing)
2. Write a function to verify a message with its signature.

## Phase 2: Interaction with Bitcoin
The goal of this assignment is to allow students to interact with the Bitcoin network and gain practical experience in broadcasting transactions. This hands-on experience will help them understand how Bitcoin transactions work, the role of network nodes and miners, and the decentralized nature of the blockchain.

![image](https://github.com/UT-ACM-Student-Chapter/Blockchain-SoC-Projects/assets/88896798/26f0e560-1c5a-4d06-aba4-5ce4fe2996e2)


### StoryLine:
After mastering the fundomentals of cryptography during his adventures, TinTin's insatiable curiosity led him down a new path: the world of cryptocurrencies. Fascinated by the potential of digital currencies like Bitcoin, he delved deeper into the intricate world of blockchain technology.

### Part 1: Generating an address
In this part of the assignment, our goal is to utilize cryptography libraries to generate Bitcoin addresses. This involves applying cryptographic techniques to create secure and unique identifiers for Bitcoin transactions, ensuring the security and privacy of the digital currency system. Generating Bitcoin addresses is a fundamental step in understanding the principles of blockchain technology and cryptocurrency transactions.

### Part 2: Simple transfer
The primary objective of this assignment section is to facilitate an understanding of Bitcoin transactions through practical implementation using the <strong>python-bitcoinlib</strong> library. By creating simple Bitcoin transfers, we aim to delve into the intricate workings of transactions, including how they are structured, signed, and how Bitcoin scripts are organized within outputs. This hands-on approach will empower learners to gain insight into the inner workings of the Bitcoin network, offering a deeper comprehension of the blockchain's mechanics and the role of cryptographic signatures in securing transactions. Ultimately, this exercise will equip participants with valuable knowledge about the core principles of Bitcoin's transaction processing, enhancing their cryptocurrency expertise.

### Part 3: Multisig Transfer
The primary objective of this assignment section is to delve into more advanced Bitcoin transfers, specifically exploring Multisignature (Multisig) transactions, and comparing them with the traditional Pay-to-Public-Key-Hash (P2PKH) scripts. By engaging in the creation and analysis of Multisig transactions, participants will gain a deeper understanding of the intricate nuances of Bitcoin's scripting capabilities. This advanced exercise aims to showcase the enhanced security and flexibility offered by Multisig, where multiple signatures are required to authorize a transaction, as opposed to the simpler P2PKH approach. Through hands-on experience, learners will discern the differences, advantages, and potential use cases of these diverse scripting methods, ultimately broadening their comprehension of Bitcoin's versatile functionality.


## Submission Guidelines:
- Donwload the [Phase1 Notebook](https://github.com/UT-ACM-Student-Chapter/Blockchain-summer-course/blob/main/CA1/CryptoGraphy-CA.ipynb) and [Phase2 Notebook](https://github.com/aamirpashaa/Blockchain-summer-course/blob/main/CA2/Bitcoin-CA.ipynb) files from these links, and complete them. You have to install [jupyter notebook](https://jupyter.org/install) and [python](https://www.python.org/downloads/) on your system.     
- Provide well-commented Python code for each part of the assignment.
- Include explanations for the design choices you made in terms of algorithms and libraries.
- Write a report summarizing the concepts of symmetric and asymmetric cryptography, hash functions, and their practical applications.
- Include screenshots or examples of the program in action for each part.

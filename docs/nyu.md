```yaml
Instructor: Giovanni Di Crescenzo
Institute: NYU
Reference:
  - KL: Katz, Lindell. Introduction to Modern Cryptography
  - MOV: Menezes, Oorschot, Vanstone. Handbook of Applied Cryptography
Code: CS-GY 6903
Stream: Cybersecurity
Level: Graduate
Semester: 3 (Fall)
Year: 2024-2025
```

# Applied Cryptography

## Homework 1

## Homework 2


Lecture 2 focuses on key ideas in algorithms, complexity theory, and modern
cryptography. It starts by explaining how we measure the size of inputs (like
how many bits are needed) and how long algorithms take to run (running time).
There are two types of running times: worst-case (longest time) and average-case
(how long it usually takes). It introduces Big-O notation to describe the growth
of running time as inputs get larger.

The lecture talks about one-way functions, which are easy to
compute but hard to reverse. These are important for secure systems like
public-key cryptography. It also introduces trapdoor functions, which are like
one-way functions, but with a secret key (trapdoor) that allows someone to
reverse the process easily. These functions help in encrypting messages
securely.

The lecture covers P vs NP, a major problem in computer science. P is the set of
problems that can be solved quickly by a computer, while NP is the set of
problems that can be verified quickly if you have the right answer. The lecture
also discusses how modern cryptography uses hard problems from NP to create
secure encryption systems. Finally, it talks about implementation challenges,
like balancing between security and efficiency.

## Homework 5

Module 5 of CS 6903 focuses on symmetric encryption, a method where the same
key is used for both encryption and decryption. The lecture introduces
Indistinguishability under Chosen Message Attack (IND-CMA), which is an
important security goal in encryption. An encryption scheme achieves IND-CMA if
an attacker can't distinguish between two encrypted messages even after making
multiple queries to the encryption system. The module explains how block
ciphers like AES and DES work. These ciphers break messages into
fixed-size blocks and encrypt each block with a key.

It also covers the structure of block ciphers, focusing on
Substitution/Permutation Networks (SPN) and Feistel Networks, which are
used in AES and DES, respectively. SPNs mix and substitute data to make it more
secure, while Feistel networks use multiple rounds of encryption to ensure the
data is hard to break.

The lecture also discusses attacks like the meet-in-the-middle attack,
differential cryptanalysis, and linear cryptanalysis, which target
weaknesses in block ciphers. Finally, it covers modes of operation like
ECB, CBC, OFB, and CTR, which describe how block ciphers can be
applied to encrypt larger messages. These modes balance security and efficiency,
with some being more secure against certain types of attacks.

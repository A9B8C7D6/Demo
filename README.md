# README for InLab 2

| Name             | Roll number |
| ----             | ----------- |
| Anand Narasimhan | 210051001   |

## About the repository

This repository is part of a lab in which we were required to learn about **bash**, **git** and **markdown**. These repositories, in partiular, tested our skills with git, by asking us to implement different types of hash functions mapping a *string* to a *number*. The first hash function just added all the characters in the string and took the remainder with respect to 3, which was the next prime after 01, the last two digits of my roll number. The second used **polynomial accumulation**, with the remainder being wrt 3 and the polynomial being wrt 101, which was the next prime after 98 (99 - 1). 

$hash_1(s) = \sum_{i} s[i] \mod m $

$hash_2(s) = \sum_{i} s[i] p^i \mod m $

## To run the files

To run the files, just execute `test.sh` with one command line argument, which is the string that gets hashed. 

## Question 1

For Question 1, the two aliases were `alias sizeOfFiles='du -ah'` and `alias numberOfFiles='du -ah | wc -l'`

https://www.markdownguide.org/extended-syntax/#tables
https://stackoverflow.com/ (Too many links to show)
https://docs.github.com/en/get-started/

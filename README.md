RSA Factoring Challenge
Overview
By: Julien Barbier
Weight: 1
Project Duration: Dec 10, 2023, 7:00 PM - Dec 22, 2023, 7:00 PM
Auto QA Review: 0.0/0 mandatory & 0.0/123 optional
Altogether: 0.0%
Mandatory: No mandatory tasks
Optional: 0.0%

Background Context
Before diving into the details, consider setting the mood by starting this [song](insert link to song) in the background.

We've intercepted communication on an unsecured network containing numbers used to encrypt critical documents. It appears that these numbers may not always be generated with sufficiently large prime numbers. Your mission, should you choose to accept it, is to factorize these numbers as quickly as possible before the target fixes this vulnerability, enabling us to decode the encrypted documents.

This project is entirely optional. Participating in any part of this project will add a project grade of over 100% to your average. While your score won't be affected if you choose not to participate, if your current average is higher than your score on this project, your average might decrease. Have fun!

Resources
Read or watch:

[RSA](insert link)
[How does HTTPS provide security?](insert link)
[Prime Factorization](insert link)
[Why RSA?](insert link)
Requirements
General:

Choose the programming language of your preference.
Operating System needs to be Standard Ubuntu 20.04 LTS.
Tasks
0. Factorize all the things!
#advanced
Score: 0.0% (Checks completed: 0.0%)

Factorize as many numbers as possible into a product of two smaller numbers.

Usage:

bash
Copy code
factors <file>
<file> is a file containing natural numbers to factor.
One number per line.
All lines will be valid natural numbers greater than 1.
No empty lines, and no space before and after the valid number.
The file will always end with a new line.
Output format: n=p*q (one factorization per line).
p and q don’t have to be prime numbers.
Example:

bash
Copy code
cat tests/test00 
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
bash
Copy code
time ./factors tests/test00
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773
Repo:

GitHub repository: [RSA-Factoring-Challenge](insert link)
File: factors
1. RSA Factoring Challenge
#advanced
Score: 0.0% (Checks completed: 0.0%)

RSA Laboratories states that for each RSA number n, there exist prime numbers p and q such that n = p × q. The challenge is to find these two primes, given only n.

This task is the same as Task 0, except:

p and q are always prime numbers.
There is only one number in the files.
How far can you go in less than 5 seconds?

Read: [RSA Factoring Challenge](insert link)

Example:

bash
Copy code
cat tests/rsa-1
6
bash
Copy code
./rsa tests/rsa-1
6=3*2
Repo:

GitHub repository: [RSA-Factoring-Challenge](insert link)
File: rsa

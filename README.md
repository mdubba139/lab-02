# Lab 2
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- team member 1 Michael Wasson

Please keep in mind that my answers for the server questions relied on research from  stackoverflow and IBM.com. I needed documentation for questions about parameter, return types
etc.

## Lab Question Answers

Answer for Question 1: When I added 50% loss to my local environment (UDP), only about half the numbers that I sent to the UDP server were recieved.

Question 2: Meanwhile, after adding 50% loss to local environment while using TCP, all the numbers that I sent over to the TCP server were recieved.

Question 3: The speed of UDP was always very fast. TCP became much slower after adding 50% loss. I suspect that this is because packets had to keep being resent since some were failing to reach the TCP server on their first try. 

...

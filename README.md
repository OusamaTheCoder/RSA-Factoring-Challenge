## RSA Factoring Challenge

This project involves factorizing numbers to decrypt encrypted documents. Here's a quick overview:

### Background Context

Before diving into the project, start with the mood-setting song provided. The task involves sniffing an unsecured network to find numbers used in encrypting crucial documents. It appears that these numbers may not always be generated using sufficiently large prime numbers. The mission is to factorize these numbers as quickly as possible before the target fixes the encryption bug.

### Resources

Before starting the project, familiarize yourself with the following topics:

- RSA
- HTTPS security mechanism
- Prime factorization concepts
- Importance of RSA encryption

### Requirements

#### General

- Choose a programming language of your choice.
- Operating System requirement: Standard Ubuntu 20.04 LTS.

#### Tasks

**Task 0: Factorize all the things!**

Factorize as many numbers as possible into a product of two smaller numbers. Here are the details:

- **Usage**: `factors <file>`
  - `<file>`: a file containing natural numbers to factorize.
  - Each number should be on a separate line.
- Output format: `n=p*q` where `p` and `q` are factors.
- You can work on the numbers in any order.
- Your program should run without any external dependencies.
- Time limit: 5 seconds.
- Push your scripts, source code, etc., to your repository.

Example:

```bash
./factors testfile
```

**Task 1: RSA Factoring Challenge**

This task is similar to Task 0, with the difference that `p` and `q` are always prime numbers, and there's only one number in each file.

Example:

```bash
./rsa rsa-1
```

### Repository

- GitHub repository: [RSA-Factoring-Challenge](https://github.com/OusamaTheCoder/RSA-Factoring-Challenge)
- File for Task 0: `factors`
- File for Task 1: `rsa`

This project is entirely optional and will significantly boost your project grade if completed successfully. Enjoy the challenge!

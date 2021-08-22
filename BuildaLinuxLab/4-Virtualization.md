# Virtualization
##  [Register for the Free Course Today!](https://roppers.thinkific.com/courses/computing-fundamentals)
## Introduction
Building your own home lab is important for a lot of reasons, but most importantly it is fun and teaches you a bunch of valuable information. In this section we will install a virtual machine for us to work on. What you will be making is uniquely yours and will be something that you will work on and refine for the rest of your time doing the computers. This is your new workbench/hangout spot, so take pride in what you are making and make it yours.

Before we start, first we will learn about Virtualization.

## Virtualization
Virtualization is when we run an operating system on top of another operating system. Using Virtualization software on the Host OS, the Guest OS or OSs are able to pass through to the Hosts hardware. By abstracting away from the hardware, it appears to the Guest OSs that they are all on their own dedicated machines.

[<img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Hardware_Virtualization.JPG">](https://en.wikiversity.org/wiki/IT_Fundamentals/2014/Virtualization)



Virtualization software is known as a hypervisor. Hypervisors are programs used for running and operating the Guest OSs, which we refer to as Virtual Machines. By allocating resources and controlling when they turn on and off, hypervisors allow fine-tuned control as well as built-in automatic functions which contribute to stability. There are two primary types of hypervisors; "bare-metal" and "hosted". Bare-metal hypervisors run directly on top of a server and act like their own OS, managing all the things an OS does. Hosted hypervisors are programs that run on an OS like Linux, and have the OS handle the responsibilities. Hypervisors are able to run as many OSs as the underlying hardware can support, which is usually limited by RAM. Modern computers should have enough RAM to host at least one VM, but dedicated cloud servers can host hundreds of VMs at a time.

## Benefits of Virtualization
The primary benefit of virtualization is the ability to share resources between multiple OSs, which allows us to have servers allocate resources as necessary. This is very beneficial for some server setups, as well as desktop users who need a different OS every once in a while.

Another benefit is that we can save a VM and easily transport it to another system and know that it will work when we turn it on. Because the hardware is abstracted there is no concern that we will have compatibility issues.

A third major benefit is that when we use a VM, we can be confident that we will not break the host environment with whatever we do in there. That means we can do whatever we want, like play around with malware or delete important files, and when we are done we can turn off the VM and revert back to its original state.


## Assignment

Please respond in the format from the last assignment I demoed. The point of this assignment, and the format I ask you to respond in, is to teach you the thought processes you need to ingrain, along with stopping you from trying to learn too much too quickly. Even better, in later sections it helps me figure out what you don't understand so I can modify the material for other students.

Write and answer the Pre-Questions that are required for you to understand your answer to the question that was asked. Only go one level deep into the rabbit hole, please, I have designed the course to only require one level deep max in order to confidently move forward.

I greatly appreciate your feedback on how this attempt at question and answer works for you, either in #feedback or the question response.


Some of these require Google.

```markdown
Questions:

1. What is virtualization?
2. Why do we use virtualization?
3. What is the difference between the Host and a Guest VM?
4. What is the difference between a container and a VM?
5. What is the difference between VMs and the cloud? (Trick question)


Resources:

1. Google

```

Write up a few sentences for each in the usual format.

```
 Pre-Questions:
1. (any questions you asked and had to solve in order to understand the question)

 Answers:

 1. (the actual answer to the question)

 Resources:
1.  (any helpful resources beyond what was given, especially if you had to google some of them)

 Post-Questions:
1. (any questions you still have that did not get answered)

 Feedback:
1. (any feedback on how the question was asked, the material, really anything)

```

##  [Click Here to Start Learning Today!](https://roppers.thinkific.com/courses/computing-fundamentals)
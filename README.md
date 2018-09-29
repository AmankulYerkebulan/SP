# SP

*  What is an operating system? What does it do? 

    Answer :ÊOperating system is a software that is responsible for making it easy to run programs  even allowing you to run many at the same time and allowing programs to share memory.
    Operating system manages the computer's memory and processes, as well as all of its software and hardware. It also allows you to communicate with the computer without knowing how to speak the computer's language.

*  What is virtualization? 
    Answer : Virtualization refers to running two or more operating systems on one physical PC.

*  How does an OS provide access to its features?Êyour answer goes here

*  What illusion does a virtualized CPU provide?Ê
    Answer: The virtual processor delivers the illusion that the system has a very large number of virtual CPUs.

* How does this affect the user experience?Ê
    Answer: Well-influenced. For example , if user wanted to run music and some textbook particular time, which should run ?  And for this virtualizations will help user.
    
* How does this affect the developer experience?Ê
    Answer: Each operation has memory which will saved in array in bytes. As the program runs, it slowly updates the value and prints out the result.

* What if the CPU were not virtualized?Ê
    Answer : If you wanted run two or many program, so you would wait when first program finished and then run other program and also would wait.
*  What is a memory address?Ê
    Answer: During program execution, each object such as a variable or an array is located somewhere in an area of memory. The location of an object in the memory is called its address.
    
*  What is memory virtualization?Ê
    Answer: Each virtual machine consumes memory based on its configured size, plus additional overhead memory for virtualization.
The configured size is a construct maintained by the virtualization layer for the virtual machine. It is the amount of memory that is presented to the guest operating system, but it is independent of the amount of physical RAM that is allocated to the virtual machine, which depends on the resource settings (shares, reservation, limit) explained below.

* Why would we want this?Ê
    Answer : For example, consider a virtual machine with a configured size of 1GB. When the guest operating system boots, it detects that it is running on a dedicated machine with 1GB of physical memory. The actual amount of physical host memory allocated to the virtual machine depends on its memory resource settings and memory contention on the ESXi host. In some cases, the virtual machine might be allocated the full 1GB. In other cases, it might receive a smaller allocation. Regardless of the actual allocation, the guest operating system continues to behave as though it is running on a dedicated machine with 1GB of physical memory.
    
*  What happens if you write a C/C++ program that writes past the end of an array?Ê
    Answer: It's undefined behavior, and anything can happen.
    The standard says that undefined behavior can mean anything, so you can't really have any expectations, not even with the same compiler.
* Can this affect other programs? Answer:ÊNever

*  What is a thread?
    ÊAnswer : A thread is the smallest unit of processing that can be performed in an OS. In most modern operating systems, a thread exists within a process - that is, a single process may contain multiple threads.
*  Why would we ever write a multi-threaded program?Ê
    Answer: When multiple threads are running concurrently, this is known as multithreading, which is similar to multitasking. Basically, an operating system with multitasking capabilities allows programs (or processes) to run seemingly at the same time. On the other hand, a single program with multithreading capabilities allows individual sub-processes (or threads) to run seemingly at the same time.One example of multithreading is downloading a video while playing it at the same time. Multithreading is also used extensively in computer-generated animation.
    
*  What is atomicity?Ê
    Answer: Atomic operations in concurrent programming are program operations that run completely independently of any other processes. Atomic operations are used in many modern operating systems and parallel processing systems.
    * Is a C/C++ statement atomic?ÊAnswer : Yes
* Is a Java statement atomic? Answer:ÊIn general, no. Some are, but many are not
* Is an assembler statement atomic?ÊAnswer: Not always
*  What does persistence mean? Answer: Persistence,  is a noun describing data that outlives the process that created it.
*  How does OS hard drive virtualization differ from CPU & memory virtualization?Êyour answer goes here
*  How does running multiple programs at the same time increase CPU efficiency?Êyour answer goes here
*  What is multiprogramming?ÊAnswer : Multiprogramming is a rudimentary form of parallel processing in which several programs are run at the same time on a uniprocessor. Since there is only one processor, there can be no true simultaneous execution of different programs. Instead, the operating system executes part of one program, then part of another, and so on. To the user it appears that all programs are executing at the same time.


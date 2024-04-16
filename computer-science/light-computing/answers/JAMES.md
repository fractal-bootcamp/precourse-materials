# COMPUTING

## QUESTIONS

- What is a computer?
  - a computer is a machine that has some distinct hardware and software patterns. Historically a computer use to be a person, typically a woman, who made mathematical calculations. As automation started to happen these calculations were done by hardware and software systems. At the core of these hardware systems are switches or gates that can be in the open or closed position, aka a 0 or 1. As computers became more powerful these gates became smaller and smaller and now billions of these transistors are in each computational unit like a phone, laptop, desktop, gaming system or even car. The subsystems of a computer are the Central Processing Unit, the General Processing Unit, Random Access Memory, Battery, screen, keyboard and mouse for IO. ports for data access. On top of this hardware we have machine code or binary. the switches or transistors are put into groups of bits. 8 bits equals a byte and a byte is related to a character in an ASCII table. this machine code is able to manipulate and change these bytes into more complex data structures. On these sit the operating system that interacts with all of the hardware and software subsystems from the CPU to the GPU to the RAM and Hard Drive and is the orchestrator. On this OS sits applications like the browser that allows us to interact with the internet and other applications like VS code and GIT.
  - update: A computer is an electronic device capable of performing complex calculations and tasks. It consists of both hardware and software components. Hardware includes the Central Processing Unit (CPU), which acts as the brain; Random Access Memory (RAM), which stores data temporarily for quick access; and storage devices like SSDs for long-term data storage. Key peripherals include input/output devices like keyboards, mice, and monitors. At the most fundamental level, computers operate on binary data (0s and 1s), processed by transistors within the CPU.

    **Key Components:**
    - **CPU (Central Processing Unit)**: Executes instructions from software applications.
    - **RAM (Random Access Memory)**: Temporarily stores data that the CPU needs quick access to.
    - **Storage**: Holds data long-term, accessible by the computer's system when needed.


- What is an operating system?
  - an OS is a piece of software that is an orchestrator of all of a computers subsystems. see above.
  - update: OS is software that manages computer hardware and software resources and provides services for computer programs.
  - An operating system (OS) is system software that manages computer hardware, software resources, and provides common services for computer programs. Its primary tasks include managing memory, processing tasks, enforcing security, and handling input/output operations. The OS allows user applications to interact with the hardware without needing to know all the details of the hardware.

    **Examples:**
    - **Windows**, **macOS**, and **Linux** are among the most popular operating systems.


- What is a runtime?
  - I believe a runtime is a complex call stack of operations that are ordered to be processed by the computer. we can't run all of our operations at the exact same time so the runtime allows us to prioritize those operations to maximize the output of our computer's resources.
  - update: runtime is the environment in which a program or application executes including software services that help execute the program.
  - A runtime, or runtime environment, refers to the state of an operating system that allows a software program to execute. It provides programming libraries and a platform-specific execution environment for the software. The runtime handles the program's operations, managing memory allocation, and other system states.

    **Example:**
    - **Java Runtime Environment (JRE)** allows Java programs to run on different operating systems without modification.


- What is memory? RAM? CPU?
  - memory is a data store. we have a few different types of memory locally, the Random Access Memory for shorter term data persistence and the Hard Drive that could be a disk, magnetic tape or even solid state memory for faster read/write times. CPU is the Central Processing Unit. It's an amazingly complex chip that is the central "brain" of a computer that organizes and manages all of the other subsystems.
  - Memory in computing refers to the components or devices that store data. **RAM (Random Access Memory)** is volatile memory used to store data temporarily while a computer is running; it allows data to be accessed quickly by the CPU. The **CPU (Central Processing Unit)** is the primary component of a computer that interprets and executes instructions from hardware and software.

    **Key Points:**
    - **RAM**: Used for storing operating system, application programs, and data currently in use.
    - **CPU**: Processes instructions, manages operations within the computer, and performs input/output operations.


- What is a thread? What is a process?
  - a thread is a resource dedicated to completing a single operation from start to finish. a process is a batch of commands for the computer to execute before starting another thread of operation.
  - A thread is the smallest unit of processing that can be scheduled by an operating system. A process is a program in execution, which contains one or more threads. Threads within the same process share resources like memory and process state, while each thread includes its own program counter and stack.

    **Technical Insight:**
    - Multiple threads can exist within one process, executing concurrently and sharing resources such as memory, yet operating independently.


- What is a browser?
  - a browser is an application that sit on the operating systems and requests resources from the CPU to provide operation on behalf of the user operating the computer with the primary purpose of interacting with data requested and responded through the internet to a server or controller. We primarily use human readable domains, but these are resolved through DNS servers to IP addresses so we can make a request to a specific computer. the browser recieves the response from the server and then renderes the data for the user in the UI. A primary function of most browser applications is the event loop which is a way to manage resources, requests and repsonses. One of the first browsers what netscape navigator by Marc Andreson and was the birth of the JavaScript language.
  - A browser is a software application used to access and view websites on the internet. It requests information from a server using HTTP or HTTPS, interprets web pages coded in HTML, CSS, and JavaScript, and renders them for user interaction.

    **Core Functions:**
    - **Rendering Engine**: Converts HTML and CSS into visible content.
    - **JavaScript Engine**: Executes JavaScript code to make web pages interactive.

    **Historical Insight:**
    - Netscape Navigator was one of the first web browsers to popularize the internet, leading to innovations such as JavaScript.


## RESOURCES

- Threads and Processes
  https://learn.microsoft.com/en-us/windows/win32/procthread/about-processes-and-threads

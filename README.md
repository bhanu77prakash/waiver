As mentioned in the email, since our program includes computer engineering aspect, we had a rigorous curriculum which included the following courses. I have mentioned detailed syllabus of each of the courses mentioned below and also the reference material used for the courses. 

Courses completed in the Systems area:  
<i>In <b>each and every</b> course mentioned below, I have received an <b>Excellent grade - top 10% of the course</b></i>
1. [CS21002 SWITCHING CIRCUITS AND LOGIC DESIGN](#switch)   
	 - An introductory course covering the basics needed for our CS31001 COMPUTER ORGANIZATION AND ARCHITECTURE course (which is similar to the 15-513 offered at CMU). The course covered all the logic gates and sequential circuits both at theory and implementation level. 
2. [CS29002 SWITCHING LABORATORY](#switchlab) 
	 - A laboratory course that covers the practical implementation of the above mentioned course. Using all the concepts that we have learnt, we have designed a complete digital clock using breadboards in this lab.
3. [CS31001 COMPUTER ORGANIZATION AND ARCHITECTURE](#coa)
	 - An in-depth course covering the basic blocks of a CPU; complete arithmetic logic unit (ALU) - theory and design; instruction set architectures (ISA) - RISC in MIPS and CISC; memory system design - RAM, CACHE, ROMs; input and output device handling.
4. [CS39001 COMPUTER ORGANIZATION LABORATORY](#coalab) 
	 - A rigorous lab component for writing assembly language code; writing VERILOG code for the ALU and deploying it on FPGA IC board; i/o interfacing; etc. I have uploaded some of the verilog codes (many of them are written in the lab computers) and assembly codes in this repo. 
5. [CS30003 Compilers](#comp)
	 - An in-depth course that covered a wide range of topics in C compiler. Covered lexical, sytax, semantic analyses, symbol tables, registers, run-time environments and intermediate codes etc. 
6. [CS39003 Compilers lab component](#complab)
	 - Another rigorous lab that covered all the components of a compiler. Through step by step assignments, we have completed a mini C compiler. 
7. [CS30002 OPERATING SYSTEMS](#os)
	 - Started with understanding the kernel, process management, scheduling, context switches and proceeded to learning about resource allocaiton, threads, concurrency, and deadlocks. Further covered the paging, cache, virual and physical memory management systems, file management. 
8. [CS39002 OPERATING SYSTEMS LABORATORY](#oslab)
	 - Implemented system calls for both process creation and management, functionalites of a shell, implemented shared memory, simulated CPU scheduling algos and threads, implemented memory resident unix-like file system and finally a complete memory management system. Uploaded the assignment descriptions here 
9. [CS40001 COMPUTER NETWORKS](#nets)
	 - This course covered all the network layers in a top-down approach; started with the application layer protocols HTTP, FTP, POP and IMAP, transport services, TCP/IP, UDP protocols, IP addressing, internet routing - DVR, Bellman Ford, LSR, BGP protocols, router architecture, Quality of service, data link layer - STP, Error correction, channel allocation etc. 
10. [CS49001 NETWORKS LABORATORY](#netslab)
	 - Introduced us to the Wireshark tool for analysing the network; moved to a step by step development of a protocol similar to the QUIC protocol; used the developed protocol for implementing a concurrent file server and p2p messaging platform; ended the lab with a blockchain implementation as part of lab evaluation. 
11. [CS43304 DATABASE MANAGEMENT SYSTEMS](#dbms)
	 - An in-depth course about the databases. Started with the relational query language, ER relationships and diagrams, database architecture, query and transaction processing, storage strategies and data warehousing. 
	 - Included a lab component where we extensively explored the SQL language, developed a smart mess management system using databases for both web (php,html) and mobile (android studio) platforms. 

Here is a detailed syllabi of the above mentioned courses.  
<i>Main references for each course are italicized</i>

1.	### <a href="switch"></a>CS21002 SWITCHING CIRCUITS AND LOGIC DESIGN - I have got an Excellent grade (top 10% of the course)
	1. Switching Circuits: Logic families: TTL, nMOS, CMOS, dynamic CMOS and pass transistor logic (PTL) circuits, inverters and other logic gates, area, power and delay characteristics, concepts of fan-in, fan-out and noise margin.
	2. Switching theory: Boolean algebra, logic gates, and switching functions, truth tables and switching expressions, minimization of completely and incompletely specified switching functions, Karnaugh map and Quine-McCluskey method, multiple output minimization, representation and manipulation of functions using BDD's, two-level and multi-level logic circuit synthesis.
	3. Combinational logic circuits: Realization of Boolean functions using NAND/NOR gates, Decoders, multiplexers. logic design using ROMs, PLAs and FPGAs. Case studies.
	4. Sequential circuits: Clocks, flip-flops, latches, counters and shift registers, finite-state machine model, synthesis of synchronous sequential circuits, minimization and state assignment, asynchronous sequential circuit synthesis.
	5. ASM charts: Representation of sequential circuits using ASM charts, synthesis of output and next state functions, data path control path partition-based design.

2. ### <a href="switchlab"></a>CS29002 SWITCHING LABORATORY - I have got an Excellent grade (top 10% of the course)
	1. Pulse Circuits: Bistable, astable and monostable MVs and Schmitt Triggers using transistors, OP Amps and 555 timers.
	2. TTL and CMOS Gates: Study the characteristics of TTL and MOS gates.
	3. Combinational logic circuits: Design and implementation of combinational circuits such as ALU and 7-segment LED display driver.
	4. Sequential Circuits: Design of sequence generators and detectors, counters, design of ASMs such as, traffic light controllers, lift controllers, etc.
	5. At the end of this laboratory, we have implemented a complete Digital Clock. 
	6. References
		1. <i>Z. Kohavi, Switching and Finite Automata Theory, Tata McGraw-Hill.</i>
		2. H. Taub and D. Schilling, Digital Integrated Electronics, McGraw-Hill.
		3. Randy H. Katz and Gaetano Borriello, Contemporary Logic Design, Prentice Hall of India.
		4. Giovanni De Micheli, Synthesis and Optimization of Digital Circuits, Tata McGraw-Hill.

3.	### <a href="coa"></a>CS31001 COMPUTER ORGANIZATION AND ARCHITECTURE 	- I have got an Excellent grade (top 10% of the course) - This is very similar to the 15-513 course offered by CMU.
	1. Basic functional blocks of a computer: CPU, memory, input-output subsystems, control unit. Instruction set architecture of a CPU - registers, instruction execution cycle, RTL interpretation of instructions, addressing modes, instruction set. Case study - instruction sets of some common CPUs.
	2. Data representation: signed number representation, fixed and floating point representations, character representation. Computer arithmetic - integer addition and subtraction, ripple carry adder, carry look-ahead adder, etc. multiplication - shift-and-add, Booth multiplier, carry save multiplier, etc. Division - non-restoring and restoring techniques, floating point arithmetic.
	3. CPU control unit design: hardwired and micro-programmed design approaches, Case study - design of a simple hypothetical CPU.
	4. Memory system design: semiconductor memory technologies, memory organization.
	5. Peripheral devices and their characteristics: Input-output subsystems, I/O transfers - program controlled, interrupt driven and DMA, privileged and non-privileged instructions, software interrupts and exceptions. Programs and processes - role of interrupts in process state transitions.
	6. Performance enhancement techniques
		1. Pipelining: Basic concepts of pipelining, throughput and speedup, pipeline hazards.
		2. Memory organization: Memory interleaving, concept of hierarchical memory organization, cache memory, cache size vs block size, mapping functions, replacement algorithms, write policy.

4.	### <a href="coalab"></a>CS39001 COMPUTER ORGANIZATION LABORATORY - I have got an Excellent grade (top 10% of the course) - Again similar to the assignment of the 15-513 course offered by CMU
	1. Familiarization with assembly language programming.
	2. Synthesis/design of simple data paths and controllers, processor design.
	3. Interfacing - DAC, ADC, keyboard-display modules, etc.
	4. Development kits as well as Microprocessors/PCs may be used for the laboratory, along with design/simulation tools as and when necessary.
	5. References
		1. <i>David A. Patterson and John L. Hennessy, Computer Organization and Design: The Hardware/Software Interface, Elsevier.</i>
		2. <i>John P. Hayes, Computer Architecture and Organization, McGraw Hill.</i>
		3. Carl Hamachar, Zvonco Vranesic and Safwat Zaky, Computer Organization, McGraw Hill.
		4. William Stallings, Computer Organization and Architecture: Designing for Performance, Pearson Education.
		5. Vincent P. Heuring and Harry F. Jordan, Computer Systems Design and Architecture, Pearson Education.

5.	### <a href="comp"></a>CS30003 Compilers - I have got an Excellent grade ()
	1.	Introduction: Phases of compilation and overview.
	2.	Lexical Analysis (scanner): Regular language, finite automata, regular expression, from regular expression to finite automata, scanner generator (lex,flex).
	3.	Syntax Analysis (Parser): Context-free language and grammar, push-down automata, LL(1) grammar and top-down parsing, operator grammar, LR(O), SLR(1), LR(1), LALR(1) grammars and bottom-up parsing, ambiguity and LR parsing, LALR(1) parser generator (yacc,bison)
	4.	Semantic Analysis: Attribute grammar, syntax directed definition, evaluation and flow of attribute in a syntax tree.
	5.	Symbol Table: Its structure, symbol attributes and management.
	6.	Run-time environment: Procedure activation, parameter passing, value return, memory allocation, and scope.
	7.	Intermediate Code Generation: Translation of different language features, different types of intermediate forms.
	8.	Code Improvement (optimization): Analysis: control-flow, data-flow dependence etc.; Code improvement local optimization, global optimization, loop optimization, peep-hole optimization etc. Architecture dependent code improvement: instruction scheduling (for pipeline), loop optimization (for cache memory) etc.
	9.	Register allocation and target code generation
	10.	Advanced topics: Type systems, data abstraction, compilation of object oriented features and non-imperative programming languages.

6.	### <a href="complab"></a>CS39003 Compilers lab component – I have got an Excellent grade (top 10% of the course)
	Familiarity with compiled codes (assembly language) of RISC and CISC machines, writing a scanner, writing predictive parser for a small language, small experiment with scanner (lex/flex) and parser (yacc/byson) generator (such as translation of regular expression to NFA or the construction or parse tree), writing scanner-parse specification for a small language, translation of the language to an intermediate form (e.g. three-address code), generation of target code (in assembly language). Code improvement (optional).  
	References
	1.	<i>Alfred V. Aho, Ravi Sethi, Jeffrey D. Ullman, Compilers: Principles, Techniques and Tools, Addison-Wesley.</i>
	2.	Michael L. Scott, Programming Language Pragmatics, Elsevier.
	3.	Andrew W. Appel, Modern Compiler Implementation in C/Java, Cambridge University Press.
	4.	Keith D. Cooper and Linda Torczon, Engineering a Compiler, Elsevier.
	5.	Allen I. Holob, Compiler Design in C, Prentice-Hall.
	6.	Steven S. Muchnik, Advanced Compiler Design and Implementation, Elsevier.
	7.	Randy Allen and Ken Kennedy, Optimizing Compilers for Modern Architectures, Elsevier.

7.	### <a href="os"></a>CS30002 OPERATING SYSTEMS  -  I have got an Excellent grade (top 10% of the course)
	1. Evolution of Operating Systems, Structural overview, Concept of process and Process synchronization, Process Management and Scheduling, Hardware requirements: protection, context switching, privileged mode; Threads and their Management; Tools and Constructs for Concurrency, Detection and Prevention of deadlocks, Dynamic Resource Allocation, Design of IO systems, File Management, Memory Management: paging, virtual memory management, Case Studies.

8.	### <a href="oslab"></a>CS39002 OPERATING SYSTEMS LABORATORY - I have got an Excellent grade (top 10% of the course)
	1. Familiarization with UNIX system calls for process management and inter-process communication
	2. Experiments on process scheduling and other operating system tasks through simulation/implementation under a simulated environment (like Nachos).
	3. References
		1. <i>William Stallings, Operating Systems: Internals and Design Principles, Prentice Hall of India.</i>
		2. <i>Avi Silberschatz, Peter Galvin, Greg Gagne, Operating System Concepts, Wiley Asia Student Edition.</i>
		3. D. M. Dhamdhere, Operating Systems: A Concept-Based Approach, Tata McGraw-Hill.
		4. Charles Crowley, Operating System: A Design-oriented Approach, Irwin Publishing.
		5. Gary J. Nutt, Operating Systems: A Modern Perspective, Addison-Wesley.
		6. Maurice Bach, Design of the Unix Operating Systems, Prentice-Hall of India.
		7. Daniel P. Bovet, Marco Cesati, Understanding the Linux Kernel, O'Reilly and Associates.

9.	### <a href="nets"></a>CS40001 COMPUTER NETWORKS - I have got an Excellent grade (top 10% of the course)
	1. Introduction to networks and layered architecture. 
	2. Data communication concepts, transmission media and topology, multiplexing. 
	3. Circuit switching and packet switching, data link layer, layer 2 switches and ATM switches, SONET/SDH. 
	4. Medium access control. CSMA CD, TDMA, FDMA, CDMA. Network layer and addressing, IP version 4 and 6. 
	5. Routing algorithms. Transmission layer, TCP and UDP. Congestion control techniques. WAN, ATM. Internetworking. Wireless communications. Network management and security.

10.	### <a href="netslab"></a>CS49001 NETWORKS LABORATORY - I have got an Excellent grade (top 10% of the course)
	1. Simulation experiments for protocol performance, configuring, testing and measuring network devices and parameters/policies; network management experiments; Exercises in network programming.
	2. Implemented a complete end to end QUIC protocol based concurrent file server and peer to peer messaging platform. 
	3. References
		1. <i>Andrew S. Tanenbaum, Computer Networks, Prentice Hall.</i>
		2. <i>Computer Networking: A Top - Down Approach, by James Kurose, Keith Ross</i>
		3. Behrouz A. Forouzan, Data Communication and Networking, McGraw-Hill.
		4. William Stallings, Data and Computer Communication, Prentice Hall of India.
		5. Douglas Comer, Internetworking with TCP/IP, Volume 1, Prentice Hall of India.
		6. W. Richard Stevens, TCP/IP Illustrated, Volume 1, Addison-Wesley.

11.	### <a href="dbms"></a>CS43304 DATABASE MANAGEMENT SYSTEMS - I have got an Excellent grade (top 10% of the course) - Has lab component as well. 
	1. Database system architecture Data Abstraction, Data Independence, Data Definition and Data Manipulation Languages.
	2. Data models Entity-relationship, network, relational and object oriented data models, integrity constraints and data manipulation operations.
	3. Relational query languages Relational algebra, tuple and domain relational calculus, SQL and QBE.
	4. Relational database design Domain and data dependency, Armstrong's axioms, normal forms, dependency preservation, lossless design.
	5. Query processing and optimization Evaluation of relational algebra expressions, query equivalence, join strategies, query optimization algorithms.
	6. Storage strategies Indices, B-trees, hashing.
	7. Transaction processing Recovery and concurrency control, locking and timestamp based schedulers, multiversion and optimistic Concurrency Control schemes.
	8. Advanced topics Object-oriented and object relational databases, logical databases, web databases, distributed databases, data warehousing and data mining.
	9. Laboratory
		1.Database schema design, database creation, SQL programming and report generation using a commercial RDBMS like ORACLE/SYBASE/DB2/SQL-Server/INFORMIX. Students are to be exposed to front end development tools, ODBC and CORBA calls from application Programs, internet based access to databases and database administration.
	10. References
		1. <i>Abraham Silberschatz, Henry Korth, and S. Sudarshan, Database System Concepts, McGraw-Hill.</i>
		2. <i>J. D. Ullman, Principles of Database Systems, Galgotia.</i>
		3. Bipin Desai, An Introduction to Database Systems, Galgotia.
		4. Raghu Ramakrishnan, Database Management Systems, WCB/McGraw-Hill.
		5. R. Elmasri and S. Navathe, Fundamentals of Database Systems8, Addison-Wesley.
		6. Serge Abiteboul, Richard Hull and Victor Vianu, Foundations of Databases. Addison-Wesley.

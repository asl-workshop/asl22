### Advances in Separation Logics (ASL 2022)

The past two decades have witnessed important progress in static analysis and verification of code with low-level pointer and heap manipulations, mainly due to the development of Separation Logic (SL). The impact of SL is attested, in academia, by the Goedel Prize 2016 and the CAV Award 2016, as well as in industry, by the integration of SL-based analyses with software development at Facebook. SL is a resource logic, a dialect of the logic of Bunched Implications (BI) designed to describe models of the heap memory and the mutations that occur in the heap as the result of low-level pointer updates. The success of SL in program analysis is due to the support for local reasoning, namely the ability of describing only the resource(s) being modified, instead of the entire state of the system. This enables the design of compositional analyses that synthesize specifications of the behavior of small parts of the program before combining such local specifications into global verification conditions.

The expressivity of SL and, in general, of resource logics such as BI, comes with the inherent difficulty of automating the reasoning, most decision problems, such as satisfiability or entailment being undecidable. In spite of such theoretical hardships, recent results show that important fragments of SL are within elementary complexity classes. This progress hints at possible standardisations of automated or interactive theorem proving tools and techniques, the creation of benchmark libraries and the organization of competitions.

Another interesting line of work consists in finding alternatives to the underlying semantic domain of SL, namely heaps with aggregative composition, in order to address other fields in computing, such as self-adapting distributed networks, blockchain and population protocols, social networks or biological systems.

### Due to the ongoing Covid-19 and overall international situation, ASL 2022 will be organized as a virtual event. 

ASL 2022 is affiliated to [IJCAR 2022](https://easychair.org/smart-program/IJCAR2022/index.html) at [FLOC 2022](https://www.floc2022.org/). 

See detailed [program](https://easychair.org/smart-program/FLoC2022/ASL-index.html). 

As part of this workshop, we intend to organize a fourth edition of the [Separation Logic Competition (SL-COMP)](https://sl-comp.github.io) for solvers targeting fragments of Separation Logics.  

### Registration

* Virtual participation is free of charge but requires registration via this [link](https://asl2022.rsvpify.com/).

### Keynote Speakers

![](philippa-1.jpg) ***Philippa Gardner, Imperial College London***

***Exact Separation Logic***

***Abstract***: Over-approximating (OX) program logics, such as separation logic (SL),
are used to verify properties of heap-manipulating programs: all
terminating behaviour is characterised, but the reported results and
errors need not be reachable. OX function specifications are thus
incompatible with true bug-finding supported by symbolic execution
tools such as Pulse and Gillian. In contrast, under-approximating (UX)
program logics, such as incorrectness separation logic (ISL), are used
to find true results and bugs: reported results and errors are
reachable, but not all behaviour can be characterised. UX function
specifications thus cannot capture full verification. We introduce exact separation logic (ESL) for reasoning about
heap-manipulating sequential programs, which provides fully verified
function specifications compatible with true bug finding: all
terminating behaviour is captured in full, and all reported results
and errors are reachable.  ESL supports mutually recursive functions,
which require subtle definitions of internal and external function
specifications compared with the familiar definitions for OX logics.
We prove a frame-preserving soundness result for ESL, and ISL and SL,
thus demonstrating functional compositionality of UX reasoning. We
verify exact specifications of list algorithms using standard
inductive predicates, observing the difference between abstraction
which hides information and OX reasoning which looses information.  We
introduce a symbolic execution semantics that can call functions with
ESL specifications, and prove a backwards completeness result that
demonstrates that verified ESL function specifications are indeed
compatible with true bug-finding.



![](ralf-2.jpg) ***Ralf Jung, MIT CSAIL*** 

***Functional correctness specifications for concurrent data structures:
Logical Atomicity in Iris*** ![](ralf-slides.pdf)

**Abstract**: Concurrent separation logic (CSL) has demonstrated that separation logic is
exceptionally well-suited for reasoning about concurrent programs. However, CSL
on its own is not able to express and exploit the desired notion of functional
correctness for concurrent data structures: linearizability. While CSL is
regularly employed to *prove* linearizability, linearizability is an
extra-logical notion: when working inside the separation logic, there is no way
to make *use* of the fact that some data structure is linearizable. Therefore, the TaDA paper in 2014 proposed a new style of specifying concurrent
data structures: *logically atomic Hoare triples*. These triples provide a
simple way to turn a specification of a sequential data structure (say, a stack)
into a concurrent variant of the same specification, stipulating that each
operation must "behave atomically". This enables clients of logically atomic
triples to make use of the "invariant rule", a key proof rule in CSL to reason
about an atomic step of execution. In this talk, I will explain how logically
atomic triples are used in Iris to specify and verify concurrent data structures
as well as clients of these data structures. I will also show how logically
atomic triples are defined inside the Iris program logic by composing
lower-level logical primitives.

### Committees

*Program Committee*

 - Nadia Polikarpova (UCSD, San Diego, USA)
 - James Brotherston (UCL, London, UK)
 - Qinxiang Cao (Shanghai Jiaotong University)
 - Dan Frumin (University of Groningen, The Netherlands)
 - Lennart Beringer (Princeton University, USA) 
 - Arthur Charguéraud (INRIA Strasbourg, France)
 - Radu Iosif (Verimag, CNRS, Univ. Grenoble Alpes, France)
 - Le Quang Loc (UCL, London, UK)
 - Alessio Mansutti (University of Oxford, UK)
 - Christoph Matheja (DTU, Lyngby, Denmark)
 - Daniel Méry (University of Loraine, France)
 - Koji Nakazawa (Nagoya University, Japan)
 - Nicolas Peltier (LIG, CNRS, Grenoble, France)
 - Adam Rogalewicz (Brno University of Technology, Czech Republic)
 - Mihaela Sighireanu (LMF, ENS Paris-Saclay, France)
 - Florian Zuleger (Vienna University of Technology, Austria)
   
*Organizing committee*

 - Radu Iosif (Verimag, CNRS, Univ. Grenoble Alpes, France)
 - Nikos Gorogiannis (Meta, London, UK)
 - Robbert Krebbers (Radboud Univ. Nijmegen, The Netherlands)
 - Mihaela Sighireanu (LMF, ENS Paris-Saclay, France)
 - Makoto Tatsuta (NII, Tokyo, Japan)
 - Thomas Noll (RWTH, Aachen, Germany)

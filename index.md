# ASL 2022 

*Advances in Separation Logic is a workshop affiliated to [IJCAR 2022](https://easychair.org/smart-program/IJCAR2022/index.html) at [FLOC 2022](https://www.floc2022.org/)*

## Context

The past two decades have witnessed important progress in staticanalysis and verification of code with low-level pointer and heap manipulations, mainly due to the development of SeparationLogic (SL). The impact of SL is attested, in academia, by the Goedel Prize 2016 and the CAV Award 2016, as well as in industry, by the integration of SL-based analyses with software development at Facebook. SL is a resource logic, a dialect of the logic of Bunched Implications (BI) designed to describe models of the heap memory and the mutations that occur in theheap as the result of low-level pointer updates. The success of SL in program analysis is due to the support for local reasoning, namely the ability of describing only the resource(s) being modified, instead of the entire state of the system. This enables the design of compositional analyses that synthesize specifications of the behavior of small parts of the program before combining such local specifications into global verification conditions.

The expressivity of SL and, in general, of resource logics such as BI, comes with the inherent difficulty of automating the reasoning, most decision problems, such as satisfiability or entailment being undecidable. In spite of such theoretical hardships, recent results show that important fragments of SL are within elementary complexity classes. This progress hints at possible standardisations of automated or interactive theorem proving tools and techniques, the creation of benchmark libraries and the organization of competitions.

Another interesting line of work consists in finding alternatives to the underlying semantic domain of SL, namely heaps with aggregative composition, in order to address other fields incomputing, such as self-adapting distributed networks, blockchain and population protocols, social networks or biological systems.



### Submission Guidelines

All papers must be original and not simultaneously submitted to another journal or conference.  We consider submissions on topics including:
  - decision procedures for SL and other resource logics,
  - computational complexity of decision problems such as satisfiability, entailment and abduction for SL and other resource logics,
  - axiomatisations and proof systems for automated or interactive  theorem proving for SL and other resource logics,
  - verification conditions for real-life interprocedural and  concurrent programs, using SL and other resource logics,
  - alternative semantics and computation models based on the notion  of resource,
  - application of separation and resource logics to different  fields, such as sociology and biology.

We consider **short papers up to 8 pages** and **regular papers between 9 and 15 pages** (LNCS style, references excluded). The selection of the papers will be done by a peer-review processinvolving a program committee of renowned researchers. In order to encourage submission of high quality papers that report on ongoingresearch, we will not publish formal proceedings. Revised versions ofthe papers presented at ASL can thus be subsequently submitted elsewhere.

The submission is done on [Easychair](https://easychair.org/conferences/?conf=asl2022).



### Important Dates

  - Submission deadline: **May 10, 2022 (AOE)**
  - Notification:
  - Workshop: 



### Committees

*Program Committe*

 - Arthur Charguéraud (INRIA Saclay, France)
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
 - Nikos Gorogiannis (Facebook, UCL, London, UK)
 - Robbert Krebbers (Radboud Univ. Nijmegen, Holland)
 - Mihaela Sighireanu (LMF, ENS Paris-Saclay, France)
 - Makoto Tatsuta (NII, Tokyo, Japan)
 - Thomas Noll (RWTH, Aachen, Germany)


**System Requirements Specification (SRS)**

Introduction
************


Purpose
-------


Scope
-----



**Deliverable**:

**Benefits**:

Definitions, acronyms, and abbreviations
----------------------------------------



References
----------



.. This subsection should

.. a. Provide a complete list of all documents referenced elsewhere in
.. the SRS;

.. b. Identify each document by title, report number (if applicable),
.. date, and publishing organization;

.. c. Specify the sources from which the references can be obtained.
.. This information may be provided by reference to an appendix or to
.. another document.

.. NOTE: This is not the same thing as a list of the documents in your literature review; however, many of them may end up here, too.

Overview
--------
* Overall Description
   + Product Perspective
   + Interfaces
   + Product Function
   + Constraints
   + Assumptions

* Specific Requirements (Organized by feature)
   + External
   + Functional
   + Performance

.. This subsection should

.. a. Describe what the rest of the SRS contains;

.. b. Explain how the SRS is organized. NOTE: Describe which organization you will be using for section 3.

Overall Description
*******************

Product Perspective
-------------------


.. This section should put the product in perspective with other related products. If the product is independent and totally self-contained, it should be so stated here. If the SRS defines a product that is a component of a larger system, then this subsection should describe the relationship between the two.
.. A block diagram showing the major components of the larger system, interconnections, and external interfaces should be provided here.
.. This subsection should also describe how the software operates inside various constraints. For example, these constraints could include the following interfaces:

.. The interfaces described here are associated with things external to the system being developed.  The following sections should describe what you, as developers, need to know about the external systems to interface with them.
.. If your project is multi-disciplinary, this is the place to clearly define how your system will interface with the parts/modules being built by the other disciplinary teams. Naturally, their documentation should include the same interface specification and all of them should be kept consistent.

System interfaces
^^^^^^^^^^^^^^^^^


.. This should list each system interface and identify the functionality of the software to accomplish the system requirement and the interface description to match the system.

.. _user_interfaces:

User interfaces
^^^^^^^^^^^^^^^

.. This should specify the following:

.. a. The logical characteristics of each interface between the software product and its users. This includes those configuration characteristics (e.g., required screen formats, page or window layouts, content of any reports or menus, or availability of programmable function keys) necessary to accomplish the software requirements.

.. b. All the aspects of optimizing the interface with the person who must use the system. This may simply comprise a list of do's and don'ts on how the system will appear to the user. One example may be a requirement for the option of long or short error messages. Like all others, these requirements should be verifiable, e.g., "a clerk typist grade 4 can do function X in Z min after 1 hour of training" rather than "a typist can do function X." (This may also be specified in the Software System Attributes under a section titled Ease of Use.)

Hardware interfaces
^^^^^^^^^^^^^^^^^^^


.. This should specify the logical characteristics of each interface between the software product and the hardware components of the system. This includes configuration characteristics (number of ports, instruction sets, etc.). It also covers such matters as what devices are to be supported, how they are to be supported, and protocols. For example, terminal support may specify full-screen support as opposed to line-by-line support.

Software interfaces
^^^^^^^^^^^^^^^^^^^

.. This should specify the use of other required software products (e.g., a data management system, an operating system, or a mathematical package), and interfaces with other application systems (e.g., the linkage between an accounts receivable system and a general ledger system). For each required software product, the following should be provided:
.. Name
.. Mnemonic
.. Specification number
.. Version number
.. Source
.. For each interface, the following should be provided:
.. Discussion of the purpose of the interfacing software as related to this software product.
.. Definition of the interface in terms of message content and format.  It is not necessary to detail any well-documented interface, but a reference to the document defining the interface is required.

Communications interfaces
^^^^^^^^^^^^^^^^^^^^^^^^^

.. This should specify the various interfaces to communications such as local network protocols, etc.

Memory
^^^^^^

N/A

.. This section should specify any applicable characteristics and limits on primary and secondary memory.

Operations
^^^^^^^^^^

.. See :ref:`User Interfaces <user_interfaces>`.

See User Interfaces.

.. This section should specify the normal and special operations required by the user such as
.. a.The various modes of operations in the user organization (e.g., user-initiated operations);
.. b.Periods of interactive operations and periods of unattended operations;
.. c.Data processing support functions;
.. d.Backup and recovery operations.
.. NOTE: This is sometimes specified as part of the User Interfaces section.

Site adaptation requirements
^^^^^^^^^^^^^^^^^^^^^^^^^^^^


.. This section should
.. a.Define the requirements for any data or initialization sequences that are specific to a given site, mission, or operational mode (e.g., grid values, safety limits, etc.);
.. b.Specify the site or mission-related features that should be modified to adapt the software to a particular installation.

.. _product-function-lablel:

Product Functions
-----------------

The diagram below shows an overview of the functions our software provides:

.. Provide a summary of the major functions that the software will perform. This is an outline of the functional requirements in section 3.1, so don’t be too specific here.
.. Note that for the sake of clarity

.. a. The functions should be organized in a way that makes the list of functions understandable to the customer or to anyone else reading the document for the first time.

.. b. Textual or graphical methods can be used to show the different functions and their relationships. Such a diagram is not intended to show a design of a product, but simply shows the logical relationships among variables.

User Characteristics
--------------------

.. Describe the general characteristics of the intended users including educational level, experience, and technical expertise.  It should not be used to state specific requirements, but rather should provide the reasons why certain specific requirements are later specified in Section 3 of the SRS.

Constraints
-----------

.. Specify here any issues that will limit the developer’s options.
.. These include:
.. a. Regulatory policies;
.. b. Hardware limitations (e.g., signal timing requirements);
.. c. Interfaces to other applications;
.. d. Parallel operation;
.. e. Audit functions;
.. f. Control functions;
.. g. Higher-order language requirements;
.. h. Signal handshake protocols (e.g., XON-XOFF, ACK-NACK);
.. i. Reliability requirements;
.. j. Criticality of the application;
.. k. Safety and security considerations.


Assumptions and dependencies
----------------------------


.. This section of the SRS should list each of the factors that affect the requirements stated in the SRS. These factors are not design constraints on the software.  Rather, they are any changes to them that can affect the requirements in the SRS. For example, an assumption may be that a specific operating system will be available on the hardware designated for the software product.
.. Many of these assumptions will be become part of the basis of your risk-mitigation strategy.

Apportioning of requirements
----------------------------

Section 2.2 (product function) lays out the priority of the requirements for this project.  The last requirement to be completed is the Wiki Help Framework, and this can be delayed for future visitations of this project.  Other future work includes additional educational software applications and a framework for updates in areas that do not have access to the Internet.

.. This section should identify requirements that may be delayed until future versions of the system.  A necessary part of the process is to identify all of the requirement, estimate the effort required, and prioritize the requirements.  This section will identify known requirements that will not be incorporated into the system describe by this SRS.

Specific Requirements
*********************

.. This section of the SRS should contain all of the software requirements to a level of detail sufficient to enable designers to design a system to satisfy those requirements, and testers to test that the system satisfies those requirements. Throughout this section, every stated requirement should be externally perceivable by users, operators, or other external systems. These requirements should include at a minimum a description of every input (stimulus) into the system, every output (response) from the system, and all functions performed by the system in response to an input or in support of an output. As this is often the largest and most important part of the SRS, the following principles apply:

.. a. Specific requirements should be stated in conformance with all the characteristics described in 4.3.

.. b. Specific requirements should be cross-referenced to earlier documents that relate.

.. c. All requirements should be uniquely identifiable.

.. d. Careful attention should be given to organizing the requirements to maximize readability.

External interface requirements
-------------------------------

.. For most systems, this section addresses issues pertaining to the (graphical) user interface (e.g. which versions of web browsers must be supported). It may also discuss the interfaces to other external (existing) systems. For embedded systems, this describes the interface requirements for the hardware and/or other software subsystems.
.. This should be a detailed description of all inputs into and outputs from the software system. It should complement the interface descriptions in Section 2 (user, hardware, software, and communications interfaces) and should not repeat information there.

User interfaces
^^^^^^^^^^^^^^^


.. Requirements for interaction with user interfaces.

Hardware interfaces
^^^^^^^^^^^^^^^^^^^

Software interfaces
^^^^^^^^^^^^^^^^^^^

.. Requirements for interaction with software interfaces.

Communications interfaces
^^^^^^^^^^^^^^^^^^^^^^^^^

.. Requirements for interaction with communications interfaces.

Functional Requirements
-----------------------

.. Functional requirements should define the fundamental actions that must take place in the software in accepting and processing the inputs and in processing and generating the outputs.
.. Requirements must be written in the format: “x will/shall/must y” or “Given a, x will/shall/must y.”
.. Each requirement must address only one measurable and testable portion of your project.
.. It may be appropriate to partition the functional requirements into sub-functions or sub-processes. This does not imply that the software design will also be partitioned that way.
.. This should be, by far, the longest section of your document. Be sure to address each requirement of your system, no matter how trivial it may seem.

Performance Requirements
------------------------

.. This subsection should specify both the static and the dynamic numerical requirements placed on the software or on human interaction with the software as a whole. Static numerical requirements may include the following:
.. a. The number of terminals to be supported;

.. b. The number of simultaneous users to be supported;

.. c. Amount and type of information to be handled.
.. Static numerical requirements are sometimes identified under a separate section entitled Capacity.
.. Dynamic numerical requirements may include, for example, the numbers of transactions and tasks and the amount of data to be processed within certain time periods for both normal and peak workload conditions.
.. All of these requirements should be stated in measurable terms.
.. For example,
.. 95% of the transactions shall be processed in less than 1 s.
.. rather than,
.. An operator shall not have to wait for the transaction to complete.
.. NOTE: Numerical limits applied to one specific function are normally specified as part of the processing sub-paragraph description of that function.

Design constraints
------------------

Software system attributes
--------------------------

Reliability
^^^^^^^^^^^

* Code must be robust, and fail gracefully.

Availability
^^^^^^^^^^^^

* All code is open source.

.. Requirements for availability of the system or the information it handles.

Security
^^^^^^^^

Maintainability
^^^^^^^^^^^^^^^


Portability
^^^^^^^^^^^

Other Requirements
------------------

.. Place any requirements that don't logically fit elsewhere into this section.
.. Appendices
.. The appendices are not always considered part of the actual SRS and are not always necessary. They may include

..       a. Sample input/output formats, descriptions of cost analysis studies, or results of user surveys;

..       b. Supporting or background information that can help the readers of the SRS;

..       c. A description of the problems to be solved by the software;

..       d. Special packaging instructions for the code and the media to
..       meet security, export, initial loading, or other requirements.

.. When appendices are included, the SRS should explicitly state whether or not the appendixes are to be considered part of the requirements.
.. CS401 Note: There will probably many collections of information for your project well suited for inclusion in an appendix vice the main body. Don't hesitate to use appendices.
.. Index
.. List the major terms from this document and provide a hyperlink to a bookmark at that point (don't use page numbers on a website!).

Appendices
**********

.. The appendices are not always considered part of the actual SRS and are not always necessary. They may include
.. a. Sample input/output formats, descriptions of cost analysis studies, or results of user surveys;

.. b. Supporting or background information that can help the readers of the SRS;

.. c. A description of the problems to be solved by the software;

.. d. Special packaging instructions for the code and the media to meet security, export, initial loading, or other requirements.

.. When appendices are included, the SRS should explicitly state whether or not the appendixes are to be considered part of the requirements.



Index
*****

.. List the major terms from this document and provide a hyperlink to a bookmark at that point (don't use page numbers on a website!)

# Glossary

The following list contains terms and their meaning used in ELISA's working groups, workshops, meetings and other activities.

Please note:

 * This content should not be relied upon as definitive or final guidance from ELISA
 * This list is not exhaustive but tries to provide a starting point.
 
| Term | Explanation |
| :---- | :---- |
| AoU (Assumption of Use) | Generally refers to conditions or assumptions about how a system will be used. These could include environmental factors, user interactions, and operational constraints. |
| ARP4754 | Aerospace Recommended Practice (ARP) Guidelines for Development of Civil Aircraft and Systems, published at SAE International, dealing with the development processes which support certification of Aircraft systems. |
| ASIL (Automotive Safety Integrity Level) | A classification system defined in ISO 26262 for the automotive industry. It categorizes the risk levels of potential hazards based on their severity, exposure, and controllability. ASIL helps determine the necessary safety measures and requirements to ensure compliance with the standard. It is derived from the Safety Integrity Level (SIL) concept in IEC 61508. |
| Bug | An observable difference between what the software is intended to do and what it does. Other name is defect. Reference [1]  p.44 |
| Code centric | A development process often used in open source projects where the source code is the foundational part and other work products are created around the code, which is in contrast to the original understanding of the waterfall- or V-model. |
| Component |  An independent unit that can be composed and deployed independently. Ideally the unit has well defined interfaces and dependencies. Reference [1] p. 94 |
| Decomposition | In general the process of breaking down complex systems into simpler parts. Functional Safety Decomposition is a strategic approach that breaks down a safety requirement into redundant safety requirements allocated to independent elements. |
| Development processes | A series of steps or activities undertaken during the development of software, including planning, analysis, design, implementation, testing, deployment, and maintenance.|
| DAL | Short for Development Assurance Level (DAL) defined in ARP4754, determined from the safety assessment process and hazard analysis by examining the effects of a failure condition in the system. The failure conditions are categorized by their effects on the aircraft, crew, and passengers into No Effect, Minor, Major, Hazardous and Catastrophic. |
| DO-178C | DO-178C, Software Considerations in Airborne Systems and Equipment Certification is the primary document by which the certification authorities approve all commercial software-based aerospace systems. |
| Element |  Very generic term that is used to refer for example to a basic unit or component within a system, but is used inconsistently. |
| Failure | Termination of the ability of a system to perform a required function or its inability to perform within previously specified limits; an externally visible deviation from the system’s specification. Reference [1] p. 248|
| Fault | An "imperfection" or deficiency in a work product where that work product does not meet its requirements or specifications and needs or be either repaired or replaced. Reference [1] p. 248 |
| Functional safety | The part of the overall safety of a system or piece of equipment that depends on automatic protection operating correctly in response to its inputs or failure in a predictable manner (fail-safe). The automatic protection system should be designed to properly handle likely human errors, systematic errors, hardware failures and operational/environmental stress. |
| Functional safety assessment | Independent investigation, based on evidence, to determine if a system meets its required level of functional safety and achieves its target SIL (or similar integrity goal). |
| Hazard | A potential source of harm. Among this are injuries, environmental or other damage. |
| Incident |  Defect or malfunction in a system that could lead to an unacceptable risk. |
| IEC 61508 | International standard published by the International Electrotechnical Commission (IEC) consisting of methods on how to apply, design, deploy and maintain automatic protection systems called safety-related systems. It is titled Functional Safety of Electrical/Electronic/Programmable Electronic Safety-related Systems (E/E/PE, or E/E/PES). It is a risk-based standard, therefore the risk of hazards is qualitatively assessed and measures to detect, avoid, control or mitigate those are defined. |
| ISO 26262 | A standard that specifies the safety requirements for electrical and/or electronic systems within production automobiles defined by functional safety. Derived from and related to IEC 61508. |
| Item | Term used by ISO 26262 to describe a safety-related product or system intended to perform a safety function within a larger system. |
| Lifecycle | Stages that a product goes through from its inception to retirement, including development, production, operation, and end of life.|
| Mixed-criticality | A system containing hardware and/or software that can execute several applications of different criticality, such as safety-critical and non-safety critical, or of different safety integrity levels (SIL). | 
| Proven in use | Method of ensuring the reliability and safety of a system by demonstrating its performance over time under actual operating conditions. PIU for short is an argument that a reliable operating history demonstrates fitness for safety applications.|
| Quality Management | Performing processes and activities that determine quality policies, objectives and responsibilities so the project will satisfy the needs for which it was undertaken. Reference [1] p. 210 |
| Reliability | Degree to which a system or software performs specific functions under specified conditions for a specified period.  Reference [1] p. 176 |
| Reproducible |  Results obtained by an action (e.g., building or executing software) should be achieved again in the exact same fashion upon re-performing the action. |
| Requirement | A condition that must be satisfied for the output of a work effort to be acceptable. It is an explicit, objective, clear condition to be satisfied. A specification (or spec) is a set of requirements that is typically used by developers in the design stage of product development and by testers in their verification process. |
| Risk | Relation or likelihood of the hazardous event and the event consequence severity. The risk is reduced to a tolerable level by applying safety functions which may consist of E/E/PES, associated mechanical devices, or other technologies. |
| Route 3S | Certification pathway according to IEC 61508 for pre-existing software. Assessment of non-compliant development demonstrating compliance with the requirements of this standard for the avoidance and control of systematic faults in software. “S” stands for the “systematic capability”. |
| Safe | Generally refers to being free from harm, danger, or risk. |
| Safe Linux | Implies that safety can be allocated to the system which involves Linux, but there is no direct safety argumentation applied to Linux, safety is achieved in other system layers. |
| Safe state | A state a system enters to avoid unreasonable risk. It may involve degrading or disabling functions to mitigate harm from a malfunction or fault. |
| Safety analysis | Analytical evaluations aimed at demonstrating evidence that systems provide acceptable levels of safety. There are different approaches like STPA.   |
| Safety case |  A structured argument, supported by evidence, intended to justify that a system is acceptably safe for a specific application in a specific operating environment. |
| Safety Integrity Standard | A standard that defines requirements and processes for ensuring functional safety, such as IEC 61508 or ISO 26262. |
| Safety lifecycle |  A systematic approach of managing safety considerations during the lifecycle. |
| Safety Linux | This means that safety argumentation is directly allocated to Linux as the operating system or the Linux Kernel. Hence Linux itself is subject of safety assessments to meet different safety integrity levels (SIL).  |
| Safety manual | A document that shall provide all relevant information about the Safety functionality provided by an element and how to use it correctly including proper use, limitations, constraints and required activities for the integration and/or usage of elements. |
| Safety mechanism |  A technical solution to detect, avoid, control, or mitigate the harmful effects of failures. Examples are redundancy, fault detection and handling among others. | 
| Safety mitigation | Is the reduction of something harmful that has occurred or the reduction of its harmful effects. |
| Safety Plan | A formal document outlining a project's approach to safety management, including objectives, responsibilities, methods. |
| Safety requirement | Define safety mechanisms and other safety measures to minimize the risks to reach the Safety Goal(s). There may be a hierarchical approach to requirements as in ISO 262626, starting with Safety Goals and progressing through Functional, Technical, and Software Requirements. |
| Safety standard |  standards designed to ensure the safety of products, activities and processes, etc.|
| SEooC (Safety element out of context) | A safety-related element which is not developed in a particular context, but with assumptions of use for the assumed context of operation. Term used in ISO 26262.|
| Severity | Is a rating of the potential harm (like damage to people, equipment, the environment, or other assets) from a system malfunction.|
| SIL (Safety Integrity Level) | The qualification of integrity used to define in a standardized way a set of properties of a system, in a wide range of industry fields: aerospace, railways, etc. They go from SIL 4, more restrictive, to SIL 1, less stringent. |
| SPDX | Short for System Package Data Exchange, is a standardized way to track software components, including their licenses, copyrights, and security information, promoting transparency in software development. |
| STPA (System-Theoretic Process Analysis) | "A relatively new hazard analysis technique based on an extended model of accident causation. In addition to component failures, STPA assumes that accidents can also be caused by unsafe interactions of system components, none of which may have failed." [2] |
| SW-Element | Generally refers to a software component or module of software within a larger software system. |
| System | Is a set of components that act together as a whole to achieve some  common goal, objective, or end. A system may contain subsystems and may also be part of a larger system. |
| System Design | Is the overall system architecture, hardware architecture, software architecture, modules, interfaces, data management, and communication among modules. Reference [1] p.316 |
| Test | A systematic activity that examines software by executing it or analyzing its artifacts to verify that it meets requirements, uncover defects, and evaluate attributes such as functionality, reliability, usability, performance, safety, and security. |
| V-Model | A development process, often considered as an extension of the Waterfall Model. The left side deals with specification and design, the V bends at code implementation and on the right side of the “V” various levels of testing are executes. This model demonstrates the relationships between each phase of the development lifecycle and its corresponding testing phase. The horizontal and vertical axes represent the progression of time or project completeness (left-to-right) and the level of abstraction – starting with the most coarse-grained concepts at the top. The V-Model is not directly demanded in standards like IEC 61508, but many demands of the software development lifecycle referenced in it are related to it. |
| Validation | Ensures the product fulfills its specific intended purpose. It is defined as "the process of evaluating a system or component during or at the end of the development process to determine whether it satisfies specified requirements." Reference [1] p.257 |
| Verification | Ensures that the product is built correctly in that the output products of a lifecycle phase meet the specifications imposed on them in previous phases. Verification is defined as “the process of evaluating a system or component to determine whether the products of a given development phase satisfy the conditions imposed at the start of that phase". (Reference [1] p.257) May  involve peer reviews, inspections, and testing. |


Further material:

[1]: SWEBOOK - Guide to the Software Engineering Body of Knowledge v4.0a, Released Sept 2025, EDITOR Hironori Washizaki, Waseda University, IEEE Computer Society 2025, https://ieeecs-media.computer.org/media/education/swebok/swebok-v4.pdf

[2] STPA - STPA Handbook, March 2018, Nancy G. Leveson & John P. Thomas, https://psas.scripts.mit.edu/home/get_file.php?name=STPA_handbook.pdf


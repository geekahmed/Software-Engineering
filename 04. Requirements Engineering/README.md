# ﻿Chapter 2. Software processes
## Notes
- The requirements for a system are the descriptions of the services that a system should provide and the constraints on its operation.
- The process of finding out, analyzing, documenting and checking these services and constraints is called requirements engineering (RE).
- User requirements are statements, in a natural language plus diagrams, of what services the system is expected to provide to system users and the constraints under which it must operate.
	- The user requirements may vary from broad statements of the system features required to detailed, precise descriptions of the system functionality.
- System requirements are more detailed descriptions of the software system’s functions, services, and operational constraints.
	- The system requirements document (sometimes called a functional specification) should define exactly what is to be implemented. It may be part of the contract between the system buyer and the software developers.
### Section 1. Functional and non-functional requirements
- Functional requirements These are statements of services the system should provide, how the system should react to particular inputs, and how the system should behave in particular situations.
- Non-functional requirements These are constraints on the services or functions offered by the system. They include timing constraints, constraints on the development process, and constraints imposed by standards. Non-functional requirements often apply to the system as a whole rather than individual system features or services.
- Functional system requirements vary from general requirements covering what the system should do to very specific requirements reflecting local ways of working or an organization’s existing systems.
- Imprecision in the requirements specification can lead to disputes between customers and software developers.
- The functional requirements specification of a system should be both complete and consistent.
	- Completeness means that all services and information required by the user should be defined.
	- Consistency means that requirements should not be contradictory.
- Non-functional requirements are often more critical than individual functional requirements. System users can usually find ways to work around a system function that doesn’t really meet their needs.
	- However, failing to meet a non-functional requirement can mean that the whole system is unusable.
	- For example, if an aircraft system does not meet its reliability requirements, it will not be certified as safe for operation; if an embedded control system fails to meet its performance requirements, the control functions will not operate correctly.
- While it is often possible to identify which system components implement specific functional requirements, this is often more difficult with non-functional requirements. The implementation of these requirements may be spread throughout the system, for two reasons:
	- Non-functional requirements may affect the overall architecture of a system rather than the individual components.
		- For example, to ensure that performance requirements are met in an embedded system, you may have to organize the system to minimize communications between components.
	- An individual non-functional requirement, such as a security requirement, may generate several, related functional requirements that define new system services that are required if the non-functional requirement is to be implemented.
- Nonfunctional requirements arise through user needs because of budget constraints, organizational policies, the need for interoperability with other software or hardware systems, or external factors such as safety regulations or privacy legislation.
- Classification of non-functional requirements:
	- Product requirements These requirements specify or constrain the runtime behavior of the software. Examples include performance requirements for how fast the system must execute and how much memory it requires; reliability requirements that set out the acceptable failure rate; security requirements; and usability requirements.
	- Organizational requirements These requirements are broad system requirements derived from policies and procedures in the customer’s and developer’s organizations. Examples include operational process requirements that define how the system will be used; development process requirements that specify the programming language; the development environment or process standards to be used; and environmental requirements that specify the operating environment of the system.
	- External requirements This broad heading covers all requirements that are derived from factors external to the system and its development process. These may include regulatory requirements that set out what must be done for the system to be approved for use by a regulator, such as a nuclear safety authority; legislative requirements that must be followed to ensure that the system operates within the law; and ethical requirements that ensure that the system will be acceptable to its users and the general public.
- A common problem with non-functional requirements is that stakeholders propose requirements as general goals, such as ease of use, the ability of the system to recover from failure, or rapid user response. 
	- Goals set out good intentions but cause problems for system developers as they leave scope for interpretation and subsequent dispute once the system is delivered.
- Metrics for specifying non-functional requirements:
	- Speed
	- Size
	- Ease of Use
	- Reliability
	- Robustness
	- Portability
### Section 2. Requirements engineering processes
### Section 3. Requirements elicitation
### Section 4. Requirements specification
### Section 5. Requirements validation
### Section 6. Requirements change
## Exercises

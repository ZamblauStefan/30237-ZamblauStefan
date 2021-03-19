# (Bill Manager) Supplementary Specification

# Introduction
[The introduction of the Supplementary Specification provides an overview of the entire document.
The Supplementary Specification captures the system requirements that are not readily captured in the use cases of the use-case model. Such requirements include:
Legal and regulatory requirements, including application standards.
Quality attributes of the system to be built, including usability, reliability, performance, and supportability requirements.
Other requirements such as operating systems and environments, compatibility requirements, and design constraints.]



# Non-functional Requirements

[Define system quality attributes in terms of scenarios according to the following template:
-	Quality attribute definition
-	Source of stimulus: the entity (human or another system) that generated the stimulus or event
-	Stimulus: a condition that determines a reaction of the system
-	Environment: the current condition of the system when the stimulus arrives
-	Artifact: is a component that reacts to the stimulus. It may be the whole system or some pieces of it
-	Response: the activity determined by the arrival of the stimulus
-	Response measure: the quantifiable indication of the response
-	Tactics
]

##Functionality
This section lists functional requirements that are common to more than one use case.

1.System Error Logging
All system errors shall be logged. Fatal system errors shall result in an orderly shutdown of the system.

The system error messages shall include a text description of the error, the operating system error code (if applicable), the module detecting the error condition, a data stamp, and a time stamp. All system errors shall be retained in the Error Log Database.

2.Remote Access
Some functions like adding or deleting bills will be available to local area but they will be  synchronized when an internet connection is found. Paying bills will be possible only with internet connection.

## Availability
Bills manager app will be available to all persons that are 18 years or more, because it will be necessary to work with money and credit cards.
## Performance
The system will support multiple users accessing the database. Most of actions being done on the local computer then synchronizing them with database.
## Security
## Testability
## Usability
The desktop user interface will be windows 7+.
The user interface shall be designed for ease-of-use and shall be appropriate for any kind of computer users, from beginners to experts.



# Design Constraints
[This section needs to indicate any design constraints on the system being built. Design constraints represent design decisions that have been mandated and must be adhered to. Examples include software languages, software process requirements, prescribed use of developmental tools, architectural and design constraints, purchased components, class libraries, and so on.]

The system shall allow payments with any credit card.
The system shall run on any personal computer made after year 2000.

# Resources

* http://www.upedu.org/process/gdlines/md_srs.htm
* Example of Supplementary Specification: http://csis.pace.edu/~marchese/SE616_New/Samples/Example%20%20Supplementary%20Specification.htm

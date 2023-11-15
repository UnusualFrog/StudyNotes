## Construction
- the development of all parts of the system
	- Software itself
	- All documentation and new operating procedures
	- Implementation testing and configuration & change management work flows
- Programming is the largest, but least risky part of systems development
	- Project failure is not usually due to poor programming but to poor analysis, design, installation or project management
- Most organizations devote more time to testing & evaluation than to programming

## Managing Programming
- Project managers must:
	- Assign programming tasks
		- Group related classes to minimize coupling and maximize cohesion of modules
		- Assign the classes to programmers
	- Coordinate activities
	- Manage the schedule

## Coordinating Activities
- Hold weekly project meetings
- Create and enforce standards
- Divide resources into 3 areas:
	- Development
	- Testing
	- Production
- Implement change control measures

## Managing the Schedule
- Time estimates must be revised as construction proceeds
	- Build a 10% error margin into all schedules
- Common cause for schedule problems is scope creep
	- Occurs when new requirements are added to the project after the system design was finalized
	- Changes become more expensive when added later in the project schedule
- Small slippages in the schedule can add up to large schedule problems
- Risk assessment can help predict problems
	- Evaluate their likelihood
	- Evaluate their impact

## Cultural Issues
- Offshore outsourcing introduces potential cultural conflicts
- Context may influence a person's ability to see potential solutions
- Individualism vs. collectivism may determine how people work together and how they view intellectual property
- Monochronic vs. Polychronic determines how people view deadlines
- Other issues
	- Power distance
	- Uncertainty avoidance
	- Masculinity vs. Femininity
	- Long term vs. Short term orientation

## Designing Tests
- The purpose of testing is to uncover as many errors as feasible
	- Impossible to prove a system is error free
	- Too expensive to look for all possible bus
	- The purpose of testing is to uncover differences between what the system actually does and what it should do
- Four Stages of Testing:
	- Unit tests
	- Integration tests
	- System tests
	- Acceptance tests

## Testing and Object Orientation
- Encapsulation and Information-Hiding
- Polymorphism and dynamic binding
- Inheritance
- Reuse
- Object-Oriented Development Process and Products

## Test Planning
- A test plan defines a series of tests to be conducted
- Testing takes place throughout the development of an object-oriented system
	- Develop the test plan at the beginning and modify it as the system evolves
- Each test has a specific objective and describes a set of specific test cases
	- Test specifications are created for each type of constraint that must be met by a class
	- Stubs are hard-coded placeholders that allow testing using unfinished classes

## Unit Tests
- Focus on a single class
- Black box testing
	- Examines externally visible behaviors of a class
	- Driven by CRC cards, behavior state machine and method contracts, not by testers interpretation
	- Each item in the spec becomes a test
- White box testing
	- Examines the internals of a class
	- Driven by method specifications for the class
	- Small method sizes limits the usefulness of this type of testing
- Behavioral state machines can identify tests for a class

## Integration Tests
- Assess whether a set of classes that must work together do so without error
- 4 common approaches:
	- UI testing
	- Use case testing
	- Interaction testing
	- System interface testing
- Most projects use all 4 approaches

## System Tests
- Conducted to ensure all classes work together without error
- Similar to integration testing but broader in scope
	- How well the system meets both the functional and nonfunctional requirements (E.G. Usability, Documentation, Performance, and Security)

## Acceptance Tests
- Performed primarily by users with support of the project team
- Goal is to confirm that the system meets the business needs and is acceptable to the users
- Alphas testing - data is artificial
- Beta testing - data is real but carefully monitored for errors

## Developing Documentation
- Must be done throughout system development
- Two fundamentally different types
	### System Documentation
	-  Assists programmers and analysts build or maintain the system
	- Created as the project unfolds
	
	### User Documentation
	- Assists users to operate the system
	- Most users will not read the manuals before starting to use the system

- Online documentation makes searching simpler
- Developing & testing documentation takes time

## Types of Documentation
- Reference Documents
	- Tells users how to perform specific tasks
- Procedure Manuals
	- Describe how to perform business tasks
	- Each procedure normally entails multiple tasks
- Tutorials
	- Teach people how to use specific components of a system

## Designing Documentation Structure
- Online documentation will likely become the standard
- Develop a set of document navigation controls that lead the user to documentation topics
- Topics generally come from 3 sources
	- Commands and menus in the UI
	- How to perform certain tasks which can be found in
		- Use scenarios
		- WNDs
		- Real use-cases
	- Definitions of important terms

## Writing Documentation Tips
- Start with clear titles
- Include introductory text
- Finish with detailed, step-by-step instructions
- Consider using screen images
- Video tutorials are helpful

## Identifying Navigation Terms
- Table of Contents is developed from the logical structure of the documentation topics
- Sources for items for the index and search engine
	- Set of commands in the user interface (e.g., File ► Open)
	- Major concepts of the system (often use-cases and classes)
	- The set of business tasks to be performed (e.g., order placement)
	- Synonyms of the preceding items (users' vocabularies may not be precise)

## Summary
- Managing Programming
- Designing and Managing Tests
- Developing Documentation
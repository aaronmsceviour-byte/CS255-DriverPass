# CS255-DriverPass

## Who was the client and what was the goal?
DriverPass is a driver training company whose owner, Liam, identified that over 65% of students fail their DMV driving test due to a lack of practical preparation. He wanted a web-based system that would allow students to take practice tests, schedule driving lessons, and track their progress. The system also needed to support multiple roles including a secretary, IT officer, and owner, each with their own level of access.

## What did I do well?
The part of this project I feel best about is the activity diagrams. When building them I didn't just map out what the interview described, I thought through realistic scenarios and added logic that made sense even if it wasn't explicitly requested. The login diagram is a good example. I added a fail counter and account lockout mechanic because that is a real security concern for any login system, even though Liam never mentioned it specifically.

## What would I revise?
If I could revise one part it would be the class diagram. Looking back I think some of the relationships between classes could have been more detailed. Adding multiplicities to every connection, for example noting that one driver can have many appointments, would have made it a more complete reference for a developer to build from. Also while I was not needed to add attributes, including them wouldv'e helped to understand the system on a larger scale.

## How did I interpret the wants and needs? 
Interpreting user needs meant going back to the interview repeatedly and asking what each stakeholder actually needed to do their job. A customer needs to book and track lessons. A secretary needs to manage appointments on behalf of customers. An owner needs visibility into how the system is running. Keeping those distinct needs in mind prevented me from designing one generic interface and calling it done. User needs have to drive the design because a system that works technically but doesn't match how people actually work will get abandoned.


## How did I approach designing the software?
My approach to designing a system starts with understanding the problem before touching any diagrams. The interview transcript for DriverPass was the foundation for everything. From there I worked through process modeling first, identifying use cases and actors, then moved into structural modeling with the class diagram. In the future I would continue using that sequence because it mirrors how understanding naturally builds. You need to know what the system does before you can design what it is.

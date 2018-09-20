# Glue.ai binding to Solid Linked Data specification

+ "Linked Data" refers to the use of RDF-compatible approaches to distributed data and semantic linking.
+ Glue.ai application data has been represented in RDF since inception, and Glue.ai is inherently a "Linked Data" framework.
+ Glue.ai v2.x will address user data interoperability and privacy using the "Solid" ("Social Linked Data") approach.

## User Data Management:  Interoperability and Privacy

Glue.ai v2.x adopts the [Solid](https://solid.mit.edu/) approach to user data managment:   https://solid.mit.edu/   

What does this adoption mean for the Glue.ai community?  

In general, we want end-users to be able to have ownership of the data stored through any glue.ai mechanisms.
This means that end-users should be able to purge their data, export their data, and in some cases inspect
their data inside the running system.

But in a social robotics context, the "end-user" may not always be obvious.  

As a first approximation, we may need to rely on the idea of a "responsible user", e.g. the human person
who takes responsibility for launching the runtime system of the robot, together with all its data systems.
This person may be responsible for all the data collected during a particular runtime session (e.g. until 
the robot is rebooted).


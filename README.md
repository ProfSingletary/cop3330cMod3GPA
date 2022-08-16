#COP3330C Module 3 Programming Assignment

For this assignment you will continue work on the Scrum Workflow Manager 
application by replacing the logging method from Module 2 with a class
which handles the event logging. This class must implement an interface
which specifies two abstract methods: void log(Object) and an overload 
of that method: void log(Object, Instant). When log(Object) is called,
a local Instant is created and the overloaded log method is called with 
the local Instant as the second argument.

Any calls to the previous log method must be replaced by a call to the 
new event log class's methods (so you will need to instantiate the
event logging class where necessary).
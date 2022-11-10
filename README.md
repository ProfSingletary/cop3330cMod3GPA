#COP3330C Module 3 Programming Assignment

For this assignment you will continue work on the Scrum Workflow Manager
application by creating a Logger interface which will be implemented by the
ScrumWorkFlowManager class.

This interface specifies one abstract method: void log(Object) where Object 
contains a log string.

Subclasses can instantiate a Logger reference by casting a call to the
ScrumWorkFlowManager's constructor to Logger, e.g. 
 
    Logger logger = (Logger)new ScrumWorkFlowManager();

Sample output:
2022.08.12.10.05.08: Welcome to the Scrum Workflow Manager  
2022.08.12.10.05.08: Team Creation: Team formed for Scrum Workflow Manager  
2022.08.12.10.05.08: Team Member 1: Bill Bixby, Role: Product Owner  
2022.08.12.10.05.08: Team Member 2: Hulk Hogan, Role: Scrum Team Master  
2022.08.12.10.05.08: Team Member 3: Anthony Stark, Role: Developer  
2022.08.12.10.05.08: Team Member 4: Thor Odinson, Role: QA Tester  
2022.08.12.10.05.08: Team Member 5: Harry Cleese, Role: Architect  
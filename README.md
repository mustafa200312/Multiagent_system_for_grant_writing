Below is a figure of the architecture of our system. The system consists of 4 agents, each with its own task that plays an integral role in the grant writing process.
1.	The Supervisor (Orchestrator Agent): This agent is responsible for taking the grant proposal from the user and, based on it, coordinating the other agents in order to create a proper grant with the requirements the user asks, and keeps giving instructions to the other agent until the grantee simulator agent is satisfied.
2.	Budget Allocator: This agent is responsible for allocating a reasonable and acceptable budget to the grant. It uses the internet to look up the average price of the costs that will be needed to cover and gives them to the supervisor agent so he can pass them to the document formulator.
3.	Document Formulator: This agent is responsible of writing the necessary documents for the grant with the information he is given by supervisor (including the info passed by the budget allocator), at the end of the process it should be able to create a document that is satisfactory to the grantee simulator to get accepted. 
4.	Grantee Simulator: The purpose of this agent is to evaluate the overall product of the other agents and simulate a grantee to see whether the grant is likely to be accepted or not. If the agent is satisfied and sees that the grant is passable, it finishes the process of the whole system. 

This Figure show the system workflow:

![Multi_gent_system_workflow](https://github.com/user-attachments/assets/cd38f2b8-c832-4132-b5fd-1fbdfef10de9)

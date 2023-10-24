# Process Improvment Stagnation
## Indicators
- Poor documentation
- Lack of testing
- Resistance to process changes
- Siloed Knowledge
- Poor Team Engagment

## Root Cause: Unclear Roles and Responsiblities
Process improvments are implemented based on the collective understanding of each team member's role and responsiblity. The following is a flow of downstream impact when roles and responsibilites are unclear.

- Unclear Roles and Responsiblites -> Multiple Hats
- Multiple Hats -> Excessive Context Switching
- Excessive Context Switching -> Shallow Solutions (i.e. Solutions based on a simplistic understanding of the problem and its requirements)
- Shallow Solutions -> Poor Documentation. Shallow Solutions can lead to believing that documentation is unecessary because the idea is "simple enough".
  - Poor Documentation -> Ad Hoc Conversations
    - Ad Hoc Conversations -> Siloed Knowledge
- Shallow Solutions -> Just Do It. (i.e. Instead of asking questions or gathering more information, opt for implementing the given solution) 
  - Just Do It -> Brittle Process Foundation. Makes it difficult to build off of in the future since solutions are not well thought out.
  - Just Do It -> Poor Process Rationalization. Eventually team will start to rationalize poor process. Hear things like "Why bother? It works.", "It could be worse.", "It is what it is."
    - Poor Process Rationalization -> Poor Team Engagement. Team will start to realize that there should be something done about process but does not have the morale to do so.
    - Poor Process Rationalization -> Process Improvments Heavily Resisted. Team has already rationalized current process to the point of acceptance.    
  
## Solution: Define the Big Picture Process
Software development is the process of taking an idea and turning it into a product. The following diagram is a basic flow of that process.

![Idea Lifecycle](/idea-lifecycle.png?raw=true "Idea Lifecycle")

- Each box represents a concrete object that can be used to continue the flow. It could be documents, JIRA tasks, Mobile App, etc.
- Each line represents the process that generates the box. Examples include Sprint Planning sessions, Stakeholder meetings, Software development, etc.


### Exercise: Define the boxes
For each box listed in the diagram, define the following:
- Who is responsible?
- What should it include?
- Why whould it be included?

The key to the exercise is gathering EVERYONE'S EXPECTATIONS for each box. This will serve as the contract for defining each person's role and responsibility. 

For example, "Requirements Overview" is listed twice. There is a clear difference between the two. The contents of the "Requirements Overview" for someone funding the project might include expected return on investment. This could invovle people from product team (Product Manager, Product Owner) but a developer wouldn't make much sense to involve. Someone developing the project might want technical boundaries like "Must use AWS services". Here it would now make sense to include the developer along with the product team.

Note: DO NOT DEFINE SOLUTIONS! For example, take the "Requirements Overview". Do not define where this will live or how the format will be. Leave that open to the person(s) responsible to define.

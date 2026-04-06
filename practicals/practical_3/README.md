1. Class Diagram
[text](CD.drawio)

At the top, a general User class (with login/logout) is inherited by two specialized roles: Student and Professor, where students can submit assignments and view grades, while professors can set deadlines, define criteria, and review submissions. Below that, the core workflow is handled through Assignment and Submission, where students submit work that is tracked with details like attempt number, timestamp, and status. A central System class processes scoring and feedback, and the VLE (Virtual Learning Environment) acts as the interface layer that connects users to the system for actions like fetching students and sending grades. Overall, it shows a clear flow from user roles → assignment submission → evaluation → feedback delivery.


2. Object Diagram
[text](OD.drawio)


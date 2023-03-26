# Transport-Approval-System
A power Platform project for transport approval and streamline productivity in an organization. 


## Inspiration
The inspiration for the Transport Approval System is the fact that in some organizations, staff members may use unplanned means of transport to perform office tasks and not get reimbursed. Additionally, the process of getting approval to use other means of transport other than the office car can be a long and tedious process that reduces productivity. The Transport Approval System has been designed to address these issues by providing an easy and efficient way for staff members to request approval for the use of unplanned transport means, while also enabling real-time reporting for faster reimbursement and improving productivity.

## What it does
The Transport Approval System automates the approval process for staff members who request approval to use unplanned means of transport for office work. The system uses Power Automate to automate the approval process and Power Apps to allow staff members to submit their requests. Once a request is submitted, the approver is notified and can easily approve or reject the request through the system. Additionally, the system uses Power BI to generate reports on the users who used unplanned means of transport, allowing for easy reimbursement.

## How we built it
The Transport approval system was built using a combination of Microsoft Power Platform tools, including Power Automate, Power Apps, SharePoint, and Power BI. Here is an overview of the system's architecture and workflow:
1.	User submits a request through the Power Apps interface. The request includes details such as the purpose of the trip, the destination, the mode of transportation, and the estimated cost.
2.	The request is stored in a SharePoint list.
3.	A Power Automate cloud flow is triggered when a new entry is added to the SharePoint list. The cloud flow checks if the request is complete and valid, and then sends an email notification to the manager for approval.
4.	The manager can approve or reject the request through a Power Apps interface.
5.	If the request is approved, the cloud flow sends an email notification to the requester with a confirmation and instructions for reimbursement.
6.	The request data is stored in a separate SharePoint list for tracking purposes.
7.	Finally, power BI is used to create reports and dashboards that display data about the approved requests, including the number of requests, the total cost, and the average cost per request.

## Challenges we ran into
The major challenge we faced while building the transport approval system was the Integration Challenges. Since a number of members were new to power platform, it was a challenge integrating the different Power Platform tools, such as Power Automate, Power Apps, SharePoint, and Power BI, into a seamless workflow. We had to spend a significant amount of time ensuring that the data flowed smoothly between the different tools, and that the system worked as expected.

## Accomplishments that we're proud of
Some of the accomplishments that we are proud of in the Transport System project include:
1.	Automation of the approval process: We are proud to have successfully automated the approval process using Power Automate. We believe this will greatly reduce the time and effort required to approve requests for the use of unplanned means of transport, making the process more efficient.
2.	Real-time reporting: we believe our use of Power BI to generate real-time reports on users who used unplanned means of transport will improve the reimbursement process. If adopted, staff members will be reimbursed more quickly and accurately.
3.	Improved productivity: The Transport Approval System will improve productivity by reducing the time and effort required to get approval for the use of unplanned means of transport, allowing staff members to focus on their core duties and responsibilities.

## What we learned
While building the Transport approval system, we learned several important lessons. Some of these greatest lessons learnt were:
1.	Power Platform Capabilities: We learned about the capabilities of the Power Platform tools, including Power Automate, Power Apps, SharePoint, and Power BI. We gained a deeper understanding of how these tools could be used to automate processes, visualize data, and improve the user experience.
2.	Benefits of Automation: The system has shown us the benefits of automation in improving efficiency, reducing manual efforts, and providing data-driven insights. We have seen how automating processes can free up time for staff to focus on higher value activities and improve productivity.
Overall, building the Transport approval system has been a valuable learning experience for us. We have gained new skills and knowledge and have a better understanding of how to use technology to improve processes and workflows.

## What's next for Transport Approval System
Moving forward, there are several potential enhancements and improvements that we could make to the Transport approval system. These include:
1.	Mobile App: We could create a mobile app version of the Power Apps interface, allowing users to submit requests and track their travel details on the go.

2.	Machine Learning: We could integrate machine learning algorithms into the system to improve the accuracy of cost estimation and provide recommendations to managers for approval.

# Business modelling for insurance claiming process


## What am I trying to do and achieve?
This is a business process model documented as a context diagram and a Data flow diagram (DFD) 

## Scenario
The business process is a insurance claiming process of an automobile insurance company. The claim is for repairing of an automobile using one of their pre-approved mechanics.  


## Why 

When a client makes claims for automobile repairs, e.g. collisions, fire damages or damages due to natural  disasters such as flood, the client can either call the insurance help centre to inform them about the nature of  the claim and provide descriptions of the damages, or they can complete the claim form online via the company  website – so they have time to think about the incident and describe it clearly. 

Either way, the insurance officer first checks the validity of the insurance policy by entering the policy number  to the system. In case the client lost the policy number, client’s personal details such as full name, phone  numbers, etc can be used to lookup for their insurance policies. Claims may be rejected if the policy number  is expired and the client’s personal details cannot be found in the system. After verification of policy number,  the officer will retrieve the automobile information, policy coverage, excess fee, etc from the database. At the  back end, the policy number is retrieved from the Policy master data which also contains the details of policy coverage and automobile information. Client’s personal details are stored in Customer master data. 

When a claim is successfully lodged, the system generates a case reference number, which is saved in the  Case event data. The client may use this reference number later, e.g. to check for the claim status, details of  repair work, etc. Then, the officer will retrieve a list of certified mechanics that meet the case requirement. 

## How
The deliverables are a context diagram and DFD.

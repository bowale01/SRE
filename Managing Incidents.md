No matter how well we plan, design, develop and try to anticipate prevention strategies, sometimes things will go wrong.

Remember trust is built based on the reliability of our services and the perception of how well we handle a situation when things go wrong.

To build good incident management practices, there must be a predefined agreement on how to operate. Having processes to follow is a good start, however, a process alone will only take you that far.  What it'll make it great is the practice to be able to perform and resolve the incidents.

# Incident lifecycle

1- Detection: Become aware of an issue, via an alert or any other means, such as a customer telling you that something is not working.

2-Triage: The decision moment to determine how bad things are, what's the impact, what's happening, and make the decision to determine if is just an anomaly or an incident.

3-Declare an incident: State the nature and severity of the incident. (Mayday, Mayday, Mayday.Pan,Pan, Pan)  

4-Mitigate the incident: how to reduce the impact or fix the problem 

5- Identify root cause: Once the incident is mitigated or the problem is fixed. It is time to understand why it happened so that it does not happen again. 

6- Incident resolved: Once the root cause is identified an incident can be considered resolved. Note incident is resolved once the root cause is  

 

How are incidents managed? Is there a systematic/structured process or methodology?

      What's the chain of command? is it clear?

      How incidents are communicated and how stakeholders are kept informed?


What are the designated roles in an incident? How are they assigned? What every role does, and when? 

Example of Roles at Google:

Incident Commander. At the top of the hierarchy that controls the incident, everyone participating in the incident will report to him. He's mission is to ensure that the incident is solved, focusing on organising and managing the incident team. Usually leveraging the technical expertise of the group rather than its own.  

Communications Lead:

Operations Lead:

Primary Responder:

Secondary Responder:

 

What are the roles related to incident management at ad-tech?

How do you keep a record of the troubleshooting and mitigation actions taken?

Slack/ Teams Chat/What boards do we have to radiate information without requiring customers/stakeholders to call? For example Google Cloud Status page.

 

# What is an incident?
Anything that affects user impact, revenue or reputation. 

Note incident and spark incident are two different things. A spark incident is usually created on the back of an alert, while an incident is anything that affects customers. 

Customers are sky media users or partners using ad-tech systems


When to declare an incident?  
How to determine and take action to mitigate an incident?

How-to troubleshoot and get to the root cause of an incident?

How to resolve an incident?

How to document incidents

When and how to perform postmortems?

Anytime an SLO is breached.

Anytime there's an incident that requires an immediate/emergency response, some companies make them mandatory for high-severity incidents.

Anytime other team has been impacted



 See  Blameless Postmortems https://github.com/bowale01/SRE/blob/main/Blameless%20postmortem.md  to see how to perform them

A quick checklist to see if we are ready for incidents.

Have clear criteria to determine when to declare an incident. 

Have a pre-establish communication channel (slack,teams, dashboards similar  to Google Cloud status dashboard https://status.cloud.google.com/)

Have an agreed structure template for communications during the incident and for blameless postmortems.

Determine how to keep track and record the triage steps followed and mitigation actions. 

Have a clear chain of command and clearly define roles 

Practice, or perform drills regularly


Actions:

Break the link between alert and incident

Have an alert manager to reduce the number of alerts, which are then converted into spark incidents. As examples:

Data lake generated 165 in a month, spark incidents associated with the same ... missing file

Landmark generates also... 

Have a clear definition of incident management-related roles and responsibilities

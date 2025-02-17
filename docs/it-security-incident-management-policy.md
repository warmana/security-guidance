---
redirect_from:
  - /it-incident-management-policy/
---
# IT Security Incident Management Policy

## How to use this policy

This policy is for all users and is part of a set of Ministry of Justice \(MoJ\) policies and supporting guides that cover various aspects of incident and disaster management and response.

The policies are:

-   IT Security Incident Management Policy
-   [IT Disaster Recovery Policy](it-disaster-recovery-policy.md)
-   [IT Investigations - Planning and Operations Policy](it-investigations-planning-and-operations-policy.md)

The supporting guides are:

-   [IT Incident Response Plan and Process Guide](it-security-incident-response-plan-and-process-guide.md)
-   [IT Disaster Recovery Plan and Process Guide](it-disaster-recovery-plan-and-process-guide.md)

This policy describes what is needed to manage an IT Security Incident.

Information is listed beneath the following headings:

-   [Policy statements](#policy-statements)
-   [What is IT Security Management?](#what-is-it-security-management)
-   [Definition of an IT Security incident](#definition-of-an-it-security-incident)
-   [Types of incidents](#types-of-incidents)
-   [Incident detection and reporting](#incident-detection-and-reporting)
-   [Incident categories](#incident-categories)
-   [Escalations](#escalations)
-   [Incident management stakeholders](#incident-management-stakeholders)
-   [Investigations](#investigations)
-   [System recovery](#system-recovery)
-   [Lessons learned](#lessons-learned)

### MoJ Security Team

In this policy, 'MoJ Security Team' refers to all the security teams within the MoJ.

The MoJ Security Team are responsible for:

-   incident ownership, monitoring, tracking and communication
-   sanctioning enhanced monitoring where appropriate
-   updating the incident management database
-   analysing security incidents as required
-   initiating a forensic investigation\(in accordance with the [IT Investigations - Planning and Operations Policy](it-investigations-planning-and-operations-policy.md)\)
-   providing progress reports to relevant parties

To contact the MoJ Security Team, send an email to [security@justice.gov.uk](mailto:security@justice.gov.uk).

## Policy statements

This policy refers to the Policy Statements, **POL.IMP.001** to **POL.IMP.014**.

**POL.IMP.XXX** indicates the specific policy statement to be adhered to.

## What is IT security management?

IT Security Incident management is the ability to react to MoJ IT security incidents in a controlled, pre-planned manner.

Preparation and planning are key factors to successful information security management. This policy sets out good practice for dealing with IT security incidents.

## Definition of an IT Security Incident

A security incident is defined by the National Cyber Security Centre \(NCSC\) as:

-   a breach of an IT system's security policy in order to affect its integrity or availability
-   the unauthorised access or attempted access to an IT system

An IT incident may result in sensitive information being exposed, which might compromise MoJ business delivery or the Data Protection Act.

An incident might also cause harm or damage to individuals or organisations and result in operational disruption or reputational damage to the MoJ.

All MoJ staff **shall** be aware of the definition of a security incident and how to report it.

## Incident Response

An incident response is the action taken when a security incident is detected or reported.

Responding to an incident requires informed decisions, taken as part of a consistent approach that is designed to reduce the consequences of the incident.

The process to respond to an incident **should** be described in detail in an Incident Response Plan.

**POL.IMP.001**: Each MoJ IT system and service **shall** have an IT Security Incident Response Plan.

The [IT Incident Response Plan and Process Guide](it-security-incident-response-plan-and-process-guide.md) has information on what to include in a Response Plan.

## Types of Incidents

Types of IT Security related incidents include:

-   breaches of the [IT Security Acceptable Use Policy](acceptable-use.md)
-   detection of malicious code such as viruses and malware
-   network attacks or Denial of Service \(DOS\) attacks
-   scanning and probing of a network, which might consume significant network resources
-   the discovery of a new network vulnerability
-   release of a patch or software update which is considered critical or an emergency
-   a penetration test on a live operational IT system that reveals critical vulnerabilities
-   unauthorised access to an MoJ IT system
-   personal data incident due to accidental or deliberate loss or release of personal information
-   any alert or activity report generated by an MoJ IT system that proves to be a real security alert

## Incident Detection and Reporting

Security incidents may be discovered by:

-   protective monitoring solutions
-   incident reports by MoJ staff
-   third-party reports to the MoJ
-   breaches of MoJ IT Security Policy detected by an IT system
-   data surrounding IT security incidents or suspected IT security incidents can be captured and monitored for suspected malicious activity or breaches of security

**POL.IMP.002**: All MoJ IT Security incidents or suspected incidents **shall** be reported to the IT Service Desk as soon as they are identified.

**POL.IMP.003**: All MoJ IT Security incidents involving personal data **shall** be reported to the MoJ Data Protection Team.

The MoJ Security Team is responsible for maintaining a database of IT Security incidents across MoJ IT systems.

This database contains:

-   security incident reports
-   the status of all reported security incidents and any actions taken to mitigate them

[Further guidance on how to report a security incident.](reporting-an-incident.md)

## Incident Categories

Security incidents are categorised to assess their impact and required level of escalation.

The three categories are:

-   Low impact
-   Medium impact
-   High impact

**POL.IMP.004**: All IT Security incidents **shall** be categorised by the incident response team.

An IT incident may need to be recategorised if there are changes to the nature and impact of the incident.

### Low impact incident

Low impact incidents are typically minor events such as a low-level breach in IT Security or a short-term loss of an IT service.

### Medium impact incident

Medium impact incident are typically caused by:

-   disregard for the MoJ IT Security Policy leading to a minor breach in security or the potential of data loss
-   inappropriate use of MoJ IT assets
-   theft or loss of data from an IT system that does not contain any personal information and is not protectively marked
-   damage to an MoJ IT asset that impacts its usability
-   connecting unauthorised equipment to an MoJ IT system
-   prolonged or permanent failure of an MoJ IT system
-   prolonged set of unsuccessful attempts to scan an IT network or instigate a denial of service attack
-   a new critical security vulnerability in an IT system
-   localised report of malicious code such as a virus on a terminal

### High impact incident

High impact incidents require immediate escalation to the relevant Senior Information Risk Owner \(SIRO\), the MoJ Security Team, and the Data Protection Team if personal data is involved.

High impact incidents may require forensic investigation.There is more information on this in the [IT Investigations - Planning and Operations Policy](it-investigations-planning-and-operations-policy.md).

High impact incidents are typically caused by:

-   malicious activity or espionage
-   an incident that attracts media coverage
-   intrusion into an IT network
-   widespread malicious code attacks
-   the theft or loss of personal or protectively marked data from an IT system

## Escalations

If an incident needs to be escalated, it **shall** follow the chain of command through the incident response command structure.

The exact chain of escalation **should** be outlined in the IT system's Incident Response Plan.

A typical command chain might be from the incident manager to the Major Incident Management team, to the relevant SIRO to Chief Security Officer \(CSO\) to Ministerial response.

Reasons for escalation might include:

-   issues of national security
-   if the incident is receiving media coverage
-   if the incident has caused harm to a member of staff or public
-   the MoJ has suffered reputational damage
-   a requirement to report to another Department or central management function
-   significant actual or potential loss of personal information where the Information Commissioner’s Office and Cabinet Office need to be informed

**POL.IMP.005**: Each IT Security Incident Response Plan **shall** include a pre-arranged escalation path, where each stakeholder is named and is aware of their role. Contact the Major Incident Management team if you need help creating documented escalation paths.

## Incident Management Stakeholders

There are likely to be both internal and external stakeholders involved in incident management and response.

These will vary depending on the specific IT system or service.

**POL.IMP.006**: All MoJ staff **shall** report any actual or suspected incidents, including breaches of MoJ Security Policy, to their line manager and to the IT Service Desk.

**POL.IMP.007**: As part of operational readiness, Each SIRO **shall** ensure that each IT system or service under their remit has an [IT Security Incident Response Plan](it-security-incident-response-plan-and-process-guide.md). A guide for writing a plan is available in the [IT Security Response Plan and Process Guide](it-security-incident-response-plan-and-process-guide.md).

**POL.IMP.008**: All High impact IT Security incidents and any IT Security incident involving personal data **shall** be reported to the SIRO for your business area.

**POL.IMP.009**: All IT Security incidents involving the suspected or actual loss, theft, or compromise of an Information Asset **shall** be reported to the Information Asset Owner \(IAO\).

**POL.IMP.010**: If the IT Service Desk receives a report of a security incident, this **shall** be reported to the MoJ Security Team.

## Investigations

The MoJ Security Team is responsible for the investigation of all MoJ IT Security incidents.

If legal or disciplinary proceedings require evidence to be gathered, a forensic investigation may be needed.The [IT Investigations - Planning and Operations Policy](it-investigations-planning-and-operations-policy.md) gives more information.

**POL.IMP.011**: The MoJ Security Team **shall** maintain documentation on investigations undertaken.

**POL.IMP.012**: Any investigation of an IT Security incident and the events surrounding it **shall** be reported to all relevant stakeholders.

## System Recovery

Following an IT Security incident, the IT system, services or any compromised assets **shall** be restored to business as usual \(BAU\).

If MoJ IT systems or services are restored using backups, the systems or services being restored **shall** pre-date the incident and **shall not** contain any weaknesses that could be exploited further.

**POL.IMP.013**: The IT Security Incident Response Plan **shall** show how an MoJ IT System or service will be restored or recovered following an IT Security incident. The method used to restore or recover an MoJ IT System **shall** be captured in the system's disaster recovery plan.

The [IT Disaster Recovery Plan and Process Guide](it-disaster-recovery-plan-and-process-guide.md) has more information.

## Lessons Learned

Once the cause of an IT Security incident has been identified steps **shall** be taken to make sure it will not happen again.

A report **shall** be prepared that describes:

-   the incident
-   the investigation
-   the actions taken to restore the IT system or service to BAU
-   all lessons learned

Lessons learned **should** include action points on how to improve the business systems to reduce the likelihood of the incident re-occurring.

This report **should** be sent to the SIRO who is responsible for forwarding it to all relevant stakeholders.

**POL.IMP.014**: For each Medium and High impact IT Security incident, a report **shall** be prepared, to include:

-   a description of the incident
-   a description of the incident investigation and its outcome
-   mitigations and actions taken to resolve the incident
-   any lessons learned and recommendations made

## Contact and Feedback

For any further questions or advice relating to security, or for any feedback or suggestions for improvement, contact: [security@justice.gov.uk](mailto:security@justice.gov.uk).


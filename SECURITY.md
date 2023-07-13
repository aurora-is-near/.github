# Aurora Security Policy

We are trying our best to eliminate as many vulnerabilities as possible during our development process and to avoid any potential risks bound to their exploitation. However we are not faultless. 

One of the measures we decided to take is to carefully develop our Security policy and create the Bug Bounty Program in order to find the tricky vulnerabilities that even an audit cannot point to. You have the skill, work with us!

How to?

Explore our code, check our web app. Read through details of our Bug Bounty Program. But please, always make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service. 


All security related issues should be reported via email to security@aurora.dev. Please follow the incident management process described below. We will attempt to respond within 48 hours to all reported issues.

Thank you for taking the time to responsibly disclose any vulnerabilities you find.



## Security Bug Bounties

We call on you to help us find bugs in our smart contracts code and app, securely report it to us and work with us in accordance with rules of our Bug Bounty Program. 
That will allow us not only to recognize you and your skill on our website, but also reward you for all the hard work!

Detailed description of our Bug Bounty Program including issues, payment policy, eligibility and the scope can be found [here](https://hackenproof.com/aurora).

## Known Issues

Nothing to find here. Yet.



## Incident management process


### 1. Reporting an incident and establishing communication channel

To report a security issue send an email to security@aurora.dev. Please allow us easier identification of the email and start the Subject with 'Security issue: *Risk level*'. 

In the report include at least: your GitHub handle, description of the issue, components, reproduction, any other relevant details; your name is optional.

**In response to your email, a designated member of aurora-is-near organization will:**
  - create new draft security advisory in https://github.com/aurora-is-near/[repository]/security/advisories
  - add you, the reporter, and members of incident response group to the draft security advisory
  - create new temporary private fork
  - reply to the reporter with link to the new draft security advisory

### 2. Triage

The issue will be discussed within the newly created draft security advisory. 

At this time the issue will be evaluated by members of the incident response group, there might be changes in risk level or the issue can be dismissed as known, duplicate, etc.

If necessary, other members of aurora-is-near organization can be added as collaborators to the draft security advisory.


### 3. Fix preparation

A new branch will be created in the temporary private fork made in the draft security advisory, here the fixes for the issue will be prepared and later pushed to the main branch in the temporary private fork.

Code review from the reporter is ideal, as well as from multiple members of the core development team.


### 4. Fix implementation

The fix will be implemented within a reasonable time period which will be disclosed within the draft security advisory. 
If you consider resolution time too long, please have a written conversation about it with us before disclosing details of the vulnerability to someone else.


### 5. Public disclosure and release

Once the code has been deployed, the patches from the security advisory can be merged into the main source repository. 

We currently do not use the Github workflow to publish security advisories. Once the issue and fix have been disclosed, the GitHub security advisory is no longer needed and can be closed.

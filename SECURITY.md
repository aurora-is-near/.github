# Aurora Security Policy

We are trying our best to eliminate as many vulnerabilities as possible during our development process and to avoid any potential risks bound to their exploitation. However we are not faultless. 

One of the measures we decided to take is to carefully develop our Security policy and to create the Bug Bounty Program in order to find the tricky vulnerabilities that even an audit cannot point to. You have the skill, work with us!

How to?

Explore our code, check our web app. Read through details of our Bug Bounty Program. But please, always make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service. 

All issues in scope of the Bug Bounty Program should be reported through [Immunefi](https://immunefi.com/bounty/aurora/).  
All other security issues should be reported via email to security@aurora.dev. Please follow the incident management process described below. We will attempt to respond within 48 hours to all reported issues.

Thank you for taking the time to responsibly disclose any vulnerabilities you find.



## Security Bug Bounties

We call on you to help us find bugs in our smart contracts code and web app, securely report it to us and work with us in accordance with rules of our Bug Bounty Program. 
That will allow us not only to recognize you and your skill on our website, but also reward you for all the hard work!

Detailed description of our Bug Bounty Program with Immunefi including issues, payment policy, eligibility and out of scope items can be found [here](https://immunefi.com/bounty/aurora/). 

Assets in Scope for Bug Bounty Program can be found [here](https://github.com/aurora-is-near/aurora-security-public/blob/main/ABBP-AssetsInScope.md).


## Known Issues

Nothing to find here. Yet.



## Incident management process


### 1. Reporting an incident and establishing communication channel

To report a security issue send an email to security@aurora.dev. Please allow us easier identification of the email and start the Subject with 'Security issue: *Risk level*'. 

In the report include at least: your GitHub handle, description of the issue, components, reproduction, any other relevant details; your name is optional.

We encourage you to use encrypted communication to ensure confidentiality of the vulnerability report. Please use our public key designated for encryption and another designated for signature. Also when writing to us, please provide your public key, so we can continue to communicate in an encrypted fashion.
```
PGP key fingerprint, Encryption: 4529 27CB 24C4 AFF8 609E  64FA 6885 6FE9 E33D 23CC
PGP key fingerprint, Signature: 48F2 B425 8D4E 22C1 805F  A069 D87D D16B 0456 C1D8
Plaintext PGP key, Encryption: At the bottom of this page.
Plaintext PGP key, Signature: At the bottom of this page.
```

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



## Plaintext PGP Public keys

**Encryption**

```
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
safGWgIMFQLG/SMOdpvYDJX+
=UH4r
-----END PGP PUBLIC KEY BLOCK-----
```

**Signature**
```
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
RHiS0cdEFFxdYaLfw9jX
=em2z
-----END PGP PUBLIC KEY BLOCK-----
```

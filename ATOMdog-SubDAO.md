# Overview

### Problem Statement

**Premise:** Through a community pool spend proposal, the Cosmos community pool can be accessed via an on-chain vote. If the vote passes, funding is immediately transferred from the community pool to the recipient wallet.

**Problem:** ATOM stakeholders seek transparency and accountability for projects that they fund via the community pool.   

**Solution:** A community-facilitated and sortition-oriented watchdog committee can provide a viable and easily accessible solution for holding projects accountable for the appropriation of Cosmos Hub common resources.   

### One-liner
The Cosmos Hub community pool has common-pool-resource attributes but lacks key characteristics relevant to sustainably governing commons, such as the capability to monitor and sanction appropriators of the pool. Cosmos stakeholders risk depletion of common resources and coordination failure if these issues are not resolved. 

### Goals
- Develop a pool of verified stakeholders that are willing to participate in the sortition and auditing process
- Resolve disputes about milestone achievement between community members and pool appropriators
- Audit the use of the community pool after funding has been released 
- Ensure that agreed upon deliverables from community pool spends are met
- Grant clear community ownership over the accountability layer of governance
- Sanction appropriators via reports if they violate their agreed upon mandate 

### Non-Goals
- Coordinate or assess product-work between Cosmos core teams and community funded projects
- Perform work outside of the Cosmos Hub
- Assess the value or usefulness of proposals
- Provide governance voting recommendations
- Audit aspects or qualities of projects that fall outside of the agreed upon scope of the original proposal
- Facilitate the formation of KPIs and OKRs in the proposal process
- Determine boundaries for community pool use
- Write or change code related to governance tooling
- Assist proposers in the proposal process
- Provide feedback on draft proposals
- Hold or release funding in a multi-sig wallet 
- Develop templates for community pool spend proposals
- Develop an identity system to prevent sybil attacks in the sortition system

### Other impacts
*The impacts that this will have on the proposal process.*
A clear accountability language and standard for community pool spend proposals will have to be ratified by the community. All proposers that have received community-pool funding will need to provide access in the form of both artificats and time-commitments to the watchdog committee. Future recipient wallets should be transferred to neutral parties or vesting accounts in order to provide easy clawback access for dispersed funds. 

### Ideas Considered
*A description of ideas considered that may come into consideration in the design / implementation, or in future.*
- Providing watchdog services for the Interchain
- Dispute resolution services for the Interchain
- Improved UX for joining and coordinating sortition pools using zk proofs to verify stakeholders have skin in the game without disclosing address or personal information, limiting the needed disclosures from sortition members to the use of their voice and written-language. 
- An identity system to mitigate attack vectors related to sortition such as sybil attacks. 

### KPIs
*The metrics we can use to measure the impact of this solution?* 
- Quantity of unique candidates in the sortition pool 
- Number of projects audited
- The average number of projects audited by each sortition candidate
- The number of reports issued to the community 
- Number of milestones analyzed
- Deliverable approval percentage

### Success Criteria
*The criteria that must be met in order to consider this project a success?*
- Every Cosmos Hub community pool spend proposal audited and report issued for as long as the watchdog committee has ratified authorities from Cosmos Hub stakeholders
- The creation of a sortition pool of at least 50 verified stakeholders 

### User Stories

- As an ATOM stakeholder, I want to sign up to audit community projects so that I can be selected to participate in the watchdog committee.
- As a sortition candidate, I want to be alerted when I have the opportunity to participate in the watchdog committee so that I can declare my attendance.    
- As an auditor, I want to be compensated for my time so that I can spend the time to participate in the watchdog committee without incurring an opportunity cost.    
- As an auditor, I want access to artifacts and 1:1s with team members of the project that I am auditing so that I can be informed about what is happening on the project.    
- As an auditor, I want to be able to ask domain-experts questions that I have so that I can effectively write reports.    
- As an auditor, I want to be able to fill in a template to present my findings so that I don't have to spend too much energy or time on this process.  
- As an auditor, I want guidance about how to analyze projects so that I can perform my role well.  
- As a facilitator, I want to be able to send a form for sortition candidates to fill out so that I can quickly build a pool of sortition candidates without doing too much manual work.  
- As a facilitator, I want to send a form for sortition candidates to fill out so that I can quickly build a pool of sortition candidates without doing too much manual work.  
- As an ATOM stakeholder, I want to preserve my privacy when proving that I am a stakeholder so that I can feel safe and secure.  
- As an ATOM stakeholder, I want to know that projects are being audited by stakeholders with skin in the game so that I can feel more confident in their results.  
- As a facilitator, I want to randomly select sortition candidates from the sortition pool so that I can invite them to participate in sortition.  
- As an ATOM stakeholder, I want assurance that the sortition process is truly random so that I know that the process isn't corrupted. 
- As an ATOM stakeholder, I want to see reports about what the watchdog committee does so that I can asses if its fulfilling its mandate. (The committee has the burden to prove its work).
- As a facilitator, I want to teach sortition-selected candidates how to analyze projects so that they can do their job well, and therefore so can I.  
- As a facilitator, I don't want to answer the same questions over and over again so that I waste time that could be better spend doing something else.  
- As a facilitator, I want to be compensated for my work so that I'm able to do it to the best of my ability and with full commitment.  
- As an ATOM stakeholder, I want to publicly raise questions to the watchdog commitee so that I can be sure they are doing their job well.
- As an ATOM stakeholder, I want to disolve the watchdog committee if they are not living up to their mandate so that the committee doesn't have irreversible power. 
- As a facilitator, I want to interface with the community in a space that has low signal and high noise so that I don't waste time. 

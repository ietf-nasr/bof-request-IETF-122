# Name: NASR - Network Attestation for Secured foRwarding

## Description

<!-- Replace this with a few paragraphs describing the BOF request.
Fill in the details below. Keep items in the order they appear here.-->

In the current network deployments, communicating entities implicitly rely on peer entities and use paths as determined by the control plane.
These available path(s) are implicitly trusted.
Communicating entities have very little information about the entities in the paths over which their traffic is carried, and have no available means to audit the entities and paths, beyond basic properties like latency, throughput, and congestion.
However, increased demand in network security, privacy, and robustness makes tools for enabling visibility of the entities' security posture a necessity.

Path-agnostic traffic signing and encryption has been the primary method to ensure data confidentiality, integrity and authenticity today.
However, with the increasing amount of attacks, and vulnerabilities, new emerging threats are imposing requirements that go beyond the data security currently provided.

With these additional security and privacy requirements, there is a need to provide enhanced or added services beyond the pure encryption-based data security; requiring better visibility of the security posture of the underlying network elements.
Specifically, to satisfy the visibility of the network elements' security state, proof that data is traversed through network elements (devices, links and services) that satisfy security posture claims to avoid exposure of unqualified elements is needed.

## Required Details
- Status: WG Forming
- Responsible AD: Deb Cooley
- BOF proponents: Luigi Iannone (luigi.iannone@huawei.com); Nancy Cam-Winget (ncamwing@cisco.com)
- Number of people expected to attend: 150
- Length of session (1 or 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
  - Chair Conflicts: LISP; 6LO; SCIM, WIMSE, OAUTH, SPICE, TEEP
  - Technology Overlap: RATS; PANRG; SAVNET, SIDROPS
  - Key Participant Conflict:  OAUTH, SCITT, SPRING, RTGWG


## Information for IAB/IESG

<!-- 
To allow evaluation of your proposal, please include the following items:
- Any protocols or practices that already exist in this space:
- Which (if any) modifications to existing protocols or practices are required:
- Which (if any) entirely new protocols or practices are required:
- Open source projects (if any) implementing this work:
-->

The proponents believe that a new working group is required.
Since the previous non-WG forming BoF in IETF 120, the proponents have been meeting to provide a proposed charter that describes the problem statement and initial scope.
In accordance to the feedback received from the IAB the intended work has been presented at PANRG during IETF 121.
Some drafts have also been authored by individuals to serve as starting points to highlight the current challenges and proposed use cases that can be used to reinforce the problem statement and proposed charter.
Presentation and discussion on the changes since the previous BoF and progress on these items will be part of the agenda.

- Any protocols or practices that already exist in this space:
  - Technology developed by the RATS WG is relevant to this proposal.
- Which (if any) entirely new protocols or practices are required:
  - Evidence collection and verification for path attestation.
  - Proof of transit technology.

## Agenda

- Note Well and Agenda Bashing - Chairs
- Why are we here? - Chairs
  - Summary feedback previous BoF and how concerns have been addressed
- Internet-Drafts, speakers, timing
  - TBD
- Open Mic Discussion
  - Feedback from the community
- Explore consensus and next steps

## Links to the mailing list, draft charter if any, relevant Internet-Drafts, etc.
- Mailing List: https://www.ietf.org/mailman/listinfo/nasr
- Draft charter: https://github.com/ietf-nasr/NASR-Charter
- Relevant Internet-Drafts:
  - Requirements:
    - https://datatracker.ietf.org/doc/draft-liu-nasr-requirements/
  - Architecture:
    - https://datatracker.ietf.org/doc/draft-liu-nasr-architecture/
  - NASR Service Model:
    - In progress
  - Path Attestation Claims Set:
    - In Progress
  - Proof of Transit:
    - Revision of https://datatracker.ietf.org/doc/draft-iannone-spring-srv6-pot/

## Previous Discussions/Meetings  

### Agenda/Material/Minutes of the listed meetings can be found [HERE](https://github.com/ietf-nasr/NASR-Meetings)

- NASR Interim Meeting 26 Feb 2025 (Scheduled)
- NASR Interim Meeting 12 Feb 2025 (Scheduled)
- NASR Interim Meeting 22 Jan 2025 (Scheduled)
- NASR Interim Meeting 08 Jan 2025
- NASR Interim Meeting 11 Dic 2024
- NASR Interim Meeting 27 Nov 2024
- NASR Side meeting @ IETF 121
- NASR not WG forming BOF @ IETF 120
- Path Validation Side Meeting @IETF 118.
- NASR Side Meeting @IETF 119

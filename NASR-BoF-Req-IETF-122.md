# Name: NASR - Network Attestation for Secured foRwarding

## Description

<!-- Replace this with a few paragraphs describing the BOF request.
Fill in the details below. Keep items in the order they appear here.-->

In the current network deployments, communicating entities implicitly rely on peer entities and use paths as determined by the control plane.
These available path(s) are implicitly trusted.
Communicating entities have very little information about the entities in the paths over which their traffic is carried, and have no available means to audit the entities and paths, beyond basic properties like latency, throughput, and congestion.
However, increased demand in network security, privacy, and robustness makes tools for enabling visibility of the entities' security posture a necessity.

Path-agnostic traffic signing and encryption has been insofar the primary method to ensure data confidentiality, integrity and authenticity. However, an increasing amount of attacks, vulnerabilities, and new emerging requirements are deeming the data security provided by such methods insufficient

Clients with high security and privacy requirements are not anymore satisfied with pure encryption-based data security measures, having no confidence of the security aspects of the underlying network elements. Clients now require proofs that data traverse through security-satisfying network elements (devices, links and services), avoiding any exposure to unqualifying elements. Clients would like to propose security requirements, such as paths composed of devices with the latest security updates, have passed integrity checks, or routes confined within specific geographical areas. Accordingly, operators should provide verifiable proofs to the clients for operational visualization, internal inspection and external auditing.


## Required Details

- Status: WG Forming
- Responsible AD: Deb Cooley
- BOF proponents: Luigi Iannone (luigi.iannone@huawei.com); Nancy Cam-Winget (ncamwing@cisco.com)
- Number of people expected to attend: ~100
- Length of session (1 or 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: LISP; 6LO; 
   - Technology Overlap: RATS; PANRG; 
   - Key Participant Conflict:  OAUTH, SCITT, SPRING, RTGWG, SAVNET, SIDROPS
     
## Information for IAB/IESG

<!-- 
To allow evaluation of your proposal, please include the following items:
- Any protocols or practices that already exist in this space:
- Which (if any) modifications to existing protocols or practices are required:
- Which (if any) entirely new protocols or practices are required:
- Open source projects (if any) implementing this work:
-->

Since the previous non-WG forming BoF in IETF 120, the group of interested person have worked on the feedback received. Clarification on the difference with SAVNET has been agreed. Presentation of the effort in the PAN RG has been done in IETF 121. Scope has been revised to clarify that NASR will focus on accountable forwarding, not working on new routing proposals. Problem statement has been refine accordingly. Various interested persons are actively working on various items, like the architecture, the service model, an use-case and requirement document. Presentation and discussion on the changes since the previous BoF and progress on these items will be part of the agenda.

- Any protocols or practices that already exist in this space:
  - Technology developed by the RATS WG  is relevant to this proposal.
- Which (if any) modifications to existing protocols or practices are required:
  - May be some extension to RATS.
- Which (if any) entirely new protocols or practices are required:
  - Evidence collection and verification for path attestation
  - Proof of transit technology
- Open source projects (if any) implementing this work
  - None

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

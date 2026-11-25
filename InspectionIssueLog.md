
# SRS Inspection Issue Log

**Inspecting Team:** GirlCode  
**Document Inspected:** NewGrant Draft SRS (8.zip)  
**Inspection Date:** November 23, 2026  
**Status:** Inspection meeting complete

## 1. Purpose

This log records the concerns raised during the November 23, 2026 inspection of the NewGrant draft SRS. Each entry identifies the section reviewed and describes what the reviewers found or questioned.

## 2. Inspection Issue Log

| Issue ID | File / Section | Issue Type | Description | Severity | Status |
|---|---|---|---|---|---|
| INS-01 | 1.2 – Document Conventions | Organization or traceability issue | Reviewers found the evidence citations hard to read and follow. | Minor | Preliminary |
| INS-02 | 1.3 – Project Scope | Unclear terminology | Reviewers could not tell what the grant program abbreviations stood for in this section. | Minor | Preliminary |
| INS-03 | 2.3 – Operating Environment | Possible incomplete requirement | Reviewers questioned whether the operating environment was described in enough detail to guide implementation. | Minor | Preliminary |
| INS-04 | 2.5 – Assumptions and Dependencies | Possible incomplete requirement | Reviewers asked what happens to NewGrant if an external service it relies on becomes unavailable. | Minor | Preliminary |
| INS-05 | 3.1.1 – Log In | Possible incomplete requirement | Reviewers questioned whether the use case covers both failed sign-in attempts and attempts to access something the user does not have permission to use. | Major | Preliminary |
| INS-06 | 3.3.2 – View Grant Cycle | Mock-up access issue | Some reviewers could not view the mock-up during the meeting. It was unclear whether the problem was in the document or how it was shared. | Minor | Preliminary |
| INS-07 | 3.3.4 – Delete Grant Cycle | Unclear requirement | Reviewers questioned whether a grant cycle needs to be deleted and, if so, what information must be kept or can be recovered. | Major | Preliminary |
| INS-08 | 3.3.5 – Accept Late Application | Organization or traceability issue | The use case appeared to be missing links to relevant business rules already listed in Appendix B. | Minor | Preliminary |
| INS-09 | 3.3.5 – Accept Late Application | Conflicting stakeholder evidence | It was unclear whether the CoR Chair must approve a late application or only be consulted. | Major | Preliminary |
| INS-10 | 3.2.1 and 3.4.1; BR-5 | Possible inconsistency | Reviewers questioned how the eligibility verification rule applies when HR verification is unavailable and the application is stored. | Major | Preliminary |
| INS-11 | 3.4.3 – Edit Application | Unclear requirement | If an application is edited while approval is in progress, it is unclear which version receives sign-off. | Major | Preliminary |
| INS-12 | 3.4.4 and 3.6.1; BR-7 and BR-8 | Possible inconsistency | The cited sections and rules appeared to disagree on whether an applicant can withdraw an application after it has been declined. | Major | Preliminary |
| INS-13 | 3.6.3 – Reassign Approver | Unconfirmed approval authority | Reviewers could not confirm the authority for assigning the Dean as approver when the Department Chair is unavailable. | Major | Preliminary |
| INS-14 | 4.3 and 5.2 – HR/SIS Integration | Inconsistent requirements | Section 4.3 describes checking both HR and SIS, while Section 5.2 says SIS is not used in the current release. | Major | Preliminary |
| INS-15 | 5.2 – Software Interfaces | Assumption to validate | The time between email retries and the total retry period are identified as analyst assumptions, not stakeholder-confirmed targets. | Minor | Preliminary |

## 3. Issue Types

The Issue Type column describes the concern raised during the inspection, such as unclear wording, a possible gap in a requirement, conflicting information, or difficulty tracing a requirement to its source. INS-06 records a problem viewing a mock-up, and INS-15 records an assumption to validate. Neither entry is a confirmed defect.

## 4. Severity Guidelines

- **Major:** A concern that could change what the system does, who can approve an action, what data is kept, or how a requirement is tested.
- **Minor:** A concern about wording, organization, or documentation where the reviewers did not identify a significant effect on system behavior.

After the meeting, the 15 concerns were rated by potential impact: 8 Major and 7 Minor. A severity rating does not mean the concern is a confirmed defect.

## 5. Inspection Notes

- Late applications (INS-08 and INS-09): Reviewers raised two separate concerns: which business rules apply, and whether the CoR Chair must approve a late application or only be consulted.
- Application sign-off (INS-11): Reviewers could not tell which version is approved if an applicant edits the application while approval is in progress.
- HR/SIS integration (INS-14): Section 4.3 describes checking both HR and SIS, but Section 5.2 says SIS is not used in the current release. The two sections need to agree on which systems are used.

## 6. Final Status

The November 23 inspection ended in conditional acceptance of the NewGrant draft SRS. This log records the 15 concerns raised during the inspection.

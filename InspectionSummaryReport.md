
# SRS Inspection Summary Report

## 1. Inspection Information

| Field | Details |
|---|---|
| Inspecting Team | GirlCode |
| Inspected Document | NewGrant Draft SRS (8.zip) |
| Inspection Date | November 23, 2026 |
| Scheduled Time | 2:00–4:00 PM EST |
| Meeting Format | Online (Zoom) |
| Inspection Status | Inspection Completed — Reports Finalized |
| Inspection Recording | Recording submitted separately |

## 2. Inspection Participants and Roles

| Participant | Role |
|---|---|
| Hafsa Khan | Moderator / Inspector |
| Zion Akakpo (Faith) | Reader 1 / Inspector |
| Sadika Wafiha | Co-Reader / Inspector |
| Spogmay Mohamedi | Recorder / Inspector |

All four members attended the recorded inspection meeting and participated in reviewing and discussing the assigned SRS.

Faith reviewed Sections 1, 2, 6.5, and Appendix B during the meeting. Sadika presented Sections 3, 4.3, 5.2, and Appendix D. Hafsa moderated the discussion, while Spogmay recorded inspection findings.

## 3. Inspection Objectives

The purpose of this inspection is to identify and document potential defects in the assigned SRS.

The inspection follows the procedures discussed in ITEC 4040 Lecture 5.1 — Validating and Testing Requirements.

The inspection focuses on:

- Completeness
- Correctness
- Quality attributes
- Organization and traceability
- Other relevant requirements issues

The inspection emphasized identifying and documenting defects rather than developing solutions, with findings assessed collaboratively against the specified requirements and supporting evidence.

## 4. Inspection Preparation

Before the meeting, GirlCode distributed the assigned anonymized SRS (8.zip), confirmed participant roles, and prepared the inspection checklist, meeting agenda, and recording arrangements.

All four members completed independent reviews of the SRS using the Inspector's Checklist from Lecture 5.1, focusing on completeness, correctness, quality attributes, organization, and traceability.

The reported individual preparation times were:

| Participant | Approximate Preparation Time |
|---|---|
| Hafsa Khan | 2 hours |
| Faith (Zion Akakpo) | 1 hour |
| Sadika Wafiha | Approximately 1 hour or slightly more |
| Spogmay Mohamedi | 1 hour 15 minutes |

**Total reported preparation effort:** At least 5 hours 15 minutes, excluding additional meeting coordination and preparation of supporting materials.

The Moderator also prepared a structured meeting script and checklist to guide the inspection procedure.

## 5. Inspection Procedure

The formal inspection was conducted online on November 23, 2026, and recorded for course submission. All four members introduced themselves by voice and confirmed their inspection roles.

The Moderator opened the meeting by explaining the inspection objectives, confirming individual preparation, and establishing discussion guidelines based on Lecture 5.1. These included prioritizing significant requirements defects, maintaining orderly turn-taking, limiting prolonged discussions, and recording issues rather than attempting to resolve them during the meeting.

The Readers guided the team through the assigned SRS sections:

- Faith: Sections 1, 2, 6.5, and Appendix B.
- Sadika: Sections 3, 4.3, 5.2, and Appendix D.

After each section or use case, participants shared interpretations and raised potential defects using the Inspector's Checklist. Findings were discussed collaboratively, including comparisons between related use cases, business rules, interface requirements, and stakeholder evidence.

The Recorder maintained inspection notes, while the Moderator requested clarification of issue locations, encouraged participation, and redirected discussions when necessary to manage time.

The inspection concluded with a review of the findings, a team discussion of the document's overall quality, agreement on an inspection recommendation, and individual lessons learned.

The inspection findings were consolidated into 15 preliminary issue entries in the Inspection Issue Log. Each entry identifies the relevant SRS location, issue type, description, proposed severity, and status.

## 6. Inspection Results

| Metric | Result |
|---|---|
| Total preliminary findings | 15 preliminary findings |
| Major issues | 8 (provisional severity) |
| Minor issues | 7 (provisional severity) |
| Sections inspected | 1, 2, 3, 4.3, 5.2, 6.5, Appendix B, Appendix D |
| Actual meeting duration | 1:48:13 |

The inspection identified 15 preliminary concerns, including 8 classified as Major and 7 as Minor based on their potential impact. These severity classifications do not establish that every concern is a confirmed defect.

The main findings concerned:

- Eligibility verification and application submission consistency (INS-10).
- Withdrawal restrictions and conflicting business rules (INS-12).
- HR/SIS integration inconsistencies (INS-14).
- Late-application approval authority and business-rule traceability (INS-08 and INS-09).
- Application editing and version-specific approval (INS-11).
- Approver reassignment authority (INS-13).
- Authentication, deletion, interface assumptions, and documentation clarity (remaining issue entries).

Some findings were raised across multiple SRS sections and were consolidated into individual entries to avoid duplication.

The detailed descriptions, classifications, and preliminary statuses are recorded in the [Inspection Issue Log](InspectionIssueLog.md).


## 7. Inspection Outcome and Recommendation

**Inspection Outcome: Conditional Acceptance**

Based on the formal inspection conducted on November 23, 2026, the GirlCode inspection team recommends **conditional acceptance** of the NewGrant Draft SRS.

The SRS is generally well structured and provides detailed functional use cases, supporting stakeholder evidence, and relevant system documentation. However, the inspection identified several requirements requiring clarification, correction, or further validation to ensure completeness, consistency, and correctness.

A total of **15 preliminary findings** were documented in the Inspection Issue Log, including **8 Major and 7 Minor concerns**, classified according to their potential impact. The primary concerns involve eligibility verification, application withdrawal, late-application approval authority, approver reassignment, software interface dependencies, and inconsistencies between functional requirements and business rules.

The severity classifications reflect the potential impact of the findings and do not necessarily indicate confirmed defects. Further clarification and stakeholder validation are recommended to resolve ambiguities and verify assumptions.

The inspection team concluded that the identified concerns could be addressed through appropriate revisions and verification without requiring a complete re-inspection at this stage. Therefore, **conditional acceptance is recommended, subject to satisfactory resolution of the documented findings**.

Detailed findings, requirement references, severity classifications, and statuses are provided in the accompanying [Inspection Issue Log](InspectionIssueLog.md).

## 8. Follow-up Actions

| Action | Responsible Party | Target Date |
|---|---|---|
| Finalize and classify Inspection Issue Log findings | Faith and Sadika | November 24, 2026 |
| Finalize Inspection Summary Report | Hafsa and Spogmay | November 24, 2026 |
| Cross-check the Summary Report against the finalized Issue Log | All GirlCode members | November 25, 2026 |
| Prepare anonymized combined PDF (8.pdf) | GirlCode | November 25, 2026 |
| Verify GitHub repository and recording links | GirlCode | November 25, 2026 |
| Submit final inspection deliverables | GirlCode | November 25, 2026, EOD |

The team agreed to complete the reports before final submission. Issues requiring clarification or correction will be documented for the authoring team through the finalized Issue Log.

## 9. Lessons Learned

The inspection highlighted several opportunities to improve future requirements reviews.

**Time Management:** The team recognized that some discussions lasted longer than intended, requiring later sections to be reviewed more quickly. Future inspections would benefit from stricter time allocation and earlier identification of issues requiring follow-up.

**Cross-Requirement Consistency:** Reviewing related use cases and business rules together helped identify inconsistencies that were less apparent when examining individual requirements independently.

**Structured Inspection Procedures:** The Moderator's Checklist and Inspector's Checklist supported an organized review and helped maintain focus on identifying defects rather than developing solutions.

**Collaboration and Participation:** Discussing requirements as a team helped participants recognize unclear wording, assumptions, and inconsistencies that they had not identified during individual preparation. More balanced and interactive participation would further improve future inspections.

**Documentation Practices:** The team found the detailed use cases, diagrams, and mock-ups useful. The inspection also demonstrated the importance of clear evidence links and traceability for efficient requirements validation.

Overall, the exercise reinforced the value of independent preparation, structured discussion, and collaborative requirements verification.

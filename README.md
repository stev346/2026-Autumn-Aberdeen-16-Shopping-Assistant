# CampusCue

**A multimodal campus task assistant**

Mobile Intelligent Applications | Group 16 | Phase One

CampusCue is a proposed mobile application that turns coursework screenshots, classroom audio and documents into task drafts with source references. Students review deadlines, resolve conflicting requirements and confirm reminders. Short video is planned for the next development milestone.

## Team

| Member | Role |
| --- | --- |
| 何嘉俊 | Team leader |
| 王舜祺 | Team member |
| 陈实 | Team member |
| 李文豪 | Team member |

## Phase one deliverables

- [App Business Plan PDF](docs/CampusCue_App_Business_Plan_EN.pdf)
- [Editable business plan text](docs/CampusCue_App_Business_Plan_EN.md)
- [Presentation PowerPoint](presentation/CampusCue_Phase1_EN.pptx)
- [Presentation PDF backup](presentation/CampusCue_Phase1_EN.pdf)
- [English speaker script and Q&A](presentation/Speaker_Notes_EN.md)
- [Interview and validation protocol](research/Validation_Protocol_EN.md)

## Target users and value

The initial users are undergraduate students in one accessible course cohort. The core use case is keeping track of assignment requirements received across multiple sources. Group leaders are a secondary audience.

The proposed value is a checkable coursework workflow: combine sources for an assignment, review extracted requirements against the evidence, resolve uncertainty, then save a confirmed task and reminder. Interviews and prototype tests will evaluate whether this reduces effort compared with current tools.

## Planned scope

| Development milestone | Capabilities |
| --- | --- |
| First | Text, JPG/PNG, text based PDF, DOCX and short audio; structured tasks, source review, explicit date conflicts for a user selected assignment and reminders |
| Second | Short video with audio and selected frames, scanned PDFs and automatic duplicate suggestions |

## Proposed AI workflow

1. Import user selected materials the user is authorised to process.
2. Extract text, image information or timestamped speech.
3. Use existing AI models to produce structured task candidates.
4. Validate fields and display supporting source passages.
5. Ask the user to resolve uncertain dates and confirm the task.
6. Save the confirmed task and schedule the chosen reminder.

## Current status

This repository contains the phase one proposal and presentation. Application development and user validation remain planned work. Reported budgets, performance thresholds and pilot targets are assumptions, not measured results.

## Repository identity

Course organisation: `android-app-development-course`

Planned repository name: `2026-Autumn-Aberdeen-16-CampusCue`

## Development and data handling

The course permits existing AI models. Providers and implementation details will be selected after reviewing cost, accuracy and data handling. Setup instructions will be added when application code is available. API keys, private recordings and participant identities must not be committed.

## References

The business plan includes the source list, competitor comparison and the limits of the available evidence. The proposed workflow is not claimed to be a new foundation model or the first AI task manager.

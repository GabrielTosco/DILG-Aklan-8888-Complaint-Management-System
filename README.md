# DILG Aklan 8888 Complaint Management System

**A role-based web application for recording, assigning, tracking, and resolving citizen complaints.**

Developed as an **On-the-Job Training (OJT) project at the Department of the Interior and Local Government (DILG) – Aklan**.

**Tech stack:** PHP · MySQL · HTML · CSS · JavaScript

![DILG Aklan 8888 Complaint Management System interface](frontpage.png)

## Project overview

The application helps organize the handling of 8888 citizen complaints. Instead of relying on scattered records, the workflow provides a central place to record complaints, attach documents, assign them to local government units (LGUs), track responses, and archive resolutions.

The project focuses on **record management, traceable workflows, and role-based access**.

## Key features

- **Complaint intake and assignment:** Record complaints, attach PDF documents, and assign cases to municipalities.
- **Resolution workflow:** Responders upload resolution documents; encoders review, complete, or reopen cases for revision.
- **Role-based access:** Different permissions for encoders, responders, and read-only viewers.
- **Tracking and organization:** Complaint statuses, timestamps, comments, search, filtering, and document archives.
- **Monitoring tools:** Dashboard analytics and notifications to support administrative follow-up.

## User roles

| Role | Main responsibilities |
| --- | --- |
| **Encoder** | Creates and assigns complaints, reviews resolutions, marks cases complete, or requests revisions |
| **Responder** | Views assigned complaints and uploads or updates resolution documents |
| **Viewer** | Reviews complaint information and downloads available documents without editing records |

## Example complaint workflow

1. An encoder records a complaint and uploads its PDF.
2. The complaint is assigned to the responsible municipality.
3. A responder reviews the assigned complaint and uploads a resolution PDF.
4. The encoder evaluates the response.
5. The complaint is marked **Complete** or reopened for revision.

Tracked statuses include **Received**, **Pending**, and **Complete**.

## Screenshots

<details>
<summary>View application screenshots</summary>

### Complaint management

![Complaint management screen 1](8888p1.png)

### Application workflow

![Complaint management screen 2](8888p2.png)

### Additional interface

![Complaint management screen 3](8888p3.png)

</details>

## Documentation and source

**User manuals**
- [Encoder manual](Documentation/DILG8888_Encoder_Manual.docx)
- [LGU manual](Documentation/DILG8888_LGU_Manual.docx)
- [MLGOO manual](Documentation/DILG8888_MLGOO_Manual.docx)
- [Project presentation](Documentation/Presentation-Complaint-Manager_20260407_103606_0000.pptx)

**Application source**
- [Source code archive (ZIP)](source-code/dilg8888-20260803T050205Z-1-001.zip)

The implementation is currently provided as a ZIP archive in this repository. A browsable source tree and setup guide would make it easier for others to review and reproduce the application.

---

*Built during OJT at DILG Aklan. Project details and screenshots are provided for portfolio and technical review purposes.*

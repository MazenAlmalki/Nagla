# Nagla updates

## 2026-11-08 — Visual business model canvas

- Added a one-page, nine-section canvas using the layout supplied in chat.
- Filled each section with Naqla’s proposed business model and embedded the canvas in the README and business model document.
- Kept the launch scope and commercial model marked as assumptions to validate.

Detailed design decisions and workflow notes are recorded here. For the current focus and project status, see [README.md](README.md).

## 2026-11-08 — Business model drafted

- Added [BUSINESS_MODEL.md](BUSINESS_MODEL.md) covering customer segments, value proposition, marketplace operations, partners, revenue, and costs.
- Included illustrative SAR unit economics, a pilot launch plan, performance metrics, and risks to validate.
- Identified open decisions; Saudi launch scope, pricing, and financial figures remain assumptions.
- Request prompt: “build the busseins model now”.

## 2026-11-08 — Project overview organized

- Added a formatted README describing the current work on `Mazzen`.
- Summarized progress on branding, the customer experience, and the technician experience.
- Kept detailed workflow and prompt records below, and clarified that app implementation has not started in this repository.

## 2026-11-08 — Branding and proposed customer and technician workflows

Branch: `Mazzen`

Status: Design documentation based on the two reference images supplied in chat. These screens and features are proposed; no application functionality has been implemented yet.

### Prompt used

The prompt supplied for this update was:

> add this to the updates also state what prompt i used what the work flow for both the user and tecnion s

Branch instruction:

> only edit the mazen branch

The target branch was subsequently clarified as `Mazzen`: https://github.com/MazenAlmalki/Nagla/tree/Mazzen.

The original prompts used to generate the reference images were not supplied. The prompt above records the documentation request, not an image-generation prompt.

### Brand direction

- Name: نقلة / Naqla (repository name: Nagla).
- Logo: an N-shaped mark incorporating a doorway and a moving box, with Arabic and English wordmarks.
- Variants shown: full-color logo, monochrome logo, standalone icon, and app icon preview.
- Palette shown: dark navy `#102B36`, teal `#19A69C`, lime `#CFF26B`, white `#FFFFFF`, and pale mint `#EEF4F0`.
- The customer screens use teal and lime; the technician screens use blue to distinguish the two roles.

### Customer workflow — رحلة المستخدم (العميل)

1. **Explore and register:** Access the app, create an account, and open a dashboard showing moving-plan progress and the next task.
2. **Create a moving plan:** Set the moving date and follow a checklist covering preparation, moving day, and after the move. Tasks include inventorying rooms, choosing a moving company, arranging home services, and preparing packing supplies.
3. **Inventory belongings:** Photograph rooms and use the proposed AI room scan to identify furniture and other items. Review the detected items, add missing items manually, and choose an action such as moving or replacing each item. Save the inventory to update the plan.
4. **Choose services:** Compare and book moving companies, and arrange services for the new home, including electricity, internet, water, or other services. Review active requests in one place.
5. **Schedule and pay:** Confirm the service appointment and payment as shown in the journey overview. Detailed payment screens and payment methods are not specified in the reference.
6. **Track execution:** Follow the request status live and communicate with the assigned technician when needed.
7. **Complete and rate:** Confirm completion of the move or service and rate the experience.

Customer features shown include AI room scanning, a moving checklist, provider comparison and booking, home-service management, live tracking, and a central view of requests and belongings.

### Technician workflow — رحلة الفني (الموظف)

1. **Receive assigned tasks:** Open the dashboard to see today's tasks, pending work, and completed jobs. Use the task list to review new, in-progress, and completed requests.
2. **Review job details:** Inspect the request number, pickup and destination addresses, appointment time, property/access notes, and inventory of items.
3. **Accept the task:** Accept the request after reviewing its details and coordinate with the customer as needed.
4. **Perform the move:** Collect the belongings, transport them, arrive at the new address, and hand over the items.
5. **Update status live:** Record progress through collection, transport, arrival, and delivery so the customer can follow the job.
6. **Complete and report:** Mark the request as delivered and completed, then access the job report and customer rating.
7. **Manage daily work:** Use the profile and schedule views to review appointments, completed-job counts, performance, ratings, and settings.

Technician features shown include task management, addresses and inventory details, live status updates, customer communication, daily scheduling, and performance tracking.

### Reference material

- Image 1 supplied in chat: bilingual logo, logo variants, app icon preview, and color palette.
- Image 2 supplied in chat: customer and technician mobile screen concepts and journey overviews.
- The images are referenced here as design sources; image files have not been added to the repository.

# Houzz Pro Project Management Workflow

This reference outlines the operational procedures for managing projects, creating estimates, building schedules, and logging daily work in Houzz Pro.

## 1. Project Planning & Estimation

### Step 1: Pre-Estimation Job Costing
Before creating an estimate in Houzz Pro, you **must** use the `rsmeans-cost-estimator` skill to determine accurate job costing, labor hours, and material pricing based on the project scope.

### Step 2: Granular Breakdown
Estimates must include a highly granular breakdown of all necessary steps. For example, a painting task should explicitly list caulking, puttying, sanding, priming, and multiple finish coats.

### Step 3: Creating the Estimate in Houzz Pro
1.  Navigate to the specific Project and select **Estimates**.
2.  Choose the creation method:
    *   **From Scratch/Template:** Manually input the data gathered from the RSMeans analysis.
    *   **AutoMate AI (Voice/Text):** Input a detailed text prompt describing the RSMeans data, and allow the AI to generate the edit-ready line items.
3.  **Review:** Ensure the estimate is clear, professional, and free of internal reference data (like target builder costs) before presenting it to Wade for approval.

## 2. Scheduling

### Creating the Schedule
1.  Once an estimate is approved by the client, navigate to **Schedule**.
2.  Use **AutoMate AI** to instantly convert the approved Estimate into a full Schedule.
3.  **Client Expectations:** Always adjust the schedule to reflect the higher end of the time estimates (determined during the RSMeans phase) to provide the client with reasonable expectations.
4.  **Dependencies:** Ensure finish-to-start dependencies are correctly linked (e.g., drywall must finish before painting starts).

### Workday Exceptions
Ensure the schedule accounts for non-working days by configuring Workday Exceptions in the company settings (`https://pro.houzz.com/manage/projects/workday-exceptions`).

## 3. Daily Operations

### Daily Logs
Field crews (or Wade) should provide daily updates.
1.  Navigate to **Daily Logs**.
2.  Input the raw notes, crew hours, and attach photos.
3.  Use **AutoMate AI** to clean up the text, improve clarity, and fix spelling errors.
4.  Review the AI's suggestions for follow-up tasks based on the log content and add them to the **Tasks & Punchlist**.

### Tasks & Punchlist
-   Break down the project into actionable to-dos.
-   Assign tasks to specific team members or subcontractors with clear due dates.

## 4. Visualizations (Takeoffs & 3D Plans)
-   **Takeoffs:** Upload PDF plans. Use AutoMate AI (on eligible simplified plans) to automatically detect spaces and calculate area/length measurements.
-   **3D Floor Plans:** Upload 2D plans and use AutoMate AI to generate detailed 3D models to help clients visualize the design.

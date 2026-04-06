# Implementation Plan: Insurance Policy Admin 

Based on the highly detailed analysis of the stunning new UI mockup, I've outlined the exact structural and stylistic approach to writing the codebase for the **Insurance Policy Admin** dashboard.

## User Review Required

> [!IMPORTANT]
> Since we are creating a completely new interface from scratch, please review the structural breakdown below. If you approve, I will automatically generate the code files for you!

## Proposed Changes

We will be creating two new files in the `apps/insurance-policy-admin/src/` directory.

#### [NEW] [index.html](file:///c:/Users/jiten/OneDrive/Desktop/Learning/Courses/MIT%20Agentic%20AI%202026/Module%202/mit-agentic-ai-module-2/apps/insurance-policy-admin/src/index.html)
- **Top Navigation Bar**: Featuring the "InsuraSure" branding, main navigation links (with 'Dashboard' active), a pill-shaped search bar, and the user profile dropdown.
- **Asymmetrical Grid Layout (70/30 split)**:
  - **Left Column (Dashboard Area)**:
    - Title breadcrumbs showing the Policy Number and Name.
    - Side-by-side **Policy Summary Grid** and stacked **Key Highlight Rows** (Face Amount, Cash Value, Next Premium).
    - A comprehensive **Transactions Data Table** at the bottom (Date, Type, Description, Amount, Status) with pagination widgets.
  - **Right Column (Contextual Content)**:
    - **Owner Details Card**: Profile photo, name, age, icon-based contact info (phone, address, email), and an "Edit" ghost button.
    - **Agent Details Card**: Profile photo, name, agent ID, and identical icon-based contact info.

#### [NEW] [style.css](file:///c:/Users/jiten/OneDrive/Desktop/Learning/Courses/MIT%20Agentic%20AI%202026/Module%202/mit-agentic-ai-module-2/apps/insurance-policy-admin/src/style.css)
- **Theme**: Premium Enterprise Light Mode.
- **Color Palette**: 
  - Background: Ultra-light gray-blue (`#F4F7F9`).
  - Cards: Pure White (`#FFFFFF`) with subtle rounded corners (10px) and soft shadow elevation.
  - Primary Accent: Corporate Blue (`#0056D2`).
- **Pill Badges**: Implementing specific styles for dynamic states (e.g., Pale Green background with Dark Green text for "Active" and "Processed" statuses).

## Verification Plan
Once created, you will be able to verify the design looks like a premium enterprise App by opening `apps/insurance-policy-admin/src/index.html` in your browser.

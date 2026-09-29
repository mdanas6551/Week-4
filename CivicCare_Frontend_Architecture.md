# CivicCare – Your Voice. Our Responsibility.

## Project Overview

**CivicCare** is a citizen-focused public grievance portal frontend concept.

- **Project Type:** Frontend Only
- **Technology:** HTML5 + CSS3
- **Data:** Mock / Sample Data
- **Backend:** Not included
- **Database:** Not included
- **APIs:** Not included
- **Real Authentication:** Not included
- **Government Integration:** Not included

## Brand Identity

- **Name:** CivicCare
- **Tagline:** Your Voice. Our Responsibility.
- **Style:** Modern government-style, professional, trustworthy, citizen-friendly
- **Primary Colors:** Blue and White
- **Visuals:** Realistic civic/public-service imagery

## Website Pages

1. Home
2. Submit Complaint
3. Complaint Categories
4. Complaint Details
5. Track Complaint
6. Citizen Dashboard
7. About CivicCare
8. Departments / Services
9. Contact / Help Center
10. Login
11. Sign Up

## Header / Navigation

Classic government header:

- Left: CivicCare logo / wordmark
- Center: Home, Submit Complaint, Categories, Track Complaint, Dashboard, Departments, About, Contact
- Right: Login and Sign Up

Requirements:
- Clear active-page indicator
- Responsive layout
- High contrast
- Keyboard accessible
- Visible focus states

## Home Page

### Hero

Heading:
> Your Voice. Our Responsibility.

Supporting text:
> Report public issues, track your complaints, and stay informed about your service requests.

Primary CTA: **Submit a Complaint**  
Secondary CTA: **Track Complaint**

### Large Service Search

Placeholder:
> Search for a complaint or public service...

Search should help citizens find complaint categories, services, and departments.

### Complaint Categories

Use simple cards for:

- Roads and Potholes
- Water Supply
- Electricity and Street Lights
- Garbage and Sanitation
- Drainage
- Public Transport
- Public Infrastructure
- Government Services
- Other Public Issues

### How CivicCare Works

```text
1. Report    → Submit your public complaint.
2. Review    → Complaint enters the review process.
3. Track     → Follow progress using your Complaint ID.
4. Resolve   → View the final complaint status.
```

## Complaint Categories Page

Use simple cards. Each card contains:

- Icon
- Category name
- Short description
- Report Issue action

## Submit Complaint

Use a **four-step wizard form**.

### Step 1 — Complaint Information

Fields:
- Complaint Category
- Complaint Title
- Complaint Description

### Step 2 — Location

Fields:
- Address / Location
- Area / Locality
- City
- Additional Location Details

### Step 3 — Supporting Evidence

Frontend placeholder for:
- Photo upload
- Document upload
- Additional information

> No real file processing is implemented.

### Step 4 — Review & Submit

Show a summary of the entered information.

Mock confirmation:

```text
Complaint Submitted Successfully

Complaint ID: CC-2026-00125
Status: Submitted
```

> Complaint IDs and results are sample/mock content.

## Complaint Details Page

Use a **status-focused layout**.

Show:

- Complaint ID
- Category
- Title
- Description
- Location
- Submission date
- Current status
- Last updated date
- Supporting evidence placeholder

### Supported Sample Statuses

```text
Submitted
Under Review
Assigned
In Progress
Resolved
Closed
```

### Progress Timeline

```text
✓ Submitted
  Complaint received

✓ Under Review
  Complaint reviewed

✓ Assigned
  Assigned for further action

● In Progress
  Currently being processed

○ Resolved
  Pending

○ Closed
  Pending
```

## Track Complaint Page

Require both:

- Complaint ID
- Mobile Number

Example:

```text
Complaint ID: [ CC-2026-00125 ]
Mobile Number: [ Enter mobile number ]
[ Track Complaint ]
```

Result should show mock complaint information and a link to Complaint Details.

## Citizen Dashboard

Use a **service dashboard** layout.

### Main Areas

- Total Complaints
- Active Complaints
- Resolved Complaints
- Complaint History
- Notifications
- Service Shortcuts

### Status Cards

Example:

```text
Active Complaints
3
Currently being processed
```

```text
Resolved Complaints
5
Successfully resolved
```

```text
Total Complaints
8
All submitted complaints
```

### Notifications

Use simple notification cards.

Example:

```text
Complaint Update
Complaint CC-2026-00125 has moved to In Progress.
Sample Date
```

## Departments / Services Page

Use **Search + Filter**.

Search placeholder:

```text
Search departments or services...
```

Example filters:

- All
- Roads
- Water
- Sanitation
- Transport
- Infrastructure
- Government Services

Use generic/sample department names. Do not present invented names as real government departments.

## About CivicCare

Use a professional organization-page structure.

### Mission

> To provide citizens with a simple and accessible way to report, understand, and track public issues.

### Services

- Complaint submission
- Complaint tracking
- Citizen dashboard
- Public service discovery
- Citizen support

### Values

- Accessibility
- Transparency
- Simplicity
- Responsibility
- Citizen Focus

### Process

```text
Report → Review → Assignment → Progress → Resolution
```

## Contact / Help Center

Use a **government help center** design.

Include:

- Support information
- Sample contact details
- FAQs
- Support form

FAQ examples:

- How do I submit a complaint?
- How can I track my complaint?
- Where can I find my Complaint ID?
- Can I update my complaint?
- How do I contact support?

Support form fields:

- Name
- Email
- Subject
- Message

> Contact information must be clearly treated as sample content.

## Login

Use a formal government-style login layout.

Fields:

- Email / Mobile Number
- Password

Options:

- Remember Me
- Forgot Password?

CTA: **Login**

Additional link: **Create an account**

> Authentication is frontend-only and non-functional.

## Sign Up

Fields:

- Full Name
- Email
- Mobile Number
- Password
- Confirm Password

CTA: **Create Account**

> Registration is frontend-only and non-functional.

## Footer

Use a **government-style footer** with:

### CivicCare

```text
CivicCare
Your Voice. Our Responsibility.
```

### Quick Links

- Home
- About
- Contact
- Categories

### Citizen Services

- Submit Complaint
- Track Complaint
- Dashboard
- Departments

### Support

- Help Center
- FAQs
- Contact Support

Bottom:

```text
© 2026 CivicCare
Frontend Concept — Sample Data
```

## Navigation Flow

```text
                         HOME
                          |
        ------------------------------------
        |          |          |            |
   Categories   Submit     Track       Dashboard
                  |          |            |
              Wizard     Complaint      Services
                  |       Details          |
                  |          |       -------------
                  |          |       |     |     |
                  |          |   Complaints Depts Notifications
                  |
              Complaint
               Details

        ------------------------------------
        |                 |                |
      About            Contact         Login / Sign Up
```

## Main User Journey — Submit Complaint

```text
Home
 ↓
Submit Complaint
 ↓
Step 1: Complaint Information
 ↓
Step 2: Location
 ↓
Step 3: Evidence
 ↓
Step 4: Review
 ↓
Submit
 ↓
Sample Complaint ID
 ↓
Complaint Details
```

## Main User Journey — Track Complaint

```text
Home
 ↓
Track Complaint
 ↓
Enter Complaint ID
 ↓
Enter Mobile Number
 ↓
Track
 ↓
Complaint Status
 ↓
Complaint Details
```

## Responsive Design

The website must support:

- Desktop
- Laptop
- Tablet
- Mobile

Use a responsive header and responsive cards.

Cards should stack on smaller screens. Forms should use available width and avoid horizontal scrolling.

## Accessibility

Use an **advanced accessibility-focused structure**.

### Semantic HTML

Use:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

### Requirements

- Proper form labels
- Keyboard navigation
- Visible focus states
- Good text/control contrast
- Large clickable areas
- Screen-reader-friendly structure
- Descriptive image alt text
- Status indicators that do not rely only on color

Example:

```text
✓ Resolved
● In Progress
○ Pending
```

## Civic Images

Use realistic civic/public-service imagery related to:

- Roads
- Potholes
- Water supply
- Street lights
- Garbage collection
- Drainage
- Public infrastructure
- Public transportation

Images should support the content and include appropriate alt text.

## UI Component System

### Buttons

- Primary Button
- Secondary Button
- Outline Button
- Text Link

### Cards

- Category Card
- Status Card
- Notification Card
- Service Card
- Information Card

### Form Components

- Text Input
- Select
- Textarea
- File Upload Placeholder
- Checkbox
- Radio Button
- Form Step Indicator

### Status Components

- Submitted
- Under Review
- Assigned
- In Progress
- Resolved
- Closed

## Suggested Project Folder Structure

```text
civiccare/
│
├── index.html
│
├── pages/
│   ├── submit-complaint.html
│   ├── categories.html
│   ├── complaint-details.html
│   ├── track-complaint.html
│   ├── dashboard.html
│   ├── about.html
│   ├── departments.html
│   ├── contact.html
│   ├── login.html
│   └── signup.html
│
├── css/
│   ├── style.css
│   ├── responsive.css
│   └── components.css
│
├── images/
│   ├── hero/
│   ├── roads/
│   ├── water/
│   ├── sanitation/
│   ├── infrastructure/
│   └── transport/
│
└── README.md
```

## CSS Architecture

### Global

- CSS Variables
- Reset
- Typography
- Body
- Links

### Layout

- Container
- Grid
- Flexbox
- Sections
- Spacing

### Components

- Header
- Footer
- Buttons
- Cards
- Forms
- Status
- Timeline
- Notifications

### Responsive

Use CSS media queries for:

- Desktop
- Tablet
- Mobile

## Design Principles

1. **Simple** — Citizens should understand each page quickly.
2. **Professional** — Use a clean government-service visual language.
3. **Trustworthy** — Keep information structured and transparent.
4. **Accessible** — Support keyboard navigation, screen readers, readable text, and sufficient contrast.
5. **Responsive** — Support desktop, tablet, and mobile screens.
6. **Consistent** — Reuse the same header, footer, buttons, cards, and typography.
7. **Citizen-first** — Prioritize submitting and tracking complaints.
8. **No false government claims** — Use sample/mock government data only.
9. **Frontend-only** — Clearly distinguish UI demonstrations from real functionality.
10. **Smooth navigation** — Connect all major pages through clear links and CTAs.

## Final Architecture Summary

```text
CIVICCARE
│
├── Home
│   ├── Hero
│   ├── Service Search
│   ├── Complaint Categories
│   ├── How It Works
│   └── Citizen Support
│
├── Submit Complaint
│   ├── Step 1: Complaint Information
│   ├── Step 2: Location
│   ├── Step 3: Evidence
│   └── Step 4: Review & Submit
│
├── Complaint Categories
│   └── Category Cards
│
├── Complaint Details
│   ├── Complaint Information
│   ├── Current Status
│   ├── Status Cards
│   └── Progress Timeline
│
├── Track Complaint
│   ├── Complaint ID
│   ├── Mobile Number
│   └── Sample Status Result
│
├── Citizen Dashboard
│   ├── Complaint Summary
│   ├── Status Cards
│   ├── Complaint History
│   ├── Notifications
│   └── Service Shortcuts
│
├── Departments / Services
│   ├── Search
│   ├── Filters
│   └── Service Cards
│
├── About CivicCare
│   ├── Mission
│   ├── Services
│   ├── Values
│   └── Process
│
├── Contact / Help Center
│   ├── Support Information
│   ├── FAQs
│   └── Contact Form
│
├── Login
│
└── Sign Up
```

## Final Technical Scope

### Included

- HTML page architecture
- CSS styling
- Responsive layouts
- Navigation links
- Forms
- Mock complaint data
- Mock status tracking
- Mock dashboard
- Mock notifications
- Civic imagery placeholders
- Accessibility structure
- Reusable UI components

### Not Included

- Backend
- Database
- APIs
- Real authentication
- Real government systems
- Real complaint processing
- Real file storage
- Real SMS/Email notifications
- Real location services

## Project Goal

Build a clean, professional, accessible, and responsive **CivicCare citizen grievance portal frontend** that demonstrates how citizens can discover public services, submit complaints, track complaint progress, and access citizen support through a simple and connected user experience.

**CivicCare — Your Voice. Our Responsibility.**

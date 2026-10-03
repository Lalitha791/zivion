Sure. Here is **only the README matter**, clean and ready to paste into `README.md`.

# ZIVION

## Property & Facility Management Platform

ZIVION is a centralized property and facility management platform that connects **Properties/RWAs, Residents, Zivion Teams, Agencies, Technicians, and Security Personnel** through dedicated mobile applications and web portals.

The platform helps manage residential communities, residents, maintenance services, workforce, security operations, visitors, deliveries, vehicles, amenities, documents, contracts, and service requests from a single ecosystem.

---

## Applications

### Resident App

Used by property owners, tenants, and family members.

**Features:**
- Registration and Login
- Property and Unit Information
- Owner/Tenant Profile
- Family Management
- Cases and Service Requests
- Work Order Tracking
- Visitor Management
- Gate Pass
- OTP and QR Verification
- Delivery Management
- Vehicle Management
- Amenities and Clubhouse
- Documents
- Notifications
- Feedback

### Agency App

Used by external service agencies to manage maintenance operations and workforce.

**Features:**
- Agency Dashboard
- Work Orders
- Service Requests
- Job Assignment
- Technician Management
- Workforce Management
- Scheduling
- Service Categories
- SLA Monitoring
- Technician Performance
- Properties Served
- Contracts
- Documents
- Reports
- Notifications
- Agency Profile

### Security App

Used by security personnel to manage community security operations.

**Features:**
- Visitor Verification
- Gate Pass Verification
- QR Scanning
- OTP Verification
- Visitor Entry and Exit
- Vehicle Entry and Exit
- Delivery Management
- Staff and Domestic Help Entry
- Cab and Driver Entry
- Incident Management
- Emergency Alerts
- Shift Management
- Shift Handover
- Visitor History

---

## Web Portals

### Resident Portal

Provides residents with web access to:

- Property Information
- Resident Profile
- Family Members
- Cases
- Service Requests
- Work Orders
- Visitors
- Vehicles
- Amenities
- Documents
- Notifications
- Feedback

### Agency Portal

Provides agencies with desktop-based operational management.

**Modules:**
- Dashboard
- Work Orders
- Service Requests
- Workforce
- Properties
- Schedule
- SLA
- Performance
- Contracts
- Documents
- Reports
- Notifications
- Settings

### Zivion Internal Portal

Used by Zivion employees and administrators.

**Modules:**
- Property Management
- Resident Management
- Agency Management
- Workforce Management
- Case Management
- Work Orders
- Service Requests
- Technician Assignment
- SLA Monitoring
- Security Operations
- Contracts
- Documents
- Reports
- User and Role Management
- Notifications
- Audit Logs

---

## Core Workflow

ZIVION follows a structured service management workflow:

```text
Resident / RWA
      ↓
     Case
      ↓
Help Desk Review
      ↓
 Work Order
      ↓
Service Request
      ↓
Technician Assignment
      ↓
   Schedule
      ↓
Technician Accepts
      ↓
   Starts Work
      ↓
Notes / Photos
      ↓
Completes Service Request
      ↓
   Zivion Review
      ↓
 Work Order Closed
      ↓
    Case Closed
      ↓
Resident Feedback
```

One Case can contain multiple Work Orders, and one Work Order can contain multiple Service Requests.

---

## Service Categories

ZIVION supports configurable service categories:

- Plumbing
- Electrical
- Civil
- HVAC
- Housekeeping
- Landscaping
- Pest Control
- Security
- General Maintenance
- Other

New service categories can be added by authorized Zivion administrators without redesigning the application.

---

## Workforce Management

Agencies can manage:

- Agency Presidents
- Directors
- Operations Managers
- Supervisors
- Technicians
- Security Workforce
- Other Service Personnel

Technician information includes:

- Name
- Role
- Skills
- Assigned Properties
- Availability
- Current Status
- Active Jobs
- Shift
- Performance

---

## SLA Management

ZIVION monitors service-level commitments and provides:

- Response SLA
- Resolution SLA
- SLA Alerts
- SLA Breaches
- Escalations
- Performance Tracking

---

## Property Management

The platform manages:

- Properties
- Towers
- Units
- Owners
- Tenants
- Family Members
- Parking
- Vehicles
- Amenities
- Clubhouses
- Facilities
- Property Documents
- Property Contracts

---

## Visitor Management

ZIVION supports different types of visitors:

- Guests
- Friends
- Family
- Drivers
- Domestic Help
- Service Providers
- Event Guests

Visitor verification can be performed using:

- Gate Pass
- OTP
- QR Code

---

## Delivery Management

Supported delivery types include:

- Swiggy
- Zomato
- Amazon
- Flipkart
- Blinkit
- Zepto
- Courier
- Other

### Delivery Flow

```text
Delivery Arrives
      ↓
Security Identifies Delivery
      ↓
Resident Notified
      ↓
Resident Allows
      ↓
Package Dropped
      ↓
Resident Collects
```

---

## Vehicle Management

ZIVION supports:

- Resident Vehicles
- Visitor Vehicles
- Staff Vehicles
- Service Vehicles
- Vehicle Entry
- Vehicle Exit
- Vehicle History

---

## Notifications

The platform provides notifications for:

- New Work Orders
- Service Assignments
- SLA Alerts
- Visitor Requests
- Delivery Arrivals
- Approvals
- Service Completion
- Security Events
- Announcements

---

## Reports & Analytics

ZIVION provides operational reporting for:

- Work Orders
- Service Requests
- Completion Rate
- On-Time Completion
- SLA Performance
- Technician Performance
- Agency Performance
- Resident Feedback
- Property Operations

---

## User Roles

### Property Side

- Property
- RWA
- RWA Associates
- Owners
- Tenants
- Adult Family Members
- Clubhouse
- Facility Managers

### Agency Side

- President
- Director
- Operations Manager
- Supervisor
- Technician
- Security Manager
- Security Supervisor
- Shift In-charge
- Security Personnel

### Zivion Side

- Super Admin
- IT Admin
- Zivion Property Manager
- Help Desk Associate I
- Help Desk Associate II
- IT Operations
- IT Service Desk
- Legal
- Accounting
- Developer
- QA
- Manager

---

## Security

Security is a core requirement of ZIVION.

The platform follows role-based and least-privilege access principles.

### Security Features

- Role-Based Access Control
- Property-Level Access
- Organization-Level Access
- Record-Level Permissions
- Field-Level Permissions
- Secure Authentication
- Secure APIs
- Audit Logs
- Data Protection
- Restricted Production Access

Users can access only the information required for their role, organization, property, or assigned work.

---

## UI/UX Design

ZIVION follows a modern, clean, professional, and responsive design system.

### Primary Colors

```text
Primary Navy       #0B1220
Electric Blue      #3B82F6
Cyan               #22D3EE
Background         #F8FAFC
Dark Background    #060B14
Primary Text       #111827
Secondary Text     #64748B
Success             #10B981
Warning             #F59E0B
Error               #EF4444
Border              #E2E8F0
Agency Accent       #6366F1
```

### Primary Gradient

```text
#3B82F6 → #22D3EE
```

### Design Principles

- Clean and spacious layouts
- Rounded cards
- Minimal shadows
- Consistent outline icons
- Clear status badges
- Short descriptions
- Responsive design
- Mobile-friendly navigation
- Consistent typography
- Reusable components

---

## Core Components

The platform uses reusable UI components such as:

- Button
- Card
- Glass Card
- Stat Card
- Status Badge
- Icon Button
- Input
- Search Bar
- Property Card
- Ticket Card
- Activity Card
- User Card
- Header
- Sidebar
- Bottom Navigation
- Modal
- Dropdown
- Tabs
- Empty State
- Loading State

---

## Project Structure

```text
ZIVION/
│
├── resident-app/
├── agency-app/
├── security-app/
│
├── resident-portal/
├── agency-portal/
├── zivion-portal/
│
├── backend/
├── database/
├── documentation/
│
└── README.md
```

---

## Installation

### Prerequisites

- Node.js
- npm
- Git
- Database
- Code Editor

Check the installed versions:

```bash
node --version
npm --version
git --version
```

### Clone Repository

```bash
git clone <repository-url>
```

### Navigate to Project

```bash
cd ZIVION
```

### Install Dependencies

```bash
npm install
```

### Run Development Server

```bash
npm run dev
```

---

## Environment Variables

Create the required environment configuration file.

Example:

```env
API_BASE_URL=
DATABASE_URL=
AUTH_URL=
JWT_SECRET=
```

Do not commit passwords, API keys, tokens, or other sensitive credentials to the repository.

---

## Git Workflow

```text
main
  │
  ├── develop
  │     ├── feature/resident-app
  │     ├── feature/agency-app
  │     ├── feature/security-app
  │     └── feature/work-orders
  │
  └── release
```

Common commands:

```bash
git status
git add .
git commit -m "Add feature"
git push
```

---

## Testing

Testing should cover:

- Authentication
- Authorization
- Role Permissions
- Property Access
- Case Creation
- Work Order Creation
- Service Request Assignment
- Technician Workflow
- SLA Tracking
- Visitor Verification
- QR/OTP Validation
- Delivery Workflow
- Notifications
- Responsive UI
- API Error Handling
- Unauthorized Access

---

## Future Enhancements

Potential future enhancements include:

- Advanced Analytics
- AI-Assisted Service Classification
- Predictive Maintenance
- Automated Technician Assignment
- Smart SLA Prediction
- Advanced Security Monitoring
- Digital Payments
- Automated Reports
- AI Support Assistant
- Advanced Property Insights

---

## Project Summary

ZIVION provides a unified platform for managing:

**Properties · Residents · Agencies · Workforce · Maintenance · Security · Visitors · Deliveries · Vehicles · Amenities · Documents · Contracts · Operations**

---

## License

This project is proprietary software.

All rights reserved.



























1. What is ZIVION?
Answer:
ZIVION is a property and facility management platform. It connects residents, properties or RWAs, ZIVION employees, service agencies, technicians, and security teams in one system. It helps manage maintenance, visitors, deliveries, vehicles, amenities, workforce, and property operations.
2. What problem does ZIVION solve?
Answer:
In a residential community, maintenance, security, residents, and agencies may be managed separately. ZIVION brings these activities into one platform so that requests can be raised, assigned, tracked, completed, and reviewed systematically.
3. Who are the main users?
Answer:
The main users are:
- Residents
- RWA or property management
- ZIVION employees
- Service agencies
- Technicians
- Security personnel
Each user gets access according to their role.
4. What are the applications in ZIVION?
Answer:
ZIVION has three main mobile applications:
1. Resident App
2. Agency App
3. Security App
It also has three web portals:
1. Resident Portal
2. Agency Portal
3. ZIVION Internal Portal
5. What does the Resident App do?
Answer:
The Resident App allows residents to manage their property-related activities. They can raise service requests, track maintenance, manage visitors, gate passes, deliveries, vehicles, amenities, documents, notifications, and feedback.
6. What does the Agency App do?
Answer:
The Agency App is used by external service agencies to manage their workforce and complete jobs assigned by ZIVION.
The main features are:
- Work Orders
- Service Requests
- Technician Assignment
- Workforce
- Scheduling
- SLA
- Performance
- Properties
- Contracts
- Reports
7. What does the Security App do?
Answer:
The Security App is used to manage security operations such as visitor verification, gate passes, OTP/QR verification, vehicle entry and exit, deliveries, staff entry, incidents, emergency alerts, and shifts.
8. What is the main workflow of ZIVION?
Answer:
Resident raises Case
        ↓
ZIVION Help Desk reviews
        ↓
Work Order
        ↓
Service Request
        ↓
Technician Assignment
        ↓
Schedule
        ↓
Technician performs work
        ↓
Technician completes Service Request
        ↓
ZIVION reviews
        ↓
Work Order closed
        ↓
Case closed
        ↓
Resident feedback

This is one of the most important flows to understand.
9. What is a Case?
Answer:
A Case represents the main problem or request raised by a resident or property side.
For example:
A resident reports water leakage in their bathroom.

That complaint becomes a Case.
10. What is a Work Order?
Answer:
A Work Order represents the work assigned to an agency or team to resolve a Case.
For example:
Plumbing work is assigned to ABC Maintenance Agency.

That becomes a Work Order.
11. What is a Service Request?
Answer:
A Service Request represents the individual task that needs to be performed as part of a Work Order.
For example:
Work Order: Bathroom Water Leakage

Service Requests:
1. Inspect leakage
2. Repair pipe
3. Replace damaged fitting

12. What is the difference between Case, Work Order and Service Request?
Answer:
Term	Meaning
Case	Main problem raised
Work Order	Work assigned to agency/team
Service Request	Individual task to complete


One Case can have multiple Work Orders, and one Work Order can have multiple Service Requests.
13. Give a real example of the complete process.
Answer:
Suppose a resident reports water leakage.
The resident raises a Case. The ZIVION Help Desk reviews it and identifies it as a plumbing issue. A Work Order is created and assigned to a plumbing agency. The agency selects an available technician and schedules the job. The technician visits the property, starts the work, adds notes or photos, and completes the Service Request. ZIVION reviews the completion, closes the Work Order, and finally closes the Case. The resident can then provide feedback.
14. Who assigns the technician?
Answer:
The technician can be assigned through the agency's workforce and assignment process. The system can help identify suitable technicians based on factors such as:
- Skill
- Service category
- Property
- Availability
- Current workload
- Shift
- Status
15. What is Workforce Management?
Answer:
Workforce Management means managing the people who perform services.
For example, an agency can manage:
- Technicians
- Supervisors
- Operations Managers
- Security workforce
- Their skills
- Availability
- Assigned properties
- Current jobs
- Performance
16. What is Scheduling?
Answer:
Scheduling is used to decide when a particular job will be performed and which technician will handle it.
It helps agencies manage technicians' upcoming jobs and avoid workload conflicts.
17. What is SLA?
Answer:
SLA stands for Service Level Agreement.
It defines the expected time for responding to or completing a service.
For example:
A plumbing request may need to be responded to within 2 hours and resolved within 24 hours.

ZIVION monitors whether the service is within the agreed time.
18. What happens when an SLA is about to expire?
Answer:
The system can show an SLA alert and notify the responsible team so that they can take action before the SLA is breached.
19. What happens when an SLA is breached?
Answer:
The system records the breach and can trigger escalation or notification to the appropriate team for further action.
20. Can a technician close a Case?
Answer:
No. The technician completes the assigned Service Request. ZIVION reviews the completion, then the Work Order and Case can be closed according to the workflow.
21. Why can't the technician directly close the Case?
Answer:
Because the Case represents the overall resident issue. ZIVION needs to verify that the required work has actually been completed before the overall Case is closed.
22. Can one Work Order have multiple Service Requests?
Answer:
Yes.
For example:
Work Order
    ↓
Service Request 1
Service Request 2
Service Request 3

All required Service Requests need to be completed before the Work Order can be closed.
23. What happens if only one Service Request is completed?
Answer:
The Work Order should not be considered fully completed if other required Service Requests are still pending.
24. What services does ZIVION support?
Answer:
The platform supports configurable categories such as:
- Plumbing
- Electrical
- Civil
- HVAC
- Housekeeping
- Landscaping
- Pest Control
- Security
- General Maintenance
- Other
25. Can new service categories be added?
Answer:
Yes. Authorized ZIVION administrators can add new service categories without redesigning the application.
26. What is RBAC?
Answer:
RBAC means Role-Based Access Control.
It means users get access based on their role and responsibilities.
For example:
A technician should see their assigned work, while a ZIVION administrator may have access to broader operational information.

27. Why is RBAC important in ZIVION?
Answer:
ZIVION handles property, resident, security, and operational information. RBAC ensures that users can access only the information required for their role.
28. What can a technician access?
Answer:
A technician should primarily access their assigned Service Requests and the information required to perform those jobs.
29. What can a security guard access?
Answer:
Security personnel should access only the information required for security operations, such as visitor, gate pass, vehicle, and delivery information for their assigned property.
30. What is the purpose of the Agency Portal?
Answer:
The Agency Portal provides agencies with a larger desktop interface for managing their operations, including workforce, Work Orders, Service Requests, schedules, SLA, performance, properties, contracts, documents, and reports.
31. What is the purpose of the ZIVION Internal Portal?
Answer:
It is used by ZIVION employees to operate and manage the platform. They can manage properties, residents, agencies, cases, work orders, service requests, support, SLA, security operations, users, permissions, and reports.
32. How does visitor management work?
Answer:  
A resident can create or approve a visitor through the system. When the visitor arrives, security verifies the visitor using the configured method such as OTP, QR code, or gate pass. The entry is recorded, and the visitor's exit can also be recorded.
33. How does delivery management work?
Answer:
Delivery arrives
      ↓
Security identifies delivery
      ↓
Resident is notified
      ↓
Resident allows
      ↓
Package is received/dropped
      ↓
Resident collects package

The system records the delivery activity.
34. What is the purpose of vehicle management?
Answer:
Vehicle Management allows the system to maintain vehicle information and track vehicle entry and exit for residents, visitors, staff, and service personnel.
35. What is the purpose of notifications?
Answer:
Notifications keep users informed about important events such as new Work Orders, assignments, visitor requests, deliveries, SLA alerts, approvals, and service completion.
36. What is the purpose of Reports?
Answer:
Reports help management understand operational performance.
For example:
- Number of Work Orders
- Completion Rate
- On-Time Completion
- SLA Performance
- Technician Performance
- Agency Performance
- Resident Feedback
37. Why does ZIVION need different apps?
Answer:
Because each user has different responsibilities.
For example:
- Resident → raises and tracks requests
- Agency → manages workforce and jobs
- Security → manages visitors and entry
- ZIVION employee → manages operations
Separating the applications keeps the user experience simple and ensures proper access control.
38. What is the most important part of the Agency App?
Answer:
The main focus is Workforce + Work Orders + Service Requests + Scheduling + SLA + Performance.
The Agency App is mainly an operational application for managing service work and the people who perform it.
39. What is the most important security concept in ZIVION?
Answer:
The most important concept is role-based and least-privilege access. Each user should only access the data and actions necessary for their role.
40. Explain ZIVION in one minute.
Answer:
ZIVION is a property and facility management platform that connects residents, properties, service agencies, technicians, and security teams. It provides separate apps and portals for different users. Residents can raise and track service requests, manage visitors, deliveries, vehicles, and amenities. Agencies can manage their workforce, Work Orders, technicians, schedules, SLA, and performance. Security teams manage visitors, vehicles, deliveries, and entry operations. ZIVION employees manage the overall operations, cases, assignments, properties, agencies, and support. The main service workflow is Case → Work Order → Service Request → Technician Assignment → Work Execution → ZIVION Review → Closure → Resident Feedback.



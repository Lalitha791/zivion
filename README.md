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

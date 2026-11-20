# Phase 6 — New Life Sports Center: Production Management System Showcase

## Objective

Create a professional public engineering case study for the New Life Sports Center project, with particular emphasis on the custom-built **Administration Panel, operational management features, security architecture, and QA engineering practices**.

This project should demonstrate my ability to design, develop, test, and maintain software for a real business.

Unlike QA Practice, which is primarily a testing and learning platform, New Life Sports Center represents a real-world application with business requirements, administrative workflows, operational constraints, and production release considerations.

## 1. Repository Information

**Private source repository:** `hakdogan1/newlife`

**Proposed public showcase repository:** `newlife-sports-management-showcase`

**Live website:** https://newlifesporbandirma.com.tr/

The private repository must remain private.

The new public repository should contain only:

- Professional English README documentation
- Authorized, sanitized screenshots
- High-level architecture diagrams
- Non-sensitive technical case studies
- Verified testing and engineering evidence

Do not publish application source code, configuration files, authentication details, customer data, or infrastructure secrets.

Do not create the public repository without my explicit approval.

## 2. Administration Panel — Main Project Highlight

The **New Life Sports Center Administration Panel** should be the primary focus of this showcase.

Present it as a custom-developed management environment designed to centralize website administration and sports center operations.

### Administration Dashboard

Document and demonstrate:

- Centralized administration dashboard
- Modular management sections
- Responsive desktop, tablet, and mobile interfaces
- Navigation and administrative workflows
- Development Lock functionality
- Unsaved-change protection
- Administrative usability and accessibility improvements

Explain how the dashboard helps administrators manage multiple operational areas through a unified interface.

### Sports Branch Management

Highlight:

- Creating and managing sports branches
- Editing branch information
- Visibility controls
- Ordering and drag-and-drop functionality
- Structured content sections
- Rich-text editing
- Branch restoration and removal workflows
- Data persistence and validation

Describe how branch management separates public website presentation from administrative data management.

### Class Scheduling and Lesson Management

This is one of the most important administrative features.

Document:

- Weekly lesson scheduling
- Creating and editing lessons
- Branch selection
- Group management
- Lesson duration controls
- Copying lessons to other days
- Coach assignment
- Responsive lesson editing dialogs
- Mobile-first scheduling workflows
- Schedule validation and persistence

Pay particular attention to mobile usability.

Explain how the interface supports staff members who need to create or modify lessons quickly from a phone.

Clearly distinguish completed, locally implemented, planned, and production-released features.

### Staff and Coach Management

Document verified capabilities related to:

- Staff records
- Staff ordering
- Centralized duty definitions
- Multiple duties per staff member
- Coach and branch relationships
- Staff visibility settings
- Coach selection within lesson scheduling
- Data consistency across administrative modules

Do not present unfinished integration work as production functionality.

### Content Management

Describe the administrative tools for:

- Website section management
- Reusable content templates
- Text and image sections
- Card layouts
- Galleries
- FAQ sections
- Calls to action
- Rich-text content
- Public visibility management

### Image and Brand Management

Highlight:

- Universal image editor
- Desktop, tablet, and mobile preview modes
- Image positioning
- Zoom and rotation
- Fit and fill modes
- Preview and saved-output consistency
- Brand asset management
- Logo variants
- Responsive Hero images

Explain the engineering challenges involved in consistent image presentation across different screen sizes and real devices.

## 3. Security and Access Control

Document the verified administrative security model.

Relevant areas include:

- Authentication
- Role-Based Access Control (RBAC)
- Stable UUID-based user identities
- Protected system accounts
- Two-factor authentication
- Email verification where implemented
- Session management
- Session revocation
- Rate limiting
- CSRF protection
- Input validation
- Development Lock

Security documentation must distinguish between features that are implemented, planned, and currently deployed.

Do not disclose security-sensitive implementation details.

Do not publish real user records, authentication secrets, recovery codes, session identifiers, or administrative endpoints that are not already intended for public disclosure.

## 4. Responsive UX and Mobile Administration

Create a dedicated section describing the mobile administration experience.

Explain the importance of:

- Touch-friendly controls
- Mobile lesson entry
- Responsive dialogs
- Accessible form interactions
- Keyboard navigation
- Clearly grouped fields
- Appropriate button placement
- Reduced horizontal scrolling
- Consistent layout across screen sizes

Discuss engineering challenges such as differences between browser device emulation and actual iPhone rendering.

Show validated improvements using genuine screenshots where safe.

## 5. QA Engineering and Test Automation

Present New Life Sports Center as a real-world example of applying quality engineering throughout software development.

Document verified use of:

- Playwright browser testing
- Python regression testing
- PHP validation tests
- Manual functional testing
- Responsive UI testing
- Regression testing
- Security-related test scenarios
- Release readiness checks
- GitHub pull request workflows
- CI/CD validation

Include representative testing scenarios covering:

- Creating and editing lessons
- Validating incorrect or missing inputs
- Role-based access restrictions
- CSRF and session behaviour
- Data persistence
- Mobile layout behaviour
- Image editor preview consistency
- Staff and coach assignment

Use actual test evidence only.

Where previous test runs are documented, identify their relevant branch, commit, environment, and date when available.

Never combine test results from different revisions into a single misleading claim.

Do not describe a CI run blocked by GitHub Actions billing limits as a passing execution.

## 6. Release Engineering

Document the project's engineering workflow:

Development → Testing → Pull Request → Review → CI Validation → Controlled Merge → Approved Deployment → Production Verification.

Explain:

- Git branch isolation
- Pull request review
- Regression validation
- GitHub Actions
- Release readiness decisions
- Backup procedures
- Production verification
- GO / NO-GO reporting
- CI infrastructure limitations and documented exceptions

Do not claim full automation where manual approval or intervention is required.

## 7. Screenshots and Visual Documentation

Screenshots should be one of the main strengths of this repository.

### Public Website Screenshots

Capture from the live public website:

1. Homepage — desktop
2. Homepage — mobile
3. Sports branches
4. Responsive Hero section

### Administration Panel Screenshots

Prepare sanitized images showing:

1. Administration Dashboard
2. Weekly Class Schedule
3. Mobile Lesson Editor
4. Sports Branch Management
5. Staff Management
6. Content Management
7. Universal Image Editor
8. User and Role Management, only if safe to show

Prefer screenshots from an isolated local environment populated with fictional demonstration data.

Do not capture real user or customer data for public use.

Do not expose personal names, email addresses, phone numbers, credentials, session tokens, internal identifiers, or sensitive security configuration.

If a safe administrative screenshot cannot be obtained, mark it as unavailable rather than manufacturing evidence.

Store approved images under:

`docs/screenshots/`

Optimize images for GitHub README rendering.

## 8. Recommended README Structure

Create a professional English README using the following structure:

1. Project Overview
2. Live Website
3. Project Highlights
4. Administration Panel
5. Class Scheduling and Coach Management
6. Staff and Branch Management
7. Content and Image Management
8. Authentication and Access Control
9. Responsive Administration Experience
10. Technical Architecture
11. Quality Assurance and Testing
12. CI/CD and Release Engineering
13. Engineering Challenges and Solutions
14. Screenshots and Demonstrations
15. My Role and Contributions
16. Current Status and Future Development

Include high-level Mermaid architecture diagrams where appropriate.

The README should be understandable to recruiters while retaining enough technical detail for software engineers and QA leads.

## 9. Public Repository Presentation

**Proposed repository name:**

`newlife-sports-management-showcase`

**Suggested description:**

"Engineering case study of a production sports center website and custom administration platform, featuring class scheduling, staff management, RBAC, responsive UX, and QA automation."

Suggested topics:

`software-engineering`, `qa-automation`, `sports-management`, `admin-dashboard`, `php`, `playwright`, `responsive-design`, `rbac`, `ci-cd`

Verify the actual technology stack before applying repository topics.

## 10. GitHub Profile Integration

Add New Life Sports Center to the proposed Featured Projects section of my GitHub profile.

Present the three engineering projects as complementary examples:

**QA Practice:** Testing education, testability design, and automation concepts.

**Portfolio Engineering:** Interactive QA demonstrations, CI/CD, deployment safeguards, and quality engineering.

**New Life Sports Center:** Real-world business application, administrative workflows, security, responsive UX, and production-oriented QA.

Each project should link to its public engineering case study and relevant live application.

Do not include private repository links as publicly accessible source-code links.

## 11. Security and Authorization

The private New Life Sports Center repository is the authoritative source for technical verification.

Use read-only access to inspect it.

Do not modify the private source repository as part of this documentation task.

Do not change production content, user data, administrative settings, or deployment configuration.

Do not publish any screenshots without checking them for sensitive information.

Explicit approval is required before:

- Creating the new public repository
- Committing changes
- Pushing commits
- Opening pull requests
- Merging
- Renaming repositories
- Changing visibility
- Deploying changes

## 12. Execution Order and Expected Report

Complete the previously defined QA Practice and Portfolio Engineering assessment first.

Then:

1. Inspect the private New Life Sports Center repository in read-only mode.
2. Verify implemented functionality and current development status.
3. Identify which features are deployed and which remain local.
4. Prepare a complete public case-study README.
5. Prepare authentic, sanitized screenshots.
6. Validate engineering claims and available test evidence.
7. Review documentation for security and confidentiality risks.
8. Present the proposed repository structure and changes.
9. Stop before any GitHub write operation and request explicit approval.

Provide a final report identifying completed preparation, verified findings, assumptions, blocked tasks, testing evidence, security checks, and pending approvals.

**The primary showcase should be the custom Administration Panel and its real-world operational workflows.**

The goal is to demonstrate that I can contribute not only as a QA Automation Engineer but also across testability, frontend engineering, administrative application design, security validation, and controlled software delivery.

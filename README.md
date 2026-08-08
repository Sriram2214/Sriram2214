Build a modern, professional, responsive PERSONAL ACADEMIC & RESEARCH PORTFOLIO WEBSITE for:

Mr. K. Daniel Raj, B.Tech., M.E., (MBA), MISTE.

The website must be designed as a long-term personal academic portfolio where I can update all information from an ADMIN DASHBOARD without modifying source code.

CORE REQUIREMENT:
Create a complete CRUD-based CMS.

Whenever I want to add a new publication, book chapter, conference paper, achievement, experience, project, certificate, event, or other profile information, I should simply log in to the Admin Dashboard and use Add/Edit/Delete.

The changes must immediately reflect on the public website.

DO NOT hardcode portfolio content into frontend components.

==================================================
1. TECHNOLOGY STACK
==================================================

Frontend:
- Next.js latest stable version
- TypeScript
- Tailwind CSS
- shadcn/ui
- Framer Motion
- Lucide React icons

Backend:
- Next.js API routes / Server Actions
- PostgreSQL database
- Prisma ORM

Authentication:
- Secure Admin Login
- Email/username + password
- Password hashing
- Protected admin routes
- Session-based authentication

Storage:
- Cloudinary or Supabase Storage for profile photo, certificates, publication files, project images and other uploads.

Deployment-ready for:
- Vercel
- PostgreSQL/Supabase

==================================================
2. PUBLIC WEBSITE
==================================================

Create these main sections:

1. Home
2. About Me
3. Education
4. Experience
5. Research Profile
6. Publications
7. Book Chapters
8. Books
9. Patents
10. Conferences
11. Reviewer / Editorial Roles
12. Research Projects
13. Skills
14. Professional Memberships
15. Courses / Certifications
16. Achievements
17. Events / FDP / Workshops
18. Gallery
19. Contact

Use smooth scrolling and modern page transitions.

==================================================
3. HERO SECTION
==================================================

Display:

Mr. K. Daniel Raj
B.Tech., M.E., (MBA), MISTE.

Primary designation:
Assistant Professor | Computer Science & Engineering | Researcher

Add:
- Professional profile photo
- Short academic introduction
- View Research
- View Publications
- Download CV
- Contact Me

Social/profile buttons:
- LinkedIn
- Google Scholar
- ORCID
- Scopus
- ResearchGate
- Semantic Scholar
- IGI Global

Do not invent profile URLs. Store every URL in the database so I can change it from Admin.

==================================================
4. ABOUT SECTION
==================================================

Create an editable professional biography.

It must be managed through Admin Dashboard.

Include:
- Academic background
- Teaching interests
- Research interests
- Professional interests
- Career objective

==================================================
5. EDUCATION CRUD
==================================================

Database fields:

id
qualification
specialization
institution
location
startYear
endYear
modeOfStudy
percentageOrCGPA
status
description
displayOrder
isVisible

Admin operations:

CREATE
READ
UPDATE
DELETE

Example records can be imported from my resume.

==================================================
6. EXPERIENCE CRUD
==================================================

Fields:

id
designation
organization
location
employmentType
startDate
endDate
isCurrent
description
displayOrder
isVisible

Display experience as a professional timeline.

Admin must be able to:
- Add experience
- Edit experience
- Delete experience
- Change order
- Mark current position

==================================================
7. PUBLICATION MANAGEMENT
==================================================

This is one of the MOST IMPORTANT modules.

Create separate database tables for:

A. Journal Publications
B. Scopus Journal Publications
C. Book Chapters
D. Conference Publications
E. Preprints
F. Books
G. Patents

Each publication must be independently editable.

Journal Publication fields:

id
title
authors
journalName
publisher
volume
issue
year
doi
indexing
status
abstract
keywords
paperUrl
doiUrl
pdfUrl
publicationType
featured
displayOrder
isVisible

Admin buttons:

+ Add Publication
Edit
Delete
Duplicate
Publish/Unpublish

DO NOT require code modification to add a new paper.

If I publish another paper tomorrow, I should only need:

Admin Dashboard → Publications → Add New → Save

==================================================
8. BOOK CHAPTER CRUD
==================================================

Fields:

title
authors
bookTitle
publisher
isbn
year
indexing
chapterUrl
doi
status
description
displayOrder
isVisible

Show publication status clearly:

Published
Accepted
Under Review
In Press

==================================================
9. PATENT CRUD
==================================================

Fields:

title
applicationNumber
filingDate
publicationDate
status
inventors
patentUrl
description
displayOrder
isVisible

Create a professional patent card.

==================================================
10. CONFERENCE PUBLICATION CRUD
==================================================

Fields:

title
conferenceName
conferenceYear
location
publisher
indexing
status
paperUrl
doi
description
displayOrder
isVisible

Allow filtering by:
- Year
- IEEE
- Springer
- Scopus
- International
- National
- Published
- Accepted

==================================================
11. RESEARCH PROJECT CRUD
==================================================

Fields:

title
shortDescription
fullDescription
researchArea
technologies
dataset
methodology
results
githubUrl
demoUrl
paperUrl
image
year
status
featured
displayOrder
isVisible

Create attractive project cards.

==================================================
12. RESEARCH PROFILE
==================================================

Create editable profile cards for:

Google Scholar
ORCID
Scopus Author ID
VIDWAN
ResearchGate
Semantic Scholar
IGI Global

Each profile must have:

platformName
profileUrl
icon
description
displayOrder
isVisible

I must be able to change URLs from Admin.

==================================================
13. REVIEWER / EDITORIAL ROLES
==================================================

Create CRUD.

Fields:

organization
journalOrConference
role
year
description
profileUrl
logo
displayOrder
isVisible

Examples:
Reviewer
Editorial Board Member
Technical Program Committee Member
Reviewer / Author Affiliate

==================================================
14. SKILLS
==================================================

Create skill categories:

Programming
AI / ML
Web Development
Database
Research
Professional Skills
Soft Skills

Fields:

skillName
category
skillLevel
yearsOfExperience
icon
displayOrder
isVisible

Show skills using clean cards/progress indicators.

==================================================
15. MEMBERSHIPS
==================================================

CRUD fields:

organization
membershipType
membershipNumber
year
validUntil
website
logo
description
isVisible

==================================================
16. CERTIFICATIONS / COURSES
==================================================

CRUD:

courseName
provider
year
certificateNumber
certificateUrl
certificateImage
description
isVisible

==================================================
17. ACHIEVEMENTS
==================================================

CRUD:

title
organization
date
category
description
certificateUrl
image
featured
isVisible

==================================================
18. ADMIN DASHBOARD
==================================================

Create a professional admin dashboard.

Dashboard should display:

Total Publications
Journal Publications
Book Chapters
Conference Papers
Books
Patents
Research Projects
Reviewer Roles
Achievements
Experience Records

Include a sidebar:

Dashboard
Profile
Education
Experience
Publications
Book Chapters
Books
Patents
Conferences
Preprints
Research Projects
Research Profiles
Reviewer Roles
Skills
Memberships
Courses
Achievements
Events
Gallery
Messages
Site Settings

Every module must have:

+ Add New
Search
Filter
Sort
Edit
Delete
Duplicate
Publish/Unpublish
Reorder

Use confirmation dialogs before deletion.

==================================================
19. PROFILE SETTINGS
==================================================

Create a centralized Profile Settings page.

I should be able to change:

Name
Professional title
Designation
Short bio
Full bio
Profile photo
Email
Phone
Location
LinkedIn
Google Scholar
ORCID
Scopus
ResearchGate
Semantic Scholar
Website
CV

Do not hardcode these values.

==================================================
20. SITE SETTINGS
==================================================

Admin should be able to change:

Website title
Meta description
Keywords
Favicon
Logo
Theme
Primary accent color
Footer text
Copyright
Social links
Contact information

==================================================
21. ANALYTICS
==================================================

Admin dashboard should display:

Total website visits
Publication page views
Most viewed publications
Research project views
Contact enquiries

If practical, integrate Google Analytics.

==================================================
22. SEARCH & FILTER
==================================================

Public website must have global search.

Search:

Publications
Book Chapters
Books
Patents
Projects
Conferences
Achievements

Publication page must support:

Search by title
Search by author
Search by year
Filter by indexing
Filter by publication type
Filter by status

==================================================
23. PUBLICATION STATISTICS
==================================================

Automatically calculate statistics from the database.

Examples:

Journal Publications
Book Chapters
Conference Publications
Books
Patents
Preprints
Reviewer Roles

IMPORTANT:
Never manually hardcode these numbers.

If I add a new publication from Admin, the statistics should automatically increase.

Example:

Current:
Journal Publications = 2

Admin adds:
New Journal Publication

Automatically:
Journal Publications = 3

==================================================
24. FEATURED CONTENT
==================================================

Admin should be able to mark:

Featured Publication
Featured Project
Featured Achievement
Featured Book
Featured Patent

Featured items should automatically appear on the Home page.

==================================================
25. RESUME / CV
==================================================

Add:

Download CV

The CV should be replaceable through Admin Dashboard.

Admin:
Settings → CV → Upload New CV

No source code changes required.

==================================================
26. CONTACT SYSTEM
==================================================

Create contact form:

Name
Email
Subject
Message

Store messages in database.

Admin can:

View
Mark as Read
Mark as Unread
Delete

==================================================
27. DATABASE DESIGN
==================================================

Use normalized PostgreSQL database.

Suggested models:

User
Profile
Education
Experience
Publication
BookChapter
Book
Conference
Preprint
Patent
ResearchProject
ResearchProfile
ReviewerRole
Skill
Membership
Certification
Achievement
Event
Gallery
ContactMessage
SiteSetting

Every table should include:

id
createdAt
updatedAt

Where relevant include:

displayOrder
isVisible
featured

==================================================
28. SECURITY
==================================================

Implement:

- Protected admin routes
- Secure authentication
- Password hashing
- Server-side validation
- Client-side validation
- SQL injection protection through Prisma
- XSS protection
- CSRF protection where applicable
- Secure file uploads
- File type validation
- File size limits
- Rate limiting for contact form
- Never expose database credentials
- Never expose admin API keys to frontend

==================================================
29. UI / DESIGN
==================================================

Design style:

Premium academic + modern technology portfolio.

Avoid:
- Excessive animations
- Excessive gradients
- Overdecorated layouts
- Generic template appearance
- Huge unnecessary text

Use:

- Clean typography
- White / dark professional theme
- Subtle blue accent
- Glassmorphism only where appropriate
- Professional cards
- Timeline layouts
- Publication cards
- Research statistics
- Minimal animations
- Responsive design

Must look professional enough for:

Assistant Professor
Researcher
IEEE Author
Academic Writer
Research Collaborator

==================================================
30. RESPONSIVE DESIGN
==================================================

Must work perfectly on:

Desktop
Laptop
Tablet
Mobile

Admin dashboard should also be responsive.

==================================================
31. SEO
==================================================

Implement:

SEO metadata
Open Graph
Twitter/X cards
Sitemap
Robots.txt
Structured data / JSON-LD
Person schema
ScholarlyArticle schema where appropriate

Optimize for searches such as:

Daniel Raj Assistant Professor
Daniel Raj CSE
Daniel Raj Researcher
Daniel Raj Publications
Daniel Raj AI Researcher

==================================================
32. IMPORTANT CONTENT RULE
==================================================

Use the uploaded resume as the initial data source.

Do not invent achievements, publications, indexing claims, positions, DOI numbers, awards, or academic qualifications.

Import the existing resume information into the database as seed data.

If information is unavailable, leave it blank rather than creating fake content.

==================================================
33. MOST IMPORTANT FUNCTIONAL REQUIREMENT
==================================================

The website must behave like a personal CMS.

I should NOT have to ask a developer to update my website.

Example:

I publish a new research paper.

I open:

/admin

Login

Publications
→ Add New

Enter:

Title
Authors
Journal
Year
DOI
Indexing
Status
URL
Abstract

Click:

SAVE

Then the paper automatically appears on:

Home → Featured Publications (if selected)
Publications page
Research statistics
Search results
Relevant category

The same principle must work for every section.

==================================================
34. CRUD REQUIREMENT
==================================================

Every editable section must support:

CREATE
READ
UPDATE
DELETE

Use reusable CRUD components.

Do not duplicate unnecessary code.

Implement:

DataTable
FormModal / FormPage
DeleteConfirmation
SearchBar
Filter
Pagination
SortableList
ImageUploader
FileUploader
RichTextEditor
Toast Notifications

==================================================
35. ADMIN EXPERIENCE
==================================================

The Admin Dashboard should be simple enough that a non-developer can manage the website.

Example:

Dashboard
→ Publications
→ Add Publication
→ Fill Form
→ Save

No coding.

No database commands.

No source-code modification.

No redeployment for normal content updates.

==================================================
36. FINAL REQUIREMENTS
==================================================

Generate:

1. Complete frontend
2. Backend/API
3. PostgreSQL database schema
4. Prisma schema
5. Authentication
6. Admin dashboard
7. CRUD operations
8. File upload system
9. Seed data from resume
10. Responsive UI
11. SEO
12. Error handling
13. Loading states
14. Empty states
15. Form validation
16. Database migrations
17. README
18. Environment variable example
19. Deployment instructions

The final result must be production-ready and maintainable.

MOST IMPORTANT:
CONTENT MUST BE DATABASE-DRIVEN.

I want to update my entire academic profile from one Admin Dashboard.

Do not hardcode dynamic portfolio information into the frontend.

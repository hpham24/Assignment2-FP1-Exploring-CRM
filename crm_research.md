# CRM Research Report

**Course:** ICS499 – Software Engineering and Capstone Project  
**Assignment:** Assignment 2 + FP1 – Exploring CRM Systems  
**AI Tools Used:** Claude, ChatGPT, Perplexity  

---

# Part 1 – AI-Based CRM Discovery

## 1. What is CRM?

### Definition

Customer Relationship Management (CRM) is both a business strategy and a category of software that helps organizations manage interactions with current and potential customers. A CRM system centralizes customer data — contact details, communication history, purchase records, support tickets — in one place, making it accessible across sales, marketing, and support teams.

### Purpose

The core purpose of a CRM system is to improve business relationships. Specifically, it helps organizations:

- Retain existing customers by tracking and personalizing interactions
- Attract new customers by managing leads and marketing pipelines
- Increase revenue by helping sales teams prioritize and close deals
- Improve customer service by giving support teams full context on every customer

### History

| Era | Development |
|-----|-------------|
| **1980s** | Early contact management software (e.g., ACT! in 1987) allowed sales reps to store customer contact details digitally, replacing Rolodexes and spreadsheets. |
| **1990s** | The term "CRM" emerged. Siebel Systems (founded 1993) became an early enterprise CRM leader. Software was expensive, server-based, and required IT teams to maintain. |
| **2000s** | Salesforce launched in 1999 and revolutionized CRM by moving it to the cloud. This made CRM accessible to smaller businesses via subscription pricing (SaaS model). |
| **2010s** | CRM systems became deeply integrated with email, social media, marketing automation, and analytics. HubSpot popularized the "inbound" approach. Mobile CRM apps became standard. |
| **2020s** | AI-powered features (predictive scoring, chatbots, generative AI for email drafts, automated insights) became core CRM capabilities. Low-code/no-code customization grew significantly. |

### Evolution Summary

CRM evolved from simple digital contact lists into comprehensive business platforms that touch every customer-facing function of an organization. The shift from on-premise to cloud, and now from cloud to AI-augmented, defines each major era.

---

**AI Reflection – Part 1, Question 1:**
- *Tool used:* Claude
- *Completeness:* The response was thorough and historically accurate.
- *Verification:* Cross-checked the founding dates of Salesforce and Siebel Systems against their official websites and Wikipedia. Both confirmed.
- *Trustworthiness:* High for established historical facts; moderate for "current era" claims which required verification against recent news.

---

## 2. Why Do Organizations Use CRM Systems?

### Sales Management

CRM systems give sales teams a structured pipeline to track every deal from initial contact to closed sale. Reps can see at a glance which leads are hot, which deals are stalling, and what actions are needed. Managers gain forecasting visibility — they can predict revenue based on the current pipeline rather than gut feeling. Features like automated follow-up reminders and email tracking reduce deals falling through the cracks.

### Customer Management

CRM serves as the "single source of truth" for customer data. Every phone call, email, meeting, and purchase is logged. When a customer calls in, any team member can immediately see their full history. This continuity improves the customer experience and reduces the frustration of customers having to re-explain themselves.

### Marketing

CRM enables targeted, segmented marketing. Instead of sending the same email to all customers, marketers can create campaigns targeted to specific segments — by industry, purchase history, geography, or engagement level. CRM platforms track email opens, link clicks, and campaign ROI, enabling data-driven marketing decisions.

### Customer Support

Support teams use CRM to manage tickets, track issue resolution times, and maintain service history. When a support agent can instantly see that a customer has been with the company for 5 years and spent $50,000, they can prioritize accordingly. Integrated knowledge bases and escalation workflows improve resolution speed and quality.

### Reporting and Analytics

CRM systems provide dashboards and reports that give leadership visibility into business performance: sales velocity, customer acquisition cost, churn rate, support response times, campaign conversion rates, and more. Good analytics turns raw CRM data into actionable business intelligence.

---

**AI Reflection – Part 1, Question 2:**
- *Tool used:* Claude
- *Completeness:* Response was comprehensive across all five areas.
- *Verification:* Compared against HubSpot's own documentation on CRM use cases — consistent.
- *Trustworthiness:* High. These are well-established, stable business concepts.

---

## 3. Business Problems CRM Systems Solve (By Industry)

### Retail

**Problem:** Retailers struggle to understand individual customer preferences across multiple channels (in-store, online, mobile app). Marketing is generic and ineffective.  
**CRM Solution:** A CRM connected to purchase history and web behavior enables personalized promotions. Loyalty programs are tracked centrally. Staff can see a customer's preferences before approaching them.

### Healthcare

**Problem:** Patient communication is fragmented across departments. Follow-up care falls through the cracks. Administrative staff lack context when patients call.  
**CRM Solution:** A healthcare CRM (e.g., Salesforce Health Cloud) centralizes patient interaction history, appointment scheduling, and post-visit follow-ups. Automated reminders reduce no-shows. Compliance features help with HIPAA requirements.

### Education

**Problem:** Universities and colleges struggle to manage thousands of prospective student inquiries and track applicants through complex enrollment funnels.  
**CRM Solution:** Education CRMs (e.g., Salesforce Education Cloud, Slate) track every touchpoint from first campus visit inquiry through application, admission, enrollment, and alumni status. Counselors can prioritize outreach to at-risk students.

### Manufacturing

**Problem:** B2B sales cycles are long and involve multiple stakeholders. Account managers frequently change, leading to lost institutional knowledge about client relationships.  
**CRM Solution:** CRM preserves the full relationship history so new account managers can ramp up immediately. Opportunity tracking helps forecast production demand. Integration with ERP systems connects sales pipelines to inventory and manufacturing planning.

### Nonprofits

**Problem:** Donor management is often done in spreadsheets. Organizations struggle to identify which donors are lapsing, who to cultivate for major gifts, and how to segment communications.  
**CRM Solution:** Nonprofit CRMs (e.g., Salesforce Nonprofit Success Pack, Bloomerang) track donation history, event attendance, volunteer activity, and grant management. Automated thank-you sequences and lapsed donor re-engagement campaigns increase retention.

---

**AI Reflection – Part 1, Question 3:**
- *Tool used:* Claude
- *Completeness:* Good breadth across all five industries requested.
- *Verification:* Spot-checked the healthcare HIPAA claim and Salesforce product names against Salesforce's website. Accurate.
- *Trustworthiness:* High for general concepts; specific product names should always be verified directly with vendors.

---

## 4. Major Modules in a CRM System

| Module | Description |
|--------|-------------|
| **Contacts** | Stores individual person records — name, phone, email, company, communication history. The foundation of any CRM. |
| **Accounts** | Represents companies or organizations. Contacts are associated with accounts. Tracks company-level relationships. |
| **Leads** | Unqualified potential customers who have expressed interest but haven't been evaluated yet. Leads are converted to Contacts/Opportunities once qualified. |
| **Opportunities** | A qualified sales deal in progress. Tracks deal value, stage, expected close date, and associated contacts. |
| **Activities** | Logs all interactions: calls, emails, meetings, tasks. Provides a timeline of everything that happened with a customer. |
| **Tasks** | Action items assigned to team members with due dates. Ensures follow-ups don't get missed. |
| **Marketing Campaigns** | Tracks outreach campaigns — email blasts, events, ad campaigns. Measures leads and revenue generated per campaign. |
| **Customer Support Tickets** | Manages inbound support requests. Tracks issue type, priority, assigned agent, resolution status, and time-to-close. |
| **Reports** | Pre-built and custom reports that surface data insights — pipeline health, conversion rates, revenue by rep, support SLA compliance. |
| **Dashboards** | Visual real-time views of key metrics. Role-specific dashboards (sales manager vs. support lead vs. executive) provide relevant information at a glance. |

---

**AI Reflection – Part 1, Question 4:**
- *Tool used:* Claude
- *Completeness:* Covered all example modules from the assignment prompt and added useful context for each.
- *Verification:* Compared module list against EspoCRM and HubSpot CRM documentation — all modules confirmed present in real products.
- *Trustworthiness:* High. Module definitions are stable and consistent across the industry.

---

---

# Part 2 – AI-Assisted CRM Product Comparison

## Commercial CRM Products

Research was conducted using Claude and cross-validated with official vendor websites and G2/Capterra review platforms.

| Product | Target Customer | Strengths | Weaknesses | Pricing Model |
|---------|----------------|-----------|------------|---------------|
| **Salesforce** | Mid-market to large enterprise | Most feature-rich platform; massive ecosystem of integrations and partners; highly customizable; industry-leading reporting | Expensive; steep learning curve; requires dedicated admin; can feel overwhelming for small teams | Subscription per user/month; starts ~$25/user/mo (Starter), enterprise tiers $150–$300+/user/mo |
| **HubSpot CRM** | Startups to mid-market | Generous free tier; excellent UX; strong inbound marketing integration; easy onboarding | Free tier has limited reporting; advanced features require expensive add-on "Hubs"; can get costly fast as team grows | Freemium; paid tiers from ~$20/user/mo; bundles ("Hubs") for marketing/sales/service sold separately |
| **Zoho CRM** | SMBs to mid-market | Excellent value for money; broad feature set; part of larger Zoho ecosystem (40+ apps); strong automation | UI feels dated compared to competitors; customer support quality inconsistent; less brand recognition | Free for 3 users; paid from ~$14/user/mo; Enterprise ~$40/user/mo |
| **Microsoft Dynamics 365** | Mid-market to large enterprise | Deep integration with Microsoft 365, Teams, and Azure; strong ERP integration (Dynamics Finance & Operations); trusted by IT departments | Complex licensing; expensive; implementation typically requires a Microsoft partner; less intuitive than Salesforce or HubSpot | Module-based pricing; Sales Professional ~$65/user/mo; enterprise bundles higher |

---

## Open Source CRM Products

| Product | Features | Technology Stack | Community Support | Ease of Installation |
|---------|----------|-----------------|-------------------|---------------------|
| **EspoCRM** | Contacts, Accounts, Leads, Opportunities, Activities, Email, Calendars, Reports, REST API | PHP, MySQL, JavaScript (Vue.js frontend) | Active forum and GitHub; good documentation; regular releases | Moderate — requires PHP/MySQL server; Docker option available; online demo at demo.espocrm.com |
| **SuiteCRM** | Full CRM suite including Marketing Campaigns, Cases, Contracts, PDF templates, Workflow engine | PHP, MySQL, JavaScript | Large community (fork of SugarCRM); active GitHub; many community plugins | Moderate — traditional LAMP stack install; can be complex; SaaS-hosted option available |
| **Odoo CRM** | CRM module is part of a full ERP suite; Leads, Pipeline, Activities, Email integration | Python (Odoo framework), PostgreSQL, JavaScript | Very large community; extensive documentation; Odoo.com forums | Easy via Docker or Odoo.com cloud; on-premise more complex due to full ERP scope |

---

## Analysis

### Which commercial CRM appears most popular?

**Salesforce** is the clear market leader. With over 150,000 customers and approximately 20% market share globally, it consistently tops analyst reports from Gartner and IDC. Its Trailhead learning platform, massive AppExchange ecosystem, and deep enterprise feature set have made it the default choice for companies building serious CRM practices.

### Which open-source CRM appears most mature?

**SuiteCRM** is arguably the most mature, as it originated as a fork of the widely-deployed SugarCRM Community Edition, inheriting years of development and a large existing user base. However, **Odoo** is the most complete platform overall, as it extends far beyond CRM into a full ERP suite. For pure CRM maturity and stability, SuiteCRM edges out.

### Which CRM would you recommend for a small business?

**HubSpot CRM (free tier)** is the top recommendation for a small business. Reasons:
- Free forever plan covers contacts, deals, tasks, email, and basic reporting
- Excellent user experience minimizes training time
- Scales naturally as the business grows
- Strong integration with Gmail, Outlook, and popular small business tools

If budget is a concern and technical capacity exists, **EspoCRM** (open source, self-hosted) is a compelling free alternative.

### Which CRM would you recommend for a large enterprise?

**Salesforce** is the recommended choice for large enterprises. Reasons:
- Unmatched customization depth for complex processes
- Enterprise-grade security, compliance, and data governance
- Largest partner and integrator ecosystem for complex implementations
- Industry-specific Clouds (Health Cloud, Financial Services Cloud, Manufacturing Cloud)
- Scalability to support tens of thousands of users across global organizations

For enterprises deeply embedded in the Microsoft ecosystem, **Microsoft Dynamics 365** is a strong alternative due to native integration with Azure Active Directory, Teams, and Office 365.

---

---

# Part 3 – Open Source CRM Exploration: EspoCRM

## Selected CRM: EspoCRM

**Demo Environment:** [https://demo.espocrm.com](https://demo.espocrm.com)  
**Version Explored:** EspoCRM 8.x (online demo)  
**Method:** Used the publicly available demo environment — no local installation required.

---

## Screenshots

The following screenshots were captured from the EspoCRM demo environment and are stored in the `screenshots/` folder:

| Screen | File | Description |
|--------|------|-------------|
| Login Screen | `screenshots/login.png` | EspoCRM login page |
| Dashboard | `screenshots/dashboard.png` | Default dashboard with activity stream and pipeline widgets |
| Contacts Module | `screenshots/contacts.png` | Contacts list view with search and filter options |
| Leads Module | `screenshots/leads.png` | Leads list view with status and source columns |
| Reports Module | `screenshots/reports.png` | Reports list showing available built-in report templates |

> **Note:** Screenshots captured from demo.espocrm.com on June 1, 2026. The demo resets periodically so data shown is sample data provided by EspoCRM.

---

## Installation Experience

### Was installation easy?

For this assignment, the publicly hosted demo at **demo.espocrm.com** was used, which requires no installation. Simply navigating to the URL and logging in with the demo credentials provided on the page gives immediate access to a fully populated CRM instance.

If installing locally, EspoCRM provides reasonably clear documentation for a traditional LAMP stack (Linux, Apache, MySQL, PHP) setup. A Docker Compose option is also available, which simplifies local setup significantly:

```bash
git clone https://github.com/espocrm/espocrm-docker.git
cd espocrm-docker
docker-compose up -d
```

### What challenges occurred?

Using the demo environment, no technical challenges were encountered. The demo credentials are pre-populated on the login page.

For a hypothetical local install, the primary challenges would be:
- Ensuring the correct PHP version (8.1+ required) and enabling necessary PHP extensions
- Configuring proper file permissions on the installation directory
- Setting up cron jobs for background processing (email sync, notifications)

### How did AI help?

Claude was used to:
- Identify which open-source CRM had the most accessible demo environment for quick evaluation
- Generate a list of specific features to look for during evaluation
- Explain what each module in EspoCRM is designed to do before exploring it live
- Draft evaluation questions to make the review more structured

---

## Product Experience

### What features impressed you?

1. **Clean, modern UI** — EspoCRM has a noticeably more polished interface than many open-source competitors. The layout is intuitive and doesn't feel like a port of 2005-era enterprise software.

2. **Relationship linking** — The way EspoCRM links Contacts → Accounts → Opportunities → Activities in a single record view is well-implemented. Clicking into any record shows all related entities in subpanels below.

3. **Email integration** — EspoCRM supports syncing with IMAP/SMTP email so that all email communications are logged directly against CRM records. This is a feature some competitors only offer in paid tiers.

4. **REST API** — EspoCRM ships with a full REST API out of the box. This makes integration with other systems (website forms, helpdesk tools, marketing platforms) feasible without purchasing add-ons.

5. **Custom Fields and Layouts** — The admin panel allows adding custom fields to any entity and rearranging layouts without writing code. This is important for adapting the CRM to a specific organization's needs.

6. **Reports module** — The built-in reporting tool allows creating list reports and grid (pivot-style) reports. It's not as powerful as dedicated BI tools but covers common business reporting needs well.

### What features were missing or limited?

1. **Marketing campaign automation** — EspoCRM's campaign functionality is basic compared to HubSpot or Salesforce Marketing Cloud. There are no visual workflow builders or advanced drip sequence tools.

2. **Native mobile app** — While the web UI is mobile-responsive, there is no native iOS or Android app in the open-source version. A native app is available in the paid EspoCRM Cloud tier.

3. **Telephony/VoIP integration** — No built-in call logging from a phone system. This would require third-party integration.

4. **Advanced analytics** — The reporting module is adequate for basic reporting but lacks trend analysis, forecasting, and predictive analytics that enterprise CRMs provide.

5. **AI features** — No built-in AI-powered features (lead scoring, next best action, email generation). These are increasingly standard in commercial CRMs.

### Would you use it in a real organization?

**Yes, with qualifications.**

EspoCRM is a strong choice for:
- Small to mid-sized organizations with limited budget
- Organizations with an internal IT team capable of maintaining a self-hosted PHP/MySQL application
- Teams that need a clean, functional CRM and are willing to trade advanced features for cost savings
- Organizations that value data sovereignty (hosting their own CRM data rather than trusting a SaaS vendor)

It would **not** be ideal for:
- Large enterprises requiring deep customization, complex workflows, and enterprise-grade support SLAs
- Sales teams that need advanced AI-assisted selling features
- Organizations without any technical staff to manage the self-hosted environment

Overall, EspoCRM represents one of the best free/open-source CRM options available. It demonstrates that an open-source product, when well-maintained, can deliver a professional-grade experience comparable to low-tier commercial CRM products.

---

---

# Part 4 – CRM Architecture Exploration

## Overview

This section proposes an architecture for a custom-built CRM system using PHP and MySQL, designed as a class project / learning exercise. The MVP focuses on three core modules: **Contacts, Leads, and Opportunities** — the essential sales pipeline foundation of any CRM.

---

## Functional Modules

### MVP Modules (Build First)

| Module | Purpose | Why It's Priority |
|--------|---------|-------------------|
| **Contacts** | Store and manage individual customer records | Everything else links to a Contact — it's the foundation |
| **Leads** | Track unqualified prospects entering the pipeline | Represents top-of-funnel; converts into Contacts/Opportunities |
| **Opportunities** | Manage active deals with stage, value, and close date | Core of sales pipeline tracking |

### Future Modules (Post-MVP)

| Module | Purpose |
|--------|---------|
| **Accounts** | Group contacts by company/organization |
| **Activities** | Log calls, meetings, emails against records |
| **Tasks** | Assign follow-up actions with due dates |
| **Reports** | Summarize pipeline health and conversion metrics |
| **User Management** | Role-based access (admin, sales rep, manager) |

---

## Database Design

The following tables support the MVP modules. Each table uses an auto-incrementing primary key and timestamps for auditing.

### `contacts` table

| Column | Type | Constraints | Notes |
|--------|------|-------------|-------|
| `id` | INT | PRIMARY KEY, AUTO_INCREMENT | Unique identifier |
| `first_name` | VARCHAR(100) | NOT NULL | Contact's first name |
| `last_name` | VARCHAR(100) | NOT NULL | Contact's last name |
| `email` | VARCHAR(150) | UNIQUE | Must be unique across all contacts |
| `phone` | VARCHAR(20) | — | Optional phone number |
| `company` | VARCHAR(150) | — | Company or organization name |
| `status` | ENUM | DEFAULT 'active' | Either 'active' or 'inactive' |
| `created_at` | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP | Set automatically on insert |
| `updated_at` | TIMESTAMP | ON UPDATE CURRENT_TIMESTAMP | Auto-updates on every change |

```sql
CREATE TABLE contacts (
    id          INT AUTO_INCREMENT PRIMARY KEY,
    first_name  VARCHAR(100) NOT NULL,
    last_name   VARCHAR(100) NOT NULL,
    email       VARCHAR(150) UNIQUE,
    phone       VARCHAR(20),
    company     VARCHAR(150),
    status      ENUM('active', 'inactive') DEFAULT 'active',
    created_at  TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at  TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
);
```

### `leads` table

| Column | Type | Constraints | Notes |
|--------|------|-------------|-------|
| `id` | INT | PRIMARY KEY, AUTO_INCREMENT | Unique identifier |
| `first_name` | VARCHAR(100) | NOT NULL | Lead's first name |
| `last_name` | VARCHAR(100) | NOT NULL | Lead's last name |
| `email` | VARCHAR(150) | — | Optional — not all leads have email |
| `phone` | VARCHAR(20) | — | Optional phone number |
| `source` | ENUM | DEFAULT 'other' | Where the lead came from (web, referral, etc.) |
| `status` | ENUM | DEFAULT 'new' | Pipeline status: new → in_process → converted/dead |
| `assigned_to` | INT | FK → users(id) | Which sales rep owns this lead |
| `converted_contact_id` | INT | FK → contacts(id) | Links to Contact record when converted |
| `created_at` | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP | Set automatically on insert |
| `updated_at` | TIMESTAMP | ON UPDATE CURRENT_TIMESTAMP | Auto-updates on every change |

```sql
CREATE TABLE leads (
    id           INT AUTO_INCREMENT PRIMARY KEY,
    first_name   VARCHAR(100) NOT NULL,
    last_name    VARCHAR(100) NOT NULL,
    email        VARCHAR(150),
    phone        VARCHAR(20),
    source       ENUM('web', 'referral', 'email', 'cold_call', 'other') DEFAULT 'other',
    status       ENUM('new', 'in_process', 'assigned', 'converted', 'dead') DEFAULT 'new',
    assigned_to  INT,
    converted_contact_id INT,
    created_at   TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at   TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    FOREIGN KEY (assigned_to) REFERENCES users(id),
    FOREIGN KEY (converted_contact_id) REFERENCES contacts(id)
);
```

### `opportunities` table

| Column | Type | Constraints | Notes |
|--------|------|-------------|-------|
| `id` | INT | PRIMARY KEY, AUTO_INCREMENT | Unique identifier |
| `name` | VARCHAR(200) | NOT NULL | Deal name (e.g. "Acme Corp - 50 Licenses") |
| `contact_id` | INT | NOT NULL, FK → contacts(id) | The contact this deal is linked to |
| `amount` | DECIMAL(10,2) | — | Expected deal value in dollars |
| `stage` | ENUM | DEFAULT 'prospecting' | Pipeline stage from prospecting to closed |
| `close_date` | DATE | — | Expected or actual close date |
| `assigned_to` | INT | FK → users(id) | Sales rep responsible for this deal |
| `created_at` | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP | Set automatically on insert |
| `updated_at` | TIMESTAMP | ON UPDATE CURRENT_TIMESTAMP | Auto-updates on every change |

```sql
CREATE TABLE opportunities (
    id           INT AUTO_INCREMENT PRIMARY KEY,
    name         VARCHAR(200) NOT NULL,
    contact_id   INT NOT NULL,
    amount       DECIMAL(10,2),
    stage        ENUM('prospecting','qualification','proposal','negotiation','closed_won','closed_lost') DEFAULT 'prospecting',
    close_date   DATE,
    assigned_to  INT,
    created_at   TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
    updated_at   TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
    FOREIGN KEY (contact_id) REFERENCES contacts(id),
    FOREIGN KEY (assigned_to) REFERENCES users(id)
);
```

### `users` table

| Column | Type | Constraints | Notes |
|--------|------|-------------|-------|
| `id` | INT | PRIMARY KEY, AUTO_INCREMENT | Unique identifier |
| `name` | VARCHAR(150) | NOT NULL | Full name of the user |
| `email` | VARCHAR(150) | UNIQUE, NOT NULL | Used as login username |
| `password` | VARCHAR(255) | NOT NULL | Stored as bcrypt hash — never plaintext |
| `role` | ENUM | DEFAULT 'sales_rep' | Controls access level: admin, manager, sales_rep |
| `created_at` | TIMESTAMP | DEFAULT CURRENT_TIMESTAMP | Set automatically on insert |

```sql
CREATE TABLE users (
    id           INT AUTO_INCREMENT PRIMARY KEY,
    name         VARCHAR(150) NOT NULL,
    email        VARCHAR(150) UNIQUE NOT NULL,
    password     VARCHAR(255) NOT NULL,
    role         ENUM('admin', 'manager', 'sales_rep') DEFAULT 'sales_rep',
    created_at   TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## Recommended Libraries and Tools

| Library | Purpose | Why Use It |
|---------|---------|------------|
| **Bootstrap 5** | Frontend CSS framework | Quickly builds a clean, responsive UI without writing custom CSS from scratch |
| **jQuery / DataTables** | Interactive tables with search, sort, pagination | Contacts and Leads list views need these features; DataTables adds them with minimal code |
| **Chart.js** | Pipeline charts and dashboards | Visualizes opportunities by stage; easy to integrate with PHP-generated JSON data |
| **PHPMailer** | Send emails from PHP | Handles SMTP email sending for notifications and follow-up reminders |
| **Composer** | PHP dependency manager | Manages PHPMailer and other packages cleanly; standard in modern PHP projects |
| **PDO (built-in PHP)** | Database abstraction layer | Safer than raw mysqli; supports prepared statements to prevent SQL injection |

---

## Security Considerations

Security is critical even for a class project CRM, since it handles personal contact data.

| Threat | Mitigation |
|--------|-----------|
| **SQL Injection** | Use PDO prepared statements for all database queries — never concatenate user input directly into SQL |
| **Cross-Site Scripting (XSS)** | Escape all output with `htmlspecialchars()` before rendering in HTML |
| **Authentication** | Hash passwords with `password_hash()` (bcrypt); never store plaintext passwords |
| **Session Hijacking** | Regenerate session ID on login; use `session_regenerate_id(true)` |
| **Unauthorized Access** | Check user role/session on every page load; redirect unauthenticated users to login |
| **CSRF Attacks** | Include a CSRF token in all forms and validate it on submission |

---

## MVP Proposal

### Goal
Build the smallest functional CRM that demonstrates the core sales pipeline: capturing a Lead, converting it to a Contact, and tracking it as an Opportunity through to close.

### MVP Feature Set

1. **User login/logout** with session-based authentication
2. **Contacts module** — Create, Read, Update, Delete (CRUD) contact records
3. **Leads module** — CRUD leads with status tracking (New → In Process → Converted)
4. **Opportunities module** — CRUD opportunities linked to contacts, with pipeline stage and deal value
5. **Basic dashboard** — Count of open leads, active opportunities, and total pipeline value

### What's Intentionally Left Out of MVP
- Email integration
- File attachments
- Reporting module
- Role-based permissions (single admin user is fine for MVP)
- Mobile optimization

### Development Sequence
1. Set up database and `users` table → build login system
2. Build Contacts CRUD (simplest module, no foreign keys)
3. Build Leads CRUD with status dropdown
4. Build Opportunities CRUD linked to Contacts
5. Add dashboard with summary counts using simple SQL aggregate queries

---

## Architecture Diagram

The architecture diagram is located at [`architecture/crm_architecture.png`](./architecture/crm_architecture.png).

The system follows a classic three-tier web architecture:

- **Presentation Layer** — HTML/CSS (Bootstrap), JavaScript (jQuery, Chart.js) rendered in the browser
- **Application Layer** — PHP handles routing, business logic, form validation, session management, and database queries via PDO
- **Data Layer** — MySQL stores all CRM data in relational tables with foreign key constraints

All user requests flow through PHP, which queries MySQL and returns rendered HTML back to the browser. There is no separate API layer in the MVP — PHP renders pages server-side.

---

## Why This Stack for a Class Project?

PHP and MySQL were chosen because:
- Both are widely taught and well-documented, making it easy to find help
- The LAMP stack (Linux, Apache, MySQL, PHP) runs on nearly any hosting environment including free tiers
- PHP handles HTML generation, form processing, and database queries in a single language — reducing context switching for a solo developer
- MySQL's relational model is a natural fit for CRM data, where contacts, leads, and opportunities are linked by foreign keys
- This stack mirrors what EspoCRM and SuiteCRM themselves are built on, making the research in Parts 2 and 3 directly relevant

---

**🩺 Vaidyog – Healthcare Job Portal**

User app: https://play.google.com/store/apps/details?id=com.vaidyog.user

Recruiter app: https://play.google.com/store/apps/details?id=com.vaidyog.recruiter.app

web: http://healthcarejobs.vaidyog.com/login

As the Lead QA Tester for the Vaidyog Healthcare Job Portal, I was responsible for validating the platform across all interfaces —

📱 User App (Candidates)
📱 Recruiter App
🖥️ Admin & Sub-Admin Web Panel

My testing ensured that Vaidyog delivered secure, accurate, fast, and user-friendly job searching and recruitment workflows across the healthcare ecosystem.

**🧩 🔍 Scope of Testing & Key Responsibilities**

**✔️ Full Functional Coverage**

I performed complete functional testing across modules like:

Authentication & onboarding for all roles

Plan-based job posting & job application limits

Recruiter–candidate interaction workflows

Admin-level approvals and platform configurations

**✔️ Role-Based Testing**

Validated permissions and access controls for:
Admin → Sub-Admin → Recruiter → Candidate
Ensured every role saw only their intended modules & data.

**✔️ Complex Scenario Testing**
Plan expiry → job posting disabled

Job count exceeding limit → error validation

Candidate in a lower plan attempting premium job applications

Data discrepancies between analytics charts and raw DB

Cross-role interactions (Recruiter post → Candidate apply → Admin review)

**📱 User App (Candidate) – Deep Testing Coverage**

🟢 User Core Modules

OTP authentication

Profile creation (education, specialization, experience)

Job search:

Role-based

Education-level

Work type

Posted date range

Job detail consistency & requirement visibility

Job apply → success flow

Plan restrictions:

Application limit reached

Premium job access restricted

Saved jobs, history, notifications

🧪 Special Test Scenarios

Search speed test (after developer implemented aggregation pipelines)

No-result scenarios

Case-insensitive keyword search

Pagination & infinite scroll validation

**🧑‍⚕️ Recruiter App – Deep Testing Coverage**

🟢 Recruiter Workflow Testing

Recruiter onboarding & verification

Job posting with all mandatory fields

Job update/edit validation

Plan-based job posting limits:

Limits exceeded

Plan expired

No plan assigned

📊 Analytics Testing

Checked accuracy across:

Active vs expired postings

Plan usage %

Candidate applications count

Graph color accuracy, legends, filters

🧪 Special Scenarios

Recruiter deleting a job → removed across candidate app

Recruiter job status changes reflected in real-time

Edge cases for invalid salary formats, job titles, filters

**🖥️ Admin Panel – Full Testing Coverage**

🟢 Admin Functional Testing

Create & manage plans (job post limit, validity days)

Assign plans to recruiters & users

Recruiter approval flow

Update platform masterdata:

Work types

Roles

Education levels

Clinical sub-domains

📉 Analytics Testing

Manually validated Chart.js graphs by comparing:

Aggregated DB results (Mongo queries)

Admin panel displayed values
Ensured absolute accuracy between UI and backend data.

🧪 Critical Scenarios

Suspended recruiter should not post or view analytics

Expired plans → auto-block job posting

Editing masterdata reflects instantly on all apps

⚙️ API & Performance Validation

🔥 Advanced Testing Areas

Validated API responses for job filters

Query performance after optimization with Aggregation Pipelines

Checked endpoint handling for incorrect/invalid filters

Ensured pagination, sorting, and indexing worked properly

**🐞 Bug Reporting & Communication**

I delivered high-quality bug reports with:

📝 Detailed steps to reproduce

🎯 Expected vs actual behavior

📍 Environment (mobile, browser)

🎥 Supporting screenshots / screen recordings

🔥 Clear severity (Critical, Major, Minor)

🔁 Final retesting & regression status

This structure helped developers understand, replicate, and fix issues much faster, reducing back-and-forth time.

🚀** Key Outcomes of My Testing Contribution**

📌 Platform Stability Increased

Identified multiple issues in job posting logic, plan validation, analytics mismatches, and search edge cases.

📌 Search Performance Improved

After my reports, the developer optimized MongoDB aggregation — reducing latency by 47%.

📌 Plan-Based Logic Became More Robust

Complex scenarios were stabilized: expiry, limit exceeded, premium jobs, partial data.

📌 Better User Experience

Resolved UI/UX issues across apps, ensuring smooth onboarding & application flow.

📌 Analytics Accuracy Achieved

Charts now perfectly reflect real backend data due to cross-verification testing.

📌 Higher Quality Release

Delivered a stable, production-ready build with fewer regressions and improved flow.


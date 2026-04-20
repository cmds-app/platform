# Release notes

When each release goes Live, we post release notes here describing what's new, what's changed, and what's been fixed.

Looking for a specific release date? See Release dates.

Release notes will be posted here as each release goes Live.

## Upcoming: Version 26.2

The next update to the Live environment is scheduled May 7, 2026 at 8:00 PM MDT.

Here is a comprehensive list of changes for pre-release testing. It was generated from the source code repository using the following command:

`git diff --name-only release/v26.1..release/v26.2` (321 commits, 184 web-forms-related file changes).

## 1. Directly Modified ASPX Pages

These forms had their markup (`.aspx`) or code-behind (`.aspx.cs`) changed. Every URL below must be retested.

### Admin — Assessments

| ASPX | URL |
|---|---|
| `~/UI/Admin/Assessments/Attachments/Forms/Change.aspx` | `ui/admin/assessments/attachments/change` |
| `~/UI/Admin/Assessments/Attachments/Forms/Delete.aspx` | `admin/assessments/attachments/delete` |
| `~/UI/Admin/Assessments/Attempts/Forms/Report.aspx` | `ui/admin/assessments/attempts/report` |
| `~/UI/Admin/Assessments/Banks/Forms/Print.aspx` | `ui/admin/assessments/banks/print` |
| `~/UI/Admin/Assessments/Forms/Forms/ChangeAddendum.aspx` | `ui/admin/assessments/forms/change-addendum` |
| `~/UI/Admin/Assessments/Forms/Forms/Print.aspx` | `ui/admin/assessments/forms/print` |
| `~/UI/Admin/Assessments/Forms/Forms/Publish.aspx` | `ui/admin/assessments/forms/publish` |
| `~/UI/Admin/Assessments/Questions/Forms/Change.aspx` | `ui/admin/assessments/questions/change` |
| `~/UI/Admin/Assessments/Specifications/Forms/Workshop.aspx` | `ui/admin/assessments/specifications/workshop` |

### Admin — Contacts

| ASPX | URL |
|---|---|
| `~/UI/Admin/Contacts/People/Forms/CreateUserConnection.aspx` | `ui/admin/contacts/people/create-user-connection` |
| `~/UI/Admin/Contacts/People/Forms/SendEmail.aspx` | `ui/admin/contacts/people/send-email` |

### Admin — Events

| ASPX | URL |
|---|---|
| `~/UI/Admin/Events/Classes/Forms/Outline.aspx` | `ui/admin/events/classes/outline` |
| `~/UI/Admin/Events/Registrations/Search.aspx` | `ui/admin/events/registrations/search` |

### Admin — Learning

| ASPX | URL |
|---|---|
| `~/UI/Admin/Learning/Programs/Delete.aspx` | `ui/admin/learning/programs/delete` |
| `~/UI/Admin/Learning/Programs/Describe.aspx` | `ui/admin/learning/programs/describe` |
| `~/UI/Admin/Learning/Programs/Enrollments/Assign.aspx` | `ui/admin/learning/programs/enrollments/assign` |
| `~/UI/Admin/Learning/Programs/ModifyAchievement.aspx` | `ui/admin/learning/programs/modify-achievement` |
| `~/UI/Admin/Learning/Programs/ModifyCatalog.aspx` | `ui/admin/learning/programs/modify-catalog` |
| `~/UI/Admin/Learning/Programs/ModifyContent.aspx` | `ui/admin/learning/programs/modify-content` |
| `~/UI/Admin/Learning/Programs/ModifyNotification.aspx` | `ui/admin/learning/programs/modify-notification` |
| `~/UI/Admin/Learning/Programs/ModifyPublication.aspx` | `ui/admin/learning/programs/modify-publication` |
| `~/UI/Admin/Learning/Programs/ModifySettings.aspx` | `ui/admin/learning/programs/modify-settings` |
| `~/UI/Admin/Learning/Programs/Outline.aspx` | `ui/admin/learning/programs/outline` |
| `~/UI/Admin/Learning/Programs/Tasks/Assign.aspx` | `ui/admin/learning/programs/tasks/assign` |

### Admin — Messages

| ASPX | URL |
|---|---|
| `~/UI/Admin/Messages/Mailouts/Failures/Search.aspx` | `ui/admin/messages/mailouts/failures/search` |
| `~/UI/Admin/Messages/Messages/Forms/Content.aspx` | `ui/admin/messages/content` |

### Admin — Records

| ASPX | URL |
|---|---|
| `~/UI/Admin/Records/Logbooks/ValidateExperience.aspx` | `ui/admin/records/logbooks/validate-experience` |
| `~/UI/Admin/Records/Logbooks/Validators/Entries/ViewExperience.aspx` | `ui/admin/records/logbooks/validators/entries/view-experience` |
| `~/UI/Admin/Records/Logbooks/Validators/Forms/ValidateExperience.aspx` | `ui/admin/records/logbooks/validators/validate-experience` |

### Admin — Reports / Sites / Workflow

| ASPX | URL |
|---|---|
| `~/UI/Admin/Reports/Build.aspx` | `ui/admin/reports/build` |
| `~/UI/Admin/Sites/Pages/Forms/Outline.aspx` | `ui/admin/sites/pages/outline` |
| `~/UI/Admin/Workflow/Cases/AssignContacts.aspx` | `ui/admin/workflow/cases/assign-contacts` |
| `~/UI/Admin/Workflow/Cases/Close.aspx` | `ui/admin/workflow/cases/close` |
| `~/UI/Admin/Workflow/Cases/Delete.aspx` | `ui/admin/workflow/cases/delete` |
| `~/UI/Admin/Workflow/Cases/Describe.aspx` | `ui/admin/workflow/cases/describe` |
| `~/UI/Admin/Workflow/Cases/Download.aspx` | `ui/admin/workflow/cases/download` |
| `~/UI/Admin/Workflow/Cases/ModifyStatus.aspx` | `ui/admin/workflow/cases/modify-status` |
| `~/UI/Admin/Workflow/Cases/ModifyTitle.aspx` | `ui/admin/workflow/cases/modify-title` |
| `~/UI/Admin/Workflow/Cases/ModifyType.aspx` | `ui/admin/workflow/cases/modify-type` |
| `~/UI/Admin/Workflow/Cases/Outline.aspx` | `ui/admin/workflow/cases/outline` |
| `~/UI/Admin/Workflow/Cases/SendEmail.aspx` | `ui/admin/workflow/cases/send-email` |
| `~/UI/Admin/Workflow/Comments/Create.aspx` | `ui/admin/workflow/comments/create` |
| `~/UI/Admin/Workflow/Comments/Delete.aspx` | `ui/admin/workflow/comments/delete` |
| `~/UI/Admin/Workflow/Comments/Modify.aspx` | `ui/admin/workflow/comments/modify` |
| `~/UI/Admin/Workflow/Forms/OutlineWotabs.aspx` | `ui/admin/workflow/forms/outline-wotabs` |

### CMDS

| ASPX | URL |
|---|---|
| `~/UI/CMDS/Admin/Achievements/Credentials/AssignCertificate.aspx` | `ui/cmds/admin/achievements/credentials/assign-certificate` |
| `~/UI/CMDS/Admin/Achievements/Edit.aspx` | `ui/cmds/admin/achievements/edit` |
| `~/UI/CMDS/Admin/Reports/DepartmentProfileDetails.aspx` | `ui/cmds/admin/reports/department-profile-details` |
| `~/UI/CMDS/Admin/Reports/TrainingCompletions.aspx` | `ui/cmds/admin/reports/training-completions` |
| `~/UI/CMDS/Admin/Reports/TrainingExpiryDates.aspx` | `ui/cmds/admin/reports/training-expiry-dates` |
| `~/UI/CMDS/Admin/Validations/Competencies/Validate.aspx` | `ui/cmds/admin/validations/competencies/validate` |
| `~/UI/CMDS/Design/Validations/Competencies/Search.aspx` | `ui/cmds/design/validations/competencies/search` |
| `~/UI/CMDS/Design/Validations/Competencies/Start.aspx` | `ui/cmds/design/validations/competencies/start` |
| `~/UI/CMDS/Portal/Validations/Competencies/Start.aspx` | `ui/cmds/portal/validations/competencies/start` |
| `~/UI/CMDS/Portal/Validations/Competencies/Submit.aspx` | `ui/cmds/portal/validations/competencies/submit` |

### Root / Lobby / Portal

| ASPX | URL |
|---|---|
| `~/UI/Home.aspx` | `ui/home` |
| `~/UI/Lobby/SignOut.aspx` | `ui/lobby/signout` |
| `~/UI/Portal/Assessments/Attempts/Answer.aspx` | `ui/portal/assessments/attempts/answer` |
| `~/UI/Portal/Assessments/Attempts/Result.aspx` | `ui/portal/assessments/attempts/result` |
| `~/UI/Portal/Events/Classes/Outline.aspx` | `ui/portal/events/classes/outline` |
| `~/UI/Portal/Events/Classes/RegisterEmployee.aspx` | `ui/portal/events/classes/register-employee` |
| `~/UI/Portal/Home/Achievements.aspx` | `ui/portal/home/achievements` |
| `~/UI/Portal/Home/LearningPlan.aspx` | `ui/portal/home/learning-plan` |
| `~/UI/Portal/Home/Statistics.aspx` | `ui/portal/home/statistics` |
| `~/UI/Portal/Learning/Course.aspx` | `ui/portal/learning/course` |
| `~/UI/Portal/Learning/Plan.aspx` | `ui/portal/learning/plan` |
| `~/UI/Portal/Learning/Programs/Plan.aspx` | `ui/portal/learning/programs/plan` |
| `~/UI/Portal/Profile.aspx` | `ui/portal/profile` |

## 2. High-Impact Shared Control / Master Page Changes

These changes affect MANY forms. Smoke-test a representative page in each bucket below.

- **`UI/Layout/Portal/Portal.master`** — every `ui/portal/*` page (sign-in state, branding, chrome). Spot-check: `ui/portal/home`, `ui/portal/learning/catalog`, `ui/portal/events/calendar`, `ui/portal/profile`.
- **`UI/Layout/Common/Controls/Navigation/AdminNavigation.ascx[.cs]`** + **`AdminHeader.ascx.cs`** — every `ui/admin/*` page. Spot-check: `ui/admin/home`, `ui/admin/assessments/home`, `ui/admin/records/home`, `ui/admin/workflow/home`.
- **`UI/Layout/Common/Controls/Navigation/PortalHeader.ascx.cs`** + **`PortalBreadcrumbs.ascx.cs`** — every portal page header/breadcrumb.
- **`UI/Layout/Common/Controls/BundleJsHeader.ascx`** — any page loading bundled JS; verify no client-side errors after deploy.

## 3. ASCX User Control Changes — Pages to Retest by Module

Shared controls whose callers cover multiple URLs above. Prioritize the URL already listed in Section 1; otherwise pick at least one page from the module.

| Changed Control | Pages Affected (retest) |
|---|---|
| `Admin/Assessments/Attachments/Controls/*.ascx[.cs]` (AttachmentsTabsNav, ImagePrint, ImageRepeater, QuestionAttachmentRepeater) | `ui/admin/assessments/attachments/add`, `/change`, `/history`, `/scan-images`, `/usage`, `admin/assessments/attachments/delete` |
| `Admin/Assessments/Attempts/Controls/QuestionAnalysisRepeater.ascx`, `QuestionCompetencyRatioRepeater.ascx` | `ui/admin/assessments/attempts/report`, `/ratio`, `/advanced-analytics`, `/view`, `/taker-report`, `/skillscheck-report` |
| `Admin/Assessments/Attempts/Reports/Controls/SearchCriteria.ascx[.cs]` | `ui/admin/assessments/attempts/reports/search`, `/search-performance-report` |
| `Admin/Assessments/Forms/Controls/FormAddendumDetails.ascx.cs` | `ui/admin/assessments/forms/change-addendum`, `/content` |
| `Admin/Assessments/Options/Controls/OptionReadRepeater.ascx.cs` | `ui/admin/assessments/questions/change`, `/analysis`, `/add`, portal `ui/portal/assessments/attempts/answer`, `/result` |
| `Admin/Assessments/Outlines/Controls/FormsSection.ascx[.cs]`, `QuestionsSection.ascx`, `SpecificationsSection.ascx` | `ui/admin/assessments/banks/outline`, `/content` |
| `Admin/Assessments/Questions/Controls/QuestionPrintCompact/External/Internal.ascx[.cs]`, `WorkshopQuestionRepeater.ascx[.cs]`, `QuestionStatisticsPanel.ascx[.cs]` | `ui/admin/assessments/banks/print`, `ui/admin/assessments/forms/print`, `/workshop`, `/publish`, `ui/admin/assessments/questions/analysis`, `ui/admin/assessments/specifications/workshop` |
| `Admin/Assets/Files/Controls/UploadDetail.ascx.cs` | `ui/admin/assets/files/upload`, `/browse`, `/edit`, `ui/admin/assets/uploads/browse`, `/info` |
| `Admin/Contacts/Groups/Controls/RoleGrid.ascx` | `ui/admin/contacts/groups/outline`, `/manage`, `/edit` |
| `Admin/Contacts/People/Controls/EditTabDetails.ascx`, `RegistrationGrid.ascx.cs`, `UserConnectionGrid.ascx.cs` | `ui/admin/contacts/people/edit`, `/create`, `/create-user-connection`, `/edit-user-connection`, `/delete-user-connection` |
| `Admin/Courses/Outlines/Controls/ActivityEditAssessment.ascx`, `ModuleTreeView.ascx` | `ui/admin/courses/manage`, `ui/admin/courses/modules/delete`, `ui/admin/courses/activities/delete` |
| `Admin/Events/Classes/Controls/RegistrationGrid.ascx.cs` | `ui/admin/events/classes/outline`, `ui/admin/events/registrations/search` |
| `Admin/Events/Registrations/Classes/Controls/SearchCriteria.ascx[.cs]`, `SearchResults.ascx[.cs]`, `Reports/ExamLoginCredentialsReport.ascx[.cs]` | `ui/admin/events/registrations/search`, `ui/admin/events/registrations/exams/search`, `ui/admin/registrations/classes/*` (add/card/delete/edit/move) |
| `Admin/Learning/Programs/Controls/ProgramContactTab.ascx.cs` | `ui/admin/learning/programs/outline`, `/describe`, `/modify-notification` |
| `Admin/Messages/Emails/Controls/SearchResults.ascx.cs` | `ui/admin/messages/emails/search` |
| `Admin/Messages/Mailouts/Controls/CompletedGrid.ascx`, `ScheduledGrid.ascx` | `ui/admin/messages/mailouts/search`, `/schedule` |
| `Admin/Messages/Mailouts/Failures/Controls/SearchCriteria.ascx[.cs]`, `SearchResults.ascx[.cs]` | `ui/admin/messages/mailouts/failures/search` |
| `Admin/Messages/Messages/Controls/SendEmail.ascx.cs` | `ui/admin/contacts/people/send-email`, `ui/admin/workflow/cases/send-email`, `ui/admin/messages/content` |
| `Admin/Records/Achievements/Controls/CredentialGrid.ascx[.cs]` | `ui/admin/records/achievements/outline`, `ui/admin/records/credentials/outline`, `/search` |
| `Admin/Records/Logbooks/Controls/CompetencyProgressGrid.ascx[.cs]`, `Entries/Controls/LogEntryCompetencyGrid.ascx[.cs]` | `ui/admin/records/logbooks/outline`, `/content`, `/competencies/search`, `/entries/search`, `/view-experience`, `/validate-experience`, and matching `validators/*` URLs |
| `Admin/Reporting/Controls/LoginHistorySearchResults.ascx` | `ui/admin/reporting/login-history` |
| `Admin/Reports/Queries/Controls/QuerySearchCriteria.ascx` | `ui/admin/reports/queries/search` |
| `Admin/Sales/Invoices/Controls/SearchCriteria.ascx[.cs]` | `ui/admin/sales/invoices/search` |
| `Admin/Sales/Reports/EventRegistrationPayment/SearchCriteria.ascx[.cs]`, `SearchResults.ascx[.cs]` | `ui/admin/sales/reports/event-registration-payments` |
| `Admin/Sites/Pages/Controls/ContentBlocksManager/Viewer.ascx[.cs]`, `ContentSectionViewer.ascx[.cs]` | `ui/admin/sites/pages/outline`, `/content`, `/change-page-setup`, `/change-structure`, `/change-settings`, any public site page rendering |
| `Admin/Workflow/Cases/Controls/CaseDocumentList.ascx[.cs]`, `SearchCriteria.ascx.cs` | `ui/admin/workflow/cases/search`, `/outline`, `/describe` |
| `CMDS/Admin/Achievements/SearchCriteria.ascx[.cs]` | `ui/cmds/admin/achievements/search` |
| `CMDS/Common/Controls/User/EmployeeAchievementDetails.ascx.cs`, `SignOff.ascx[.cs]`, `UpcomingSessionList.ascx.cs` | `ui/cmds/admin/validations/competencies/validate`, `ui/cmds/portal/validations/competencies/validate`, `/submit`, `ui/admin/dashboard/employer`, `ui/portal/home` (CMDS tiles) |
| `CMDS/Portal/Achievements/Credentials/SearchResults.ascx.cs` | `ui/cmds/portal/achievements/credentials/search` |
| `CMDS/Portal/Validations/Competencies/SearchCriteria.ascx.cs`, `SearchResults.ascx.cs` | `ui/cmds/portal/validations/competencies/search` |
| `HomeCmds.ascx.cs` | `ui/home` (CMDS landing panel) |
| `Portal/Assessments/Attempts/Controls/AnswerQuestionOutput.ascx.cs`, `ResultQuestionOutput.ascx.cs` | `ui/portal/assessments/attempts/answer`, `/result`, `/start` |
| `Portal/Contacts/Referral/Controls/SearchCriteria.ascx.cs` | `ui/portal/contacts/referral/search`, `/outline`, `/create` |
| `Portal/Events/Classes/Controls/Venue.ascx[.cs]`, `VenueAddress.ascx[.cs]` | `ui/portal/events/classes/outline`, `/search`, `/register`, `/register-employee`, `/register-multiple` |
| `Portal/Identity/Controls/MFASelectMode.ascx.cs` | `ui/lobby/signin-mfa`, `ui/lobby/signin-challenge`, `ui/portal/identity/authenticate` |
| `Portal/Learning/Controls/PlanAchievementTypeRepeater.ascx[.cs]` | `ui/portal/learning/plan`, `ui/portal/home/learning-plan`, `ui/portal/learning/programs/plan` |
| `Portal/Records/Logbooks/Controls/CompetencyList.ascx[.cs]`, `CompetencyProgressGrid.ascx[.cs]` | `ui/portal/records/logbooks/outline`, `/search`, `/outline-entry` |
| `Portal/Workflow/Forms/Controls/Confirm.ascx[.cs]`, `Launch.ascx.cs` | `ui/portal/workflow/forms/submit/confirm`, `/launch`, `/start`, `/resume`, `/answer`, `/review`, `/review-print`, `/goto`, `/complete`, `/delete` |

## 4. Retest Scope Summary

- **Direct ASPX changes:** 68 forms → all must be retested.
- **Shared controls:** ~35 ASCX changes spanning Assessments, Contacts, Events, Learning, Messages, Records, Sales, Sites, Workflow, CMDS, and Portal.
- **Site-wide chrome:** Portal master + Admin/Portal navigation/header/breadcrumb controls — regression-check navigation, breadcrumbs, and header on a sample page per area.

## 5. Additional Testing Beyond ASPX Forms

The v26.2 diff contains 573 non-web-forms file changes across 321 commits / 59 unique TEC tickets. The items below are **not covered** by the ASPX/ASCX retest list and need their own test passes.

### 5.1 New React (Shift.UI) screens — TEC-434 Workshop Redevelopment

Largest feature in this release. Migrates the legacy `WorkshopQuestionRepeater.ascx` flow into React and introduces two new screen families. Test end-to-end: load, edit, save, filter, attachments, comments, navigation back to legacy `.aspx` callers.

- **FormWorkshop** — `src/ui/Shift.UI/src/routes/admin/assessments/forms/FormWorkshop*` (entry URL: `client/admin/assessment/forms/workshop`). Verify Form details, Questions, Summaries tabs; question options (single/multi/boolean/matching); asset/image selection; filter by change date; posting comments; "replace" commands; unsaved-changes guard.
- **SpecWorkshop** — `src/ui/Shift.UI/src/routes/admin/assessments/specs/SpecWorkshop*`. Verify Specification tab, BankView tab, Competencies, Criteria, calculations.
- **WorkshopQuestions / WorkshopAttachments / WorkshopComments / WorkshopProblems** — `src/ui/Shift.UI/src/routes/admin/assessments/{questions,other}/`. Verify interaction with the legacy `~/UI/Admin/Assessments/Specifications/Forms/Workshop.aspx` entry point.
- **Permission inheritance:** `config/RouteSettings.json` now maps `client/admin/assessment/forms/workshop` → `evaluation/banks`. Confirm users with only "banks" permissions can access the new Workshop and users without cannot.

### 5.2 React auth / session / page-content — TEC-371

Auth plumbing on the React side was reworked. Test on both a fresh browser (no cookie) and an authenticated session.

- **Cookie/auth flow:** `src/api/Shift.Api/Security/Cookies/{CookieController,CookieService,LoginHelper}.cs`, `Internal/Authentication/{CookieAuthenticationHandler,PrincipalProvider}.cs`. Test sign-in, session refresh, session extension on non-authenticated users (should be rejected), sign-out.
- **Impersonation on React screens:** start/stop impersonation via `ui/portal/security/impersonation/start|stop`, then load a React route (e.g., Workshop) and confirm identity propagates.
- **PageContent React module:** `src/ui/Shift.UI/src/routes/admin/sites/pages/content/PageContent*` + `src/api/Shift.Api/Workspace/PageContentController.cs`. Entry from `ui/admin/sites/pages/content`. Test create/edit/delete blocks, HTML/image/image-list editors, unsaved-changes prompt, "Save & Close" redirect, recently-created block tab (TEC-371 crash fix).
- **Route inheritance:** `config/RouteSettings.json` maps `client/admin/sites/pages/content` → `workspace/pages` — verify permission propagation.

### 5.3 Mailgun webhook / Message Failures Report — TEC-466

Brand-new integration. Needs both a functional test and a configuration test.

- **Webhook endpoint:** `source/InSite.UI/Api/Controllers/MessageController.cs` plus `source/InSite.UI/Api/Models/MailgunWebhook/*` (22 new model classes). Test all event types: Accepted, Delivered, Failed, Opened, Clicked, Complained, Unsubscribed. Verify signature validation rejects unsigned payloads.
- **New setting:** `config/AppSettings.json` → `MailgunCallbackEnabled` (default `false`). Test both flag states.
- **Report UI:** `ui/admin/messages/mailouts/failures/search` (also listed in Section 1). Confirm records posted by webhook appear here.

### 5.4 Database upgrade scripts

Sixteen SQL upgrade scripts ship in this release. Run them against a production-like DB and verify no errors and no reserved-keyword collisions.

| Script | Ticket |
|---|---|
| `v26.1/261.2026.0330.1457 TEC-744.sql` | TEC-744 |
| `v26.1/261.2026.0402.1851 TEC-756.sql` | TEC-756 |
| `v26.1/261.2026.0408.1341 TEC-761.sql` | TEC-761 |
| `v26.2/261.2026.0322.1708 TEC-717.sql` | TEC-717 |
| `v26.2/262.2026.0218.1915 TEC-371.sql` | TEC-371 |
| `v26.2/262.2026.0224.1524 TEC-466.sql` | TEC-466 |
| `v26.2/262.2026.0226.1738 TEC-595.sql` | TEC-595 |
| `v26.2/262.2026.0227.1258 TEC-129.sql` | TEC-129 |
| `v26.2/262.2026.0303.1343 TEC-540.sql` | TEC-540 |
| `v26.2/262.2026.0306.1837 TEC-581.sql` | TEC-581 |
| `v26.2/262.2026.0309.1745 TEC-632.sql` | TEC-632 |
| `v26.2/262.2026.0309.1818 TEC-633.sql` | TEC-633 |
| `v26.2/262.2026.0319.1504 TEC-466.sql` | TEC-466 |
| `v26.2/262.2026.0326.0920 TEC-670.sql` | TEC-670 |
| `v26.2/262.2026.0331.2030 TEC-434.sql` | TEC-434 |
| `v26.2/262.2026.0401.1656 TEC-725.sql` | TEC-725 |

### 5.5 API controller additions

Wire up Postman / integration smoke tests for new controllers.

- `src/api/Shift.Api/Evaluation/Workshops/BankWorkshopController.cs` (was `QuestionWorkshopController`)
- `src/api/Shift.Api/Evaluation/Workshops/FormWorkshopController.cs`
- `src/api/Shift.Api/Evaluation/Workshops/SpecWorkshopController.cs`
- `src/api/Shift.Api/Workspace/PageContentController.cs`
- `src/api/Shift.Api/Timeline/{CommandController,QueryController,TimelineService}.cs` — new `api/timeline/aggregates/{aggregateId}` endpoint.
- `source/InSite.UI/Api/Controllers/BookingEventsController.cs` — changed alongside `api/booking/events/retrieve` permission entry in RouteSettings.

### 5.6 Behavioral bug fixes (not visible from ASPX diff)

These commits change runtime behavior without necessarily changing the `.aspx` or `.aspx.cs` file. Each needs its listed flow retested.

| Ticket | Area | Retest |
|---|---|---|
| TEC-527 | Unspecified hotfix series (4 commits) | Regression-check recently-reported hotfix area |
| TEC-610 | INSPIRE — retain "recent" filter between sessions | Sign out/in; verify "recent" criteria persists |
| TEC-614 | React route permissions for non-operator users | Log in as non-operator; open each React route |
| TEC-615 | INSPIRE — Person Code / Email on Attempt Search | `ui/admin/assessments/attempts/reports/search` criteria & results |
| TEC-621 | CAMLPR — Permission Lists required | Validation in achievement/credential flows |
| TEC-625 | BCWS — Form-based case assignment by Supervisor/Manager | Org setting + form submission → case creation |
| TEC-626 | BCWS — Program enrollments improvements | `ui/admin/learning/programs/enrollments/assign` (also Section 1) |
| TEC-632 | BCWS — Training Completions report column | `ui/cmds/admin/reports/training-completions` (Section 1) |
| TEC-633 | BCWS — Organization-customizable help text | Help text on org-scoped screens |
| TEC-645 | BCWS — Case creation via Form | Form submission → case creation |
| TEC-646 | Form Submission button rename | `ui/portal/workflow/forms/submit/*` |
| TEC-667 | CAMLPR — Date Received column on Case Attachments | `ui/admin/workflow/cases/outline` attachments tab |
| TEC-670 | RCABC — Search on Event Registrations | `ui/admin/events/registrations/search` (Section 1) |
| TEC-679 | Function type updated via group survey response | Survey response → group membership side effect |
| TEC-685 | SkillsCheck — achievement badge on dashboard | `ui/portal/home` |
| TEC-690 | Assessment Form Outline fix | `ui/admin/assessments/forms/content` |
| TEC-702 | Unspecified fix | Regression |
| TEC-717 | Unspecified feature (DB + commit) | Smoke test + DB script |
| TEC-723 | BCWS — Manager/Supervisor + Case owners | Case ownership flows |
| TEC-724 | Program Content fix + delete dead code | `ui/admin/learning/programs/modify-content`, `/describe` |
| TEC-725 | NCSHA MR01 report update | `ui/admin/plugin/ncsha/refresh-reports` |
| TEC-728 | Redirect when editing Class Registration | `ui/admin/registrations/classes/edit` |
| TEC-733 | Events on Calendar display | `ui/portal/events/calendar` |
| TEC-734 | Effective Since / Before date fields | Date pickers across admin screens |
| TEC-737 | French translations for Portal Classes | `ui/portal/events/classes/*` in FR locale |
| TEC-740 | ITA notifications not triggered on Exam Publish | `ui/admin/events/exams/*` publish flow |
| TEC-742 | Sections in assessment attempts | `ui/portal/assessments/attempts/start|answer|result` |
| TEC-743 | "Invalid name" on edit-uploads | `ui/cmds/admin/achievements/edit-uploads` |
| TEC-744 | (fix; DB migration included) | Per TEC-744 ticket |
| TEC-745 | ITA016 notification | Notification trigger flow |
| TEC-750 | (4 commits) | Per TEC-750 ticket |
| TEC-754 | Hotfix | Per TEC-754 ticket |
| TEC-756 | (fix; DB migration included) | Per TEC-756 ticket |
| TEC-759 | Unspecified fix | Regression |
| TEC-760 | Form Submissions showing "Someone" instead of user name | `ui/portal/workflow/forms/submit/*` and admin view |
| TEC-761 | (DB migration + commits) | Per TEC-761 ticket |
| TEC-762 | Marketing redirects for industry/audience pages | Public-site redirect rules |
| TEC-763 | Login redirect from Form response start | Unauthenticated → `ui/portal/workflow/forms/submit/start` |
| TEC-767 | MFA "Unsupported mode" | `ui/lobby/signin-mfa`, `signin-challenge` |
| TEC-768 | Null reference in RejectMailout command | Mailout rejection flow |
| TEC-769 | MissingGradebookException | Gradebook flows |
| TEC-771 | Connection Attributes investigation | User connection data |
| TEC-772 | Addendum figures disappearing post-publish | `ui/admin/assessments/forms/change-addendum` → publish |
| TEC-773 | `.sql` upload on Queries search | `ui/admin/reports/queries/search` |

### 5.7 Persistence layer changes (server-side query behavior)

Query logic changed in these files — verify result sets on the affected UIs remain correct.

- `InvoiceSearch.cs` → `ui/admin/sales/invoices/search`
- `VEventRegistrationPaymentFilter/Helper.cs` → `ui/admin/sales/reports/event-registration-payments`
- `EventSearch.cs` → `ui/admin/events/classes/search`, `ui/portal/events/calendar`
- `RegistrationSearch.cs` → `ui/admin/events/registrations/search`
- `StorageService.cs`, `TFileSearch.cs` → `ui/admin/assets/files/browse`, `ui/admin/assets/uploads/browse`
- `MembershipSearch.cs` → `ui/admin/contacts/memberships/search`
- `PersonCriteria.cs`, `PersonFilter.cs` → `ui/admin/contacts/people/search`
- `AttemptSearch.cs` → `ui/admin/assessments/attempts/reports/search`
- `BankStore.cs`, `QBankQuestionConfiguration.cs` → `ui/admin/assessments/banks/*`
- `ProgramSearch.cs`, `ProgramSearch1.cs` → `ui/admin/learning/programs/search`
- `EmailOutbox.cs`, `VMailoutFailureConfiguration.cs`, `XMailoutConfiguration.cs`, `MessageHelper.cs`, `MessageSearch.cs`, `MessageStore.cs` → `ui/admin/messages/*`
- `AchievementStore.cs` → `ui/admin/records/achievements/*`
- `CmdsProcessor.cs`, `CmdsReportHelper.cs`, `EmployeeCompetencyFilter.cs`, `UserCompetencyRepository.cs`, `VCmdsCredentialSearch.cs` → CMDS reports & validations
- `SkilledTradesBC/{EventProcessor,RegistrationProcessor}.*.cs` → STBC-specific event/registration flows
- `CaseSearch.cs`, `SurveyStore.cs` → `ui/admin/workflow/cases/search`, workflow forms

### 5.8 Config & build

- `config/AppSettings.json` — new `MailgunCallbackEnabled` key (default `false`). Deploy-time check that the per-environment override exists in UAT/Prod.
- `config/RouteSettings.json` — two new permission-inheritance entries (workshop & page content). Test with least-privilege users.
- `build/Build-Engine.ps1`, `build/Build-Shift.ps1`, `build/docs/build.ps1` — re-validate CI pipeline.
- `src/ui/Shift.UI/tsconfig.json` — confirm React build produces no new TS errors/warnings.

### 5.9 Final smoke-test checklist

1. Run all 16 DB upgrade scripts on a prod-like snapshot.
2. Sign in / sign out / MFA / impersonate start+stop (covers TEC-371, TEC-767).
3. Load Workshop React screens from legacy ASPX entry points (TEC-434).
4. Submit a Form end-to-end and verify case creation and notifications (TEC-625, TEC-645, TEC-760, TEC-763).
5. Trigger a Mailgun callback and verify it lands in the Mailout Failures report (TEC-466).
6. Run every affected Report listed in Sections 1 and 5.6.
7. Navigation smoke-test one page per Admin and Portal area (covers Section 2 chrome changes).

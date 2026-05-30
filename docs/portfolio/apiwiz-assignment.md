# APIwiz Technical Writing Assessment

**Client:** APIwiz (Interview Process)
**Role:** Technical Writer Candidate
**Type:** Documentation Skills Assessment

---

## Assignment Brief

Completed a practical technical writing assessment for APIwiz covering three documentation disciplines. The full deliverables are included below.

**Task 1: Create a User Guide for Docuwiz.io**

Create a User Guide Manual for a product named Docuwiz.io. The guide should be written in Google Docs and follow a standard user guide structure, aligned with the Microsoft Writing Style Guide.

*Scope:* Sign up and explore the platform. Review each tab and module (Guides, References, Recipes, Categories, Workspace Settings). Explain how to create, manage, and publish Guides, References, and Recipes. Present the content in a user journey format, showing how a new user would navigate and use the product step by step.

*Standards:* Clear, concise, and user-focused language. Active voice and present tense. Consistent tone, terminology, and formatting. Proper headings, lists, notes, and callouts.

**Task 2: FAQ Writing for TaskFlow**

Write a comprehensive FAQ section for the TaskFlow project management tool using the following raw user complaints from the support team:

> Why can't I log in? People don't understand how to assign tasks to others. Many users asking how to change their password. Some users confused about the difference between free and paid plans. Users asking how to delete their account. People asking why they are not getting email notifications. Users want to know how many people can be added to one project. Some asking if TaskFlow works on mobile. Users asking how to export tasks to PDF. People confused about how to set task priority. Users asking how to create a subtask. Some users don't know how to archive completed tasks. Users asking how to share a project with external members. People asking how to change their profile picture. Users confused about how to use filters in the dashboard. Some users asking what happens to their data if they cancel their subscription. Users asking how to restore deleted tasks. People want to know if TaskFlow integrates with Slack or Google Calendar. Some users asking how to set task reminders. Users confused about the difference between admin and member roles.

*Requirements:* Minimum 15 FAQ entries. Natural, user-friendly tone. Clear, concise answers of 2-4 sentences each.

**Task 3: Troubleshooting Guide for TaskFlow**

Write a complete troubleshooting guide for TaskFlow based on the following raw issues from the development and support teams:

> App crashes when uploading files bigger than 10 MB. Login fails when using special characters in password. Dashboard not loading on Internet Explorer. Email notifications going to spam. Tasks not syncing between mobile and desktop. Dark mode not working on older Android phones below version 9. Export to PDF fails when task description is too long. Search bar not returning results when using filters together. Users cannot add more than 5 attachments per task. Video files are not supported in attachments. App is slow when a project has more than 500 tasks. Two-factor authentication code not being received by some users. Users getting logged out automatically after 10 minutes of inactivity. Calendar view not displaying tasks correctly when due date is not set. Google Calendar sync not working for users in certain time zones. Subtasks not appearing in the main task list view. Bulk task export taking too long for large projects. Notifications not clearing after being read on mobile app.

*Requirements:* Document all 18 issues. Include a quick reference table. Use Note, Tip, or Warning boxes. End with a Contact Support section.

**Submission Timeline:** Complete and share within 3 days.

---

## Task 1: Docuwiz.io User Guide

A complete user guide for creating and managing guides, references, and recipes in Docuwiz.io. The guide follows the Microsoft Writing Style Guide and is structured as a user journey from account creation through publishing.

### Table of Contents

1. About This Guide — Product overview, intended audience, prerequisites
2. Getting Started — Account creation (Google, GitHub, manual sign-up)
3. Onboarding Flow — Dashboard navigation, overview, quick actions
4. Creating and Managing Guides — Documentation workspace, revisions, import, table of contents
5. Creating API References — Endpoints, importing OpenAPI specs, publishing
6. Building Recipes — Combining guides and endpoints into workflows
7. Managing Categories — Organizing content for readers
8. Configuring Workspace Settings — General settings, team management, source control, portal customization
9. Troubleshooting — Common issues and resolutions
10. Glossary — Key terminology
11. Contact Support — Escalation paths

### Key Sections

**Getting Started:** Users can sign up via Google, GitHub, or email. After verification, they create a workspace and receive a subdomain (e.g., `himani.docuwiz.io`). An optional sample content toggle helps new users explore the platform.

**Dashboard:** The left navigation panel provides access to Overview, Guides, References, Recipes, Categories, and Settings. The header bar includes refresh, comments, notifications, search, and profile controls.

**Creating Guides:** A triple-pane layout supporting Markdown, with breadcrumb navigation, import from local files or connected repos, and a dynamic table of contents. Content can be published or unpublished with a single click.

**API References:** Supports creating references from scratch or importing OpenAPI/Swagger/Postman collections. Endpoints can be organized into categories with HTTP method badges.

**Workspace Settings:** Four areas — General (display name, OpenAI API key, search index), Team Members (invite with Admin/Editor/Collaborator roles), Source Control (GitHub/GitLab integration for docs-as-code), and Portal Customization (hero section, header, theme, embedded CSS/JS).

### Writing Standards Applied

- Microsoft Writing Style Guide — active voice, present tense, consistent terminology
- User journey format — step-by-step navigation for new users
- Proper headings, lists, notes, tips, and warning callouts
- Glossary of platform-specific terms

---

## Task 2: TaskFlow FAQ

20 frequently asked questions for TaskFlow with clear, user-friendly answers.

1. **Why can't I sign in to my account?**
   First, check that you're using the correct email and password. If you've forgotten your password, select Forgot password on the sign-in screen to reset it. You can also try clearing your browser's cache and cookies. If your account is locked after too many attempts, wait 15 minutes and try again, or contact support for help.

2. **How do I change my password?**
   Go to Settings (or Profile Settings in the upper right corner) and select Account or the Security tab. Enter your current password, then enter and confirm your new password and save changes. You can also reset your password from the sign-in screen if you can't sign in.

3. **How do I change my profile picture?**
   Select your avatar in the top-right corner, then go to Profile or Profile Settings. Select your current picture or the "Change Photo" option to upload a new one. Supported formats are JPG, PNG, and GIF, up to 5 MB.

4. **How do I delete my account?**
   Go to Settings, select Account or Account Settings, then select Delete account at the bottom of the page. You'll need to confirm by entering your password and reading the confirmation prompt carefully. All your data, including tasks and projects, is permanently removed after 30 days.

5. **What's the difference between admin and member roles?**
   Admins have full control over the workspace, including project settings, billing, inviting and removing members, and user management. Members can create and edit tasks, comment, and upload files within assigned projects, but they can't change core project settings or manage the team roster.

6. **How do I assign a task to someone else?**
   Open the task and select the Assignee field in the task details panel. Search for the person by name or email, then select them from the project collaborators. They'll get a notification about the new assignment. You can assign a task to one person or multiple people.

7. **How do I set a priority level on a task?**
   Open the task and select the Priority dropdown menu within the task details window. Choose from Low, Medium, High, or Urgent. Priority tasks show a colored label in your task list so they stand out at a glance.

8. **How do I create a subtask?**
   Open the parent task, scroll to the Subtasks section, and select Add subtask. Type the subtask title and press Enter. You can assign subtasks independently and set their own due dates as smaller action items dependent on the parent task.

9. **How do I archive completed tasks?**
   Select one or more completed tasks in your task list, then select Archive from the toolbar or context menu. Archived tasks move out of your active view but stay accessible under Archived in the sidebar. You can restore them at any time.

10. **How do I set a reminder for a task?**
    Open the task and select Set reminder in the task details. Pick a date and time, then choose whether to get reminded via email, push notification, or both. Reminders are sent at your chosen time, and you can set multiple reminders per task.

11. **How many people can I add to one project?**
    On the free plan, you can add up to 10 members per project. The Pro plan supports up to 50 members, and the Business plan has no limit. All plans let you add unlimited guests who can view tasks but not edit them.

12. **How do I share a project with external members?**
    Go to your project settings and select Invite. Enter the person's email address and set their role to Guest or provide a read-only link. Guests can view tasks and leave comments, but they can't create or edit tasks. Full collaboration usually requires the external user to have their own TaskFlow account.

13. **Does TaskFlow have a mobile app?**
    Yes. TaskFlow has dedicated mobile apps for iOS and Android, and both are free for all plans. Download them from the App Store or Google Play. Your tasks sync in real time between the mobile app and the desktop version.

14. **Why am I not getting email notifications?**
    Check your spam or junk folder first and add notifications@taskflow.io to your contacts. If that doesn't work, go to Settings, select Notifications, and confirm email notifications are enabled for the specific types of updates you want to receive.

15. **Does TaskFlow integrate with Slack or Google Calendar?**
    Yes. TaskFlow integrates with both. Connect Slack in Settings under Integrations to get task updates in a channel. Connect Google Calendar to sync task due dates to your calendar and set reminders there. Both integrations take under two minutes to set up.

16. **What's the difference between the free and paid plans?**
    The free plan includes up to 5 projects and 10 members per project with basic task collaboration. Paid plans unlock unlimited projects, advanced search, custom fields, task dependencies, integrations, custom reports, priority support, and more storage.

17. **What happens to my data if I cancel my subscription?**
    Your data stays accessible for 90 days after cancellation, during which your account reverts to the Free plan. You can export everything or reactivate your plan during this period. After 90 days, your projects and data are permanently deleted.

18. **How do I export tasks to PDF?**
    Go to the project or task list you want to export, then select Export from the toolbar. Choose PDF as the format and customize settings like including subtasks or comments. The PDF includes task titles, descriptions, assignees, due dates, and comments.

19. **How do I use filters on the dashboard?**
    Select the Filter icon at the top of your task list. You can filter by assignee, priority, due date, status, and labels. Combine multiple filters to narrow down exactly what you need. Select Clear all to remove all active filters.

20. **How do I restore a deleted task?**
    Go to Settings and select Trash or Recently Deleted. Deleted tasks stay in the trash for 30 days. Find the task you want to restore, select it, then select Restore. The task reappears in its original project with all data intact.

---

## Task 3: TaskFlow Troubleshooting Guide

A complete troubleshooting guide for TaskFlow covering 18 documented issues with a quick reference table, detailed resolution steps, and contact support.

### Quick Reference Table

| # | Issue | Solution Summary |
|---|-------|-----------------|
| 1 | App crashes on file upload | Reduce file size to 10 MB or less |
| 2 | Login fails with special characters | Change password to exclude special characters |
| 3 | Dashboard not loading | Use a modern browser like Chrome or Firefox |
| 4 | Email notifications go to spam | Add no-reply@taskflow.io to your safe sender list |
| 5 | Tasks not syncing | Manually refresh both mobile and desktop apps |
| 6 | Dark mode not working on older Android | Update Android OS to version 9 or higher |
| 7 | Export to PDF fails (long description) | Edit the task description to reduce its length |
| 8 | Search bar not returning results | Clear all filters before performing a new search |
| 9 | Cannot add more than 5 attachments | Limit is 5 per task. Consolidate files |
| 10 | Video files not supported | Convert to supported formats or share a link |
| 11 | App is slow (project over 500 tasks) | Archive completed tasks or split the project |
| 12 | Two-factor authentication code not received | Check network or use a different MFA method |
| 13 | Logged out automatically (10 min inactivity) | Security feature. Log back in to resume |
| 14 | Calendar view not displaying tasks | Set a due date for all calendar tasks |
| 15 | Google Calendar sync not working (time zones) | Match time zones in TaskFlow and Google Calendar |
| 16 | Subtasks not appearing in main list | Subtasks are visible within the parent task view |
| 17 | Bulk task export taking too long | Limit export size or archive older tasks |
| 18 | Notifications not clearing (mobile) | Log out and log back into the mobile app |

### Detailed Resolutions

#### 1. App crashes when uploading files over 10 MB

!!! tip "Prevent Upload Issues"
    Image files (PNG, JPEG) can often be compressed to under 10 MB without visible quality loss. PDFs can be reduced using the "Reduce file size" option in most PDF editors.

**Symptom:** The app closes or freezes when you try to attach a file larger than 10 MB to a task.

**Cause:** The current file upload limit is 10 MB. Files that exceed this size cause the upload process to fail and the app to become unresponsive.

**Resolution:**
1. Compress the file before uploading. Use a tool like the built-in compressor on your OS or an online compressor.
2. If the file can't be compressed below 10 MB, upload it to a cloud storage service (Google Drive, Dropbox) and share the link in the task description instead.

#### 2. Login fails when password contains special characters

**Symptom:** You can't sign in even though you're entering the correct password. This happens most often when the password includes characters like `<`, `>`, `&`, or `%`.

**Cause:** The sign-in form doesn't correctly handle certain special characters in the password field. This is a known bug.

**Resolution:**
1. Select Forgot password on the sign-in screen.
2. Enter your email address and follow the reset link.
3. Create a new password that avoids the characters `<`, `>`, `&`, `%`, and `#`.

!!! note
    You can still use most special characters in your password. Only the characters listed above cause the sign-in issue. A fix is in progress.

#### 3. Dashboard not loading on Internet Explorer

**Symptom:** The TaskFlow dashboard appears blank, loads partially, or shows broken layout in Internet Explorer.

**Cause:** TaskFlow doesn't support Internet Explorer. The app relies on modern browser features that IE doesn't provide.

**Resolution:** Switch to a supported browser: Google Chrome (version 90 or later), Mozilla Firefox (version 88 or later), Microsoft Edge (version 90 or later), or Safari (version 14 or later).

!!! note
    If your organization requires IE for other tools, use Microsoft Edge in IE compatibility mode as a temporary workaround. Edge offers better support for modern web features.

#### 4. Email notifications going to spam

**Symptom:** You're not receiving TaskFlow emails, or you find them in your spam or junk folder.

**Cause:** Your email provider's spam filter may block or redirect emails from `notifications@taskflow.io`.

**Resolution:**
1. Check your spam or junk folder for emails from `notifications@taskflow.io`.
2. Add `notifications@taskflow.io` to your email contacts or safe sender list.
3. If you use a corporate email, ask your IT team to whitelist the `taskflow.io` domain.
4. Go to Settings, select Notifications, and confirm email delivery is turned on.

#### 5. Tasks not syncing between mobile and desktop

**Symptom:** Updates you make on one device don't appear on another.

**Cause:** Sync issues usually happen when the app loses its connection or when one device is running an older version of the app.

**Resolution:**
- Pull down on the task list to force a manual refresh on the device that's out of date.
- If that doesn't work, sign out and sign back in on the affected device.
- Make sure both devices are running the latest version of TaskFlow.

!!! tip
    TaskFlow syncs in real time when both devices have a stable internet connection. If you're working offline, changes sync the next time you connect.

#### 6. Dark mode not working on older Android phones

**Symptom:** Dark mode doesn't activate or shows broken colors on Android devices running version 8 (Oreo) or earlier.

**Cause:** Dark mode relies on system-level theming APIs introduced in Android 9 (Pie).

**Resolution:** Update your device to Android 9 or later if a software update is available. If you can't update, TaskFlow defaults to light mode on older Android versions.

#### 7. Export to PDF fails when task description is too long

**Symptom:** The PDF export hangs, shows an error, or produces a corrupted file when tasks have very long descriptions.

**Cause:** The PDF renderer has a character limit per task description.

**Resolution:**
1. Shorten the descriptions on the affected tasks. Move lengthy content into attached documents or linked pages.
2. If you can't shorten the descriptions, export in CSV format instead.

!!! warning
    Repeatedly attempting PDF export with long descriptions can temporarily slow down the export service for your account. Wait a few minutes between attempts.

#### 8. Search bar returns no results when using filters

**Symptom:** Typing a search term while filters are active returns no results, even though matching tasks exist.

**Cause:** The search and filter system applies both criteria at the same time. If your search term doesn't match any of the filtered tasks, no results appear.

**Resolution:**
- Clear all active filters by selecting Clear all in the filter bar.
- Enter your search term and confirm results appear.
- Reapply the filters you need, one at a time, checking results after each.

#### 9. Can't add more than 5 attachments per task

**Symptom:** The "Add attachment" button is disabled after you've uploaded 5 files to a task.

**Cause:** The current attachment limit is 5 files per task on the free and Pro plans.

**Resolution:**
- Combine multiple files into a single ZIP archive and upload that.
- Upload files to cloud storage (Google Drive, Dropbox) and paste the sharing link in the task description.
- Upgrade to the Business plan, which supports up to 25 attachments per task.

#### 10. Video files are not supported in attachments

**Symptom:** Trying to attach a video file (MP4, MOV, AVI) shows an "Unsupported file type" error.

**Cause:** TaskFlow's attachment system supports documents, images, and spreadsheets, but not video files.

**Resolution:**
- Upload the video to a hosting platform (YouTube, Vimeo, or Google Drive) and paste the link in the task description or comments.
- If the video is a screen recording, try converting it to an animated GIF (under 10 MB) for quick visual reference.

#### 11. App is slow when a project has more than 500 tasks

**Symptom:** Loading, scrolling, and switching views takes noticeably longer in projects with 500 or more tasks.

**Cause:** The task list renders all tasks at once, which increases load time as the project grows.

**Resolution:**
1. Archive completed tasks to reduce the active task count.
2. Use filters to show only the tasks you're working on.
3. If the project has well over 1,000 tasks, consider splitting it into multiple smaller projects.

!!! tip
    The Board and Calendar views load faster than the List view for large projects because they show fewer tasks on screen at once.

#### 12. Two-factor authentication code not received

**Symptom:** You signed up for two-factor authentication (2FA) but the verification code doesn't arrive by email or text.

**Cause:** Delivery delays can happen due to email filtering, carrier issues, or rate limiting on repeated code requests.

**Resolution:**
1. Wait 60 seconds, then request a new code.
2. Check your spam or junk folder for the email.
3. If you set up backup codes when you enabled 2FA, use one of those to sign in, then update your 2FA settings.
4. Switch to an authenticator app (Google Authenticator, Authy) instead of email or SMS.

!!! warning
    If you've lost access to your 2FA method and don't have backup codes, contact support to verify your identity and regain access.

#### 13. Users getting logged out automatically after 10 minutes

**Symptom:** You're signed out of TaskFlow after about 10 minutes of inactivity.

**Cause:** The default session timeout is 10 minutes of inactivity. This is a security feature designed to protect accounts on shared or public devices.

**Resolution:**
1. Go to Settings and select Account.
2. Find Session timeout and increase the duration (options range from 10 minutes to 8 hours).
3. Save your changes.

!!! note
    Your organization admin may enforce a maximum timeout setting. If you can't change it, contact your admin.

#### 14. Calendar view not displaying tasks without due dates

**Symptom:** Tasks that don't have a due date assigned don't appear on the calendar.

**Cause:** The calendar view requires a due date to place a task on a specific day.

**Resolution:**
1. Assign due dates to all tasks you want to see on the calendar. You can do this in bulk by selecting multiple tasks and choosing Set due date.
2. Switch to the List or Board view to see all tasks, including those without due dates.

#### 15. Google Calendar sync not working in certain time zones

**Symptom:** Task due dates and reminders appear at the wrong time in Google Calendar.

**Cause:** This happens when the time zone in TaskFlow doesn't match the time zone in Google Calendar.

**Resolution:**
1. In TaskFlow, go to Settings and select Account. Check your current time zone setting.
2. In Google Calendar, open Settings and check your time zone there.
3. Make sure both are set to the same time zone.
4. Disconnect and reconnect the Google Calendar integration to force a fresh sync.

#### 16. Subtasks not appearing in the main task list view

**Symptom:** You created subtasks under a parent task, but they don't show up in the main list view.

**Cause:** By default, the task list view hides subtasks to keep the view clean.

**Resolution:**
1. In the task list view, select the View options icon (the eye symbol) at the top of the list.
2. Toggle on Show subtasks.
3. Subtasks now appear indented under their parent task in the list.

#### 17. Bulk task export takes too long for large projects

**Symptom:** Exporting a project with hundreds of tasks takes several minutes, or the export times out.

**Cause:** Large exports need to process and package a lot of data. PDF exports are slower than CSV.

**Resolution:**
1. If you need data quickly, export in CSV format instead of PDF.
2. Filter the task list to a smaller set before exporting.
3. If the export times out, wait a few minutes and try again.

!!! tip
    Schedule your exports for the beginning of the workday (before 9 AM) or after hours (after 6 PM) when server load is lower.

#### 18. Notifications not clearing after being read on mobile

**Symptom:** You read or dismiss notifications on your desktop, but they still appear as unread on the mobile app.

**Cause:** The mobile app caches notification state and may not have synced the latest read status from the server.

**Resolution:**
1. Pull down on the notification list in the mobile app to force a refresh.
2. If notifications still show as unread, close the app completely and reopen it.
3. Make sure you're running the latest version of the TaskFlow mobile app.

!!! note
    If the issue persists after updating and refreshing, contact support with your device model and OS version so we can investigate.

### Contact Support

If none of the solutions above resolve your issue, contact TaskFlow Support:

- **Email:** support@taskflow.io
- **Response time:** Within 24 hours on business days
- **What to include:** A description of the problem, the steps you've already tried, your browser or device info, and screenshots if possible

---

## Summary

This assessment demonstrates proficiency in three core technical writing skills:

| Skill | Deliverable |
|-------|-------------|
| User Guide Creation | Complete Docuwiz.io user guide — 6 chapters covering account setup, navigation, content creation, workspace configuration, troubleshooting, and glossary |
| FAQ Writing | 20 FAQ entries addressing real user pain points with clear, 2-4 sentence answers in a natural tone |
| Troubleshooting Guide | 18 documented issues with quick reference table, detailed resolution steps, callouts, and escalation path |

### Tools & Standards

Microsoft Writing Style Guide, Google Docs, User Journey Mapping, Information Architecture, FAQ Design, Troubleshooting Methodology, Markdown

### Download

[Download Full Docuwiz User Guide (PDF)](../assets/docuwiz-user-guide.pdf) — View the complete user guide in the [User Guides](user-guides.md) section.

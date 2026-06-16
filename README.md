# JIRA Interview Questions & Answers

> A curated list of JIRA interview questions covering Fundamentals, Issues & Issue Management, Workflows, Agile Boards, Scrum & Sprint Management, Epics/Stories/Backlog, JQL, Dashboards & Reporting, Permissions & Security, User & Project Administration, Automation, Integrations, APIs & Development, Advanced Administration, Real-World Scenarios, and Senior/Product-Company questions — each with a clear explanation and Java/Python code or configuration example where applicable.

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions |
| --- | --------- |
|     | **JIRA Fundamentals** |
| 1 | [What is JIRA and why is it used?](#what-is-jira-and-why-is-it-used) |
| 2 | [What are the different versions/editions of JIRA?](#what-are-the-different-versionseditions-of-jira) |
| 3 | [What is the difference between Jira Cloud and Jira Data Center?](#what-is-the-difference-between-jira-cloud-and-jira-data-center) |
| 4 | [What are the main components of JIRA?](#what-are-the-main-components-of-jira) |
| 5 | [What are issue types in JIRA?](#what-are-issue-types-in-jira) |
| 6 | [What is a JIRA project?](#what-is-a-jira-project) |
| 7 | [What is the difference between company-managed and team-managed projects?](#what-is-the-difference-between-company-managed-and-team-managed-projects) |
| 8 | [What is an issue (work item) in JIRA?](#what-is-an-issue-work-item-in-jira) |
| 9 | [What are sub-tasks in JIRA?](#what-are-sub-tasks-in-jira) |
| 10 | [How does JIRA support Agile methodologies?](#how-does-jira-support-agile-methodologies) |
| 11 | [What are the different deployment options available for JIRA?](#what-are-the-different-deployment-options-available-for-jira) |
| 12 | [What are JIRA schemes?](#what-are-jira-schemes) |
| 13 | [What are project categories in JIRA?](#what-are-project-categories-in-jira) |
| 14 | [What are project templates in JIRA?](#what-are-project-templates-in-jira) |
| 15 | [How does JIRA help software development teams?](#how-does-jira-help-software-development-teams) |
|     | **JIRA Issues & Issue Management** |
| 16 | [What are the standard issue types in JIRA?](#what-are-the-standard-issue-types-in-jira) |
| 17 | [How do you create a custom issue type?](#how-do-you-create-a-custom-issue-type) |
| 18 | [What is the difference between Epic, Story, Task and Bug?](#what-is-the-difference-between-epic-story-task-and-bug) |
| 19 | [What are issue links in JIRA?](#what-are-issue-links-in-jira) |
| 20 | [What are issue security levels?](#what-are-issue-security-levels) |
| 21 | [How can issues be cloned?](#how-can-issues-be-cloned) |
| 22 | [What are issue collectors?](#what-are-issue-collectors) |
| 23 | [How do you bulk edit issues?](#how-do-you-bulk-edit-issues) |
| 24 | [How do you move issues between projects?](#how-do-you-move-issues-between-projects) |
| 25 | [What is issue hierarchy in JIRA?](#what-is-issue-hierarchy-in-jira) |
| 26 | [What are parent-child relationships in JIRA?](#what-are-parent-child-relationships-in-jira) |
| 27 | [How can issue relationships be tracked?](#how-can-issue-relationships-be-tracked) |
| 28 | [What is an issue navigator?](#what-is-an-issue-navigator) |
| 29 | [How do you archive issues?](#how-do-you-archive-issues) |
| 30 | [What are issue properties?](#what-are-issue-properties) |
|     | **Workflows** |
| 31 | [What is a workflow in JIRA?](#what-is-a-workflow-in-jira) |
| 32 | [What are workflow statuses?](#what-are-workflow-statuses) |
| 33 | [What are workflow transitions?](#what-are-workflow-transitions) |
| 34 | [What is a workflow scheme?](#what-is-a-workflow-scheme) |
| 35 | [What is the difference between status and resolution?](#what-is-the-difference-between-status-and-resolution) |
| 36 | [How do you create a custom workflow?](#how-do-you-create-a-custom-workflow) |
| 37 | [What are workflow conditions?](#what-are-workflow-conditions) |
| 38 | [What are workflow validators?](#what-are-workflow-validators) |
| 39 | [What are workflow post-functions?](#what-are-workflow-post-functions) |
| 40 | [What are transition screens?](#what-are-transition-screens) |
| 41 | [How do workflow triggers work?](#how-do-workflow-triggers-work) |
| 42 | [How can workflows be shared across projects?](#how-can-workflows-be-shared-across-projects) |
| 43 | [What are inactive workflows?](#what-are-inactive-workflows) |
| 44 | [How do you publish workflow changes?](#how-do-you-publish-workflow-changes) |
| 45 | [What are common workflow design best practices?](#what-are-common-workflow-design-best-practices) |
| 46 | [How would you design a workflow for defect management?](#how-would-you-design-a-workflow-for-defect-management) |
| 47 | [How would you design a workflow for change requests?](#how-would-you-design-a-workflow-for-change-requests) |
| 48 | [What challenges have you faced while customizing workflows?](#what-challenges-have-you-faced-while-customizing-workflows) |
| 49 | [How do you handle workflow migrations?](#how-do-you-handle-workflow-migrations) |
| 50 | [How do workflow permissions affect transitions?](#how-do-workflow-permissions-affect-transitions) |
|     | **Agile Boards** |
| 51 | [What is a Scrum board?](#what-is-a-scrum-board) |
| 52 | [What is a Kanban board?](#what-is-a-kanban-board) |
| 53 | [What is the difference between Scrum and Kanban boards?](#what-is-the-difference-between-scrum-and-kanban-boards) |
| 54 | [How do you create a board in JIRA?](#how-do-you-create-a-board-in-jira) |
| 55 | [What are board filters?](#what-are-board-filters) |
| 56 | [How do swimlanes work?](#how-do-swimlanes-work) |
| 57 | [What are quick filters?](#what-are-quick-filters) |
| 58 | [What are card colors?](#what-are-card-colors) |
| 59 | [How do you configure board columns?](#how-do-you-configure-board-columns) |
| 60 | [What is WIP (Work-In-Progress) limit?](#what-is-wip-work-in-progress-limit) |
| 61 | [How do Kanban backlogs work?](#how-do-kanban-backlogs-work) |
| 62 | [How can you customize board views?](#how-can-you-customize-board-views) |
| 63 | [What are board permissions?](#what-are-board-permissions) |
| 64 | [How do boards support multiple projects?](#how-do-boards-support-multiple-projects) |
| 65 | [What are common board configuration mistakes?](#what-are-common-board-configuration-mistakes) |
|     | **Scrum & Sprint Management** |
| 66 | [What is a sprint?](#what-is-a-sprint) |
| 67 | [How do you create a sprint in JIRA?](#how-do-you-create-a-sprint-in-jira) |
| 68 | [What is sprint planning?](#what-is-sprint-planning) |
| 69 | [How do you start and complete a sprint?](#how-do-you-start-and-complete-a-sprint) |
| 70 | [What happens when incomplete issues remain in a sprint?](#what-happens-when-incomplete-issues-remain-in-a-sprint) |
| 71 | [What is sprint velocity?](#what-is-sprint-velocity) |
| 72 | [How is velocity calculated?](#how-is-velocity-calculated) |
| 73 | [What is a sprint goal?](#what-is-a-sprint-goal) |
| 74 | [How do sprint reports help teams?](#how-do-sprint-reports-help-teams) |
| 75 | [What is a burnup chart?](#what-is-a-burnup-chart) |
| 76 | [What is a burndown chart?](#what-is-a-burndown-chart) |
| 77 | [What are sprint permissions?](#what-are-sprint-permissions) |
| 78 | [How can sprint scope changes be tracked?](#how-can-sprint-scope-changes-be-tracked) |
| 79 | [How do you manage parallel sprints?](#how-do-you-manage-parallel-sprints) |
| 80 | [How do you troubleshoot sprint reporting issues?](#how-do-you-troubleshoot-sprint-reporting-issues) |
|     | **Epics, Stories & Backlog Management** |
| 81 | [What is an Epic?](#what-is-an-epic) |
| 82 | [How do Epics help Agile teams?](#how-do-epics-help-agile-teams) |
| 83 | [How do Stories relate to Epics?](#how-do-stories-relate-to-epics) |
| 84 | [What is backlog grooming (backlog refinement)?](#what-is-backlog-grooming-backlog-refinement) |
| 85 | [How do you prioritize backlog items?](#how-do-you-prioritize-backlog-items) |
| 86 | [What is story point estimation?](#what-is-story-point-estimation) |
| 87 | [What estimation methods can be used in JIRA?](#what-estimation-methods-can-be-used-in-jira) |
| 88 | [How do you track Epic progress?](#how-do-you-track-epic-progress) |
| 89 | [What are roadmap views?](#what-are-roadmap-views) |
| 90 | [How do advanced roadmaps work?](#how-do-advanced-roadmaps-work) |
| 91 | [How do dependencies affect backlog planning?](#how-do-dependencies-affect-backlog-planning) |
| 92 | [How do you manage large backlogs?](#how-do-you-manage-large-backlogs) |
| 93 | [What is WSJF prioritization?](#what-is-wsjf-prioritization) |
| 94 | [How do you handle backlog refinement sessions?](#how-do-you-handle-backlog-refinement-sessions) |
| 95 | [How do you visualize release planning in JIRA?](#how-do-you-visualize-release-planning-in-jira) |
|     | **JQL (JIRA Query Language)** |
| 96 | [What is JQL?](#what-is-jql) |
| 97 | [Why is JQL important?](#why-is-jql-important) |
| 98 | [What are JQL fields?](#what-are-jql-fields) |
| 99 | [What are JQL operators?](#what-are-jql-operators) |
| 100 | [What is the difference between = and IN operators?](#what-is-the-difference-between--and-in-operators) |
| 101 | [How do AND and OR operators work?](#how-do-and-and-or-operators-work) |
| 102 | [What are JQL functions?](#what-are-jql-functions) |
| 103 | [How does currentUser() work?](#how-does-currentuser-work) |
| 104 | [How does membersOf() work?](#how-does-membersof-work) |
| 105 | [How do you find issues assigned to you?](#how-do-you-find-issues-assigned-to-you) |
| 106 | [How do you find overdue issues?](#how-do-you-find-overdue-issues) |
| 107 | [How do you find unresolved bugs?](#how-do-you-find-unresolved-bugs) |
| 108 | [How do you search issues across multiple projects?](#how-do-you-search-issues-across-multiple-projects) |
| 109 | [How do you create saved filters?](#how-do-you-create-saved-filters) |
| 110 | [How do filter subscriptions work?](#how-do-filter-subscriptions-work) |
| 111 | [How do you optimize complex JQL queries?](#how-do-you-optimize-complex-jql-queries) |
| 112 | [How do you search for issues updated in the last 7 days?](#how-do-you-search-for-issues-updated-in-the-last-7-days) |
| 113 | [How do you identify blocked issues using JQL?](#how-do-you-identify-blocked-issues-using-jql) |
| 114 | [What are common JQL interview scenarios?](#what-are-common-jql-interview-scenarios) |
| 115 | [How would you write JQL for sprint reporting?](#how-would-you-write-jql-for-sprint-reporting) |
|     | **Dashboards & Reporting** |
| 116 | [What are JIRA dashboards?](#what-are-jira-dashboards) |
| 117 | [What gadgets are available in dashboards?](#what-gadgets-are-available-in-dashboards) |
| 118 | [How do you create a dashboard?](#how-do-you-create-a-dashboard) |
| 119 | [What are shared dashboards?](#what-are-shared-dashboards) |
| 120 | [What is a Filter Results gadget?](#what-is-a-filter-results-gadget) |
| 121 | [What is a Pie Chart gadget?](#what-is-a-pie-chart-gadget) |
| 122 | [What is a Two-Dimensional Filter Statistics gadget?](#what-is-a-two-dimensional-filter-statistics-gadget) |
| 123 | [What is a Created vs Resolved chart?](#what-is-a-created-vs-resolved-chart) |
| 124 | [What is an Average Age chart?](#what-is-an-average-age-chart) |
| 125 | [What reports are available in Scrum projects?](#what-reports-are-available-in-scrum-projects) |
| 126 | [What reports are available in Kanban projects?](#what-reports-are-available-in-kanban-projects) |
| 127 | [How do cumulative flow diagrams work?](#how-do-cumulative-flow-diagrams-work) |
| 128 | [What is a Control Chart?](#what-is-a-control-chart) |
| 129 | [How do you create executive dashboards?](#how-do-you-create-executive-dashboards) |
| 130 | [What are common dashboard best practices?](#what-are-common-dashboard-best-practices) |
|     | **Permissions & Security** |
| 131 | [What are permission schemes?](#what-are-permission-schemes) |
| 132 | [What are project roles?](#what-are-project-roles) |
| 133 | [What is the difference between groups and roles?](#what-is-the-difference-between-groups-and-roles) |
| 134 | [What are global permissions?](#what-are-global-permissions) |
| 135 | [What are project permissions?](#what-are-project-permissions) |
| 136 | [What is issue-level security?](#what-is-issue-level-security) |
| 137 | [How do permission schemes work?](#how-do-permission-schemes-work) |
| 138 | [How can users be restricted from viewing issues?](#how-can-users-be-restricted-from-viewing-issues) |
| 139 | [What are security levels?](#what-are-security-levels) |
| 140 | [How do you audit permissions?](#how-do-you-audit-permissions) |
| 141 | [How do permission conflicts occur?](#how-do-permission-conflicts-occur) |
| 142 | [What is anonymous access?](#what-is-anonymous-access) |
| 143 | [How do you secure sensitive projects?](#how-do-you-secure-sensitive-projects) |
| 144 | [What are common security challenges in JIRA?](#what-are-common-security-challenges-in-jira) |
| 145 | [How do you troubleshoot permission issues?](#how-do-you-troubleshoot-permission-issues) |
|     | **User & Project Administration** |
| 146 | [How do you create a new project?](#how-do-you-create-a-new-project) |
| 147 | [How do you manage project administrators?](#how-do-you-manage-project-administrators) |
| 148 | [How do you add users to JIRA?](#how-do-you-add-users-to-jira) |
| 149 | [How do groups work in JIRA?](#how-do-groups-work-in-jira) |
| 150 | [How do project roles work?](#how-do-project-roles-work) |
| 151 | [How do notification schemes work?](#how-do-notification-schemes-work) |
| 152 | [What are field configurations?](#what-are-field-configurations) |
| 153 | [What are screen schemes?](#what-are-screen-schemes) |
| 154 | [What are issue type schemes?](#what-are-issue-type-schemes) |
| 155 | [What are workflow schemes?](#what-are-workflow-schemes) |
| 156 | [How do you manage project templates?](#how-do-you-manage-project-templates) |
| 157 | [What is project archiving?](#what-is-project-archiving) |
| 158 | [How do you manage inactive users?](#how-do-you-manage-inactive-users) |
| 159 | [How do you handle project migrations?](#how-do-you-handle-project-migrations) |
| 160 | [What are common administrative responsibilities?](#what-are-common-administrative-responsibilities) |
|     | **Automation** |
| 161 | [What is JIRA Automation?](#what-is-jira-automation) |
| 162 | [What are automation rules?](#what-are-automation-rules) |
| 163 | [What are triggers in automation?](#what-are-triggers-in-automation) |
| 164 | [What are conditions in automation?](#what-are-conditions-in-automation) |
| 165 | [What are branches in automation?](#what-are-branches-in-automation) |
| 166 | [What actions can automation perform?](#what-actions-can-automation-perform) |
| 167 | [How do you automatically assign issues?](#how-do-you-automatically-assign-issues) |
| 168 | [How do you automate issue transitions?](#how-do-you-automate-issue-transitions) |
| 169 | [How do you automate notifications?](#how-do-you-automate-notifications) |
| 170 | [How do smart values work?](#how-do-smart-values-work) |
| 171 | [How do webhooks integrate with automation?](#how-do-webhooks-integrate-with-automation) |
| 172 | [How do you debug automation rules?](#how-do-you-debug-automation-rules) |
| 173 | [What are automation best practices?](#what-are-automation-best-practices) |
| 174 | [How do you prevent automation loops?](#how-do-you-prevent-automation-loops) |
| 175 | [How would you automate sprint-related activities?](#how-would-you-automate-sprint-related-activities) |
|     | **Integrations** |
| 176 | [How does JIRA integrate with Git?](#how-does-jira-integrate-with-git) |
| 177 | [How does JIRA integrate with GitHub?](#how-does-jira-integrate-with-github) |
| 178 | [How does JIRA integrate with Bitbucket?](#how-does-jira-integrate-with-bitbucket) |
| 179 | [How does JIRA integrate with GitLab?](#how-does-jira-integrate-with-gitlab) |
| 180 | [How does JIRA integrate with Jenkins?](#how-does-jira-integrate-with-jenkins) |
| 181 | [How does JIRA integrate with CI/CD pipelines?](#how-does-jira-integrate-with-cicd-pipelines) |
| 182 | [What is Smart Commits?](#what-is-smart-commits) |
| 183 | [How does JIRA integrate with Confluence?](#how-does-jira-integrate-with-confluence) |
| 184 | [How does JIRA integrate with Slack?](#how-does-jira-integrate-with-slack) |
| 185 | [How does JIRA integrate with Microsoft Teams?](#how-does-jira-integrate-with-microsoft-teams) |
| 186 | [What are webhooks in JIRA?](#what-are-webhooks-in-jira) |
| 187 | [How do REST APIs work in JIRA?](#how-do-rest-apis-work-in-jira) |
| 188 | [How do you authenticate Jira APIs?](#how-do-you-authenticate-jira-apis) |
| 189 | [What are common JIRA integration use cases?](#what-are-common-jira-integration-use-cases) |
| 190 | [How do you troubleshoot integration failures?](#how-do-you-troubleshoot-integration-failures) |
|     | **JIRA APIs & Development** |
| 191 | [What is the Jira REST API?](#what-is-the-jira-rest-api) |
| 192 | [How do you create issues using APIs?](#how-do-you-create-issues-using-apis) |
| 193 | [How do you update issues using APIs?](#how-do-you-update-issues-using-apis) |
| 194 | [How do you search issues using APIs?](#how-do-you-search-issues-using-apis) |
| 195 | [How do you transition issues using APIs?](#how-do-you-transition-issues-using-apis) |
| 196 | [How do you manage attachments through APIs?](#how-do-you-manage-attachments-through-apis) |
| 197 | [How do webhooks differ from APIs?](#how-do-webhooks-differ-from-apis) |
| 198 | [How do you secure API access?](#how-do-you-secure-api-access) |
| 199 | [What are API rate limits?](#what-are-api-rate-limits) |
| 200 | [How do you build custom JIRA integrations?](#how-do-you-build-custom-jira-integrations) |
| 201 | [How do Forge apps differ from Connect apps?](#how-do-forge-apps-differ-from-connect-apps) |
| 202 | [What is Atlassian Forge?](#what-is-atlassian-forge) |
| 203 | [How do custom apps work in JIRA?](#how-do-custom-apps-work-in-jira) |
| 204 | [How do you debug API failures?](#how-do-you-debug-api-failures) |
| 205 | [What are API best practices?](#what-are-api-best-practices) |
|     | **Advanced JIRA Administration** |
| 206 | [What is an application link?](#what-is-an-application-link) |
| 207 | [What are shared configurations?](#what-are-shared-configurations) |
| 208 | [How do custom fields impact performance?](#how-do-custom-fields-impact-performance) |
| 209 | [What is indexing in JIRA?](#what-is-indexing-in-jira) |
| 210 | [What is re-indexing?](#what-is-re-indexing) |
| 211 | [When should a full re-index be performed?](#when-should-a-full-re-index-be-performed) |
| 212 | [What are performance bottlenecks in JIRA?](#what-are-performance-bottlenecks-in-jira) |
| 213 | [How do you optimize JIRA performance?](#how-do-you-optimize-jira-performance) |
| 214 | [What is database maintenance in JIRA?](#what-is-database-maintenance-in-jira) |
| 215 | [How do you handle large-scale JIRA instances?](#how-do-you-handle-large-scale-jira-instances) |
| 216 | [What are backup and restore strategies?](#what-are-backup-and-restore-strategies) |
| 217 | [How do you perform upgrades?](#how-do-you-perform-upgrades) |
| 218 | [What are cluster nodes in Data Center?](#what-are-cluster-nodes-in-data-center) |
| 219 | [How does high availability work in JIRA Data Center?](#how-does-high-availability-work-in-jira-data-center) |
| 220 | [What monitoring tools are used for JIRA administration?](#what-monitoring-tools-are-used-for-jira-administration) |
|     | **Real-World Scenario Based Questions** |
| 221 | [A workflow change is impacting thousands of issues. How would you handle it?](#a-workflow-change-is-impacting-thousands-of-issues-how-would-you-handle-it) |
| 222 | [Users cannot transition issues despite having access. How would you troubleshoot?](#users-cannot-transition-issues-despite-having-access-how-would-you-troubleshoot) |
| 223 | [Sprint reports are showing incorrect data. What would you investigate?](#sprint-reports-are-showing-incorrect-data-what-would-you-investigate) |
| 224 | [Dashboard gadgets are not displaying results. What could be wrong?](#dashboard-gadgets-are-not-displaying-results-what-could-be-wrong) |
| 225 | [Automation rules are failing intermittently. How would you debug them?](#automation-rules-are-failing-intermittently-how-would-you-debug-them) |
| 226 | [A project requires a custom approval workflow. How would you design it?](#a-project-requires-a-custom-approval-workflow-how-would-you-design-it) |
| 227 | [Teams want different workflows but common reporting. How would you implement it?](#teams-want-different-workflows-but-common-reporting-how-would-you-implement-it) |
| 228 | [JIRA performance has degraded after adding many custom fields. What would you do?](#jira-performance-has-degraded-after-adding-many-custom-fields-what-would-you-do) |
| 229 | [How would you migrate projects from one JIRA instance to another?](#how-would-you-migrate-projects-from-one-jira-instance-to-another) |
| 230 | [How would you handle permission audits for a regulated environment?](#how-would-you-handle-permission-audits-for-a-regulated-environment) |
| 231 | [How would you integrate JIRA with a DevOps pipeline?](#how-would-you-integrate-jira-with-a-devops-pipeline) |
| 232 | [How would you create release tracking across multiple teams?](#how-would-you-create-release-tracking-across-multiple-teams) |
| 233 | [How would you manage dependencies across projects?](#how-would-you-manage-dependencies-across-projects) |
| 234 | [How would you design JIRA for a SAFe implementation?](#how-would-you-design-jira-for-a-safe-implementation) |
| 235 | [How would you build executive-level dashboards?](#how-would-you-build-executive-level-dashboards) |
| 236 | [How would you track production incidents using JIRA?](#how-would-you-track-production-incidents-using-jira) |
| 237 | [How would you configure JIRA for ITSM processes?](#how-would-you-configure-jira-for-itsm-processes) |
| 238 | [How would you automate defect triage?](#how-would-you-automate-defect-triage) |
| 239 | [How would you manage thousands of projects efficiently?](#how-would-you-manage-thousands-of-projects-efficiently) |
| 240 | [How would you troubleshoot missing notifications?](#how-would-you-troubleshoot-missing-notifications) |
|     | **Senior Engineer / Product Company Questions** |
| 241 | [How do you use JIRA in a microservices-based organization?](#how-do-you-use-jira-in-a-microservices-based-organization) |
| 242 | [How do you track technical debt in JIRA?](#how-do-you-track-technical-debt-in-jira) |
| 243 | [How do you manage cross-team dependencies?](#how-do-you-manage-cross-team-dependencies) |
| 244 | [How do you structure epics for large programs?](#how-do-you-structure-epics-for-large-programs) |
| 245 | [How do you use Advanced Roadmaps for portfolio planning?](#how-do-you-use-advanced-roadmaps-for-portfolio-planning) |
| 246 | [How do you measure team productivity using JIRA metrics?](#how-do-you-measure-team-productivity-using-jira-metrics) |
| 247 | [What JIRA metrics should engineering managers monitor?](#what-jira-metrics-should-engineering-managers-monitor) |
| 248 | [How do you avoid misuse of story points?](#how-do-you-avoid-misuse-of-story-points) |
| 249 | [How do you establish JIRA governance across an enterprise?](#how-do-you-establish-jira-governance-across-an-enterprise) |
| 250 | [If you joined a company with a poorly configured JIRA setup, what improvements would you prioritize first?](#if-you-joined-a-company-with-a-poorly-configured-jira-setup-what-improvements-would-you-prioritize-first) |

</details>

---

## JIRA Fundamentals

1. ### What is JIRA and why is it used?

   **JIRA** is a work management platform from **Atlassian** used for tracking, planning, and releasing projects. Originally designed for software development bug tracking (its name derives from "Gojira", the Japanese name for Godzilla), its flexibility now makes it suitable for software, hardware, business, marketing, HR, and IT service projects. Teams use JIRA to:

   - **Create work items** — tasks, bugs, stories, epics — and assign them to people.
   - **Track progress** through customizable workflows and boards.
   - **Manage backlogs and sprints** using built-in agile tooling.
   - **Integrate** with version control (Git), CI/CD (Jenkins), and chat (Slack).
   - **Report** with dashboards, burndown charts, and velocity metrics.

   > **Note:** In Jira Cloud, the term **work item** is the modern name for what was historically called an **issue**. Throughout this guide, *work item* and *issue* are used interchangeably.

   **[⬆ Back to Top](#table-of-contents)**

2. ### What are the different versions/editions of JIRA?

   JIRA is offered as a family of products tailored to different teams:

   | Edition | Audience | Key Features |
   | --- | --- | --- |
   | **Jira Software** | Software development teams | Agile boards (Scrum/Kanban), sprints, story points, dev integrations |
   | **Jira Work Management** (formerly Jira Core) | Business teams (marketing, HR, finance) | Forms, list/calendar/board views, simplified interface |
   | **Jira Service Management** | ITSM & customer support | Service desk queues, SLAs, request portals, incident management |
   | **Jira Product Discovery** | Product managers | Idea prioritization, roadmaps, insights |
   | **Jira Align** | Enterprise/portfolio | Scaling agile (SAFe) across large organizations |

   In terms of **hosting**, JIRA is available as **Cloud** (hosted by Atlassian) and **Data Center** (self-managed, clustered, high availability). The older single-node **Jira Server** deployment has been deprecated and reached end of support in February 2024.

   **[⬆ Back to Top](#table-of-contents)**

3. ### What is the difference between Jira Cloud and Jira Data Center?

   | Aspect | Jira Cloud | Jira Data Center |
   | --- | --- | --- |
   | **Hosting** | SaaS, managed by Atlassian | Self-hosted (on-prem or cloud IaaS) |
   | **Upgrades** | Automatic | Manual, admin-controlled |
   | **Scaling** | Handled by Atlassian | Add cluster nodes behind a load balancer |
   | **Customization** | Some limits on plugins | Full control, OSGi plugins |
   | **Compliance** | Built-in (SOC2, ISO, GDPR) | You control infrastructure & data residency |
   | **High Availability** | Built-in | Active-active clustering |
   | **Best for** | Fast start, low ops overhead | Large enterprises, strict compliance, full control |

   **Jira Cloud** is a **SaaS** solution accessed via browser; Atlassian handles upgrades, maintenance, and scaling. **Jira Data Center** is designed for large enterprises that need full control over infrastructure or must meet specific compliance requirements. Data Center runs on a single node or in a **cluster** of multiple application nodes behind a load balancer, sharing a common database and file system — if one node fails, others take over, providing **high availability**.

   **[⬆ Back to Top](#table-of-contents)**

4. ### What are the main components of JIRA?

   | Component | Role |
   | --- | --- |
   | **Project** | Container for related work items, boards, versions, and configuration |
   | **Work item (issue)** | Unit of work — task, story, bug, epic, sub-task |
   | **Board** | Scrum or Kanban visualization of work items by status |
   | **Fields & Screens** | Collect information; screens define which fields appear on create/edit/transition |
   | **Workflow** | Statuses and transitions a work item moves through |
   | **Schemes** | Reusable configuration sets (permission, notification, workflow) applied to projects |
   | **Filters & Dashboards** | Saved JQL queries and gadgets that display project data |

   These components fit together as a hierarchy: **Schemes** configure **Projects**, which contain **Work items** that flow through **Workflows** and are visualized on **Boards** and **Dashboards**.

   **[⬆ Back to Top](#table-of-contents)**

5. ### What are issue types in JIRA?

   JIRA ships with default work item types and lets you create custom ones. In a software project you typically see:

   - **Epic** — a large body of work spanning multiple stories/tasks (e.g., "Implement user authentication").
   - **Story** — a user-focused requirement delivering business value (e.g., "As a user, I can reset my password via email").
   - **Task** — a generic work item for things that don't fit other types.
   - **Bug** — a defect or error that needs fixing.
   - **Sub-task** — a smaller piece of work belonging to a parent story/task/bug.

   The standard hierarchy is **Epic → Story/Task/Bug → Sub-task**. Service projects add types like **Incident**, **Service Request**, **Change**, and **Problem**.

   **[⬆ Back to Top](#table-of-contents)**

6. ### What is a JIRA project?

   A **project** is a collection of work items sharing a common context and configuration. Each project has:

   - A unique **key** (e.g., `PROJ`) prefixed to every issue (`PROJ-101`).
   - Its own **permission scheme**, **workflow scheme**, **issue type scheme**, and field configuration.
   - A **type** (Scrum, Kanban, Service Management).
   - A **management style** — **company-managed** (centrally administered) or **team-managed** (self-configured).

   Projects provide separation of concerns so different teams and stakeholders can work independently while administrators maintain consistency through shared schemes.

   **[⬆ Back to Top](#table-of-contents)**

7. ### What is the difference between company-managed and team-managed projects?

   | Aspect | Company-managed (classic) | Team-managed (next-gen) |
   | --- | --- | --- |
   | **Configured by** | Jira administrators | Project administrators |
   | **Schemes** | Shared across projects | Independent, not reusable |
   | **Complexity** | Advanced workflows, custom fields, global permissions | Simpler, self-contained |
   | **Best for** | Large orgs needing consistency | Small autonomous teams |
   | **Custom fields** | Global (shared) | Project-scoped |

   **Company-managed** projects support complex, reusable configurations and are recommended for larger organizations that need consistency. **Team-managed** projects let teams configure boards, issue types, workflows, and fields independently — simpler to set up but with fewer features and no scheme reuse across projects.

   **[⬆ Back to Top](#table-of-contents)**

8. ### What is an issue (work item) in JIRA?

   An **issue (work item)** is a record of work to be done. It contains metadata such as **summary, description, priority, status, assignee, reporter, due date**, and custom fields. Issues have unique keys (e.g., `PROJ-101`) and can be linked, parented, or related to other issues.

   Work items support a **parent–child relationship** (tasks/stories under epics, sub-tasks under tasks) and can be **linked** using link types like *blocks*, *clones*, *duplicates*, or *relates to*.

   ```python
   # Example: fetch a work item via the Jira Cloud REST API (Python + requests)
   import requests
   from requests.auth import HTTPBasicAuth

   BASE = "https://your-domain.atlassian.net"
   auth = HTTPBasicAuth("you@example.com", "<API_TOKEN>")

   resp = requests.get(
       f"{BASE}/rest/api/3/issue/PROJ-101",
       auth=auth,
       headers={"Accept": "application/json"},
   )
   issue = resp.json()
   print(issue["key"], "-", issue["fields"]["summary"], "-", issue["fields"]["status"]["name"])
   ```

   **[⬆ Back to Top](#table-of-contents)**

9. ### What are sub-tasks in JIRA?

   **Sub-tasks** are smaller pieces of work that break down a parent issue. Key characteristics:

   - They inherit some attributes from the parent (project, epic link) but have their **own assignee and status**.
   - They **cannot exist without a parent** and **cannot have their own sub-tasks** (the hierarchy is only one level deep below standard issues).
   - They are useful for splitting a story into granular, assignable chunks (e.g., "Write API", "Write tests", "Update docs" under a single story).

   A common interview point: sub-tasks share the parent's **workflow scheme** by issue type mapping, but their progress does **not** automatically roll up to the parent unless automation is configured.

   **[⬆ Back to Top](#table-of-contents)**

10. ### How does JIRA support Agile methodologies?

    Jira Software provides built-in support for both **Scrum** and **Kanban**:

    - **Scrum boards** — sprints, separate backlog, story points, velocity charts, burndown charts, and sprint reports.
    - **Kanban boards** — continuous flow, **WIP (Work-In-Progress) limits** per column, and cumulative flow diagrams.
    - **Flexible workflows & JQL** — teams implement their own processes, prioritize backlogs, and estimate with story points or time.
    - **Release tracking** — versions, release hub, and roadmaps.

    Teams configure boards to match their workflow, groom backlogs, and track release progress, all from a single tool that also integrates with development pipelines.

    **[⬆ Back to Top](#table-of-contents)**

11. ### What are the different deployment options available for JIRA?

    The two primary deployment models today are:

    - **Jira Cloud (SaaS)** — hosted and fully managed by Atlassian; access via browser; automatic updates.
    - **Jira Data Center (self-managed)** — runs on your infrastructure, either on a single node or in a **cluster** for high availability and scalability.

    The legacy **Jira Server** (single-node on-premises) has been **discontinued** (end of support February 2024). When choosing, weigh operational overhead (Cloud is lowest) against control and compliance needs (Data Center is highest).

    **[⬆ Back to Top](#table-of-contents)**

12. ### What are JIRA schemes?

    **Schemes** are reusable configuration objects that control aspects of a project. Applying the same scheme to multiple projects ensures consistency and reduces duplication.

    | Scheme | Controls |
    | --- | --- |
    | **Permission scheme** | Who can perform actions (Create Issue, Assign Issue, Manage Sprints) |
    | **Issue type scheme** | Which issue types are available in a project |
    | **Workflow scheme** | Maps issue types to specific workflows |
    | **Screen scheme** | Associates screens with create/edit/view operations |
    | **Field configuration scheme** | Field behaviour (required/optional, hidden), descriptions |
    | **Notification scheme** | Who receives notifications for events |
    | **Issue security scheme** | Security levels restricting who can view issues |

    **[⬆ Back to Top](#table-of-contents)**

13. ### What are project categories in JIRA?

    **Project categories** are labels used to group related projects (e.g., grouping all "Marketing" projects). They:

    - **Do not** affect permissions or behaviour.
    - Help users **locate projects** in lists and search filters.
    - Can be used in JQL: `category = "Finance"`.

    An administrator creates categories under project administration and assigns projects to them. They are primarily an organizational convenience for large instances with many projects.

    **[⬆ Back to Top](#table-of-contents)**

14. ### What are project templates in JIRA?

    **Templates** provide preconfigured workflows, issue types, and fields for specific use cases. Examples include:

    - **Scrum software development**
    - **Kanban**
    - **Project management** (business)
    - **Bug tracking**
    - **IT service management**
    - **Process control / Task tracking**

    When creating a new project, selecting a template automatically sets up a board, issue types, and a workflow optimized for that work style — saving setup time and enforcing good defaults.

    **[⬆ Back to Top](#table-of-contents)**

15. ### How does JIRA help software development teams?

    Jira helps software teams across the full delivery lifecycle:

    - **Requirements & planning** — epics, stories, backlogs, and roadmaps.
    - **Execution** — sprints, boards, and WIP limits.
    - **Development integration** — Bitbucket/GitHub/GitLab show commits, branches, and pull requests on issues; **Smart Commits** transition issues from commit messages.
    - **CI/CD** — Jenkins build and deployment status appear in the development panel.
    - **Release management** — versions, release hub, and release burndown reports.

    The result is a single source of truth where planning, code, builds, and releases are all linked to the work items that drive them.

    **[⬆ Back to Top](#table-of-contents)**


## JIRA Issues & Issue Management

16. ### What are the standard issue types in JIRA?

    The default issue types depend on the project type:

    | Project Type | Standard Issue Types |
    | --- | --- |
    | **Software (company-managed)** | Epic, Story, Task, Bug, Sub-task |
    | **Business / Work Management** | Task, Sub-task, (Bug optional) |
    | **Service Management** | Incident, Service Request, Change, Problem |

    Custom issue types can always be added and shared across projects via an **issue type scheme**. Each type can have its own icon, workflow mapping, and field configuration.

    **[⬆ Back to Top](#table-of-contents)**

17. ### How do you create a custom issue type?

    You must be a **Jira administrator**:

    1. Go to **Administration → Issues → Issue types**.
    2. Click **Add issue type**, enter a **name** and **description**.
    3. Choose whether it behaves like a **standard** type (task/story level) or a **sub-task** type.
    4. Select an **icon**.
    5. Add the new type to the relevant project's **issue type scheme** so it appears when creating issues.

    Programmatically (Cloud REST API):

    ```python
    import requests
    from requests.auth import HTTPBasicAuth

    BASE = "https://your-domain.atlassian.net"
    auth = HTTPBasicAuth("admin@example.com", "<API_TOKEN>")

    payload = {
        "name": "Spike",
        "description": "Time-boxed research task",
        "type": "standard"   # or "subtask"
    }
    resp = requests.post(
        f"{BASE}/rest/api/3/issuetype",
        json=payload, auth=auth,
        headers={"Accept": "application/json", "Content-Type": "application/json"},
    )
    print(resp.status_code, resp.json())
    ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### What is the difference between Epic, Story, Task and Bug?

    | Type | Purpose | Example |
    | --- | --- | --- |
    | **Epic** | Large body of work spanning multiple sprints | "Implement a new login system" |
    | **Story** | User-centric requirement delivering value | "As a user, I can reset my password so I can regain access" |
    | **Task** | General work item, not necessarily user-facing | "Refactor authentication module" |
    | **Bug** | A defect needing a fix | "Login page throws 500 error on invalid input" |

    The classic **story format** is: *As a [user], I want [something] so that [benefit]*. Epics group stories and tasks; once all child issues are complete, the epic is considered done.

    **[⬆ Back to Top](#table-of-contents)**

19. ### What are issue links in JIRA?

    **Issue links** express relationships between work items. Common link types:

    | Link Type | Meaning |
    | --- | --- |
    | **blocks / is blocked by** | One item blocks another's progress |
    | **clones / is cloned by** | One item is a copy of another |
    | **duplicates / is duplicated by** | Items report the same thing |
    | **relates to** | Generic association |

    Link types are configurable by administrators and are searchable in JQL:

    ```sql
    -- Issues blocked by PROJ-123
    issue in linkedIssues("PROJ-123", "is blocked by")
    ```

    **[⬆ Back to Top](#table-of-contents)**

20. ### What are issue security levels?

    **Issue security levels** restrict who can **view** an individual issue. An **issue security scheme** defines one or more levels, each listing the users, groups, or roles allowed to see issues at that level. When an issue's security level is set, only those principals can view it — regardless of their general Browse Projects permission.

    Example levels: **Internal** (project team only), **Management** (leads only), **All logged-in users**. Administrators configure security schemes and assign them to projects; the **Security Level** field then appears on issues.

    **[⬆ Back to Top](#table-of-contents)**

21. ### How can issues be cloned?

    To clone an issue: select it, click **More → Clone**. You can choose whether to copy **attachments, links, sub-tasks**, and other fields. The clone:

    - Copies the original's field values.
    - Gets a **new, independent key** (changes to the clone don't affect the original).
    - Prefixes the summary with "CLONE -" by default.

    Cloning is useful for creating similar recurring tasks or replicating a template issue. For bulk cloning across projects, combine **Clone** with a subsequent **Move** operation, or use automation.

    **[⬆ Back to Top](#table-of-contents)**

22. ### What are issue collectors?

    **Issue collectors** are embeddable web forms that let **external users** submit issues directly into Jira without a Jira account. An administrator:

    1. Goes to **Administration → System → Issue collectors** (Data Center/Server; Cloud uses alternative widgets/forms).
    2. Configures the **fields**, **default issue type**, and **target project**.
    3. Embeds the generated JavaScript snippet on a website.

    When a visitor submits the form, Jira creates an issue. They are commonly used for **feedback widgets** and **bug-report buttons** on web apps. (In Jira Cloud, native issue collectors were deprecated in favor of Jira Service Management forms and third-party widgets.)

    **[⬆ Back to Top](#table-of-contents)**

23. ### How do you bulk edit issues?

    1. Go to **Filters → Advanced issue search** and run a JQL query to select issues.
    2. From the **Tools / ⋯** menu choose **Bulk change (all X issues)**.
    3. Steps: **select issues → choose operation → configure → confirm**.

    Available bulk operations include **Edit, Transition, Delete, Move, Watch, Stop Watching**. Only users with the **Bulk Change** global permission can perform these. Bulk edits do **not** by default send notifications unless you opt in, and they can be large/slow — run them during off-peak times for big result sets.

    **[⬆ Back to Top](#table-of-contents)**

24. ### How do you move issues between projects?

    Open the issue → **More → Move**:

    1. Select the **destination project** and **issue type**.
    2. Jira guides you through mapping **statuses** (if workflows differ), **custom fields**, and resolving any required-field gaps.
    3. Confirm; the issue gets a **new key** in the destination project (the old key redirects).

    For many issues at once, use **Bulk Move** from the Issue Navigator. Watch for: status mapping (target workflow may lack a matching status), field context differences, and sprint/epic links that may be dropped.

    **[⬆ Back to Top](#table-of-contents)**

25. ### What is issue hierarchy in JIRA?

    The standard hierarchy is:

    ```
    Epic
     └── Story / Task / Bug
          └── Sub-task
    ```

    With **Advanced Roadmaps** (Premium/Enterprise/Data Center) you can add higher levels such as **Initiative** above epics, or even **Theme** above that. In **team-managed** projects you can configure custom hierarchy levels. Epics group related stories/tasks; stories/tasks are individual backlog items; sub-tasks break them down further.

    **[⬆ Back to Top](#table-of-contents)**

26. ### What are parent-child relationships in JIRA?

    A work item can be the **parent** of sub-tasks. Sub-tasks inherit attributes from the parent (project, labels context) and share the same workflow scheme mapping. Important nuance for interviews:

    - In Jira's underlying data model, an **Epic** is historically **not** a true "parent" of stories — instead the **Epic Link** field associates stories/tasks with an epic.
    - **Modern Jira Cloud** has unified this under a single **Parent** field, so epics, stories, and sub-tasks now use a consistent parent relationship.

    So depending on the Jira version, "parent" may refer to the Epic Link (older) or the unified Parent field (newer Cloud).

    **[⬆ Back to Top](#table-of-contents)**

27. ### How can issue relationships be tracked?

    Several mechanisms track relationships:

    - **Issue links** (Blocks, Relates to, etc.) shown in the **Linked Issues** panel.
    - **Epic Link / Parent** field associating issues with an epic.
    - **JQL link functions** — `linkedIssues("PROJ-123", "blocks")`.
    - **Boards** display epic color bars and parent context.
    - **Advanced Roadmaps** visualizes dependencies on a timeline via the **Dependency view**.

    ```sql
    -- Find all issues that block anything in project PROJ
    project = PROJ AND issueLinkType = "blocks"
    ```

    **[⬆ Back to Top](#table-of-contents)**

28. ### What is an issue navigator?

    The **Issue Navigator** is the search interface where users run queries and view results. It offers:

    - **Basic (form-based) search** — dropdowns for project, type, status, assignee.
    - **Advanced search (JQL)** — full query language for complex conditions.
    - **List view** — table of issues; **Detail view** — selected issue alongside the list.

    From the navigator you can **save filters**, **subscribe** to them for email digests, **export** results (CSV/Excel), and configure displayed columns. It is the entry point for most reporting and bulk operations.

    **[⬆ Back to Top](#table-of-contents)**

29. ### How do you archive issues?

    Several approaches:

    - **Status-based** — move issues to a terminal status (e.g., Closed) and use a board filter to hide them.
    - **Jira Cloud Premium/Enterprise** — use the native **Archive issues** feature: select issues via JQL, then **Bulk Change → Archive**. Archived issues are hidden from search and boards but can be **restored**.
    - **Archive the whole project** — move issues into an archived project to remove clutter.

    Archiving improves performance and reduces noise while preserving history for audit and potential restoration.

    **[⬆ Back to Top](#table-of-contents)**

30. ### What are issue properties?

    **Issue properties** are **key–value pairs** that apps and workflows use to store structured metadata on an issue. They:

    - Are **not visible** in the standard UI.
    - Are accessed via REST API: `/rest/api/3/issue/{issueIdOrKey}/properties`.
    - Let apps/scripts attach data **without** creating custom fields (which add indexing overhead).

    ```python
    import requests
    from requests.auth import HTTPBasicAuth

    BASE = "https://your-domain.atlassian.net"
    auth = HTTPBasicAuth("you@example.com", "<API_TOKEN>")

    # Set a property
    requests.put(
        f"{BASE}/rest/api/3/issue/PROJ-101/properties/riskData",
        json={"riskScore": 7, "reviewed": True},
        auth=auth,
        headers={"Content-Type": "application/json"},
    )
    ```

    **[⬆ Back to Top](#table-of-contents)**


## Workflows

31. ### What is a workflow in JIRA?

    A **workflow** defines the lifecycle of an issue — the set of **statuses** it can be in and the **transitions** that move it between them. For example: `To Do → In Progress → Done`. Workflows can be simple or highly customized with conditions, validators, and post-functions. Only **Jira administrators** can create or edit workflows.

    A workflow has four building blocks: **statuses** (states), **transitions** (paths between states), **conditions/validators** (gatekeeping), and **post-functions** (automated actions after a transition).

    **[⬆ Back to Top](#table-of-contents)**

32. ### What are workflow statuses?

    **Statuses** represent the state of an issue at a point in time (e.g., To Do, In Progress, In Review, Done). Each status:

    - Maps to one of three **status categories**: **To Do** (grey), **In Progress** (blue), **Done** (green).
    - Appears as a **board column** when columns are mapped to statuses.
    - Can have a description shown to users.

    Status categories are what reports like *Created vs Resolved* and board "Done" columns rely on, so mapping each status to the correct category is important for accurate metrics.

    **[⬆ Back to Top](#table-of-contents)**

33. ### What are workflow transitions?

    **Transitions** are **one-way links** between statuses that allow an issue to move from one status to another. A transition can have:

    - A **screen** prompting for field input (e.g., resolution, comment).
    - **Conditions** controlling who can execute it.
    - **Validators** checking inputs before completion.
    - **Post-functions** performing actions afterward.

    A special **"All" / global transition** (often shown as an unconnected loop) lets an issue move to a target status from **any** status — handy for a universal "Close" action.

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is a workflow scheme?

    A **workflow scheme** associates **issue types** with **workflows**. Within one project, different issue types can use different workflows (e.g., Bugs use a defect workflow while Stories use a simpler one), or all types can share a single workflow. Projects apply one workflow scheme.

    Changing a workflow scheme on a project with existing issues triggers a **re-index** and may require **mapping** existing issues to statuses in the new workflow.

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is the difference between status and resolution?

    | Field | Describes | Example values |
    | --- | --- | --- |
    | **Status** | Where the issue is in the workflow | To Do, In Progress, Done |
    | **Resolution** | Whether/how work is *complete* | Fixed, Won't Fix, Duplicate, (empty) |

    A crucial best practice: **set the Resolution field on transitions into a Done status, and clear it when reopening**. An issue with a "Done" status but an **empty resolution** is a common misconfiguration — it shows as done on the board but counts as **unresolved** in JQL (`resolution IS EMPTY`) and reports, causing inaccurate burndown.

    ```sql
    -- The classic "looks done but isn't resolved" bug
    statusCategory = Done AND resolution IS EMPTY
    ```

    **[⬆ Back to Top](#table-of-contents)**

36. ### How do you create a custom workflow?

    1. Navigate to **Administration → Issues → Workflows**.
    2. Click **Add workflow**; provide a name and description.
    3. Use the **graphical designer** (or text/diagram mode) to add **statuses** and **transitions**.
    4. Configure **conditions, validators, post-functions**, and **transition screens**.
    5. **Save** and **publish**.
    6. Add the workflow to a **workflow scheme** and assign that scheme to projects.

    Always build and test in a non-production project or staging instance first, since publishing a change to an active workflow forces a re-index.

    **[⬆ Back to Top](#table-of-contents)**

37. ### What are workflow conditions?

    **Conditions** control whether a transition is **available** to a user. If a condition fails, the transition button is **hidden**. Examples:

    - Only the **reporter** can execute a transition.
    - Only members of a specific **project role** (e.g., Approvers) can transition.
    - Only when a **sub-task** condition is met (e.g., all sub-tasks resolved).

    Conditions are about **visibility/availability** — they gate *who* can move the issue — as opposed to validators, which gate *what data* must be present.

    **[⬆ Back to Top](#table-of-contents)**

38. ### What are workflow validators?

    **Validators** check **field values** before a transition completes. If a validator fails, the transition stops and the user sees an error. Examples:

    - Require a **comment** when closing a bug.
    - Require **time tracking** to be entered.
    - Ensure the **assignee is not blank**.
    - Require the **Resolution** field on a Done transition.

    Validators run **after** the user submits the transition screen but **before** the status actually changes, guaranteeing data quality at lifecycle boundaries.

    **[⬆ Back to Top](#table-of-contents)**

39. ### What are workflow post-functions?

    **Post-functions** execute **after** a transition completes. Some are **system-essential** (set the new status, fire the issue-updated event, re-index, add a history entry); others are **optional** and configurable:

    - Update a field (e.g., set resolution, clear resolution on reopen).
    - Assign the issue to the **current user** or **reporter**.
    - Add an automatic **comment**.
    - Trigger a **webhook** or send a notification.

    Order matters: optional post-functions you add typically run before the essential "fire event / re-index" steps. Misordered post-functions are a common source of "field not updated" bugs.

    **[⬆ Back to Top](#table-of-contents)**

40. ### What are transition screens?

    **Transition screens** appear when a user performs a transition and **request additional information** (e.g., resolution and a comment on a "Resolve Issue" transition). They:

    - Can show **different fields** than the create/edit screens.
    - Are limited to **one screen per transition**.
    - Are commonly used to enforce capturing the resolution, root cause, or approval notes at the right moment.

    For example, a "Resolve" transition screen typically shows **Resolution** and **Comment** fields only, keeping the transition focused.

    **[⬆ Back to Top](#table-of-contents)**

41. ### How do workflow triggers work?

    **Workflow triggers** automatically transition issues when events occur in **connected dev tools** (Bitbucket, GitHub, GitLab). For example, a commit, branch creation, or pull-request merge can fire "Start Progress" or "Resolve Issue". To configure:

    1. Connect your development tools to Jira (DVCS / app).
    2. Open the workflow → select a **transition** → **Add trigger**.
    3. Specify the event (e.g., *commit created*, *pull request merged*).

    Triggers reduce manual status updates by syncing issue state with development activity automatically.

    **[⬆ Back to Top](#table-of-contents)**

42. ### How can workflows be shared across projects?

    Through **workflow schemes**:

    1. Create the workflow once.
    2. Add it to a **workflow scheme**.
    3. Associate that scheme with **multiple projects**.

    All projects using the scheme then share the same workflow. This is the central mechanism for **standardization** — change the workflow once and every project using the shared scheme inherits the change (after publishing and re-index).

    **[⬆ Back to Top](#table-of-contents)**

43. ### What are inactive workflows?

    A workflow is **inactive** if it is **not used by any workflow scheme**, or its scheme is **not associated with any project**. Key behaviors:

    - **Inactive** workflows can be edited freely.
    - **Active** workflows restrict editing — to change them, Jira creates a **draft** that you edit and then publish.

    Keeping unused workflows inactive (or deleting them) reduces clutter and confusion during administration.

    **[⬆ Back to Top](#table-of-contents)**

44. ### How do you publish workflow changes?

    When you edit an **active** workflow, Jira automatically creates a **draft**. After making changes:

    1. Click **Publish Draft**.
    2. Jira warns that affected projects will be **re-indexed**.
    3. If statuses were added/removed, Jira prompts you to **map existing issues** to new statuses.
    4. Publishing **overwrites** the original workflow.

    Always publish during off-peak hours for large instances, and optionally save a backup copy of the original workflow before publishing.

    **[⬆ Back to Top](#table-of-contents)**

45. ### What are common workflow design best practices?

    - **Keep it simple** — avoid unnecessary statuses; every status should mean something distinct.
    - **Use the three status categories** consistently (To Do / In Progress / Done) so reports work.
    - **Enforce policy** with conditions and validators rather than relying on convention.
    - **Set resolution** on transitions into Done and **clear it** on reopen.
    - **Use clear names and descriptions** that end users understand.
    - **Avoid circular/redundant transitions** unless genuinely needed.
    - **Reuse** workflows via schemes instead of duplicating.

    **[⬆ Back to Top](#table-of-contents)**

46. ### How would you design a workflow for defect management?

    A typical defect workflow:

    ```
    Open → In Progress → In Review → Resolved → Closed
                                          │
                       Reopened ◄─────────┘ (from Resolved/Closed)
    ```

    Design choices:

    - **Transitions to reopen** from Resolved/Closed back to In Progress.
    - **Validator** on "Resolve" requiring a **Resolution** and a **comment**.
    - **Post-function** to **assign to the reporter** when reopened (so they verify the fix).
    - **Condition** restricting "Close" to QA or the reporter.

    **[⬆ Back to Top](#table-of-contents)**

47. ### How would you design a workflow for change requests?

    A change-request (CR) workflow:

    ```
    Draft → Submitted → Under Review → Approved → Implemented → Closed
                                          │
                       Rejected ◄─────────┘
    ```

    Design choices:

    - **Condition**: restrict the **Approve** transition to a **Change Advisory Board (CAB)** project role.
    - **Validator** on `Submitted → Under Review` requiring change specification attachments.
    - **Rework loop**: `Rejected → Draft` so the requester can revise.
    - **Post-functions**: notify stakeholders on approval; set implementation date.

    In Jira Service Management, you can leverage built-in **approval steps** instead of building approvals manually.

    **[⬆ Back to Top](#table-of-contents)**

48. ### What challenges have you faced while customizing workflows?

    Common real-world challenges:

    - **Migrating existing issues** to new/renamed statuses without losing history.
    - **Post-function ordering** — optional functions must run before the essential "fire event" step or field updates silently fail.
    - **Conflicts with automation rules** that also transition or edit issues, causing loops.
    - **Balancing simplicity vs. team-specific needs** — too many statuses slows everyone down.
    - **Active-workflow editing constraints** — needing drafts, re-index downtime, and careful mapping.

    Troubleshooting usually means reviewing the **workflow scheme**, checking **conditions/validators**, and inspecting the **automation audit log**.

    **[⬆ Back to Top](#table-of-contents)**

49. ### How do you handle workflow migrations?

    1. **Clone** the existing workflow and make changes in a **draft** or copy.
    2. Create a **new workflow scheme** and associate it with the project.
    3. During association, Jira prompts you to **map existing issues** from old statuses to statuses in the new workflow.
    4. **Test** in a staging environment first.
    5. Perform the migration during **off-peak hours** and **re-index** afterward.
    6. Communicate the change and any status renames to affected teams.

    **[⬆ Back to Top](#table-of-contents)**

50. ### How do workflow permissions affect transitions?

    Two layers gate transitions:

    1. **Permission scheme** — the user needs the **Transition Issues** permission in the project.
    2. **Workflow conditions** — additional restrictions (e.g., only the reporter can close).

    If either layer denies the action, the transition is **hidden**. So a user might have the Transition Issues permission yet still not see a specific transition because a workflow condition restricts it to a role they aren't in. The **Permission Helper** and workflow inspection together explain why a transition is unavailable.

    **[⬆ Back to Top](#table-of-contents)**


## Agile Boards

51. ### What is a Scrum board?

    A **Scrum board** organizes work into **sprints** (fixed time boxes, usually 1–4 weeks). It shows issues from the **sprint backlog** in columns such as To Do, In Progress, and Done. Scrum boards support:

    - A **separate backlog** view for grooming and sprint planning.
    - **Story points** and **velocity** tracking.
    - **Burndown charts** and **sprint reports**.

    Only issues assigned to the **active sprint** appear on the board; the backlog stays separate, keeping the board focused on current commitments.

    **[⬆ Back to Top](#table-of-contents)**

52. ### What is a Kanban board?

    A **Kanban board** visualizes a **continuous flow** of work — no time-boxed sprints. Columns represent workflow stages (e.g., Backlog, Selected for Development, In Progress, Review, Done). Teams set **WIP limits** per column to avoid overload. Kanban is ideal for **operations, support, and maintenance** teams needing continuous delivery and flexibility. Metrics focus on **cycle time**, **lead time**, and **cumulative flow**.

    **[⬆ Back to Top](#table-of-contents)**

53. ### What is the difference between Scrum and Kanban boards?

    | Aspect | Scrum | Kanban |
    | --- | --- | --- |
    | **Planning** | Time-boxed sprints | Continuous flow |
    | **Backlog** | Separate; only sprint issues on board | Whole backlog or backlog column |
    | **WIP limits** | Sprint commitment | Per-column WIP limits emphasized |
    | **Cadence** | Fixed start/end dates | Pull as capacity frees up |
    | **Metrics** | Burndown, velocity | Cumulative flow, control chart, cycle time |
    | **Best for** | Feature delivery in iterations | Support/ops, unpredictable inflow |

    **[⬆ Back to Top](#table-of-contents)**

54. ### How do you create a board in JIRA?

    From a project: **Boards → View all boards → Create board**. Then:

    1. Choose **Scrum** or **Kanban**.
    2. Base it on an **existing project** or a **saved filter**.
    3. Provide a **name** and optionally associate it with a project.

    Boards based on a **filter** can span **multiple projects** — useful for cross-team coordination. The board's filter (a saved JQL) determines which issues appear.

    **[⬆ Back to Top](#table-of-contents)**

55. ### What are board filters?

    A board's **filter** is a saved **JQL query** that determines which issues the board displays. Example:

    ```sql
    project = WEB AND type != Sub-task ORDER BY Rank ASC
    ```

    Board administrators can edit the filter to include multiple projects or custom criteria. The filter **must be shared** with users (via filter sharing settings) so they can see the board. A too-broad filter (returning tens of thousands of issues) is a frequent cause of slow boards.

    **[⬆ Back to Top](#table-of-contents)**

56. ### How do swimlanes work?

    **Swimlanes** horizontally group issues on a board. Jira supports several methods:

    | Swimlane Type | Groups by |
    | --- | --- |
    | **Stories** (default) | Sub-tasks under their parent story |
    | **Epics** | Issues by epic |
    | **Assignees** | Issues by assignee |
    | **Queries (JQL)** | Custom lanes, e.g., `assignee in membersOf('bugfix')` |
    | **No Swimlanes** | Single combined lane |

    With JQL swimlanes, Jira provides default **Expedite** and **Everything else** lanes. Swimlanes help highlight priority, ownership, or blocked work.

    **[⬆ Back to Top](#table-of-contents)**

57. ### What are quick filters?

    **Quick filters** add extra JQL on top of the board filter to refine the view with a single click. Jira ships with defaults like **Only My Issues** and **Recently Updated**. Administrators can add custom ones:

    ```sql
    -- Quick filter: "Bugs only"
    type = Bug

    -- Quick filter: "QA work"
    assignee in membersOf("qa-team")
    ```

    Multiple quick filters can be combined; clicking each toggles its condition into the active view.

    **[⬆ Back to Top](#table-of-contents)**

58. ### What are card colors?

    **Card colors** help identify issue categories at a glance on a board. Cards can be colored by:

    - **Priority** (e.g., Highest = red)
    - **Issue type** (e.g., Bugs red, Tasks blue)
    - **Assignee**
    - **Custom JQL** (e.g., color blocked issues)

    Configure via **Board settings → Card colors**. Color coding improves scanability, especially on busy boards where teams need to spot high-priority or blocked work quickly.

    **[⬆ Back to Top](#table-of-contents)**

59. ### How do you configure board columns?

    **Columns** map workflow **statuses** to board lanes:

    - Scrum boards typically have **To Do, In Progress, Done**.
    - Kanban boards often add **Backlog, Selected for Development, In Progress, Done**.

    Administrators can **add, rename, reorder, or delete** columns and map **multiple statuses to one column**. Sub-columns can show different statuses within the same category. Mapping is done in **Board settings → Columns**. Unmapped statuses won't show issues on the board — a common "missing issues" cause.

    **[⬆ Back to Top](#table-of-contents)**

60. ### What is WIP (Work-In-Progress) limit?

    A **WIP limit** restricts the number of issues allowed in a Kanban column. Benefits:

    - Prevents **multitasking** and context switching.
    - Exposes **bottlenecks** — when a column hits its limit, it highlights (often red), signaling the team to finish before pulling more.

    For example, capping **In Progress** at 3 forces the team to complete work before starting new items, improving flow and reducing cycle time. WIP limits embody the Kanban principle "stop starting, start finishing."

    **[⬆ Back to Top](#table-of-contents)**

61. ### How do Kanban backlogs work?

    A **Kanban backlog** (available for company-managed projects) separates backlog items from active board work. It adds a dedicated **Backlog** section where issues can be **prioritized** without cluttering the board. When ready, issues are dragged into **Selected for Development**, which then appears on the board. This gives Kanban teams a planning space similar to Scrum's backlog while preserving continuous flow.

    **[⬆ Back to Top](#table-of-contents)**

62. ### How can you customize board views?

    Board administrators can configure:

    - **Columns** and status mapping.
    - **Card layout** — which fields appear on cards.
    - **Quick filters** and **swimlanes**.
    - **Estimation & tracking** — story points or time.
    - **Working days** (for burndown accuracy).

    Individual users can also personalize their view: **compact vs full** cards, and **show/hide resolved issues**. Customization tailors the board to the team's process without changing underlying data.

    **[⬆ Back to Top](#table-of-contents)**

63. ### What are board permissions?

    - **Board administrators** are users who created the board or were granted admin rights; they can change the filter, columns, quick filters, and swimlanes.
    - **Viewing** a board requires permission to see the issues returned by its filter (Browse Projects on those projects) **and** access to the shared filter.
    - For Scrum, **starting/completing sprints** also requires the **Manage Sprints** project permission.

    A board can be administered by users who don't own the underlying filter, so filter ownership and board admin rights are managed separately.

    **[⬆ Back to Top](#table-of-contents)**

64. ### How do boards support multiple projects?

    By basing a board on a **filter spanning multiple projects**:

    ```sql
    project in (PROJ1, PROJ2, PROJ3) ORDER BY Rank ASC
    ```

    Issues from all included projects then appear on one board — ideal for cross-team or program-level coordination. The catch: the filter must be **shared with all relevant users**, and the projects should use **compatible status categories** so columns map cleanly.

    **[⬆ Back to Top](#table-of-contents)**

65. ### What are common board configuration mistakes?

    - **Overly broad filter** returning too many issues, slowing the board.
    - **Incorrect status-to-column mapping** so issues "vanish" (unmapped statuses).
    - **Forgetting to share** the board's filter, so teammates can't see the board.
    - **Stale WIP limits** that no longer match team capacity.
    - **Swimlanes/quick filters** that unintentionally hide issues.
    - **Mismatched estimation field** (story points vs time) breaking reports.

    **[⬆ Back to Top](#table-of-contents)**


## Scrum & Sprint Management

66. ### What is a sprint?

    A **sprint** is a **time-boxed period** (commonly 1–4 weeks, often 2) during which a team commits to completing a set of backlog items. In Jira, sprints are managed via **Scrum boards** and have a **start date, end date, and goal**. Once started, the sprint backlog should be **fixed** (scope is protected), and the team works to deliver the committed items by the end date.

    **[⬆ Back to Top](#table-of-contents)**

67. ### How do you create a sprint in JIRA?

    1. Navigate to the **Backlog** of a Scrum-board project.
    2. Click **Create Sprint** above the backlog.
    3. Provide a **name**, **goal**, and **start/end dates** (set when starting).
    4. **Drag backlog items** into the sprint.

    You can create **multiple future sprints** to plan ahead. The sprint stays in a "future" state until you explicitly **Start** it.

    **[⬆ Back to Top](#table-of-contents)**

68. ### What is sprint planning?

    **Sprint planning** is the meeting where the team selects backlog items to commit to and defines the **sprint goal**. Typical activities:

    1. Review the backlog and priorities.
    2. **Clarify requirements** and acceptance criteria.
    3. **Estimate** remaining items if not already estimated.
    4. Choose what fits based on **capacity and velocity**.
    5. Optionally break stories into **tasks/sub-tasks** and confirm the **definition of done**.

    The output is a committed sprint backlog and a clear, shared goal.

    **[⬆ Back to Top](#table-of-contents)**

69. ### How do you start and complete a sprint?

    - **Start**: From the Backlog, select the sprint, click **Start Sprint**, and enter start/end dates (typically a 1–2 week duration).
    - **Complete**: From **Active sprints**, click **Complete Sprint**. Jira moves **unresolved issues** to the next sprint or back to the backlog, and the completed sprint becomes available in reports.

    Completed sprints **cannot be reopened**, so ensure the sprint review is done before completing. Starting/completing requires the **Manage Sprints** permission.

    **[⬆ Back to Top](#table-of-contents)**

70. ### What happens when incomplete issues remain in a sprint?

    When you **Complete Sprint**, Jira prompts you to handle incomplete issues by moving them to:

    - The **next sprint** (if one exists),
    - A **new sprint**, or
    - Back to the **backlog**.

    Unfinished items should be **re-estimated** if their scope has changed. Tracking how often items carry over helps diagnose over-commitment or estimation problems. The completed sprint's report records what was and wasn't finished.

    **[⬆ Back to Top](#table-of-contents)**

71. ### What is sprint velocity?

    **Velocity** is the amount of work a team **completes** in a sprint, usually measured in **story points**. It helps forecast future capacity. To use it:

    - Sum the points of issues **completed** (resolved) during the sprint.
    - **Average** across several sprints for a reliable figure.

    Velocity is a **planning aid**, not a performance score — comparing velocity across different teams is meaningless because point scales are relative to each team.

    **[⬆ Back to Top](#table-of-contents)**

72. ### How is velocity calculated?

    List all issues **completed** in the sprint, add their story points, and record the total. Then average over multiple sprints.

    ```python
    # Compute average velocity from completed-story-point totals per sprint
    sprint_points = [16, 21, 18, 23, 19]   # completed points per sprint

    average_velocity = sum(sprint_points) / len(sprint_points)
    print(f"Average velocity: {average_velocity:.1f} points/sprint")

    # Forecast: how many sprints to clear a 120-point backlog?
    backlog = 120
    import math
    sprints_needed = math.ceil(backlog / average_velocity)
    print(f"~{sprints_needed} sprints to clear {backlog} points")
    ```

    Factors affecting velocity: team size/experience, story complexity, and external dependencies.

    **[⬆ Back to Top](#table-of-contents)**

73. ### What is a sprint goal?

    A **sprint goal** is a short statement summarizing the main objective of the sprint, e.g., *"Implement user registration and login."* It:

    - Provides **focus** and a shared sense of purpose.
    - Helps the team make **trade-off decisions** mid-sprint.
    - Gives a clear yardstick for evaluating sprint **success** at review.

    A good goal is **clear, achievable, and aligned** with product priorities — and ideally still meaningful even if a few low-priority items slip.

    **[⬆ Back to Top](#table-of-contents)**

74. ### How do sprint reports help teams?

    The **Sprint Report** shows:

    - **Completed** issues and **incomplete** issues.
    - Issues **added or removed** during the sprint (scope change).
    - A **burndown** of remaining work over the sprint.

    Teams use it in the **retrospective** to review performance, spot **scope creep**, and check estimation accuracy (committed vs completed points). It is the primary artifact for inspecting how a sprint actually went versus the plan.

    **[⬆ Back to Top](#table-of-contents)**

75. ### What is a burnup chart?

    A **burnup chart** plots **completed work** over time alongside a **total scope** line. The gap between the two lines represents **remaining work**. Its key advantage over a burndown is that **scope changes are visible** — if work is added, the total-scope line rises, making scope creep obvious rather than hidden. Teams use burnup to communicate both progress and changing scope to stakeholders.

    **[⬆ Back to Top](#table-of-contents)**

76. ### What is a burndown chart?

    A **burndown chart** plots **remaining work** versus time, with an **ideal line** declining steadily to zero at sprint end. It answers "are we on track to finish?" Deviations above the ideal line signal delays or added scope; a flat line means no progress (work blocked or not closed). Burndown is the most common Scrum chart for daily sprint health checks.

    **[⬆ Back to Top](#table-of-contents)**

77. ### What are sprint permissions?

    - **Manage Sprints** permission controls who can **create, start, complete, edit, and delete** sprints.
    - **Schedule Issues** permission is needed to set **due dates**.

    Without Manage Sprints, users can **view** sprints but not modify them. These are set in the project's **permission scheme** and typically granted to Scrum Masters and team leads.

    **[⬆ Back to Top](#table-of-contents)**

78. ### How can sprint scope changes be tracked?

    - The **Sprint Report** lists issues **added or removed** after the sprint started.
    - JQL can surface mid-sprint additions:

    ```sql
    -- Issues created during the current open sprint in the last week
    sprint in openSprints() AND created >= startOfDay(-7)
    ```

    Tracking scope change helps quantify **scope creep** and supports better planning conversations in retrospectives.

    **[⬆ Back to Top](#table-of-contents)**

79. ### How do you manage parallel sprints?

    **Parallel sprints** allow **multiple active sprints** on one board — useful when several teams share a board. To enable:

    1. Go to **Board settings → General → Parallel Sprints** (requires admin rights).
    2. Each team can **start its own sprint**.

    All sprints share the **same backlog**, so be careful assigning issues to the correct sprint. Parallel sprints add reporting complexity, so use them only when teams genuinely share one board.

    **[⬆ Back to Top](#table-of-contents)**

80. ### How do you troubleshoot sprint reporting issues?

    Check that:

    - Issues have the **Sprint field** set and are assigned to the **correct sprint**.
    - The **board filter** isn't excluding issues (e.g., hiding sub-tasks or Done issues).
    - **Estimation** is consistent (story points vs original estimate) across the board.
    - The **Resolution** field is set on Done issues so they count in burndown.
    - **Completed sprints** haven't been incorrectly re-opened or duplicated.

    A frequent culprit is the "Done but unresolved" issue — done on the board but excluded from completed metrics because resolution is empty.

    **[⬆ Back to Top](#table-of-contents)**


## Epics, Stories & Backlog Management

81. ### What is an Epic?

    An **Epic** is a high-level requirement or initiative that encompasses multiple stories/tasks and typically delivers significant value or a feature over **multiple sprints**. Epics help structure large bodies of work, can span weeks or months, are visualized on **roadmaps**, and have their own **progress indicators** (percentage of child issues or story points completed).

    **[⬆ Back to Top](#table-of-contents)**

82. ### How do Epics help Agile teams?

    Epics let teams:

    - **Organize related work** under a single umbrella.
    - **Track progress** at a feature level rather than per-issue.
    - **Communicate large goals** to stakeholders and on roadmaps.
    - **Plan releases** incrementally by completing stories within an epic.

    Product owners use epics to plan roadmaps; teams break them into smaller stories and monitor epic progress through completion percentages.

    **[⬆ Back to Top](#table-of-contents)**

83. ### How do Stories relate to Epics?

    **Stories** are the primary units of work that deliver user value. They belong to an epic via the **Epic Link / Parent** field when part of a larger initiative. Stories represent **vertical slices** of functionality (something a user can actually do). Once all stories under an epic are complete, the **epic is done**. This relationship lets teams work in small, valuable increments while still tracking toward a larger goal.

    **[⬆ Back to Top](#table-of-contents)**

84. ### What is backlog grooming (backlog refinement)?

    **Backlog grooming (refinement)** is the ongoing process of reviewing, ordering, and refining backlog items. Activities include:

    - **Clarifying requirements** and acceptance criteria.
    - **Splitting** large stories into smaller ones.
    - **Estimating** effort.
    - **Reprioritizing** based on value and dependencies.

    Regular grooming keeps the backlog **ready for sprint planning** and prevents last-minute surprises. It's typically a recurring session involving the product owner and team.

    **[⬆ Back to Top](#table-of-contents)**

85. ### How do you prioritize backlog items?

    Common prioritization methods:

    | Method | Idea |
    | --- | --- |
    | **MoSCoW** | Must / Should / Could / Won't have |
    | **Kano model** | Basics vs performance vs delighters |
    | **WSJF** | Weighted Shortest Job First (value ÷ duration) |
    | **Value vs Risk matrix** | Plot effort/risk against value |
    | **Stakeholder scoring** | Weighted input from stakeholders |

    In Jira, backlog items are ordered by **drag-and-drop** or by editing the **Rank** field. Rank is a special LexoRank-based field that maintains a global ordering without renumbering every issue.

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is story point estimation?

    **Story points** are **relative units** representing the **complexity, effort, and uncertainty** of a story (not hours). Teams commonly use the **Fibonacci sequence** (1, 2, 3, 5, 8, 13…) or **T-shirt sizes** (S/M/L/XL). Estimation sessions (**planning poker**) build team consensus. Because points are relative, they avoid the false precision of time estimates and help teams plan capacity via velocity over time.

    **[⬆ Back to Top](#table-of-contents)**

87. ### What estimation methods can be used in JIRA?

    Jira supports several estimation approaches:

    - **Story points** (default for Scrum).
    - **Original estimate** (time in hours/days).
    - **Issue count** (Kanban — each issue counts equally).
    - **Custom fields** (e.g., a Business Value field).

    Boards can be configured to **estimate with one field and track with another** — for example, estimate in **story points** but track progress using **time logged**. This is set in **Board settings → Estimation**.

    **[⬆ Back to Top](#table-of-contents)**

88. ### How do you track Epic progress?

    - The **epic panel / roadmap** shows progress bars (percentage of completed issues or story points).
    - JQL lists all issues under an epic:

    ```sql
    -- Older Jira: by Epic Link
    "Epic Link" = PROJ-123

    -- Newer Jira Cloud: by parent
    parent = PROJ-123
    ```

    - The **Epic Burndown / Epic Report** shows how epic work completes over sprints, helping forecast when an epic will finish.

    **[⬆ Back to Top](#table-of-contents)**

89. ### What are roadmap views?

    **Roadmaps** provide a **timeline view** of epics (and higher-level initiatives). They let users:

    - Plan **start/end dates** for epics.
    - Visualize **dependencies**.
    - Track **progress** at a glance.

    Basic roadmaps are available in team-managed projects and Jira Software. **Advanced Roadmaps** (Premium/Enterprise/Data Center) extend this across multiple teams, projects, and hierarchy levels.

    **[⬆ Back to Top](#table-of-contents)**

90. ### How do advanced roadmaps work?

    **Advanced Roadmaps** (formerly Portfolio for Jira) enables planning across **multiple teams and projects**. Key capabilities:

    - **Custom hierarchy levels** (Initiatives, Capabilities, Themes) above epics.
    - **Capacity planning** based on team velocity/availability.
    - **Dependency tracking** on the timeline.
    - **Scenario (what-if) planning** without committing changes.
    - **Cross-project reporting**.

    It requires Jira **Premium/Enterprise** (Cloud) or a **Data Center** license. Plans pull from multiple boards/projects and let managers model trade-offs before publishing changes back to issues.

    **[⬆ Back to Top](#table-of-contents)**

91. ### How do dependencies affect backlog planning?

    **Dependencies** (e.g., one story blocks another) influence scheduling: blocked items should be sequenced **after** their blockers. In planning:

    - **Advanced Roadmaps** visualizes dependencies on the timeline and flags scheduling conflicts.
    - JQL finds blocked work:

    ```sql
    issue in linkedIssues("PROJ-123", "blocks")
    ```

    Ignoring dependencies leads to teams starting work that can't be finished, causing mid-sprint stalls.

    **[⬆ Back to Top](#table-of-contents)**

92. ### How do you manage large backlogs?

    Strategies for keeping large backlogs healthy:

    - Hold **regular refinement** sessions to prevent stale items.
    - Use **components, labels, or custom fields** to categorize.
    - **Filter by epic or version** during grooming to focus.
    - **Archive or delete** outdated items aggressively.
    - **Split** the backlog into themes or product areas.
    - Apply **prioritization frameworks** (WSJF, MoSCoW) so the top of the backlog is always the most valuable.

    **[⬆ Back to Top](#table-of-contents)**

93. ### What is WSJF prioritization?

    **Weighted Shortest Job First (WSJF)** is a SAFe prioritization method:

    ```
    WSJF = Cost of Delay / Job Duration
    ```

    where **Cost of Delay** = user/business value + time criticality + risk reduction/opportunity enablement. Higher WSJF = higher priority (high value, short duration first).

    ```python
    def wsjf(business_value, time_criticality, risk_reduction, job_size):
        cost_of_delay = business_value + time_criticality + risk_reduction
        return round(cost_of_delay / job_size, 2)

    features = {
        "SSO login":      wsjf(8, 5, 3, 5),
        "Dark mode":      wsjf(3, 1, 1, 2),
        "Payment retry":  wsjf(9, 8, 5, 3),
    }
    for name, score in sorted(features.items(), key=lambda x: -x[1]):
        print(f"{name:14} WSJF = {score}")
    ```

    In Jira, store the component scores as **custom fields** and sort the backlog by a computed WSJF field.

    **[⬆ Back to Top](#table-of-contents)**

94. ### How do you handle backlog refinement sessions?

    - **Schedule** regular sessions (weekly or once per sprint).
    - **Invite** the product owner, Scrum Master, and team.
    - **Review highest-priority items first**.
    - **Clarify** acceptance criteria, **split** large stories, **estimate**, and **reprioritize**.
    - **Make decisions** (remove, reword, split) and **record outcomes** in Jira immediately.

    The goal is a "ready" backlog — enough refined, estimated items at the top to fill the next 1–2 sprints.

    **[⬆ Back to Top](#table-of-contents)**

95. ### How do you visualize release planning in JIRA?

    - Assign issues to a **Fix Version** (release).
    - Use the **Release Hub** to see progress, release burndown, and potential blockers.
    - **Roadmaps** show releases on the timeline.
    - For multi-team planning, use **Advanced Roadmaps** with release vehicles.

    ```sql
    -- All work targeted at release v2.0 across projects, still open
    fixVersion = "v2.0" AND resolution IS EMPTY ORDER BY priority DESC
    ```

    **[⬆ Back to Top](#table-of-contents)**


## JQL (JIRA Query Language)

96. ### What is JQL?

    **JQL (Jira Query Language)** is a flexible query language for searching issues. A query is composed of a **field**, an **operator**, a **value**, and optional **keywords** (AND, OR, NOT) plus **ORDER BY**. JQL powers **filters, boards, gadgets, automation rules**, and **REST API** searches. It is not SQL — it queries Jira's search index, not a database table.

    ```sql
    project = PROJ AND status = "In Progress" AND assignee = currentUser() ORDER BY priority DESC
    ```

    **[⬆ Back to Top](#table-of-contents)**

97. ### Why is JQL important?

    JQL lets users build **precise, reusable searches** that underpin much of Jira:

    - **Boards** use JQL filters to decide which issues appear.
    - **Saved filters** can be shared, used in dashboards, and emailed on a schedule.
    - **Automation rules** use JQL conditions.
    - **REST API** queries pass JQL to fetch issues.

    Mastering JQL enables advanced reporting, troubleshooting, and automation — it's a core skill for any Jira power user or admin.

    **[⬆ Back to Top](#table-of-contents)**

98. ### What are JQL fields?

    **Fields** represent issue attributes. Common ones: `project`, `issuetype`, `status`, `priority`, `assignee`, `reporter`, `labels`, `created`, `updated`, `duedate`, `sprint`, `fixVersion`, plus any **custom field**. Use **quotes** for fields (or values) containing spaces:

    ```sql
    "Epic Link" = PROJ-100 AND "Story Points" >= 5
    ```

    Custom fields can also be referenced by ID (`cf[10010]`) when names are ambiguous.

    **[⬆ Back to Top](#table-of-contents)**

99. ### What are JQL operators?

    | Operator | Meaning |
    | --- | --- |
    | `=`, `!=` | Equals / not equals |
    | `IN`, `NOT IN` | Membership in a list |
    | `<`, `>`, `<=`, `>=` | Numeric/date comparison |
    | `~`, `!~` | Contains / does not contain (text) |
    | `IS`, `IS NOT` | Null checks (`resolution IS EMPTY`) |
    | `WAS`, `WAS IN`, `WAS NOT` | Historical value operators |
    | `CHANGED` | Field changed over time |
    | `ORDER BY` | Sort results |

    Example using a history operator:

    ```sql
    status WAS "In Progress" BEFORE "2025-01-01"
    ```

    **[⬆ Back to Top](#table-of-contents)**

100. ### What is the difference between = and IN operators?

     - `=` checks equality against a **single value**: `status = "Done"`.
     - `IN` checks membership in a **list**: `status IN ("To Do", "In Progress")`.

     Use `IN` for multiple values instead of chaining `OR`s — it's shorter and the query planner handles it efficiently:

     ```sql
     -- Preferred
     status IN ("To Do", "In Progress", "In Review")

     -- Equivalent but verbose
     status = "To Do" OR status = "In Progress" OR status = "In Review"
     ```

     **[⬆ Back to Top](#table-of-contents)**

101. ### How do AND and OR operators work?

     - `AND` requires **all** conditions to be true.
     - `OR` requires **any** condition to be true.
     - **Parentheses** control precedence (AND binds tighter than OR, so group explicitly).

     ```sql
     (status = "In Progress" OR status = "To Do") AND assignee = currentUser()
     ```

     Without the parentheses, `AND` would bind first and change the meaning entirely — always parenthesize mixed AND/OR logic.

     **[⬆ Back to Top](#table-of-contents)**

102. ### What are JQL functions?

     **Functions** return dynamic values usable in conditions:

     | Function | Returns |
     | --- | --- |
     | `currentUser()` | The logged-in user |
     | `membersOf("group")` | Members of a group |
     | `startOfDay()`, `endOfWeek()`, etc. | Relative date boundaries |
     | `now()` | Current timestamp |
     | `openSprints()`, `closedSprints()` | Issues in open/closed sprints |
     | `linkedIssues("KEY", "type")` | Linked issues |
     | `issueHistory()` | Recently viewed issues |
     | `componentsLeadByUser()` | Components led by a user |

     ```sql
     assignee in membersOf("developers") AND due <= endOfWeek()
     ```

     **[⬆ Back to Top](#table-of-contents)**

103. ### How does currentUser() work?

     `currentUser()` returns the **currently logged-in user's account**, making filters reusable across people. The same saved filter shows each viewer their own issues:

     ```sql
     -- My open work
     assignee = currentUser() AND resolution IS EMPTY

     -- Things I'm watching
     watcher = currentUser()
     ```

     This is why "My Open Issues" works for everyone without per-user filters.

     **[⬆ Back to Top](#table-of-contents)**

104. ### How does membersOf() work?

     `membersOf("group")` expands to **all users in a group**, useful for team-based queries:

     ```sql
     -- Issues assigned to anyone on the QA team
     assignee in membersOf("qa-team")

     -- Unassigned bugs that should go to the dev team
     issuetype = Bug AND assignee IS EMPTY AND project in (PROJ)
     ```

     It keeps queries maintainable — change group membership in one place and all filters using `membersOf` update automatically.

     **[⬆ Back to Top](#table-of-contents)**

105. ### How do you find issues assigned to you?

     ```sql
     -- All issues assigned to me
     assignee = currentUser()

     -- My open (unresolved) issues
     assignee = currentUser() AND resolution IS EMPTY ORDER BY priority DESC
     ```

     Adding `resolution IS EMPTY` filters to active work, which is usually what "my issues" should mean on a dashboard gadget.

     **[⬆ Back to Top](#table-of-contents)**

106. ### How do you find overdue issues?

     ```sql
     -- Overdue and still open
     due <= now() AND resolution IS EMPTY

     -- Overdue within a specific project
     project = PROJ AND due <= now() AND resolution IS EMPTY ORDER BY due ASC
     ```

     Including `resolution IS EMPTY` avoids flagging already-closed issues whose due date has passed.

     **[⬆ Back to Top](#table-of-contents)**

107. ### How do you find unresolved bugs?

     ```sql
     project = PROJ AND issuetype = Bug AND resolution IS EMPTY ORDER BY priority DESC, created ASC
     ```

     Sorting by priority then creation date surfaces the most urgent, oldest bugs first — a useful triage queue.

     **[⬆ Back to Top](#table-of-contents)**

108. ### How do you search issues across multiple projects?

     ```sql
     -- Explicit list
     project IN (PROJ1, PROJ2, PROJ3)

     -- By project category
     category = "Finance"
     ```

     Using a **category** is convenient when projects are added/removed frequently — the query keeps working without edits as long as new projects join the category.

     **[⬆ Back to Top](#table-of-contents)**

109. ### How do you create saved filters?

     1. In the **Issue Navigator**, build your JQL.
     2. Click **Save as**, give it a **name** and **description**.
     3. Set **sharing permissions** (private, group, project, or public).

     Saved filters can then power **boards**, **dashboard gadgets**, and **subscriptions**. Sharing correctly is essential — a board built on an unshared filter won't be visible to teammates.

     **[⬆ Back to Top](#table-of-contents)**

110. ### How do filter subscriptions work?

     A **subscription** emails a filter's results on a schedule:

     1. In **Filters → View all filters**, open a filter → **Details → New subscription**.
     2. Choose **recipients** (yourself, a group), a **schedule** (daily/weekly/monthly), and a time.
     3. Optionally email **even when there are no issues**.

     Jira sends a digest of matching issues at the scheduled time — handy for "open critical bugs" or "overdue work" daily reports.

     **[⬆ Back to Top](#table-of-contents)**

111. ### How do you optimize complex JQL queries?

     - Use **`IN`** instead of many `OR`s.
     - Put **indexed/selective fields** (project, status, assignee) early.
     - **Avoid text search (`~`)** unless necessary — it's slower.
     - Use **parentheses** for clear precedence.
     - Save reusable subqueries as filters and reference them: `filter = "My Filter" AND ...`.
     - **Bound by date** to limit the result set (`updated >= -30d`).

     ```sql
     filter = "Active Sprint Work" AND issuetype = Bug AND priority IN (High, Highest)
     ```

     **[⬆ Back to Top](#table-of-contents)**

112. ### How do you search for issues updated in the last 7 days?

     ```sql
     -- Relative date: last 7 days
     updated >= -7d

     -- Scoped to a project, newest first
     project = PROJ AND updated >= -7d ORDER BY updated DESC
     ```

     Relative date syntax (`-7d`, `-1w`, `-2h`) is timezone-aware and recalculates each time the query runs.

     **[⬆ Back to Top](#table-of-contents)**

113. ### How do you identify blocked issues using JQL?

     ```sql
     -- Issues blocked by a specific issue
     issue in linkedIssues("PROJ-123", "is blocked by")

     -- All blocked issues in a project (requires ScriptRunner's issueFunction)
     project = PROJ AND issueFunction in linkedIssuesOf("project = PROJ", "is blocked by")
     ```

     Native JQL handles links from a **specific** issue; finding **all** blocked issues across a project generally needs the **ScriptRunner** add-on's `issueFunction`, or an automation that labels blocked issues.

     **[⬆ Back to Top](#table-of-contents)**

114. ### What are common JQL interview scenarios?

     ```sql
     -- High-priority bugs assigned to a specific user
     project = PROJ AND issuetype = Bug AND priority = Highest AND assignee = jsmith

     -- Unresolved issues created this week
     created >= startOfWeek() AND resolution IS EMPTY

     -- Issues without an assignee
     assignee IS EMPTY

     -- Issues transitioned to Done in the last week
     status CHANGED TO Done DURING (startOfWeek(), endOfWeek())

     -- Issues reopened recently
     status CHANGED FROM Done TO "In Progress" AFTER -14d
     ```

     **[⬆ Back to Top](#table-of-contents)**

115. ### How would you write JQL for sprint reporting?

     ```sql
     -- Everything in the current open sprint for a project
     sprint in openSprints() AND project = PROJ

     -- Completed work in a specific sprint (by sprint id)
     sprint = 5 AND resolution IS NOT EMPTY

     -- Incomplete work carried over from the current sprint
     sprint in openSprints() AND resolution IS EMPTY ORDER BY priority DESC

     -- Bugs found during the current sprint
     sprint in openSprints() AND issuetype = Bug AND created >= startOfDay(-14)
     ```

     For "added after sprint start," Jira's native JQL is limited; the **Sprint Report** UI or ScriptRunner functions give the most accurate scope-change view.

     **[⬆ Back to Top](#table-of-contents)**


## Dashboards & Reporting

116. ### What are JIRA dashboards?

     **Dashboards** are customizable pages that display project information through **gadgets**. They provide an at-a-glance view of metrics, trends, and assigned work. Each user has a **personal dashboard** and can also view **shared dashboards**. Dashboards are built from saved filters plus gadgets, making them powerful for team standups, executive reporting, and personal task tracking.

     **[⬆ Back to Top](#table-of-contents)**

117. ### What gadgets are available in dashboards?

     Jira ships with many built-in gadgets:

     | Gadget | Purpose |
     | --- | --- |
     | **Assigned to Me** | Open issues assigned to the viewer |
     | **Filter Results** | Table of issues from a saved filter |
     | **Pie Chart** | Issues grouped by a field |
     | **Created vs Resolved** | Created vs resolved trend over time |
     | **Average Age** | Avg days issues remain unresolved |
     | **Two-Dimensional Filter Statistics** | Matrix of issues by two fields |
     | **Sprint Health** | Snapshot of current sprint scope/status |
     | **Sprint Burndown** | Burndown chart |
     | **Issue Statistics** | Issues grouped by a single field |
     | **Activity Stream** | Recent activity feed |
     | **Days Remaining in Sprint** | Time left in the sprint |

     Marketplace apps add more (e.g., advanced charts, time-in-status gadgets).

     **[⬆ Back to Top](#table-of-contents)**

118. ### How do you create a dashboard?

     1. Go to **Dashboards → View all dashboards → Create new dashboard**.
     2. Provide a **name**, **description**, and assign **owners/editors**.
     3. Click **Add gadget**, choose gadgets, and configure each one's **filter**, **display options**, and **refresh interval**.
     4. **Drag and drop** to arrange the layout.
     5. Set **sharing** so the right audience can view it.

     Building dashboards on **shared filters** ensures every viewer sees consistent data.

     **[⬆ Back to Top](#table-of-contents)**

119. ### What are shared dashboards?

     **Shared dashboards** are visible to other users or groups. When creating/editing, set **Share with**: private, a group, a project, or public. Depending on share settings, others can **view** or **edit**. Shared dashboards give teams a **common view** of project health — for example, a sprint dashboard the whole team checks during standup, or an executive dashboard for leadership.

     **[⬆ Back to Top](#table-of-contents)**

120. ### What is a Filter Results gadget?

     The **Filter Results** gadget displays issues from a saved filter in **table form**. Configuration options include:

     - **Number of results** per page.
     - **Columns** to display.
     - **Sort order**.
     - Whether to **show the filter's JQL**.

     It's the most-used gadget for surfacing specific work queues (e.g., "My open bugs", "Overdue items") directly on a dashboard.

     **[⬆ Back to Top](#table-of-contents)**

121. ### What is a Pie Chart gadget?

     The **Pie Chart** gadget shows the **distribution of issues grouped by a statistic field** (status, priority, assignee, component, etc.). You specify a **filter** and a **statistic type**; the gadget renders slices with counts and percentages. It's ideal for quick composition views like "issues by priority" or "open work by assignee."

     **[⬆ Back to Top](#table-of-contents)**

122. ### What is a Two-Dimensional Filter Statistics gadget?

     The **Two-Dimensional Filter Statistics** gadget displays issues in a **matrix** of two fields — for example, **Status (rows) × Priority (columns)**. Each cell shows the count of issues matching both values. It's excellent for **cross-tab analysis**, such as seeing how many high-priority issues sit in each status, revealing where urgent work is stuck.

     **[⬆ Back to Top](#table-of-contents)**

123. ### What is a Created vs Resolved chart?

     The **Created vs Resolved** gadget plots the number of issues **created** versus **resolved** over time (daily/weekly/monthly). It reveals whether the team is **keeping up** with incoming work:

     - Resolved line above created → backlog shrinking.
     - Created consistently above resolved → backlog growing (a warning sign).

     It's a key health metric for support and maintenance teams tracking throughput vs intake.

     **[⬆ Back to Top](#table-of-contents)**

124. ### What is an Average Age chart?

     The **Average Age** gadget displays the **average number of days issues remain unresolved** over a period, as a bar chart. A rising average age indicates work is **aging** — issues are opened but not closed promptly, often signaling bottlenecks, under-staffing, or neglected low-priority items. It complements cycle-time analysis for spotting stagnation.

     **[⬆ Back to Top](#table-of-contents)**

125. ### What reports are available in Scrum projects?

     Scrum boards provide:

     - **Burndown Chart** — remaining work in the sprint.
     - **Burnup Chart** — completed work vs scope.
     - **Velocity Chart** — committed vs completed points across sprints.
     - **Sprint Report** — per-sprint completion and scope change.
     - **Epic Report** / **Epic Burndown** — epic progress.
     - **Release Burndown** — progress toward a release.
     - **Cumulative Flow Diagram** and **Control Chart**.

     **[⬆ Back to Top](#table-of-contents)**

126. ### What reports are available in Kanban projects?

     Kanban boards provide:

     - **Cumulative Flow Diagram** — issues per status over time.
     - **Control Chart** — cycle/lead time for completed issues.
     - **Cycle Time Report** — time from start to done.
     - **Lead Time Report** — time from creation to done.
     - **Release Burndown** — release progress.

     Available reports depend on whether a **Kanban backlog** is enabled. Kanban emphasizes flow metrics (cycle/lead time) over velocity.

     **[⬆ Back to Top](#table-of-contents)**

127. ### How do cumulative flow diagrams work?

     A **Cumulative Flow Diagram (CFD)** shows the **number of issues in each status over time**. The x-axis is time; the y-axis is issue count, with each status as a colored band. Interpreting it:

     - **Widening band** → a bottleneck (work piling up in that status).
     - **Parallel bands** → stable, healthy flow.
     - **Flat top band** → little new work entering.

     CFDs are a primary tool for diagnosing WIP and bottlenecks in Kanban systems.

     **[⬆ Back to Top](#table-of-contents)**

128. ### What is a Control Chart?

     A **Control Chart** displays **cycle time** or **lead time** for completed issues. Each issue is a **dot**; a **rolling average line** highlights trends, and shaded bands show the standard deviation. Teams use it to:

     - Monitor **process stability** (consistent vs erratic cycle times).
     - **Forecast** future completion times.
     - Spot **outliers** that took unusually long.

     A tight, stable control chart indicates a predictable delivery process.

     **[⬆ Back to Top](#table-of-contents)**

129. ### How do you create executive dashboards?

     Combine high-level gadgets:

     - **Created vs Resolved** (backlog trend).
     - **Average Age** (aging work).
     - **Issue Statistics** by status/priority.
     - **Sprint Health** and **Velocity**.
     - **Pie Chart** by assignee or team.
     - Custom charts from marketplace apps.

     Use filters that **aggregate across projects/programs** and **share** the dashboard with leadership. Keep it focused on outcomes (delivery, quality, risk) rather than granular task lists.

     **[⬆ Back to Top](#table-of-contents)**

130. ### What are common dashboard best practices?

     - **Keep it simple** — focus on a few key metrics per dashboard.
     - Use **filters and gadgets that answer stakeholder questions**.
     - **Limit gadget count** to avoid clutter and slow loading.
     - Use **meaningful names and descriptions**.
     - **Restrict editing rights** to prevent accidental changes.
     - Ensure **filter sharing** matches dashboard sharing so everyone sees the same data.

     **[⬆ Back to Top](#table-of-contents)**


## Permissions & Security

131. ### What are permission schemes?

     A **permission scheme** defines which users, groups, or project roles can perform actions in a project. Each project is associated with **one** permission scheme. Permissions span:

     - **Project permissions** (Browse Projects, Create Issues, Assign Issues, Transition Issues, Manage Sprints, etc.).
     - **Issue-level** actions.

     Reusing a single scheme across projects simplifies administration — change it once and all associated projects update.

     **[⬆ Back to Top](#table-of-contents)**

132. ### What are project roles?

     **Project roles** are **placeholders** representing a set of users/groups **per project** (e.g., Administrators, Developers, Users, Stakeholders). Their power is flexibility: the **same role** can have **different members** in different projects. Roles are assigned on the project's **People** page and referenced in permission and notification schemes. This lets one shared scheme behave differently per project based on each project's role membership.

     **[⬆ Back to Top](#table-of-contents)**

133. ### What is the difference between groups and roles?

     | Aspect | Groups | Roles |
     | --- | --- | --- |
     | **Scope** | Global (instance-wide) | Per-project |
     | **Managed by** | Jira administrators | Project administrators (membership) |
     | **Flexibility** | Same members everywhere | Different members per project |
     | **Typical use** | Global permissions, license groups | Project-level permission/notification targets |

     **Groups** are global collections (e.g., `jira-software-users`); **roles** are project-specific. Best practice is to grant permissions to **roles** (not groups) in schemes, so project admins can manage membership without touching the shared scheme.

     **[⬆ Back to Top](#table-of-contents)**

134. ### What are global permissions?

     **Global permissions** apply to the **entire Jira instance** and are granted to **groups**. Examples:

     - **Jira System Administrators** — full admin rights.
     - **Jira Administrators** — most admin functions.
     - **Browse Users** — view user/group lists (needed for assignee pickers).
     - **Bulk Change** — perform bulk operations.
     - **Create Shared Objects** — share filters/dashboards.

     Only **system administrators** can grant or revoke global permissions. They are distinct from project-level permissions.

     **[⬆ Back to Top](#table-of-contents)**

135. ### What are project permissions?

     **Project permissions** determine what users can do **within a project**: Administer Project, Browse Projects, Create/Edit/Delete Issues, Assign Issues, Transition Issues, Manage Sprints, Close Issues, Add Comments, etc. They are set in **permission schemes** and granted to users, groups, or roles. **Browse Projects** is the foundational permission — without it, most other permissions have no effect because the user can't even see the project's issues.

     **[⬆ Back to Top](#table-of-contents)**

136. ### What is issue-level security?

     **Issue-level security** restricts viewing of **individual issues** via an **issue security scheme**. Each **security level** in the scheme lists who (users/groups/roles) can see issues at that level. When the scheme is applied to a project, a **Security Level** field appears on issues. If a user isn't in the level's allowed list, they **cannot view** the issue — even with Browse Projects. It's used for sensitive issues (HR, security incidents) within otherwise open projects.

     **[⬆ Back to Top](#table-of-contents)**

137. ### How do permission schemes work?

     A permission scheme is a **list mapping each permission → who has it** (users/groups/roles). A project uses one scheme; changing the scheme changes permissions in **all** projects using it. You can **copy**, **edit**, and **assign** schemes to projects. Because of the shared nature, prefer granting permissions to **project roles** so the same scheme adapts per project via role membership.

     **[⬆ Back to Top](#table-of-contents)**

138. ### How can users be restricted from viewing issues?

     - Apply an **issue security scheme** and set a restrictive **security level** on sensitive issues.
     - Ensure the user lacks **Browse Projects** for projects they shouldn't see.
     - Remove them from **groups/roles** that grant access.
     - Adjust the **permission scheme** accordingly.

     Issue security **overrides** Browse Projects for viewing specific issues — it's the strongest per-issue restriction available.

     **[⬆ Back to Top](#table-of-contents)**

139. ### What are security levels?

     **Security levels** are entries within an **issue security scheme**. Each level defines **who can see** issues assigned to it. Example levels:

     - **Internal** — project team only.
     - **Management** — project leads only.
     - **All Logged-in Users** — any authenticated user.

     You assign a level to an issue via the **Security Level** field. A default level can be set so new issues are automatically protected.

     **[⬆ Back to Top](#table-of-contents)**

140. ### How do you audit permissions?

     Use the **Permission Helper** (Administration → … → Permission Helper). Enter a **user**, an **issue**, and a **permission**, and it explains **why** the user does or doesn't have that permission — tracing through group membership, project roles, scheme entries, and issue security. It's the go-to tool for answering "why can/can't this person do X?" without manually inspecting every scheme.

     **[⬆ Back to Top](#table-of-contents)**

141. ### How do permission conflicts occur?

     When a user belongs to **multiple groups/roles**, they receive the **union (most permissive)** of all granted permissions. Conflicts typically arise when someone is in a group that grants access **and** a role intended to restrict it — the **grant wins**. The key exception: **issue security** can **prevent viewing** an issue regardless of other permissions, so a user with broad permissions still can't see an issue whose security level excludes them.

     **[⬆ Back to Top](#table-of-contents)**

142. ### What is anonymous access?

     **Anonymous access** allows **unlicensed/public** users to browse issues, dashboards, or pages without logging in. To enable, an admin grants **Browse Projects** (and other permissions) to the special **Anyone / anonymous** group in the permission scheme. Use with caution — only expose **non-sensitive** projects, and never combine anonymous browse with confidential data. Most production instances keep anonymous access disabled.

     **[⬆ Back to Top](#table-of-contents)**

143. ### How do you secure sensitive projects?

     - Use a **dedicated permission scheme** with tightly scoped roles/groups.
     - **Limit** who has Browse Projects.
     - Apply **issue security schemes** for per-issue restrictions.
     - **Avoid** sharing filters/dashboards publicly that expose the data.
     - **Audit regularly** with the Permission Helper and user-management reports.
     - Disable **anonymous access**.

     Defense in depth — combining project permissions, issue security, and careful sharing — protects sensitive work.

     **[⬆ Back to Top](#table-of-contents)**

144. ### What are common security challenges in JIRA?

     - **Over-provisioning** — granting more access than needed.
     - **Stale schemes** — forgetting to update permissions when people change roles.
     - **Missing issue security** on sensitive items.
     - **Public filters/dashboards** leaking data.
     - **Misused group membership** — e.g., adding all users to `jira-administrators`.
     - **Anonymous access** left enabled inadvertently.

     Regular audits and least-privilege defaults mitigate these.

     **[⬆ Back to Top](#table-of-contents)**

145. ### How do you troubleshoot permission issues?

     1. Use the **Permission Helper** to find why a permission is missing.
     2. Check the project's **permission scheme** entries.
     3. Verify the user's **group** and **role** membership.
     4. Inspect **issue security** (it can silently block viewing).
     5. Confirm relevant **global permissions** (e.g., Bulk Change, Browse Users).
     6. Have the user **log out/in or refresh** after changes (permission caches).

     **[⬆ Back to Top](#table-of-contents)**


## User & Project Administration

146. ### How do you create a new project?

     Go to **Projects → Create project**:

     1. Choose a **template** (Scrum, Kanban, Service Management, Business).
     2. Select **company-managed** or **team-managed**.
     3. Provide a **name** and **key**.
     4. Configure initial settings (lead, access).

     You need the **Create Project** global permission (Jira Admin or higher). Choosing the right template up front sets up an appropriate board, issue types, and workflow automatically.

     **[⬆ Back to Top](#table-of-contents)**

147. ### How do you manage project administrators?

     Project administrators are assigned via **Project settings → People** by adding a user/group to the **Administrators** role. Project admins can manage project-level settings (versions, components, and — in team-managed projects — issue types, workflows, and fields). In **company-managed** projects they **cannot** change permission schemes or issue type schemes; those remain with Jira administrators, preserving organizational consistency.

     **[⬆ Back to Top](#table-of-contents)**

148. ### How do you add users to JIRA?

     A Jira admin goes to **Administration → User Management → Invite users**:

     1. Enter **email addresses**.
     2. Assign **product access** (Jira Software / Service Management / Work Management).
     3. Optionally add them to **groups**.

     The user receives an invitation email to set a password. In larger orgs, users are often provisioned automatically via **SCIM / SAML SSO** through an identity provider (Okta, Azure AD) instead of manual invites.

     **[⬆ Back to Top](#table-of-contents)**

149. ### How do groups work in JIRA?

     **Groups** are global collections of users used to grant permissions and product access. Default groups include `jira-administrators` and product-access groups like `jira-software-users`. Membership is managed in **User Management** and grants members the group's permissions (e.g., the license group grants login/product access). Groups are the right tool for **global** concerns (admin rights, licensing); for **project-level** permissions, prefer roles.

     **[⬆ Back to Top](#table-of-contents)**

150. ### How do project roles work?

     **Roles** are per-project placeholders for users/groups, enabling fine-grained control in permission schemes. For example, add developers to the **Developers** role, then grant the **Resolve Issues** permission to **Developers** in a shared scheme. Because role membership varies per project, the same scheme can produce different effective permissions in each project — letting project admins manage their own team without modifying the shared scheme.

     **[⬆ Back to Top](#table-of-contents)**

151. ### How do notification schemes work?

     A **notification scheme** defines **who receives emails** for events (issue created, updated, resolved, commented, etc.). Each event maps to recipients such as **Reporter, Assignee, Watchers, project roles, groups, or a specific email**. Projects can share notification schemes. Combined with personal notification preferences, this controls the volume and targeting of email — a frequent source of "too many" or "missing" notification complaints.

     **[⬆ Back to Top](#table-of-contents)**

152. ### What are field configurations?

     A **field configuration** controls the **behaviour of fields**: required/optional, hidden/visible, default values, and description/help text. A **field configuration scheme** associates **issue types** with field configurations, so (for example) **Due Date** can be **required** for Tasks but **optional** for Stories. This lets one project enforce different data-entry rules per issue type.

     **[⬆ Back to Top](#table-of-contents)**

153. ### What are screen schemes?

     **Screens** are collections of fields. A **screen scheme** maps screens to the three operations — **Create, Edit, View**. Screen schemes are then combined into an **issue type screen scheme**, which assigns different screens per issue type within a project. This layered model lets a Bug show different fields on create vs view, and lets Bugs and Stories use entirely different screens.

     **[⬆ Back to Top](#table-of-contents)**

154. ### What are issue type schemes?

     An **issue type scheme** determines **which issue types are available** in a project and their **order** in the create dialog. You can create custom schemes (e.g., a "Software" scheme with Epic/Story/Task/Bug/Sub-task) and **share** them across projects. Removing a type from a scheme hides it from new-issue creation while preserving existing issues of that type.

     **[⬆ Back to Top](#table-of-contents)**

155. ### What are workflow schemes?

     A **workflow scheme** maps **issue types to workflows**, allowing different issue types in the same project to follow different lifecycles (e.g., Bugs use a detailed defect workflow; Stories use a simple one). Projects apply one workflow scheme. As noted earlier, changing a scheme on a populated project triggers status mapping and a re-index.

     **[⬆ Back to Top](#table-of-contents)**

156. ### How do you manage project templates?

     Templates are chosen at **project creation** and can't be swapped afterward, but you can **adjust** the project's workflows, screens, schemes, and fields later to evolve its behaviour. For **team-managed** projects, templates ship with configurable issue types and workflows that project admins can change in place. For repeatable setups across many projects, standardize on a small set of templates and shared schemes.

     **[⬆ Back to Top](#table-of-contents)**

157. ### What is project archiving?

     In **Jira Premium/Enterprise**, admins can **archive entire projects**. Archived projects are **read-only**, **hidden** from search and boards, and **excluded from licensing counts**. Archiving reduces clutter and improves performance while preserving history; projects can be **restored** later. It's the cleanest way to retire completed initiatives without permanently deleting data.

     **[⬆ Back to Top](#table-of-contents)**

158. ### How do you manage inactive users?

     - **Remove product access** or **deactivate** the account in User Management.
     - **Remove** them from groups/roles.

     Jira **retains their historical data** (as reporter/assignee on past issues) but they **can't log in**. Deactivating rather than deleting preserves audit trails and reporting integrity. Reassign their open issues before deactivation to avoid orphaned work.

     **[⬆ Back to Top](#table-of-contents)**

159. ### How do you handle project migrations?

     1. **Plan** the mapping of issue types, workflows, fields, and schemes.
     2. Use the right tool: **Jira Cloud Migration Assistant** (Server/DC → Cloud), **Project Import** (Server/DC), or **CSV/JSON import** for simple cases.
     3. **Test** in a staging environment.
     4. **Validate** data integrity (counts, links, attachments).
     5. **Communicate** with stakeholders and schedule downtime if needed.

     For Cloud-to-Cloud, use Atlassian's cloud-to-cloud migration tooling.

     **[⬆ Back to Top](#table-of-contents)**

160. ### What are common administrative responsibilities?

     - Creating and configuring **projects** and **schemes**.
     - Managing **users, groups, and roles**.
     - Maintaining **workflows, fields, and screens**.
     - Monitoring **system health** (indexing, performance, logs).
     - Applying **upgrades and patches** (Data Center).
     - Managing **apps/integrations** and their security.
     - Providing **training and support** and enforcing **governance**.

     **[⬆ Back to Top](#table-of-contents)**


## Automation

161. ### What is JIRA Automation?

     **Jira Automation** (formerly Automation for Jira) is a built-in **no-code rule engine** that automates repetitive tasks using a **Trigger → Condition → Action** paradigm. Rules can run on schedules, respond to issue events, or fire from external webhooks, performing actions like editing fields, sending notifications, or transitioning issues. It's available in all Cloud editions (with run limits on lower tiers) and in Data Center.

     **[⬆ Back to Top](#table-of-contents)**

162. ### What are automation rules?

     An **automation rule** defines how Jira responds to an event. Its components:

     - **Trigger** — the event that starts the rule (issue created, field changed, schedule).
     - **Conditions** — optional checks that must pass (e.g., issue type is Bug).
     - **Actions** — tasks executed if conditions pass (assign, comment, transition, create sub-task).
     - **Branches** — perform actions on **related** issues (parent, sub-tasks, linked, epic).

     Every rule begins with a single trigger and can chain multiple conditions, branches, and actions.

     **[⬆ Back to Top](#table-of-contents)**

163. ### What are triggers in automation?

     **Triggers** start a rule. Common ones:

     | Trigger | Fires when |
     | --- | --- |
     | **Issue created** | A new issue is created |
     | **Issue updated** | Any field changes |
     | **Issue transitioned** | Status changes |
     | **Field value changed** | A specific field changes (filterable by operation) |
     | **Issue commented** | A comment is added |
     | **Issue assigned** | Assignee changes |
     | **Scheduled** | On a CRON schedule / time |
     | **Incoming webhook** | A third party POSTs to a generated URL |
     | **Sprint created/started/completed** | Sprint lifecycle events |

     **[⬆ Back to Top](#table-of-contents)**

164. ### What are conditions in automation?

     **Conditions** narrow a rule's scope. Examples:

     - **Issue fields condition** — check a field value (`priority = High`).
     - **JQL condition** — filter issues with a JQL expression.
     - **User condition** — check group/role membership of a user.
     - **Related issues condition** — evaluate conditions on linked/parent issues.
     - **If/else block** — branch logic based on conditions.

     If a condition fails, the rule **stops** (or the else-branch runs), preventing unwanted actions.

     **[⬆ Back to Top](#table-of-contents)**

165. ### What are branches in automation?

     **Branches** let a rule act on issues **related** to the trigger issue — parent, sub-tasks, linked issues, epic, or stories in an epic. For example: *when an issue transitions to Done, branch to the parent and, if all sub-tasks are done, transition the parent to "Ready for Review."* Branches are what enable powerful roll-up and cascade automations across the issue hierarchy.

     **[⬆ Back to Top](#table-of-contents)**

166. ### What actions can automation perform?

     Common actions: **update issue fields, assign issue, add comment, add/remove watchers, create sub-tasks, send notifications** (email, Slack, Teams), **create or edit issues in other projects, link issues, transition status**, and **send web requests** to external APIs. You can also run **Forge/Connect** app actions or call REST APIs via the *Send web request* action — making automation a lightweight integration tool.

     **[⬆ Back to Top](#table-of-contents)**

167. ### How do you automatically assign issues?

     Use a rule with an **Issue created** trigger and an **Assign issue** action. Assignment strategies include **round-robin**, **balanced workload**, **component lead**, **reporter**, or a **specific user**. Example logic:

     ```
     WHEN issue created
     IF   priority = Highest AND issuetype = Bug
     THEN assign to on-call engineer
     ELSE assign to component lead (balanced workload)
     ```

     This removes manual triage and ensures urgent items reach the right person immediately.

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you automate issue transitions?

     Create a rule with a trigger (e.g., **pull request merged** or **all sub-tasks done**) and a **Transition issue** action, optionally guarded by conditions. Examples:

     - When a **PR is merged**, transition the issue to **In Review**.
     - When **all sub-tasks are Done**, transition the parent to **Done**.

     ```
     WHEN sub-task transitioned to Done
     BRANCH to parent
       IF all sub-tasks are Done
       THEN transition parent to "Ready for Review"
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### How do you automate notifications?

     Use actions like **Send email**, **Send Slack message**, **Send Microsoft Teams message**, or **Send web request**. Example: *when a Highest-priority issue is created, email the project lead and post to a Slack channel.* Smart values personalize the message:

     ```
     Send Slack message:
     ":rotating_light: {{issue.key}} ({{issue.priority.name}}) created by
      {{issue.reporter.displayName}}: {{issue.summary}}"
     ```

     **[⬆ Back to Top](#table-of-contents)**

170. ### How do smart values work?

     **Smart values** are variables that access issue fields, user info, and other data inside automation actions. They support text, date, and list manipulation:

     ```
     {{issue.summary}}
     {{issue.reporter.displayName}}
     {{issue.fields.customfield_12345}}
     {{now.plusDays(3)}}
     {{issue.subtasks.size}}
     {{#issue.components}}{{name}} {{/}}   ← iterate over a list
     ```

     They make rules dynamic — e.g., set a due date to `{{now.plusDays(3)}}` or build a comment from issue fields.

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do webhooks integrate with automation?

     - **Incoming webhook trigger** — an external service POSTs to a generated URL to start a rule; access the payload via `{{webhookData}}`.
     - **Outgoing (Send web request)** — the rule calls an external API (Slack, Jenkins, custom service).

     ```
     WHEN incoming webhook received
     THEN create issue with summary {{webhookData.title}}
          and description {{webhookData.body}}
     ```

     This two-way capability turns automation into a hub connecting Jira with the wider toolchain.

     **[⬆ Back to Top](#table-of-contents)**

172. ### How do you debug automation rules?

     - Use the rule's **Audit Log** — shows each run, success/failure, inputs/outputs, and error messages.
     - Add **Log actions** to print smart-value content for inspection.
     - **Manually trigger** or use test events to reproduce.
     - Check **rule usage** against your plan's execution limits.
     - Verify the **actor's permissions** — rules run as a user who must have rights for the actions.

     The Audit Log is the single most useful debugging tool for intermittent or failing rules.

     **[⬆ Back to Top](#table-of-contents)**

173. ### What are automation best practices?

     - Use **specific triggers** and **narrow conditions** to avoid unnecessary executions (and conserve run quota).
     - **Reuse logic** with global/component rules and variables.
     - **Prevent loops** — disable "Allow rule trigger" where appropriate.
     - **Document** each rule with clear names and descriptions.
     - **Group** related rules.
     - **Scope** rules to specific projects rather than global when possible.

     **[⬆ Back to Top](#table-of-contents)**

174. ### How do you prevent automation loops?

     - Turn **off "Allow rule trigger"** in rule details so the rule doesn't fire itself or other rules.
     - Add **conditions** to check whether a field actually changed before editing it.
     - Use a **label or flag field** to mark that a rule already ran, and skip if present.
     - Be cautious with rules that **edit fields they also trigger on** — the classic loop.

     Loops waste execution quota and can cascade across projects, so guarding against them is essential.

     **[⬆ Back to Top](#table-of-contents)**

175. ### How would you automate sprint-related activities?

     Examples:

     - **Sprint-end reminder**: *Scheduled trigger* one day before sprint end + *JQL condition* (unresolved issues exist) + *Send Slack message*.
     - **Epic roll-up**: *Sprint completed trigger* → add a comment on the epic summarizing completed points using smart values.
     - **Carry-over**: *Sprint completed trigger* → move unresolved issues to the next sprint automatically.

     ```
     WHEN sprint completed
     FOR each incomplete issue in the sprint
       THEN move to next sprint
     THEN comment on epic: "Sprint {{sprint.name}} done: {{...}} points completed"
     ```

     **[⬆ Back to Top](#table-of-contents)**


## Integrations

176. ### How does JIRA integrate with Git?

     Jira integrates with Git through providers like **Bitbucket, GitHub, and GitLab**. Connecting a repository lets Jira display **commits, branches, and pull requests** on issues (the Development panel), trigger **workflow transitions**, and enforce rules. For Bitbucket/GitHub Cloud you connect via **DVCS accounts** or the provider's marketplace app. The link is established by referencing the **issue key** (e.g., `PROJ-123`) in branch names and commit messages.

     **[⬆ Back to Top](#table-of-contents)**

177. ### How does JIRA integrate with GitHub?

     Use the **GitHub for Jira** app:

     1. Install from the Atlassian Marketplace.
     2. Connect your **GitHub organization** and select repositories.
     3. Commits, PRs, and branches referencing Jira keys appear in the **Development panel**.

     **Smart Commits** can transition issues or log time from commit messages:

     ```bash
     git commit -m "PROJ-123 #comment Fixed null pointer #time 2h"
     ```

     **[⬆ Back to Top](#table-of-contents)**

178. ### How does JIRA integrate with Bitbucket?

     Bitbucket Cloud integrates natively via **DVCS**. Connect your **workspace**, select repositories, and enable **Smart Commits**. Jira then shows commit, branch, and PR information, lets you **create branches directly from an issue**, and can **transition issues when PRs are merged** via workflow triggers. Bitbucket has the tightest Atlassian integration since both are Atlassian products.

     **[⬆ Back to Top](#table-of-contents)**

179. ### How does JIRA integrate with GitLab?

     Via the **GitLab for Jira** app: install it and connect your GitLab instance. The integration adds a **development panel** showing commit, branch, and merge-request details. Note that **Smart Commits are not available** for GitLab by default — to transition issues from GitLab events, use **Jira automation** with incoming webhooks or GitLab pipeline integrations instead.

     **[⬆ Back to Top](#table-of-contents)**

180. ### How does JIRA integrate with Jenkins?

     Jenkins integrates via the **Jenkins for Jira** plugin (and the Atlassian "Jira" Jenkins plugin). You can:

     - Link Jenkins **build jobs** to issues.
     - Update issue status based on **build outcomes**.
     - Use **post-build actions** to comment or change fields.
     - Display **build status, results, and artifacts** in the development panel.

     Combined with automation, a successful deployment can auto-transition linked issues to "Released."

     **[⬆ Back to Top](#table-of-contents)**

181. ### How does JIRA integrate with CI/CD pipelines?

     Jira's development integrations (Bitbucket, GitHub, GitLab, Jenkins) automatically update issue information when **builds, deployments, or releases** occur. The **Deployments** feature records environment and version details on issues. Automation rules can then **transition issues after successful deployments** or generate release notes. This gives end-to-end traceability from a story to the deployment that shipped it.

     **[⬆ Back to Top](#table-of-contents)**

182. ### What is Smart Commits?

     **Smart Commits** let you control Jira issues from **commit messages** in connected Bitbucket/GitHub repositories. The syntax is:

     ```
     <ignored text> <ISSUE_KEY> #command <arguments>
     ```

     Available commands: `#comment`, `#time`, and a transition name (e.g., `#close`, `#resolve`).

     ```bash
     # Comment on an issue
     git commit -m "PROJ-34 #comment fixed indentation issue"

     # Log work
     git commit -m "PROJ-34 #time 1w 2d 4h 30m Total work logged"

     # Transition and comment together
     git commit -m "PROJ-90 #close #comment Fixed this today"
     ```

     The committer's email must match a Jira user with the necessary permissions, and commands must be on one line.

     **[⬆ Back to Top](#table-of-contents)**

183. ### How does JIRA integrate with Confluence?

     Jira and Confluence integrate deeply (both Atlassian). You can:

     - **Embed** live Jira filters, charts, and roadmaps in Confluence pages.
     - **Create Jira issues** directly from Confluence.
     - **Link** Confluence pages to issues (shown in the issue's links panel).
     - Use Confluence to capture **requirements/specs** and link them to Jira work.

     This connects documentation (Confluence) with execution (Jira), keeping requirements and tasks traceable.

     **[⬆ Back to Top](#table-of-contents)**

184. ### How does JIRA integrate with Slack?

     Install the **Jira Cloud for Slack** app and connect your workspace:

     - Configure **notifications** for issue events (created, commented, updated) per channel.
     - Use `/jira create` to **create issues** from Slack.
     - **Comment** or **update fields** directly from Slack messages via interactive buttons.

     This keeps teams informed in chat and lets them act on issues without switching context.

     **[⬆ Back to Top](#table-of-contents)**

185. ### How does JIRA integrate with Microsoft Teams?

     Install the **Jira Cloud for Teams** app:

     - Use the **messaging extension** to create and search issues.
     - Configure **channel subscriptions** for issue notifications.
     - Use **actionable cards** to comment or change status from within Teams.

     It mirrors the Slack integration for organizations standardized on Microsoft 365.

     **[⬆ Back to Top](#table-of-contents)**

186. ### What are webhooks in JIRA?

     **Webhooks** are **HTTP callbacks** Jira sends when events occur (issue created, updated, etc.). On an event, Jira POSTs a JSON payload to a configured URL, enabling **push-based integration** with external systems (Slack, Jenkins, custom services). Configure them under **Administration → System → WebHooks**, optionally scoped with a JQL filter so only relevant events fire.

     ```json
     {
       "webhookEvent": "jira:issue_updated",
       "issue": { "key": "PROJ-123", "fields": { "summary": "..." } }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

187. ### How do REST APIs work in JIRA?

     Jira exposes a **REST API** (`/rest/api/3/` for Cloud, `/rest/api/2/` for Server/DC) supporting CRUD on issues, projects, workflows, and users. You authenticate via **API tokens (Basic Auth)** or **OAuth 2.0**, and responses are **JSON**.

     ```python
     import requests
     from requests.auth import HTTPBasicAuth

     BASE = "https://your-domain.atlassian.net"
     auth = HTTPBasicAuth("you@example.com", "<API_TOKEN>")

     r = requests.get(f"{BASE}/rest/api/3/issue/PROJ-123",
                      auth=auth, headers={"Accept": "application/json"})
     print(r.json()["fields"]["summary"])
     ```

     **[⬆ Back to Top](#table-of-contents)**

188. ### How do you authenticate Jira APIs?

     - **Jira Cloud**: **API token** with Basic Auth, or **OAuth 2.0 (3LO)** for apps. For Basic Auth, create a token under **Profile → Account Settings → Security**, concatenate `email:token`, base64-encode it, and send as the `Authorization: Basic` header.
     - **Data Center/Server**: username/password or **Personal Access Tokens (PAT)**.

     ```python
     import base64
     raw = "you@example.com:<API_TOKEN>"
     header = "Basic " + base64.b64encode(raw.encode()).decode()
     # Authorization: {header}
     ```

     Never embed tokens in client-side code; store them server-side and rotate regularly.

     **[⬆ Back to Top](#table-of-contents)**

189. ### What are common JIRA integration use cases?

     - **Auto issue creation** from monitoring/alerting tools (Datadog, PagerDuty).
     - **Syncing** issues with other ticketing systems (ServiceNow, Zendesk).
     - **Smart Commits** updating issues from code.
     - **Build/deploy status** flowing from CI/CD into Jira.
     - **Release notes** generated in Confluence from versions.
     - **Chat notifications** to Slack/Teams.
     - **Custom automations** via GitHub Actions or Jenkins.

     **[⬆ Back to Top](#table-of-contents)**

190. ### How do you troubleshoot integration failures?

     - Verify **connection settings** (webhook URLs, API tokens, app installs).
     - Confirm the user/account has the **necessary permissions**.
     - Review **logs** (webhook delivery logs, automation audit log, error responses).
     - Check the **issue key format** in commit messages (Smart Commits) and **email mapping**.
     - For REST, validate **endpoint URLs**, **authentication**, and **payload structure** (use Postman to reproduce).

     **[⬆ Back to Top](#table-of-contents)**


## JIRA APIs & Development

191. ### What is the Jira REST API?

     The **Jira REST API** provides programmatic access to Jira: creating, updating, deleting, and searching issues; managing projects, components, workflows, and users; transitioning issues; attaching files; and retrieving metadata. The base path is **`/rest/api/3`** (Cloud) or **`/rest/api/2`** (Server/DC). The v3 Cloud API uses the **Atlassian Document Format (ADF)** for rich-text fields like description and comments.

     **[⬆ Back to Top](#table-of-contents)**

192. ### How do you create issues using APIs?

     Send a **POST** to `/rest/api/3/issue` with a JSON payload. Description uses **ADF** in v3:

     ```python
     import requests
     from requests.auth import HTTPBasicAuth

     BASE = "https://your-domain.atlassian.net"
     auth = HTTPBasicAuth("you@example.com", "<API_TOKEN>")

     payload = {
       "fields": {
         "project":   {"key": "PROJ"},
         "summary":   "API-created issue",
         "issuetype": {"name": "Task"},
         "description": {
           "type": "doc", "version": 1,
           "content": [{
             "type": "paragraph",
             "content": [{"type": "text", "text": "Issue created via REST"}]
           }]
         }
       }
     }
     r = requests.post(f"{BASE}/rest/api/3/issue", json=payload, auth=auth,
                       headers={"Content-Type": "application/json"})
     print(r.status_code, r.json().get("key"))
     ```

     **[⬆ Back to Top](#table-of-contents)**

193. ### How do you update issues using APIs?

     Send a **PUT** to `/rest/api/3/issue/{issueIdOrKey}`. Use `fields` to set values and `update` for add/remove operations:

     ```python
     payload = {
       "fields": {"summary": "Updated summary"},
       "update": {"labels": [{"add": "needs-review"}]}
     }
     r = requests.put(f"{BASE}/rest/api/3/issue/PROJ-123",
                      json=payload, auth=auth,
                      headers={"Content-Type": "application/json"})
     print(r.status_code)  # 204 No Content on success
     ```

     To change status you must use the **transitions** endpoint, not the `status` field directly.

     **[⬆ Back to Top](#table-of-contents)**

194. ### How do you search issues using APIs?

     Send a **POST** to `/rest/api/3/search` with a JQL body (or use the newer `/search/jql` enhanced endpoint):

     ```python
     payload = {
       "jql": "project = PROJ AND status = \"In Progress\"",
       "fields": ["summary", "status", "assignee"],
       "maxResults": 50,
       "startAt": 0
     }
     r = requests.post(f"{BASE}/rest/api/3/search", json=payload, auth=auth,
                       headers={"Content-Type": "application/json"})
     data = r.json()
     for issue in data["issues"]:
         print(issue["key"], issue["fields"]["status"]["name"])
     ```

     Use `startAt`/`maxResults` (or `nextPageToken` on newer endpoints) to paginate large result sets.

     **[⬆ Back to Top](#table-of-contents)**

195. ### How do you transition issues using APIs?

     First **GET** the available transitions, then **POST** the chosen transition ID:

     ```python
     # 1. Discover available transitions
     t = requests.get(f"{BASE}/rest/api/3/issue/PROJ-123/transitions",
                      auth=auth, headers={"Accept": "application/json"}).json()
     for tr in t["transitions"]:
         print(tr["id"], tr["name"])

     # 2. Execute a transition (and set resolution)
     payload = {
       "transition": {"id": "31"},
       "fields": {"resolution": {"name": "Fixed"}}
     }
     r = requests.post(f"{BASE}/rest/api/3/issue/PROJ-123/transitions",
                       json=payload, auth=auth,
                       headers={"Content-Type": "application/json"})
     print(r.status_code)  # 204 on success
     ```

     Transition IDs are workflow-specific, so always discover them dynamically rather than hard-coding.

     **[⬆ Back to Top](#table-of-contents)**

196. ### How do you manage attachments through APIs?

     POST to `/rest/api/3/issue/{key}/attachments` with the **`X-Atlassian-Token: no-check`** header and `multipart/form-data`:

     ```python
     headers = {"X-Atlassian-Token": "no-check"}
     with open("/path/to/file.txt", "rb") as f:
         files = {"file": f}
         r = requests.post(f"{BASE}/rest/api/3/issue/PROJ-123/attachments",
                           auth=auth, headers=headers, files=files)
     print(r.status_code, [a["filename"] for a in r.json()])
     ```

     The `X-Atlassian-Token: no-check` header is **required** to bypass XSRF protection for file uploads.

     **[⬆ Back to Top](#table-of-contents)**

197. ### How do webhooks differ from APIs?

     | Aspect | REST API | Webhooks |
     | --- | --- | --- |
     | **Direction** | You call Jira (pull) | Jira calls you (push) |
     | **Trigger** | On demand | On events |
     | **Latency** | Requires polling | Near real-time |
     | **Use** | Query/modify data | Be notified of changes |

     Best practice is to **combine** them: a webhook **notifies** your system that something changed, and your system uses the **API** to fetch full details and act — avoiding constant polling.

     **[⬆ Back to Top](#table-of-contents)**

198. ### How do you secure API access?

     - Use **HTTPS** for all calls.
     - Store **tokens securely** (secrets manager, not source code).
     - Apply **least privilege** — minimal OAuth scopes / restricted service accounts.
     - **Rotate** tokens periodically.
     - Never embed tokens in **client-side** code.
     - For OAuth apps, store **refresh tokens server-side** and follow the auth flow securely.

     **[⬆ Back to Top](#table-of-contents)**

199. ### What are API rate limits?

     Jira Cloud imposes **rate limits** on API requests (cost-based, varying by endpoint and plan). Exceeding them returns **HTTP 429 Too Many Requests** with a `Retry-After` header. Clients should implement **exponential backoff** and **cache** results:

     ```python
     import time, requests

     def call_with_backoff(url, auth, max_retries=5):
         for attempt in range(max_retries):
             r = requests.get(url, auth=auth)
             if r.status_code != 429:
                 return r
             wait = int(r.headers.get("Retry-After", 2 ** attempt))
             time.sleep(wait)
         raise RuntimeError("Rate limit exceeded after retries")
     ```

     **[⬆ Back to Top](#table-of-contents)**

200. ### How do you build custom JIRA integrations?

     - Choose an **authentication** method (API token, OAuth 2.0).
     - Use **JQL** to fetch data, process it in your app, and write back via the API.
     - Use **webhooks** for event-driven flows.
     - For apps hosted within Atlassian, use **Forge** (serverless) or **Connect** (self-hosted).
     - Respect **rate limits**, **pagination**, and **permissions**.

     A typical pattern: webhook → your service → enrich/transform → REST API update, with retries and logging throughout.

     **[⬆ Back to Top](#table-of-contents)**

201. ### How do Forge apps differ from Connect apps?

     | Aspect | Forge | Connect |
     | --- | --- | --- |
     | **Hosting** | Atlassian infrastructure (serverless) | Your own infrastructure |
     | **Auth** | Handled by platform | You implement OAuth/JWT |
     | **UI** | UI Kit / Custom UI | Full custom (iframe) |
     | **Deployment** | `forge deploy` | Host and register descriptor |
     | **Capabilities** | Growing, some limits | Maximum flexibility |
     | **Best for** | Quick, secure cloud apps | Complex, fully custom apps |

     **Forge** is Atlassian's future-facing platform — easier and more secure; **Connect** offers maximum control at the cost of hosting and auth complexity.

     **[⬆ Back to Top](#table-of-contents)**

202. ### What is Atlassian Forge?

     **Forge** is Atlassian's **serverless platform** for building cloud apps and integrations. Apps are written in **Node.js**, deployed on Atlassian's infrastructure, and benefit from **managed authentication**, **UI components** (UI Kit / Custom UI), **functions and events**, and **fine-grained scopes**. Forge handles hosting, scaling, and security, making it the recommended path for new Jira/Confluence cloud apps.

     **[⬆ Back to Top](#table-of-contents)**

203. ### How do custom apps work in JIRA?

     Apps (**add-ons/plugins**) extend Jira's functionality:

     - **Cloud apps** are built with **Forge** or **Connect**.
     - **Data Center apps** use the **Atlassian Plugin SDK** and run as **OSGi modules** inside Jira.

     Apps can add custom fields, workflow conditions/validators, dashboard gadgets, REST endpoints, and UI panels. Users install them from the **Atlassian Marketplace**. Apps must be kept updated and vetted for security and performance impact.

     **[⬆ Back to Top](#table-of-contents)**

204. ### How do you debug API failures?

     - Inspect **HTTP status codes**: `400` (bad request), `401` (auth), `403` (permission), `404` (not found), `429` (rate limit).
     - Verify **authentication** (token, scopes) and required **headers** (`Content-Type: application/json`).
     - Validate **payload structure** (ADF for rich text in v3).
     - Reproduce with **Postman** or the API docs' "Try it" feature.
     - Read the **error response body** — Jira returns descriptive `errorMessages`/`errors`.

     **[⬆ Back to Top](#table-of-contents)**

205. ### What are API best practices?

     - **Paginate** with `maxResults`/`startAt` (or `nextPageToken`).
     - **Handle rate limits** with exponential backoff.
     - **Cache** responses where feasible.
     - **Filter server-side** with JQL rather than fetching everything.
     - **Validate payloads** locally before sending.
     - **Respect permissions** — operate only on issues the account can access.
     - Request **only the fields you need** (`fields` parameter) to reduce payload size.

     **[⬆ Back to Top](#table-of-contents)**


## Advanced JIRA Administration

206. ### What is an application link?

     An **application link (AppLink)** connects Jira to another Atlassian product (Confluence, Bitbucket, Bamboo) to enable **cross-application functions** — linking Confluence pages to issues, viewing Bitbucket commits in Jira, etc. AppLinks use **OAuth** for secure authentication and are configured under **Administration → Applications → Application Links**. They establish trust so the products can share data on the user's behalf.

     **[⬆ Back to Top](#table-of-contents)**

207. ### What are shared configurations?

     **Shared configurations** means using the same **schemes** (workflow, field, notification, permission) across multiple projects. Administrators can **copy a project's configuration** and apply it to new projects for consistency, reducing duplication and administrative overhead. This is the backbone of governance at scale — a small set of standard schemes applied broadly keeps a large instance maintainable.

     **[⬆ Back to Top](#table-of-contents)**

208. ### How do custom fields impact performance?

     Many custom fields **increase indexing time** and **slow issue create/edit** because Jira evaluates and stores values for each field on every operation. Mitigations:

     - Use custom fields **sparingly**; reuse existing fields.
     - Apply **field contexts** so a field only applies to specific projects/issue types.
     - **Audit** and remove unused fields periodically.
     - In Data Center, scale hardware/nodes to handle indexing load.

     Custom-field sprawl is one of the most common causes of gradual Jira slowdown.

     **[⬆ Back to Top](#table-of-contents)**

209. ### What is indexing in JIRA?

     Jira uses a **Lucene-based search index** to return issues quickly without hitting the database for every search. The index updates whenever issues are **created, updated, or transitioned**. Boards, filters, JQL, and gadgets all rely on this index. Configuration changes (fields, workflows, apps) can make the index **inconsistent**, requiring a re-index to restore accurate search results.

     **[⬆ Back to Top](#table-of-contents)**

210. ### What is re-indexing?

     **Re-indexing** rebuilds the search index to reflect configuration changes. After changes to **field configuration schemes, custom fields, apps, or time tracking**, the index may go out of sync, producing inaccurate search/filter results. Re-indexing can take **seconds to hours** depending on issue/comment volume. To minimize impact: make **all** configuration changes first, use **background re-indexing** (Data Center) where possible, and schedule during **off-peak hours**.

     **[⬆ Back to Top](#table-of-contents)**

211. ### When should a full re-index be performed?

     Perform a **full re-index** after major changes:

     - Adding/removing **custom fields**.
     - Modifying **field configuration schemes**.
     - **Installing/uninstalling** apps.
     - Encountering **search inconsistencies** (issues missing from filters/boards).

     In **Cloud**, indexing is automatic, so manual re-indexing is rarely needed. In **Data Center**, it's a deliberate maintenance task planned around downtime windows.

     **[⬆ Back to Top](#table-of-contents)**

212. ### What are performance bottlenecks in JIRA?

     - Very large numbers of **issues**.
     - Excessive **custom fields**.
     - **Complex JQL** (wildcards, text search, unbounded queries).
     - Large **attachments**.
     - Heavy or poorly written **plugins**.
     - **Insufficient hardware** or slow **database** queries.
     - Slow **indexing**, misconfigured **caches**, and network latency.

     **[⬆ Back to Top](#table-of-contents)**

213. ### How do you optimize JIRA performance?

     - **Minimize** custom fields and unused schemes.
     - **Optimize** JQL filters and dashboards (avoid wildcards, limit results, bound by date).
     - **Archive** old projects/issues.
     - **Upgrade** to the latest version; tune **JVM/DB** parameters.
     - **Monitor** logs and instrumentation to find slow queries.
     - For Data Center, **scale horizontally** by adding cluster nodes.

     **[⬆ Back to Top](#table-of-contents)**

214. ### What is database maintenance in JIRA?

     Regular DB maintenance keeps Jira healthy:

     - **Back up** the database (and attachments) on a schedule.
     - **Check integrity**, update **indexes and statistics**.
     - **Vacuum** (PostgreSQL) or **defragment/rebuild indexes** (SQL Server) on large tables.
     - Use **supported DB versions** and allocate sufficient resources/connections.
     - Monitor for **lock contention** and slow queries.

     This applies to **Server/Data Center**; Cloud database maintenance is handled by Atlassian.

     **[⬆ Back to Top](#table-of-contents)**

215. ### How do you handle large-scale JIRA instances?

     - Deploy **Jira Data Center** with **clustering** for scalability and high availability.
     - Use **load balancers**, separate **indexing** and **shared file systems**, and optimize the **database**.
     - **Archive** old data regularly.
     - Use **automation and scripts** (or the REST API) to manage large numbers of projects/issues.
     - Enforce **governance** to prevent custom-field and scheme sprawl.

     **[⬆ Back to Top](#table-of-contents)**

216. ### What are backup and restore strategies?

     - Schedule **regular backups** (daily full, incremental between) of database and attachments.
     - **Test restores** periodically — an untested backup is not a backup.
     - For **Cloud**, use the built-in **site export**.
     - For **Data Center**, maintain **cold/hot standby** nodes and replicate the shared file system.
     - Keep **configuration files** under version control.
     - Document **RTO/RPO** targets and validate them in DR drills.

     **[⬆ Back to Top](#table-of-contents)**

217. ### How do you perform upgrades?

     - **Cloud**: upgrades are handled automatically by Atlassian.
     - **Data Center/Server**: plan carefully —
       1. Review **release notes**.
       2. **Test in staging**.
       3. **Back up** the database and home directory.
       4. **Upgrade plugins** for compatibility.
       5. Perform the **upgrade**, then **re-index**.
       6. **Verify** functionality and **roll back** if needed.

     Follow Atlassian's official upgrade guide for your specific version path.

     **[⬆ Back to Top](#table-of-contents)**

218. ### What are cluster nodes in Data Center?

     A Data Center **cluster** consists of multiple **identical application nodes** behind a **load balancer**, sharing a common **database** and **shared file system**. Adding nodes increases **concurrent user capacity** and improves response times. All nodes are **active** (active-active), and the cluster coordinates caches and indexes so users get a consistent experience regardless of which node serves them.

     **[⬆ Back to Top](#table-of-contents)**

219. ### How does high availability work in JIRA Data Center?

     In Data Center, **all nodes are active** and serve traffic. If one node fails, the **load balancer routes traffic to the remaining nodes**, so users experience little or no disruption. Sessions may be sticky to a node, but **failover is seamless** thanks to the shared database and file system that keep data consistent across nodes. This eliminates the single point of failure inherent in the old single-node Server deployment.

     **[⬆ Back to Top](#table-of-contents)**

220. ### What monitoring tools are used for JIRA administration?

     - **Atlassian's built-in tools** — Audit logs, instrumentation, and (DC) the monitoring page.
     - **JMX metrics** for JVM/Jira internals.
     - **APM/SaaS** — New Relic, Datadog, AppDynamics for app and DB performance.
     - **Database monitoring** for slow queries and locks.
     - **Application logs** (`atlassian-jira.log`, `catalina.out`).
     - **Synthetic checks** and **alerting** on response time and error rates.

     **[⬆ Back to Top](#table-of-contents)**


## Real-World Scenario Based Questions

221. ### A workflow change is impacting thousands of issues. How would you handle it?

     1. **Clone** the workflow and make changes in a **draft** or copy.
     2. **Test** thoroughly in a **staging environment**.
     3. **Communicate** to stakeholders and schedule a maintenance window.
     4. Use **bulk operations** or the migration assistant to map issues to new statuses.
     5. **Publish** during **off-peak hours**.
     6. **Re-index** afterward and verify boards/filters/reports still work.

     The key risks are status mapping and re-index downtime, so plan and rehearse the mapping before touching production.

     **[⬆ Back to Top](#table-of-contents)**

222. ### Users cannot transition issues despite having access. How would you troubleshoot?

     - Check the **permission scheme** for **Transition Issues** permission.
     - Verify the user is in the **group/role** that grants it.
     - Inspect the **workflow** for **conditions** restricting the transition (e.g., reporter-only).
     - Use the **Permission Helper** to trace the path.
     - Confirm the issue is in the **expected status** and on the **current workflow** (not an old one after a migration).

     Often the cause is a **workflow condition** rather than a missing permission.

     **[⬆ Back to Top](#table-of-contents)**

223. ### Sprint reports are showing incorrect data. What would you investigate?

     - Ensure issues have the **correct sprint** assigned and weren't added/removed mid-sprint unexpectedly.
     - Check the **board filter** for excluded issue types (e.g., hidden sub-tasks).
     - Confirm **resolutions** are set — only **resolved** issues count as completed (the "Done but unresolved" trap).
     - Validate the **estimation field** (story points vs time) matches board config.
     - Verify the sprint wasn't **re-opened/duplicated**.

     **[⬆ Back to Top](#table-of-contents)**

224. ### Dashboard gadgets are not displaying results. What could be wrong?

     - The underlying **filter isn't shared** with the viewer, or returns **no results**.
     - The user **lacks permission** to view the issues.
     - The gadget is **misconfigured** (wrong statistic field or parameters).
     - **Rate limiting** is throttling refresh.
     - The gadget **isn't supported** in your Jira edition or an app is disabled.

     Start by running the gadget's **filter directly** as the affected user to isolate permission vs configuration issues.

     **[⬆ Back to Top](#table-of-contents)**

225. ### Automation rules are failing intermittently. How would you debug them?

     - Review the rule's **Audit Log** for errors and inputs.
     - Check **trigger conditions** match the actual events.
     - Inspect **conditions and smart values** for **null references** (a field missing on some issues).
     - Confirm the **actor's permissions** for the actions.
     - **Test manually** with sample issues.
     - Check **concurrency limits** and **loop-prevention** settings, and watch the **execution quota**.

     Intermittent failures often trace to **data variation** (some issues lack a field a smart value references).

     **[⬆ Back to Top](#table-of-contents)**

226. ### A project requires a custom approval workflow. How would you design it?

     - Add **approval statuses** (e.g., Awaiting Approval, Approved, Rejected) and transitions.
     - Use **conditions** to restrict approval transitions to an **Approvers** role.
     - Use **validators** to require necessary information.
     - Add **post-functions** to notify stakeholders and set fields.
     - Implement a **rework loop** (Rejected → In Progress).

     If using **Jira Service Management**, leverage built-in **approval steps** rather than building approvals from scratch — they handle approver assignment and SLA tracking natively.

     **[⬆ Back to Top](#table-of-contents)**

227. ### Teams want different workflows but common reporting. How would you implement it?

     Create **separate workflows** mapped to issue types (or projects) via **workflow schemes**, but ensure all statuses map to the **same three status categories** (To Do / In Progress / Done). Because reports like *Created vs Resolved* and cumulative flow rely on **categories**, metrics remain comparable across teams even when their detailed statuses differ. This balances team autonomy with consistent org-level reporting.

     **[⬆ Back to Top](#table-of-contents)**

228. ### JIRA performance has degraded after adding many custom fields. What would you do?

     - **Audit** custom fields; remove unused/redundant ones.
     - **Consolidate** similar fields.
     - Use **field contexts** so fields apply only to relevant projects/issue types.
     - **Re-index** the instance.
     - Evaluate **server resources**; for Data Center, **add nodes**.
     - Establish **governance** to prevent future sprawl (approval process for new fields).

     **[⬆ Back to Top](#table-of-contents)**

229. ### How would you migrate projects from one JIRA instance to another?

     - **Cloud → Cloud**: use the **Jira Cloud Migration Assistant** / cloud-to-cloud migration.
     - **Server/DC**: use **Project Import**, or **CSV/JSON** export-import for simpler cases.
     - In the target instance, pre-create matching **issue types, workflows, fields, and schemes**.
     - Use the **import wizard** to **map fields**.
     - **Validate** data integrity (issue counts, links, attachments) and **test in staging** first.

     **[⬆ Back to Top](#table-of-contents)**

230. ### How would you handle permission audits for a regulated environment?

     - Establish a **regular audit schedule**.
     - Use the **Permission Helper** and **User Management reports** to find users with elevated rights.
     - **Restrict admin** permissions to a minimal set of users.
     - Use **roles instead of groups** to avoid broad access.
     - **Document** changes and require an **approval process** for granting roles/permissions.
     - Leverage **audit logs** for traceability and evidence during compliance reviews.

     **[⬆ Back to Top](#table-of-contents)**

231. ### How would you integrate JIRA with a DevOps pipeline?

     - Connect Jira to **version control** (Bitbucket/GitHub), **CI/CD** (Jenkins), and **deployment** tools.
     - Use **Smart Commits** to update issues from commits.
     - Configure **automation**: transition issues when PRs merge or deployments succeed.
     - Use the **Deployments** feature to show deployment status on issues.
     - **Auto-generate release notes** from version information.

     The outcome is full **traceability** from requirement → code → build → deploy, with issue status reflecting real pipeline state.

     **[⬆ Back to Top](#table-of-contents)**

232. ### How would you create release tracking across multiple teams?

     - Use **versions** and **release dates** in each project.
     - Build a **cross-project board or dashboard** showing progress by version.
     - Use **Advanced Roadmaps** to plan releases spanning teams with release vehicles and dependencies.
     - Use JQL aggregating across projects:

     ```sql
     fixVersion = "v1.0" ORDER BY project, status
     ```

     Display the results in a **Two-Dimensional Filter Statistics** gadget (status × project) for a clean release readiness view.

     **[⬆ Back to Top](#table-of-contents)**

233. ### How would you manage dependencies across projects?

     - Use **linked issues** with **Blocks**/**Depends On** link types.
     - Visualize with **Advanced Roadmaps** dependency view.
     - Create **JQL filters** to list blocked issues.
     - Use **automation** to notify when a blocking issue resolves.
     - In large programs, group dependencies under **initiatives/features**.
     - Assign a **dependency owner** and hold **regular dependency reviews**.

     **[⬆ Back to Top](#table-of-contents)**

234. ### How would you design JIRA for a SAFe implementation?

     - Use **hierarchy levels**: Portfolio → Program → Epic → Story (via Advanced Roadmaps).
     - Model **Initiatives/Capabilities** above epics.
     - Treat each **Agile Release Train (ART)** as a project (or set of projects) and link them.
     - Plan **Program Increments (PIs)** with fixed PI sprints.
     - Use **WSJF** to prioritize the backlog.
     - Track dependencies and capacity across teams in a single plan.

     **[⬆ Back to Top](#table-of-contents)**

235. ### How would you build executive-level dashboards?

     Create a dashboard with high-level gadgets: **issue counts by status/priority**, **Created vs Resolved**, **Velocity**, **high-priority defect count**, and **release progress**. Use **filters spanning multiple projects**, **Pie/Bar charts**, and a brief **narrative**. Highlight **blockers and risks** prominently. Keep it focused on **outcomes** (delivery pace, quality, risk) rather than task-level detail leadership won't read.

     **[⬆ Back to Top](#table-of-contents)**

236. ### How would you track production incidents using JIRA?

     - Create a **Production Incident** issue type.
     - Use a dedicated **workflow**: Identified → Investigating → Mitigating → Resolved → Closed.
     - Add fields for **impact, root cause, workaround**.
     - Use **automation** to notify on-call engineers and integrate with **PagerDuty/Opsgenie**.
     - Track **MTTA** (mean time to acknowledge) and **MTTR** (mean time to resolve) via reports.

     Jira Service Management's incident management features can extend this with on-call schedules and alerting.

     **[⬆ Back to Top](#table-of-contents)**

237. ### How would you configure JIRA for ITSM processes?

     - Use **Jira Service Management**.
     - Configure a service project with **request types** (Incident, Service Request, Change, Problem).
     - Set up **queues, SLAs**, and **knowledge base** integration.
     - Implement **approval steps** in workflows.
     - Configure **automation** for escalations and notifications.
     - Provide a **customer portal** for end users to raise and track requests.

     **[⬆ Back to Top](#table-of-contents)**

238. ### How would you automate defect triage?

     Create a rule triggered on **issue created**:

     ```
     WHEN issue created
     IF   issuetype = Bug
       IF severity = Critical THEN assign to on-call engineer, set due date +4h
       ELSE assign to triage lead, add label "needs-triage"
     THEN add comment acknowledging receipt
     THEN (optional) link to related incident record
     ```

     This ensures every bug is acknowledged, categorized, and routed automatically with appropriate urgency.

     **[⬆ Back to Top](#table-of-contents)**

239. ### How would you manage thousands of projects efficiently?

     - Use **standardized schemes** (permissions, notifications, workflows).
     - Use **project templates** for new projects.
     - **Automate project creation** via scripts or the REST API.
     - **Archive** unused projects.
     - Use **categories** for grouping and **roles/groups** managed centrally.
     - Consider **multiple instances** or **Data Center** for very large scale.

     ```python
     # Bulk-create projects from a CSV via REST API (sketch)
     import csv, requests
     from requests.auth import HTTPBasicAuth
     auth = HTTPBasicAuth("admin@example.com", "<API_TOKEN>")
     BASE = "https://your-domain.atlassian.net"

     with open("projects.csv") as f:
         for row in csv.DictReader(f):
             payload = {
                 "key": row["key"], "name": row["name"],
                 "projectTypeKey": "software",
                 "leadAccountId": row["lead_account_id"],
                 "assigneeType": "PROJECT_LEAD",
             }
             r = requests.post(f"{BASE}/rest/api/3/project", json=payload, auth=auth)
             print(row["key"], r.status_code)
     ```

     **[⬆ Back to Top](#table-of-contents)**

240. ### How would you troubleshoot missing notifications?

     - Check the **notification scheme** for the specific **event**.
     - Ensure the recipient is included (watcher, assignee, role, group).
     - Verify the issue isn't **restricted by issue security**.
     - Check the user's **email preferences** and **spam filters**.
     - Use the **Notification Helper** to test whether a user *should* be notified.
     - For email delivery errors, check **SMTP/outgoing mail** settings and logs.

     **[⬆ Back to Top](#table-of-contents)**


## Senior Engineer / Product Company Questions

241. ### How do you use JIRA in a microservices-based organization?

     - Create **separate projects per microservice**, or group them logically by **domain**.
     - Use **shared schemes** for consistency.
     - Use **cross-project boards/dashboards** to manage dependencies.
     - **Integrate** with CI/CD and infrastructure-as-code.
     - Use **components or labels** to identify services.
     - Use **automation** to update multiple services and track coordinated releases.

     The goal is per-service autonomy with org-level visibility into dependencies and releases.

     **[⬆ Back to Top](#table-of-contents)**

242. ### How do you track technical debt in JIRA?

     - Create a **Technical Debt** issue type or a dedicated **label**.
     - Record refactoring tasks, cleanup items, and outdated dependencies.
     - Add **story points** to represent effort.
     - Maintain a **separate backlog or board** for visibility.
     - **Allocate sprint capacity** to debt each iteration (e.g., 15–20%).
     - Use **dashboards** to visualize the debt trend over time.

     Making debt explicit and tracked prevents it from being perpetually deprioritized.

     **[⬆ Back to Top](#table-of-contents)**

243. ### How do you manage cross-team dependencies?

     - Establish a **governance model** and a clear **link taxonomy** (Blocks / Depends On).
     - Use a **shared board or roadmap** to visualize dependencies.
     - Assign a **dependency owner** for each cross-team link.
     - Use **JQL** to list blocked issues and **automation** to alert when blockers resolve.
     - Conduct **regular dependency reviews** (e.g., Scrum of Scrums).

     **[⬆ Back to Top](#table-of-contents)**

244. ### How do you structure epics for large programs?

     - Define epics around **business capabilities or deliverables**.
     - Group related stories under each epic.
     - For programs spanning teams, use a **higher-level entity (Initiative)** and link epics across projects.
     - **Limit epic scope** to deliverable increments (avoid never-ending epics).
     - Use **consistent naming** conventions.
     - **Review and split** epics when they grow too large to track meaningfully.

     **[⬆ Back to Top](#table-of-contents)**

245. ### How do you use Advanced Roadmaps for portfolio planning?

     - Create a **plan** including multiple projects and teams.
     - Define a **hierarchy**: Initiatives → Epics → Stories.
     - Enter **target dates**, **team capacities**, and **releases**.
     - Use the **timeline view** to sequence work, surface conflicts, and manage dependencies.
     - Evaluate **what-if scenarios** by adjusting scope or timing without committing.
     - Generate **program-level reports** and publish changes back to issues when ready.

     **[⬆ Back to Top](#table-of-contents)**

246. ### How do you measure team productivity using JIRA metrics?

     Use a balanced set of metrics:

     | Metric | What it shows |
     | --- | --- |
     | **Velocity** | Points completed per sprint (planning aid) |
     | **Cycle/Lead Time** | Speed from start/creation to done |
     | **Throughput** | Issues completed per sprint |
     | **Burndown/Burnup** | Progress vs plan and scope |
     | **Escaped Defects** | Quality of delivered work |
     | **Resolution Time** | How long issues take to close |

     Crucially, use metrics to spot **trends and improvement**, not to **compare teams** unfairly — relative point scales make cross-team comparison meaningless.

     **[⬆ Back to Top](#table-of-contents)**

247. ### What JIRA metrics should engineering managers monitor?

     - **Backlog growth** (Created vs Resolved).
     - **Bug aging** (average age of open defects).
     - **Sprint velocity** and **committed vs completed**.
     - **Cycle time** and **WIP distribution**.
     - **Number of blocked issues**.
     - **Deployment frequency** (via CI/CD integration).

     Visualize these on dashboards and watch **trends** rather than single data points, which can be noisy.

     **[⬆ Back to Top](#table-of-contents)**

248. ### How do you avoid misuse of story points?

     - Ensure points represent **relative effort/complexity**, **not hours**.
     - **Never** tie points to performance reviews or compensation — that incentivizes inflation.
     - Use **consistent reference stories** so estimates stay calibrated.
     - **Review estimation accuracy** regularly in retrospectives.
     - **Educate stakeholders** on the purpose of points (capacity planning, not productivity scoring).

     Misused points corrupt velocity and erode trust in estimation.

     **[⬆ Back to Top](#table-of-contents)**

249. ### How do you establish JIRA governance across an enterprise?

     - Define **governance policies** for project creation, scheme usage, workflows, fields, naming conventions, and permissions.
     - Establish a **Jira Center of Excellence** with admins and team representatives.
     - Provide **guidelines and training**.
     - **Enforce scheme reuse** and limit custom-field creation.
     - **Audit** for compliance regularly.
     - Use **automation** to enforce rules (e.g., required fields) and **document** decisions.

     **[⬆ Back to Top](#table-of-contents)**

250. ### If you joined a company with a poorly configured JIRA setup, what improvements would you prioritize first?

     A pragmatic, sequenced approach:

     1. **Assess current state** — inventory projects, schemes, workflows, custom fields, and permissions.
     2. **Clean up schemes** — consolidate duplicate workflows/fields, remove unused schemes.
     3. **Standardize processes** — define templates for projects, workflows, and fields.
     4. **Improve permissions** — enforce least privilege; use roles instead of groups for project permissions.
     5. **Implement reporting** — create useful dashboards and shared filters.
     6. **Integrate with dev tools** — connect version control, CI/CD, and chat.
     7. **Train users** on best practices.
     8. **Plan for scalability** — consider Data Center or separate instances for large scale.

     Start with **assessment and cleanup** (quick wins, reduced confusion) before standardization and scaling.

     **[⬆ Back to Top](#table-of-contents)**

---

### Disclaimer

The questions and answers in this repository are a curated summary of commonly asked JIRA interview questions. They cover concepts from foundational JIRA usage through senior-level administration, automation, integration, and enterprise governance. There is no guarantee that these exact questions will appear in any given interview — the purpose is to help you rapidly review key concepts and build deep understanding. For the most authoritative and current details, consult Atlassian's official documentation, as JIRA Cloud evolves continuously. Contributions and corrections are welcome.

Good luck with your interview 😊

---

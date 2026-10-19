# Help Desk and Service Desk Pocket Interview Guide

**Stages 1 to 5: 86 interview questions with answers, follow-ups, scenarios, and revision tools**

**By Jiwan Bhattarai**  
**IT Education Nepal - कम्प्युटर शिक्षा सबैका लागि**

***

* **Author:** Jiwan Bhattarai. Published by IT Education Nepal.
* **How to cite (IEEE):** J. Bhattarai, *Help Desk and Service Desk Pocket Interview Guide*, IT Education Nepal, 2026.
* **Feedback and corrections:** [contact@iteducationnepal.org](mailto:contact@iteducationnepal.org)
* **Trademarks:** ITIL® is a registered trademark of the PeopleCert group. Microsoft, Windows, Microsoft 365, Entra, Intune, Apple, macOS, Okta, Atlassian, Jira Service Management, and ServiceNow are trademarks of their respective owners. This handbook is independent and not endorsed by any of these organizations.

> [!IMPORTANT]
> **Disclaimer:** This handbook supports interview preparation. It is not official procedure. The interview answers, scenarios, and student stories are original teaching examples. Always follow your employer's policies, security rules, and service management process.

***

## Mission and Motivation

Let us create 10,000 quality IT engineers, from Nepal to the world.  
Learn how to learn. Learn by doing.

**Jiwan Bhattarai**  
CCIE #60261 | CEH | Mentor | Education Activist

***

## About IT Education Nepal

**IT Education Nepal (ITEN)**  
**कम्प्युटर शिक्षा सबैका लागि

IT Education Nepal (ITEN) is a volunteer-driven, nonprofit initiative that provides practical computer and IT education to Nepali-speaking learners worldwide. It was founded on the belief that geography, language, or financial circumstances should not limit access to technology education.

ITEN supports learners at all stages, from basic computer literacy and school or college computer science courses to professional IT and career-focused training. Our learning areas include Linux, CompTIA, networking, programming, cybersecurity, cloud technologies, artificial intelligence (AI), emerging technologies, technical interview preparation, and career awareness sessions.

Beyond technical education, ITEN offers mentorship, career guidance, and a supportive global technology community where learners and professionals can share knowledge, support one another, and grow together.

Our mission is simple: to make quality IT education practical, accessible, and applicable.

Let us learn and grow together.  


| Channel | Link |
| :--- | :--- |
| Website | [https://iteducationnepal.org](https://iteducationnepal.org) |
| YouTube | [https://www.youtube.com/@iteducationnepal](https://www.youtube.com/@iteducationnepal) |
| GitHub | [https://github.com/ITEN-Non-Profit](https://github.com/ITEN-Non-Profit) |
| LinkedIn | [https://www.linkedin.com/company/iteducationnepal](https://www.linkedin.com/company/iteducationnepal) |
| Facebook community | [https://www.facebook.com/groups/iteducationnepal](https://www.facebook.com/groups/iteducationnepal) |
| Telegram | [https://t.me/iteducationnepal](https://t.me/iteducationnepal) |

***

## About the Author

**Jiwan Bhattarai**  
**CCIE #60261 | CEH | Founder, IT Education Nepal | Education Activist**

Jiwan Bhattarai is a Senior Network Security Engineer and Consultant and a Cisco Certified Internetwork Expert (CCIE #60261) with more than 17 years of experience in networking, cybersecurity, and IT infrastructure. His professional experience spans government, healthcare, financial services, enterprise, telecommunications, and data-center environments across Nepal, India, the UAE, and on international projects.

Beyond engineering, Jiwan is passionate about expanding access to practical IT education and helping learners turn curiosity into real-world skills, confidence, and career opportunities. Through IT Education Nepal (ITEN) and Networking Nepal, he supports students, early-career professionals, career changers, and aspiring IT professionals with free technical education, mentorship, and community-based learning, with particular attention to learners facing financial, language, or access barriers.

His long-term mission is to help develop 10,000 skilled IT professionals from Nepal who are prepared to contribute to and compete in the global technology industry.

* **LinkedIn:** [https://www.linkedin.com/in/jiwanbhattarai](https://www.linkedin.com/in/jiwanbhattarai)

***

## How to Use This Handbook

This book is for university students, including first-year students, L1 and entry-level support candidates, and early L2 candidates reviewing the fundamentals.

| Stage | Focus | Questions |
| :--- | :--- | :--- |
| **Stage 1** | Role reality, ITSM, ticketing, and customer communication | [Q1 to Q20](#stage-1-role-reality-itsm-and-ticketing-and-customer-communication) |
| **Stage 2** | Troubleshooting and endpoint support | [Q21 to Q38](#stage-2-troubleshooting-and-endpoint-support) |
| **Stage 3** | Identity, access, networking, and VPN | [Q39 to Q58](#stage-3-identity-access-networking-and-vpn) |
| **Stage 4** | Microsoft 365, security, and knowledge management | [Q59 to Q74](#stage-4-microsoft-365-security-and-knowledge-management) |
| **Stage 5** | Interview performance and final revision | [Q75 to Q86](#stage-5-interview-performance-and-final-revision) |

### Practice method

1. Read the question and cover everything below it.
2. Give your answer aloud in about 30 to 45 seconds, in your own words.
3. Uncover the follow-up and scenario, and answer those too.
4. Check yourself against the mentor's advice.

* **Honesty:** Use only real examples from study, lab, volunteer, or work. Say "I would" for anything you have not done, and "I did" only for real experience.
* **Local rules:** Your employer sets permissions, priority labels, approvals, support hours, escalation routes, and closure rules. The answers outline safe standard practice.
* **Citations:** Each bracketed number, such as [[1]](#ref-1), is a clickable link to its source. You do not need to cite reference numbers in an interview.
* **Conventions:** Example times use the 24-hour clock in local time unless marked UTC. Product names are examples, not requirements.

***

## Contents

* [Mission and Motivation](#mission-and-motivation)
* [About IT Education Nepal](#about-it-education-nepal)
* [About the Author](#about-the-author)
* [How to Use This Handbook](#how-to-use-this-handbook)
* [List of Tables](#list-of-tables)
* [Stage 1: Role reality, ITSM and ticketing, and customer communication](#stage-1-role-reality-itsm-and-ticketing-and-customer-communication)
  * [1.1 Role reality (Q1 to Q4)](#11-role-reality-q1-to-q4)
  * [1.2 ITSM and ticketing (Q5 to Q14)](#12-itsm-and-ticketing-q5-to-q14)
  * [1.3 Customer communication (Q15 to Q20)](#13-customer-communication-q15-to-q20)
* [Stage 2: Troubleshooting and endpoint support](#stage-2-troubleshooting-and-endpoint-support)
  * [2.1 Troubleshooting method (Q21 to Q24)](#21-troubleshooting-method-q21-to-q24)
  * [2.2 Windows support (Q25 to Q30)](#22-windows-support-q25-to-q30)
  * [2.3 Printers and peripherals (Q31 to Q34)](#23-printers-and-peripherals-q31-to-q34)
  * [2.4 macOS and managed devices (Q35 to Q38)](#24-macos-and-managed-devices-q35-to-q38)
* [Stage 3: Identity, access, networking, and VPN](#stage-3-identity-access-networking-and-vpn)
  * [3.1 Identity and access (Q39 to Q48)](#31-identity-and-access-q39-to-q48)
  * [3.2 Network foundations (Q49 to Q54)](#32-network-foundations-q49-to-q54)
  * [3.3 Diagnostic tools and VPN (Q55 to Q58)](#33-diagnostic-tools-and-vpn-q55-to-q58)
* [Stage 4: Microsoft 365, security, and knowledge management](#stage-4-microsoft-365-security-and-knowledge-management)
  * [4.1 Microsoft 365 applications and files (Q59 to Q64)](#41-microsoft-365-applications-and-files-q59-to-q64)
  * [4.2 Security and safe support practice (Q65 to Q70)](#42-security-and-safe-support-practice-q65-to-q70)
  * [4.3 Knowledge management (Q71 to Q74)](#43-knowledge-management-q71-to-q74)
* [Stage 5: Interview performance and final revision](#stage-5-interview-performance-and-final-revision)
  * [5.1 Introducing yourself and showing evidence (Q75 to Q78)](#51-introducing-yourself-and-showing-evidence-q75-to-q78)
  * [5.2 Mistakes, feedback, and uncertainty (Q79 to Q82)](#52-mistakes-feedback-and-uncertainty-q79-to-q82)
  * [5.3 Escalation and closing the interview (Q83 to Q86)](#53-escalation-and-closing-the-interview-q83-to-q86)
  * [5.4 Rapid-fire revision](#54-rapid-fire-revision)
  * [5.5 Tools and commands](#55-tools-and-commands)
  * [5.6 Mock interview and job description](#56-mock-interview-and-job-description)
  * [5.7 Seven-day revision plan](#57-seven-day-revision-plan)
* [Quick Reference: Priority Grid and Templates](#quick-reference-priority-grid-and-templates)
* [Glossary](#glossary)
* [References](#references)

***

## List of Tables

* [Table 1. Rapid-fire fundamentals](#table-1-rapid-fire-fundamentals)
* [Table 2. Rapid-fire diagnostic judgment](#table-2-rapid-fire-diagnostic-judgment)
* [Table 3. Tools and commands for revision](#table-3-tools-and-commands-for-revision)
* [Table 4. Twenty-minute mock interview](#table-4-twenty-minute-mock-interview)
* [Table 5. Matching evidence to the job description](#table-5-matching-evidence-to-the-job-description)
* [Table 6. Seven-day revision plan](#table-6-seven-day-revision-plan)
* [Table 7. Example priority matrix (illustrative only)](#table-7-example-priority-matrix-illustrative-only)
* [Table 8. Ticket work note template (see Q8)](#table-8-ticket-work-note-template-see-q8)
* [Table 9. Escalation message template (see Q12, Q38)](#table-9-escalation-message-template-see-q12-q38)
* [Table 10. User update, fix time unknown template (see Q18)](#table-10-user-update-fix-time-unknown-template-see-q18)
* [Table 11. Shift handover template (see Q11)](#table-11-shift-handover-template-see-q11)

***

## Stage 1: Role reality, ITSM and ticketing, and customer communication

This stage covers the role's responsibilities, how ITSM and tickets work, and how to communicate with users.

* **Approach:** User reports issue -> understand -> assess impact -> prioritize -> troubleshoot -> communicate -> resolve or escalate -> verify -> document -> close
* **Boundary:** Your employer sets permissions, priority labels, approvals, support hours, escalation routes, and closure rules. Serious service impact or a suspected security issue is promptly escalated via the urgent escalation route.

***

### 1.1 Role reality (Q1 to Q4)

#### Q1. What does a Service Desk analyst actually do?
* **Answer:** A Service Desk analyst helps users get back to work and handles IT service requests. I would listen, document the issue, assess its impact, and use approved checks or support guides. The user should know what happens next, and the ticket should reflect it. If another team is needed, include relevant evidence in the handover. Before closing, I confirm the service works and record the outcome [[1]](#ref-1).
* **Follow-up:** *Is a help desk different from a service desk?*  
  Help Desk often refers to technical support. A service desk can also handle service requests and communication. Titles vary, so check the job description for the actual duties.
* **Scenario:** A caller says, "Email is broken." Ask: "What happens when you try to send or open a message? Is it stopping all your work?" An error description tells you more than "broken."
* **Mentor's advice:** Show the entire support journey. Fixing a device is only one part of it.

#### Q2. What would you handle at L1, and where would you stop?
* **Answer:** At L1, I collect details, review known issues, and follow approved troubleshooting steps. When my role allows, I handle password resets, standard software requests, and basic device support. I verify identity before any account action and confirm required approvals. If a step requires access I do not have, creates wider risk, or goes beyond the guide, I stop and escalate [[1]](#ref-1), [[2]](#ref-2).
* **Follow-up:** *What changes when someone moves into early L2?*  
  They may investigate further and have more permissions, within the limits the employer sets. Change controls and escalation still apply.
* **Scenario:** An online post says to turn off security software to fix an application. Do not try it. Record the symptom and ask the responsible team for an approved next step.
* **Mentor's advice:** Name a safe action and a clear stopping point. Avoid claiming unlimited access.

#### Q3. How would you organize the start of your shift?
* **Answer:** The handover and current service notices come first. Then I review assigned tickets and the shared queue for immediate impact, approaching targets, and promised updates. Tickets awaiting users or other teams still need follow-up. I take work according to the queue rules and confirm the owner of anything unclear, reassessing priorities as new information arrives [[1]](#ref-1).
* **Follow-up:** *Would you always work on the oldest ticket first?*  
  No. Impact, urgency, due targets, and queue rules come first. Among similar priorities, age can help determine the order.
* **Scenario:** You find a routine request, an update promised for 09:00, and new reports of a site outage. Alert the incident contact promptly, then arrange coverage for the update.
* **Mentor's advice:** Mention waiting tickets and handovers. Both are easy to overlook.

#### Q4. How can you show job readiness without paid support experience?
* **Answer:** I would be clear that I am a fresher, then show how I would handle a user issue, supported by a real college, lab, or volunteer example: what I observed, what I checked, how I confirmed the result, and when I needed help. If I haven't used the employer's ticketing system, I would say so and explain the workflow I understand [[1]](#ref-1).
* **Follow-up:** *Have you used ServiceNow or Jira Service Management?*  
  If not, say so: "I have not used those tools yet. I understand how to record, prioritize, update, route, and close tickets, and I would need training on your setup."
* **Scenario:** An interviewer asks for a difficult user story, and you have none. Say you have not handled that at work, then explain your approach or use a real study example, labeled as study.
* **Mentor's advice:** Use "I would" for proposed actions and "I did" only for experience.

[Back to Contents](#contents)

***

### 1.2 ITSM and ticketing (Q5 to Q14)

#### Q5. What is ITSM, and why do we use tickets?
* **Answer:** IT service management (ITSM) is how an organization plans, delivers, and supports IT services. At the Service Desk, it means using repeatable methods for handling incidents and requests. A ticket keeps the issue, owner, priority, actions, and updates in one record so that people can work together and nothing is forgotten. Phone and chat support are still recorded as required [[3]](#ref-3), [[4]](#ref-4), [[5]](#ref-5).
* **Follow-up:** *Is ITIL the same as ITSM?*  
  No. ITSM is the work of managing IT services. ITIL is guidance organizations can use for that work. A ticketing tool supports the process but is not the process itself.
* **Scenario:** A colleague asks for a quick fix in chat. Capture the work in a ticket under the intake rules. If action is urgent, act first and complete the fields afterward.
* **Mentor's advice:** Explain what a ticket helps people do. Tool names alone do not answer the question.

#### Q6. What is the difference between an incident and a service request?
* **Answer:** An incident is an unplanned interruption or reduction in service quality. A service request asks for something normally provided, such as approved software, information, or access. My first question: has an existing service failed, or is something new needed? The answer determines the workflow. Some employers classify cases differently, such as password resets, so their definitions apply [[3]](#ref-3), [[6]](#ref-6).
* **Follow-up:** *A user cannot open a shared folder. Which type is it?*  
  If access that should work has stopped, it is a possible incident. If the user needs access for the first time, it is an access request.
* **Scenario:** A new starter requests a licensed application. Confirm the application and business need, then follow the approval and licensing checks. Requesting it today does not make it an outage.
* **Mentor's advice:** Ask whether something failed or whether something new is needed.

#### Q7. How are an incident, a problem, and a change different?
* **Answer:** An incident is the interruption or degradation of service. A problem is the cause, or possible cause, of one or more incidents. A change alters something that can affect a service. At L1, I aim to restore service safely. When an issue repeats, I link the history and flag the pattern. A fix requiring a controlled change goes through the change process; a ticket is not permission [[3]](#ref-3), [[7]](#ref-7).
* **Follow-up:** *Must you find the root cause before resolving every incident?*  
  No. An approved workaround can restore service, with its limitations documented. Restored service does not prove the cause is resolved.
* **Scenario:** An application keeps failing despite a temporary fix. Include references to earlier tickets and failure times, and ask the responsible team to review the pattern.
* **Mentor's advice:** Stay at the analyst level: spot and report patterns.

#### Q8. What information belongs in a useful ticket?
* **Answer:** Include who needs help and how to reach them, the affected service or device, and a clear symptom. Then include the exact error, start time, business impact, and whether others are affected, followed by the priority reason, checks and results, status, owner, and next action. Keep facts and guesses separate. Exclude passwords, verification codes, and unrelated personal information [[1]](#ref-1).
* **Follow-up:** *What makes a good short description?*  
  Specific wording, such as "One user cannot print to the third-floor printer," is better. "Printer issue" is too vague.
* **Scenario:** Example note: "10:20 local time: One user cannot print to Printer 3. Two colleagues can. No error is shown. Printer 2 works as a workaround. Local queue check next." Add the time zone for cross-region teams.
* **Mentor's advice:** Record what each check showed so the next analyst can continue.

#### Q9. How do you decide a ticket's priority?
* **Answer:** I assess impact and urgency, then apply the employer's priority rules. Impact is how much business activity is affected; urgency is how soon harm becomes serious. That means asking who is affected, what work is blocked, whether a workaround exists, and whether a real deadline applies. Put the facts in the ticket, and review the priority when the facts change. Seniority or repeated calls alone do not raise the priority [[8]](#ref-8).
* **Follow-up:** *Can an issue affecting one person still be urgent?*  
  Yes. That person may be handling time-critical business work. I would assess the consequences and the deadline rather than count users.
* **Scenario:** Twenty people report a minor display issue. One user cannot submit a business-critical file by a fixed deadline. Compare workarounds and consequences before determining the order.
* **Mentor's advice:** Explain the facts behind your decision. See the example grid in the [Quick Reference](#table-7-example-priority-matrix-illustrative-only).

#### Q10. What is an SLA, and what would you do if a target is at risk?
* **Answer:** A service-level agreement (SLA) sets agreed service expectations, such as response and resolution targets within defined hours. A response target is not a fixed deadline. I monitor the applicable target and act before missing it. If progress is blocked, I record the reason, escalate through the agreed route, and update the user, without promising a repair time simply because a target exists [[3]](#ref-3), [[9]](#ref-9).
* **Follow-up:** *Does putting a ticket on hold stop the SLA clock?*  
  Only if the configured SLA rules allow it. A status should never change solely to hide a delay.
* **Scenario:** A ticket nears its resolution target, and the next check requires access from another team. Send the evidence and flag the risk now. Tell the user when they will next hear from support.
* **Mentor's advice:** Acknowledgment, updates, and resolution can each have different targets.

#### Q11. What does owning a ticket mean?
* **Answer:** When I own a ticket, it always has a clear next action and a responsible owner. Notes and user updates stay current, dependencies are followed up on, and the status is accurate. A transfer follows the handover rules and clearly names the next owner. Escalation doesn't always transfer technical ownership, and sending a message isn't the same as completing a handover.
* **Follow-up:** *What would you leave at the end of your shift?*  
  Current impact, checks and results, pending action, owner, due target, and the next promised update. Confirm urgent handovers via the required channel.
* **Scenario:** Your shift ends while a ticket is waiting on a vendor. Record the vendor reference, last response, open question, and next follow-up time, then confirm who will track it next.
* **Mentor's advice:** Describe ownership as visible follow-through, not as personally fixing everything.

#### Q12. When would you escalate, and what would you send?
* **Answer:** Escalate when the next step exceeds my permissions or skills, approved checks have not helped, the impact is high, or a target is at risk. Suspected security issues should be escalated promptly via the security route. The escalation includes the symptom, affected service, impact, timing, error, checks and results, evidence, and exactly what help is needed. The user is told when their next update is due [[7]](#ref-7).
* **Follow-up:** *What is functional versus hierarchical escalation?*  
  Functional escalation goes to a team with the right expertise or access. Hierarchical escalation goes to someone with authority over a service risk or blocker.
* **Scenario:** Example: "Four users cannot sign in to the finance application since 14:10 UTC. Web access works. Approved sign-in checks did not help. No known outage exists. Please check application authentication. Users expect an update at 14:40 UTC."
* **Mentor's advice:** "Not working, please fix" wastes the next team's time.

#### Q13. How would you respond to several reports of the same outage?
* **Answer:** I check whether the reports share a service, location, start time, or error, and review current notices. If the pattern suggests a wider impact, I promptly notify the designated incident contact. The system links related tickets to the main incident, and users receive approved updates. Only roles whose procedures allow it can declare a major incident or message the whole organization [[7]](#ref-7).
* **Follow-up:** *Would you close the extra tickets as duplicates?*  
  Only under the linking and closure rules. Each affected user still needs communication and a record of impact. Linking is not closure.
* **Scenario:** Six callers from different offices report the same application error within ten minutes. Capture the shared details, notify the incident contact, and give callers the agreed message without guessing the cause.
* **Mentor's advice:** Show early recognition and prompt reporting.

#### Q14. How do you resolve and close a ticket properly?
* **Answer:** I retest the original task and ask the user to confirm they can work again. The record documents the action taken, the test result, and any limitations of the workaround. Then the employer's resolution and closure process applies; some systems keep a ticket resolved for a period before closing it. If the user does not reply, the contact-attempt rules apply. Silence alone does not prove a fix worked [[10]](#ref-10).
* **Follow-up:** *What if the issue returns after closure?*  
  I would capture the new impact and timing, reopen or create a linked ticket as the workflow requires, and review earlier actions.
* **Scenario:** A test page prints, but the user's original document still fails. The task is not restored. Continue within scope or escalate with that result.
* **Mentor's advice:** Verify the user's task, and keep resolution and closure distinct.

[Back to Contents](#contents)

***

### 1.3 Customer communication (Q15 to Q20)

#### Q15. How would you begin a support conversation?
* **Answer:** I introduce myself, let the user explain, then narrow the focus. A useful opener is "What were you trying to do, and what happened instead?" Next, I confirm the affected service, start time, scope, and impact on work, then restate the key point in plain terms. Identity checks come before any account action or remote access. Ask one clear question at a time.
* **Follow-up:** *How do you avoid making the user repeat everything?*  
  I review the existing ticket first, summarize what is known, and ask only about gaps or changes.
* **Scenario:** The user says, "Nothing works." Ask: "Which task are you trying to finish right now?" Then ask what they see. A broad complaint becomes something you can investigate.
* **Mentor's advice:** Start open, then narrow the questions.

#### Q16. How would you help a user who is not technical?
* **Answer:** I use everyday language and take it one step at a time, explaining why each step matters when helpful. After each step, I ask what the user sees rather than assuming it worked. Before a restart or any other action that interrupts work, I check for unsaved work and agree on timing. Remote help uses the approved tool and consent process, and the user enters their own passwords.
* **Follow-up:** *What if the user still cannot follow the steps?*  
  I would rephrase or use an approved visual guide, then arrange remote or in-person help if needed, without blaming the user.
* **Scenario:** Instead of "Terminate the process," say: "This will close the application. Is any work still unsaved?" If they are unsure, pause and check recovery options first.
* **Mentor's advice:** "Do you understand?" often masks confusion. Ask what happened instead.

#### Q17. How would you deal with an angry user?
* **Answer:** I let them explain the impact and keep my tone steady, for example: "I understand this is stopping your work. Let me confirm what is affected so I can take the right next step." I avoid arguing, blaming another team, or promising an instant fix. Instead, I explain what I can do now and when I will update them. For abusive or threatening calls, I follow workplace procedure.
* **Follow-up:** *What if they demand your manager?*  
  I would follow the complaint or escalation process with a factual summary, while keeping the service issue's owner and next action.
* **Scenario:** A caller says, "You people never fix anything." Reply: "You have had to contact us again. I will review the earlier ticket so we do not repeat steps." Then confirm the current symptom.
* **Mentor's advice:** Acknowledge the specific disruption. Avoid saying "calm down."

#### Q18. How do you set expectations when you do not know the fix time?
* **Answer:** I share what is known, what is still being checked, and what happens next, then provide a realistic update time via the agreed channel: "The application team is investigating. There is no confirmed repair time yet. I will update you by 15:00, even if nothing changes." That time must align with support coverage. Any verified workaround should include its limitations.
* **Follow-up:** *What if you miss an update you promised?*  
  Contact the user promptly, acknowledge the missed update, share the current facts, set a new time, and fix the gap that caused it.
* **Scenario:** The resolver team has nothing new at the update time. Send a factual update anyway: "Investigation continues. No repair time is confirmed. The workaround remains available. Next update at 16:00."
* **Mentor's advice:** Promise only updates you can deliver.

#### Q19. What if a user asks you to bypass a support rule?
* **Answer:** I clarify the business need and explain the safe path. Access without approval isn't possible until the approval is recorded, so I help the user reach the right approver or follow the documented urgent-request process. Sharing credentials, skipping identity checks, or granting extra access under pressure is not an option. Genuine urgency is escalated for an authorized decision [[2]](#ref-2).
* **Follow-up:** *What if their manager says it is fine?*  
  I would verify that the manager is an authorized approver and that the approval is recorded. A verbal okay does not replace the process.
* **Scenario:** A caller claims to be an executive and demands a reset without verification. Use the approved verification route. If they cannot complete it, escalate and leave the account unchanged.
* **Mentor's advice:** Offer the next safe step so the request can still move forward.

#### Q20. What would you do if you gave a user the wrong instruction?
* **Answer:** I acknowledge it promptly and stop anything that could make it worse. Next, I review what the user did and whether it affected work or data. If I can correct it safely within my role, I do; otherwise, I escalate with the facts. The ticket gets an accurate update, the user knows the next step, and the incident goes through the reporting process.
* **Follow-up:** *How would you explain it without losing the user's trust?*  
  Directly: "The step I gave you was not correct here. Please pause while I check the safe next action." Then follow through.
* **Scenario:** You asked for a restart before checking for unsaved work. Pause changes, determine what was lost, and seek approved recovery help. Do not promise recovery or hide the instruction.
* **Mentor's advice:** Show honesty, an impact check, and recovery.

[Back to Contents](#contents)

***

## Stage 2: Troubleshooting and endpoint support

This stage covers a repeatable troubleshooting method, Windows and macOS support, printers and peripherals, and managed devices.

* **Approach:** Understand the task -> assess impact -> check for known issues -> narrow the cause -> choose a safe check -> apply an approved fix or escalate -> verify the original task -> document.
* **Boundary:** Tool access does not grant permission for every action. Repairs, recovery keys, service restarts, drivers, updates, and management changes follow the approved route. Specialist teams handle advanced repairs and fleet administration.

***

### 2.1 Troubleshooting method (Q21 to Q24)

#### Q21. Walk me through your troubleshooting method.
* **Answer:** First, I confirm what the user was trying to do, what happened, and how the work is affected. Then I review known issues and recent changes, form a likely explanation, and choose a safe check to test it. I record each result before the next change. If a fix is within my permissions, I apply it and test the original task. When I reach my limit, I send the evidence to the right team.
* **Follow-up:** *Why change only one thing at a time?*  
  It links the result to the action. Multiple changes together may restore service without showing which one helped, or may cause a new fault.
* **Scenario:** A laptop cannot use an external display. Before changing drivers, check the display's power, input, and cable, one part at a time. If a new cable restores the picture, record it and test the user's normal setup.
* **Mentor's advice:** For each check, state what its result would tell you.

#### Q22. How would you determine whether a fault is local or widespread?
* **Answer:** I compare what works with what fails: one application, the whole device, one user, or several users. When possible, I test another approved file, application, device, or connection, changing one factor at a time. This narrows the scope but does not prove the cause. Before making local changes, I check service notices, because local fixes will not help with a wider outage.
* **Follow-up:** *Would you ask someone else for their password to test?*  
  No. An authorized user can sign in themselves if the test is allowed. Otherwise, I would use an approved test account if the procedure permits.
* **Scenario:** One document fails to open, but a new blank document opens in the same application. Investigate that file or its access next, rather than reinstalling the application or replacing the laptop.
* **Mentor's advice:** Use comparisons to narrow the fault. "It worked elsewhere" is a clue, not a diagnosis.

#### Q23. What would you do if you could not reproduce an intermittent issue?
* **Answer:** I would ask for the exact time, frequency, steps, and conditions, and check whether it occurs after sleep, docking, with a particular file, or another repeatable event. An approved screenshot or relevant logs from that time would help, without unnecessary personal data. I would note that I couldn't reproduce it and agree on what to capture next time. Serious impact or a pattern requiring deeper analysis would be escalated.
* **Follow-up:** *Would you close it because it works during your call?*  
  Not for that reason alone. I would record the successful test and the remaining uncertainty, then follow the team's closure rules.
* **Scenario:** A screen goes blank only after the laptop wakes from its dock. Ask whether the built-in display still works, note the dock model and wake time, and arrange an approved repeat test.
* **Mentor's advice:** Record the conditions around the failure. "Could not reproduce" still needs a next step.

#### Q24. How would you use Event Viewer without guessing the cause?
* **Answer:** I start with the reported failure time and the affected component, then review Application or System events near that time. For each relevant entry, I record the source, event ID, time, and message, and compare them with what the user saw. An error entry is a clue, not proof. An approved guide helps me interpret it, and I send only relevant evidence to another team [[11]](#ref-11).
* **Follow-up:** *What is the difference between Task Manager and Event Viewer?*  
  Task Manager shows current processes and resource use. Event Viewer shows recorded events; the first suits a live slowdown, while the second suits investigating a past crash.
* **Scenario:** A crash happened at 11:42, but the first red error is from yesterday. Match the time and source before using any entry. An event ID alone does not identify a fix.
* **Mentor's advice:** Keep logs intact. Do not clear them or treat every warning as a fault.

[Back to Contents](#contents)

***

### 2.2 Windows support (Q25 to Q30)

#### Q25. A user says their Windows PC is slow. What would you check?
* **Answer:** I would ask whether the whole PC or a specific task is slow and when it started. During the slowdown, I check Task Manager for CPU, memory, and disk activity. I also check free storage, pending restarts, and recent changes, and compare the activity with the user's work rather than treating a single high reading as a fault. Then I try a small, approved action, such as closing an unused application after saving work, and retest [[11]](#ref-11), [[12]](#ref-12).
* **Follow-up:** *Does high memory use mean the PC needs more RAM?*  
  Not by itself. I would check whether the slowdown aligns with sustained memory pressure. Memory is working space; drive space is storage. Evidence comes before any upgrade.
* **Scenario:** Disk activity rises during an approved update and settles when it finishes. Record whether the slowdown ends as well. Do not turn off the update service to lower the reading.
* **Mentor's advice:** Do not end an unfamiliar process just because it is busy.

#### Q26. How would you handle an application that freezes or crashes?
* **Answer:** I first check whether only that application is affected and what action triggers the failure. Then I capture the error and version and look for known issues. If the app still responds, I save work and close it normally. If I need to end it, I explain the risk to unsaved work and follow the approved procedure. After reopening, I test the same task. Repeated failures require evidence, not repeated forced closes.
* **Follow-up:** *Would reinstalling the application be your first fix?*  
  No. Reinstalling can affect settings, local data, licensing, or add-ins. I would first check the scope, review approved repair options, and confirm authorization.
* **Scenario:** A drawing application crashes only when exporting one project. Test a permitted sample project and capture the error. Do not overwrite the original or assume the installation is damaged.
* **Mentor's advice:** Distinguish a freeze from a crash, and protect unsaved work first.

#### Q27. What is a Windows service, and when would you restart one?
* **Answer:** A Windows service is a background program that supports a system or application function. I check its status in the Services console against the support guide; some services run only when needed, so a stopped state is not always a fault. A restart requires permission, a procedure that calls for it, and a check of dependencies and who could be affected. Afterward, I test the function and record the result [[11]](#ref-11).
* **Follow-up:** *What if the service stops again immediately?*  
  I would capture the error and event details, then escalate if the guide offers no safe next step. Repeated restarts obscure the pattern and interrupt work.
* **Scenario:** A guide suggests restarting the local Print Spooler. Confirm you are on the user's device, understand the effect on local jobs, and check authorization. A print server restart affects many users.
* **Mentor's advice:** Checking a service and changing it are different actions.

#### Q28. How would you handle a failed or pending Windows update?
* **Answer:** I record the update identifier, the error code, and the current state (downloading, installing, or waiting to restart). Next, I check power, connectivity, storage, and the employer's update guidance. For an approved restart, the user saves work, and we agree on timing. I avoid interrupting an active installation. If it keeps failing, I escalate to endpoint support rather than retrying or changing update policies [[13]](#ref-13).
* **Follow-up:** *Would you immediately remove an update after a new fault?*  
  No. Timing suggests a link but does not prove one. I would check for known issues and gather evidence. Removal follows the approved process.
* **Scenario:** A user says an update is "stuck," but progress is still changing. Check the elapsed time against official guidance. Do not force a power-off because it is slower than expected.
* **Mentor's advice:** A managed device is not a personal test machine.

#### Q29. A laptop will not start properly. What do you check first?
* **Answer:** I first determine whether there is no power, no picture, or a failure during Windows startup. I check the power lights, the charger, the display, and any error messages. Approved external checks include a compatible, known-working charger or display. If Windows shows a stop code, I record it along with recent changes. Recovery steps that could affect data, encryption, or settings are escalated [[13]](#ref-13), [[14]](#ref-14).
* **Follow-up:** *What if the screen asks for a BitLocker recovery key?*  
  I would follow the approved identity-and-recovery-key process. Encryption is never bypassed, and the key never goes into a chat or ticket.
* **Scenario:** The laptop has power and an external monitor works, but the built-in display stays blank. That points to the display path. Record the comparison instead of reporting that Windows will not start.
* **Mentor's advice:** Distinguish power, display, and startup faults before proposing a repair.

#### Q30. How would you help a user whose system drive is nearly full?
* **Answer:** I first identify which drive is full and review storage categories before deleting anything. I use only approved cleanup options, reviewing what they remove, and I back up or safely store needed files first. I leave system folders, user profiles, and unfamiliar application data untouched. Afterward, I check free space and retest the failed task, such as saving a file or installing an update [[15]](#ref-15).
* **Follow-up:** *Is deleting a cloud-synced file a safe way to free local space?*  
  Not necessarily. It may delete the file from the synced service as well. Removing only the local copy is a different, supported option.
* **Scenario:** Downloads contains large files, and the user doesn't know which ones are needed. Review the files with the user or the owner. Do not clean the entire folder because it is large.
* **Mentor's advice:** Keeping needed data matters more than free space.

[Back to Contents](#contents)

***

### 2.3 Printers and peripherals (Q31 to Q34)

#### Q31. A user cannot print. How would you narrow down the issue?
* **Answer:** I confirm the intended printer and whether one document, one application, or all printing fails. Then I check power, paper, any display errors, the connection, and the selected printer and queue. Where permitted, a simple test document, another approved printer, or another user's result helps isolate whether the issue is document-, device-, printer-, or shared-service-related. After a fix, I test the original document [[16]](#ref-16).
* **Follow-up:** *If a test page prints, is the issue resolved?*  
  Not always. The test shows one printing path works. The user's original document and application may still fail.
* **Scenario:** Several users cannot print to one shared printer, but other printers work. Check that printer and its shared path, and report the common impact before touching anyone's driver.
* **Mentor's advice:** Start with scope and the selected printer.

#### Q32. What would you do with a print job stuck in the queue?
* **Answer:** I check the printer status and whether the queue is local or shared, then confirm with the user that they can cancel and resend the affected job. If that does not clear it, I follow the printing guide. Restarting a service or clearing queue files may require elevated permissions and can affect other jobs, so a shared queue is never cleared without authorization. Finally, the user resends once [[16]](#ref-16).
* **Follow-up:** *Why not keep pressing Print until something appears?*  
  Duplicate jobs may all print when the fault clears. Existing jobs are checked first, then one controlled retry.
* **Scenario:** One large job is blocking a shared queue. Record its owner, time, and affected users. If you lack permission, ask print support to act rather than canceling other people's work.
* **Mentor's advice:** State whose jobs your action could affect.

#### Q33. How would you troubleshoot a USB device, dock, or external monitor?
* **Answer:** I identify the specific device, connection, and symptom, then check power, cables, ports, and the monitor's input. If allowed, I try a known-working, compatible cable or port, or connect directly to the laptop to test whether the dock is involved. Device Manager shows recognition or errors. I use only approved drivers and firmware, and I change one device or driver at a time [[17]](#ref-17).
* **Follow-up:** *Does every USB-C cable support an external display?*  
  No. The cable, port, and dock must all support video. A cable that charges a laptop may not carry a display signal.
* **Scenario:** A monitor works directly from the laptop but fails through a dock. Compare the dock's power, ports, and cabling. This narrows the fault to that path without proving the dock is broken.
* **Mentor's advice:** A comparison only helps when the replacement is compatible.

#### Q34. How would you check a microphone or camera that does not work?
* **Answer:** First, check the selected device, the physical mute switch or camera cover, and the connection. Then check the application's device selection, operating system permissions, and browser site permissions. An approved recording or camera test helps distinguish an application issue from a device problem. Managed settings and driver changes follow the support process, not a workaround [[18]](#ref-18).
* **Follow-up:** *What if the device works in one application but not another?*  
  I would check the failing application's device selection and permissions. A working test confirms the device works but doesn't rule out all compatibility issues.
* **Scenario:** A headset microphone is detected, but the meeting app uses the laptop microphone. Select the correct input with the user and run an approved test, not a recording of a real meeting.
* **Mentor's advice:** Check selection, mute, and permissions before replacing hardware.

[Back to Contents](#contents)

***

### 2.4 macOS and managed devices (Q35 to Q38)

#### Q35. What macOS basics would you check before supporting a Mac?
* **Answer:** I confirm the model, chip, and macOS version in About This Mac. Finder manages files, System Settings manages device settings, and Activity Monitor shows processes and resource usage. As with Windows, I start with the symptom and a safe comparison. Shortcuts, permissions, and recovery steps vary by model and version, so I use the matching guide and the organization's procedures on a managed Mac [[19]](#ref-19), [[20]](#ref-20).
* **Follow-up:** *How would you handle an app blocked by a security warning?*  
  I would capture the message, confirm the app's approved source, and use the software request route. The warning is never overridden, and management profiles are never removed.
* **Scenario:** A colleague suggests an Intel Mac reset procedure for a Mac with Apple silicon. Check the model and current Apple guidance first. Similar symptoms do not mean the same procedure applies.
* **Mentor's advice:** Show you can find system details and use the right guide. Do not invent Mac experience.

#### Q36. A Mac is slow, or an app is not responding. What would you do?
* **Answer:** I check whether one app or the whole Mac is affected and what the user was doing. I check Activity Monitor for CPU usage and memory pressure during the issue, and I also check storage and recent changes. An app that can quit normally is closed after saving work. If Force Quit is necessary, I explain the risk of losing unsaved changes first. Then I reopen, retest, and investigate repeated failures [[21]](#ref-21), [[22]](#ref-22).
* **Follow-up:** *Does a large amount of used memory prove a Mac is short of RAM?*  
  No. The memory pressure graph and the actual slowdown matter more than used memory alone.
* **Scenario:** A user sees the spinning wait cursor during a large export, but progress continues. Check that it is still working before forcing it to quit. Record any repeated hangs on the same file.
* **Mentor's advice:** Force Quit can lose work and does not explain the cause.

#### Q37. What does L1 support do with a managed device or company app portal?
* **Answer:** A managed device receives organizational settings, approved apps, and security requirements via a management service. At L1, I confirm the correct device record and, if my role permits, review its status, last check-in, and any app errors. I might initiate an approved portal sync. Missing apps and policy changes are escalated to endpoint support. Enrollment and security requirements are never removed to clear a message [[23]](#ref-23).
* **Follow-up:** *Does a portal sync guarantee that an app will appear immediately?*  
  No. A sync triggers a check-in, but availability depends on assignment, eligibility, licensing, and processing time.
* **Scenario:** An approved app is missing from Company Portal. Confirm the work account, device, connection, and portal status, and record the sync result. Ask the responsible team to check instead of downloading an unapproved installer.
* **Mentor's advice:** Wipe, retire, and unenroll are not routine troubleshooting steps.

#### Q38. After a Windows update, one user's app keeps crashing. What would you do?
* **Answer:** I confirm the app, update, crash time, impact, and any unsaved work at risk. After checking for known issues, I test the same task with an approved sample file and ask whether others are affected. I capture the error, app and Windows versions, and relevant events. If the guide allows, I test a safe restart or an approved repair. If crashes continue, I escalate with the results, without assuming the update caused it [[13]](#ref-13).
* **Follow-up:** *What would useful escalation evidence sound like?*  
  "One laptop crashes when exporting from the design app. A sample file also fails. An approved restart did not help. Versions, update identifier, crash time, and event details are attached."
* **Scenario:** The user offers to let you turn off antivirus or uninstall the update. Explain that both require authorization. If no safe action remains, send the evidence and offer an approved workaround.
* **Mentor's advice:** Timing alone does not prove the update caused the crash.

[Back to Contents](#contents)

***

## Stage 3: Identity, access, networking, and VPN

This stage covers identity systems, account recovery, access requests, network foundations, diagnostic commands, and VPN support.

* **Approach:** Confirm the user and task -> assess impact -> identify the failed step -> review evidence -> take an authorized action or escalate -> verify access -> document.
* **Boundary:** Verify identity before any account recovery or access change. Keep passwords, recovery secrets, and verification codes out of tickets. Changes to authentication policies, DNS, routing, and shared infrastructure go to the responsible team.

***

### 3.1 Identity and access (Q39 to Q48)

#### Q39. What are Active Directory, Microsoft Entra ID, and Okta?
* **Answer:** All three manage identities and access, but they are distinct systems. Active Directory Domain Services commonly supports Windows domain accounts, computers, and policies. Microsoft Entra ID is a cloud identity service used with Microsoft 365 and other applications. Okta is another identity platform for sign-on and authentication. At L1, I identify which system manages the account and application before acting, since connected systems may not update instantly [[24]](#ref-24).
* **Follow-up:** *Is Microsoft Entra ID just a new name for Active Directory?*  
  It is the new name for Azure Active Directory, not for Active Directory Domain Services. Use the correct name and check the employer's setup.
* **Scenario:** A user can sign in to their Windows laptop but not a cloud application. Confirm which identity service the application uses. A laptop sign-in does not prove that every identity service works.
* **Mentor's advice:** Explain each system's purpose. Do not claim they share a single console or password behavior.

#### Q40. What is the difference between authentication and authorization?
* **Answer:** Authentication verifies who is signing in. Authorization determines what that identity can access or do. A user can sign in successfully and still lack permission for a folder or application. I ask where the failure occurs and capture the exact message. A sign-in failure points to the account and authentication process. A denial after sign-in points to the access request and permission path, not a password reset [[25]](#ref-25).
* **Follow-up:** *Where does single sign-on fit?*  
  Single sign-on (SSO) lets one session reach several integrated applications. Each application still needs the right permissions, and policy may require another step. SSO does not mean access to everything.
* **Scenario:** An employee signs in to the company portal but sees no tile for an application. Check whether it is assigned to them. Password resets will not create a missing assignment.
* **Mentor's advice:** Locate the failure: proving identity, meeting a sign-in requirement, or holding permission.

#### Q41. How would you reset a user's password safely?
* **Answer:** I verify identity through the approved process, confirm the exact account and service, and check whether self-service recovery is available. If authorized to reset it, I use the correct identity system and the secure handover procedure for any temporary credential. The user sets their own new password. I verify sign-in and record the action without storing passwords or codes. Failed verification goes to the recovery escalation route [[26]](#ref-26).
* **Follow-up:** *Would you reset a synchronized account in any available console?*  
  No. The system that controls the password, synchronization, and any writeback settings determines where and when a reset is supported. I would use the designated route.
* **Scenario:** A caller gives an employee's name and department and asks for a temporary password to be sent to a new personal address. Those details do not verify identity. Use the approved verification and delivery route.
* **Mentor's advice:** Knowing an employee's details does not prove they own the account.

#### Q42. What would you do with an account that keeps locking out?
* **Answer:** I confirm the account, identity system, exact message, and lockout timing. After verifying identity, I check the account state within my permissions. Unlocking and resetting the password are distinct actions, so the guide for the actual condition applies. If it locks again, I ask about recent password changes and any devices or apps with saved credentials, then escalate with evidence if needed. I never weaken the lockout policy [[27]](#ref-27).
* **Follow-up:** *Could a user still sign in to a laptop while offline?*  
  In some domain setups, cached sign-in information allows offline access. That does not prove the current password or account state is valid.
* **Scenario:** The account locks again whenever an older phone reconnects. Saved credentials are worth checking. Confirm the pattern and use the approved procedure without assuming the phone is the only cause.
* **Mentor's advice:** Treat repeated lockouts as a pattern. Report unfamiliar sign-in activity through the security route.

#### Q43. What is MFA, and how would you troubleshoot a failed MFA step?
* **Answer:** Multifactor authentication (MFA) uses more than one type of evidence to verify identity, such as a password and an approved authenticator. First, I confirm that the user started the sign-in and identify the failing method. Then I check the account, device connectivity, and the exact message; for time-based codes, the device time may matter. If allowed, an already registered alternative may be used. Recovery follows the verified process. MFA is never disabled [[28]](#ref-28).
* **Follow-up:** *Do two passwords count as two authentication factors?*  
  No. Both are something the user knows. MFA combines different factor types, and some passwordless methods also meet MFA requirements.
* **Scenario:** A user waits for a push notification, but the sign-in page asks for an app code. Confirm the method shown and guide the user to enter the code themselves, never reading it to you.
* **Mentor's advice:** Never approve a prompt or collect a one-time code for the user.

#### Q44. A user has lost their MFA phone. How would you restore access?
* **Answer:** I would use the approved identity verification and account recovery process and check whether the user has another registered method. Removing a lost method or registering a new one is handled only within my role or is routed to identity support. Report the lost device through the required process. Never add a new phone number just because the caller urgently requests it [[28]](#ref-28), [[29]](#ref-29).
* **Follow-up:** *What if the user receives MFA prompts they did not initiate?*  
  They should not approve them and should report it through the security route. If one was already approved, I would record it and escalate promptly.
* **Scenario:** A caller says their phone is lost and wants a password reset and a new MFA method. Treat it as full account recovery. A password reset alone doesn't allow you to replace the second factor.
* **Mentor's advice:** Recovery changes who can prove ownership. Keep the identity check strong under pressure.

#### Q45. How would you handle a request for folder or application access?
* **Answer:** I confirm the exact resource, access level, business need, and authorized approver, and verify the approved request before making any changes. If my role allows it, I use the standard group or application assignment for that access. Then I verify the result with the user and document what changed. A new permission design or wider access than approved goes to the resource owner or identity team [[30]](#ref-30).
* **Follow-up:** *Why use a standard access group instead of copying a colleague's permissions?*  
  Standard groups are easier to review. A colleague may hold extra or historical permissions. I would use the approved role and check any end date for temporary access.
* **Scenario:** A user wants edit rights because a colleague has them, but the approval covers read-only access. Apply only the approved level, or ask for clarification.
* **Mentor's advice:** The requester and the authorized approver may be different people.

#### Q46. What would you do during new-starter onboarding?
* **Answer:** I start with an authorized onboarding request containing the person's details, start date, role, and access. After checking for an existing account, I follow the approved naming and provisioning process. Depending on my permissions, this may include managing devices, standard apps, and group assignments. I use the secure process for first sign-in and MFA setup, and I test the work tasks with the user. I hand over unfinished items clearly [[30]](#ref-30).
* **Follow-up:** *What if the person starts today but an approval is missing?*  
  I would flag the impact to the approver via the urgent request process and continue approved tasks without granting unapproved access.
* **Scenario:** A manager emails an application list for a new starter. Confirm it uses the required authorization route. Do not create a second account because the first is not visible in one tool.
* **Mentor's advice:** Show preparation, approval, and a working first sign-in. Not every onboarding task belongs to L1.

#### Q47. How would you handle an employee's offboarding request?
* **Answer:** I act only on an authorized request and confirm the identity, effective time, and required tasks. The offboarding checklist covers access removal, session handling, device return, and any approved data handoff. I complete the steps assigned to my role and track the rest with the responsible teams, recording completion and exceptions promptly. Accounts and mailboxes are never deleted as a shortcut because retention requires separate approval [[31]](#ref-31).
* **Follow-up:** *Does deactivating an account immediately end every application session?*  
  Not necessarily. Existing sessions and app-specific access may require separate action, so I would complete the full checklist.
* **Scenario:** A departure takes effect at 17:00 in another region. Confirm the time zone and authorized timing before scheduling. For urgent action, use the escalation route and record who owns it.
* **Mentor's advice:** Offboarding is time-sensitive. Do not invent retention rules.

#### Q48. A user signs in but receives an access denied message. What would you check?
* **Answer:** I capture the resource, account, time, and the exact message, and confirm whether access worked before or if it is new. Then I check the approved assignment and any status my role can see. A denial can stem from missing permissions, a device requirement, or a sign-in policy, so the wording alone does not reveal the cause. Policy checks send the error details to the responsible team, and the policy remains unchanged [[32]](#ref-32).
* **Follow-up:** *What does Conditional Access mean at L1?*  
  It applies sign-in requirements based on conditions such as user, application, or device. At L1, I capture the failure details and don't add an exception just to remove a block.
* **Scenario:** A user opens an application on their managed laptop but is blocked on a personal device. Check the device requirement. Access on one device does not authorize bypassing the rule on another.
* **Mentor's advice:** A password reset doesn't fix access denied.

[Back to Contents](#contents)

***

### 3.2 Network foundations (Q49 to Q54)

#### Q49. What do an IP address, subnet, and default gateway do?
* **Answer:** An IP address identifies a network interface. The subnet mask or prefix indicates which addresses are on the local network. The default gateway routes traffic to other networks when no more specific route applies. I verify these on the active connection against the approved setup. A device may have multiple interfaces and both IPv4 and IPv6 addresses, so the first address shown is not necessarily the relevant one [[33]](#ref-33).
* **Follow-up:** *Is a private IP address automatically wrong for internet access?*  
  No. Private IPv4 addresses are common within many networks, and routers commonly translate them for internet access.
* **Scenario:** A laptop reaches a local device but not a service on another network. Check the gateway or routing path, destination availability, and access rules. Local success does not prove the wider path works.
* **Mentor's advice:** Explain each setting's purpose. Never assign addresses without the approved configuration.

#### Q50. What is DNS, and how can it affect a user's application?
* **Answer:** The Domain Name System (DNS) resolves names to information such as IP addresses. A user can have a working connection but still fail to reach an application if the name does not resolve correctly. I confirm the exact name and check the DNS path with an approved test. Internal names may require company DNS or a VPN. I compare the result with the symptom rather than changing DNS servers as a general fix [[33]](#ref-33).
* **Follow-up:** *Would opening a website directly by IP always prove whether DNS is the problem?*  
  No. Many websites require the hostname for routing or certificate checks. An approved name-resolution test is more reliable.
* **Scenario:** Public websites open, but an internal application name does not resolve offsite. Check the required company connection. A public DNS server may not know internal names.
* **Mentor's advice:** DNS can fail even when basic connectivity still works.

#### Q51. What is DHCP, and what would a 169.254 address tell you?
* **Answer:** Dynamic Host Configuration Protocol (DHCP) automatically assigns devices an IP address and other settings. On a Windows connection expected to use DHCP, an automatically assigned IPv4 address beginning with `169.254` can indicate that no valid lease was obtained. It does not prove the DHCP server is down. I check the active adapter, the connection, and whether others are affected, then send evidence to network support if the configuration is still missing [[34]](#ref-34).
* **Follow-up:** *Can a device with that address communicate at all?*  
  It may reach compatible devices on the same local link, but not normal routed internet access. Other interfaces or IPv6 may still work.
* **Scenario:** One wired laptop has a link-local address while nearby devices work. Check its cable, port, and adapter. Do not copy a colleague's address, which creates a duplicate and another outage.
* **Mentor's advice:** A link-local address is a clue, not a reason to restart a shared DHCP server.

#### Q52. A user says the internet is down. How would you check it?
* **Answer:** I ask whether one application or all online work fails, and whether others are affected. Then I check the active wired or wireless connection and its IP settings. Approved local, external, and name-resolution tests narrow the failure, along with known service issues and any required proxy or VPN. Those results determine the next safe check. The network stack is never reset before the scope is understood [[35]](#ref-35).
* **Follow-up:** *Does a connected Wi-Fi icon prove internet access works?*  
  No. It shows a wireless connection, not that DNS, routing, or the destination service is working.
* **Scenario:** A public website opens, but one business application fails for several users. Check that application's status. Do not report an internet outage or change adapter settings for everyone.
* **Mentor's advice:** Test the path in stages. Before disconnecting a remote user, plan the reconnection.

#### Q53. How would you troubleshoot weak or unreliable Wi-Fi?
* **Answer:** I confirm the intended network, location, signal strength, and when drops occur, and check whether nearby users are affected or whether an approved wired connection works. Patterns related to movement, distance, or a recent device change are useful. If the guide allows, I try a controlled reconnect or move to another approved location, then record the results before escalating. Access points and managed wireless profiles are left alone without authorization [[35]](#ref-35).
* **Follow-up:** *What if the user is connected to a guest network?*  
  Guest access may allow internet access but block internal resources. I would confirm the correct network and never share someone else's credentials.
* **Scenario:** Three people lose connectivity in one meeting room, but their laptops work elsewhere. I capture the location, times, network name, and devices for network support, rather than reinstalling drivers.
* **Mentor's advice:** Signal, network admission, and internet access can each fail separately.

#### Q54. What would you look for in `ipconfig` output?
* **Answer:** On Windows, `ipconfig` displays address information for network adapters, and `ipconfig /all` provides additional details such as DHCP status and DNS servers. I first identify the active adapter, then check its address, subnet, gateway, and settings against the expected configuration. Virtual adapters also appear, so an unrelated entry should not drive the diagnosis. Only necessary details go into the ticket [[36]](#ref-36).
* **Follow-up:** *Does "Media disconnected" mean the entire computer is offline?*  
  No. It refers to a single adapter. An unused Ethernet adapter can show as disconnected while Wi-Fi works.
* **Scenario:** You are helping a remote user over their only connection. Do not run `ipconfig /release`, which can end the session. Any renewal requires an approved reason and a reconnection plan.
* **Mentor's advice:** Reading configuration and changing it are different actions.

[Back to Contents](#contents)

***

### 3.3 Diagnostic tools and VPN (Q55 to Q58)

#### Q55. What does `ping` test, and what does it not prove?
* **Answer:** `ping` sends ICMP echo requests and reports replies and their timing. I use it with an approved target when the guide calls for a reachability test. A reply shows that the traffic reached the target and returned at that moment. It does not prove an application works. A timeout may mean the target or path is unavailable, but filtering can also block replies, so I compare with other permitted checks [[37]](#ref-37).
* **Follow-up:** *Does a successful `ping` prove that a secure website is available?*  
  No. `ping` uses ICMP and does not test a web connection such as HTTPS on TCP port 443. The host can reply while the web service fails.
* **Scenario:** A server does not reply to `ping`, but its web application opens. Record both results. The organization may block echo traffic, so a timeout alone does not mean the server is down.
* **Mentor's advice:** Say what the test proves and what remains unknown.

#### Q56. How would you use `nslookup` during troubleshooting?
* **Answer:** I run `nslookup` with the affected hostname and review the server and answer shown, comparing the result with the expected service. A timeout means no answer arrived in time. Name-not-found is different: a DNS server replied that the name does not exist in its view. I check spelling and the intended DNS server, then escalate with the result if needed. A successful lookup does not prove application access [[38]](#ref-38).
* **Follow-up:** *If `nslookup` succeeds but the browser fails, is DNS fully ruled out?*  
  No. The browser may use a cache or a different resolver path. The lookup only shows what that server returned.
* **Scenario:** An internal name returns name-not-found from a public resolver. Confirm the required company DNS or VPN path. Do not send internal names to other public resolvers.
* **Mentor's advice:** Record the queried name, server, answer, and time.

#### Q57. What is a VPN, and how would you handle a connection failure?
* **Answer:** A virtual private network (VPN) creates a secure connection to company resources over another network. I first verify that the underlying network is working, then confirm the approved client, profile, exact error, and failure point. Depending on the message, next steps include sign-in, MFA, device requirements, or known service issues. The client version and failure time are included in any escalation. Security controls remain enabled, and no other VPN is installed [[39]](#ref-39).
* **Follow-up:** *Does a company VPN always carry all internet traffic?*  
  No. Some configurations route all traffic, while others route only selected traffic. The organization decides, and L1 support does not change routes during routine support.
* **Scenario:** The VPN fails on hotel Wi-Fi that has not completed its access page. Check the underlying connection first before resetting the work password.
* **Mentor's advice:** Identify the failure stage: network, sign-in, device check, or tunnel.

#### Q58. The VPN shows as connected, but an internal service fails. What next?
* **Answer:** I confirm the exact resource and whether one service or all internal access fails. Then I check the approved profile, test the internal name via the expected DNS path, compare another permitted internal service, and capture the error. A tunnel can be connected while routing, name resolution, availability, or permissions still block the task. If the checks do not resolve it, I escalate with the results and provide the user with a next update time [[39]](#ref-39).
* **Follow-up:** *Does being connected to the VPN grant access to every internal resource?*  
  No. The user still needs permissions for each resource, and network rules may limit access. Broad access is not a workaround.
* **Scenario:** The internal site resolves and shows access denied after sign-in. The service responded, so check the account and assignment rather than rebuilding the VPN tunnel.
* **Mentor's advice:** A connected tunnel is one result. Verify the user's original task.

[Back to Contents](#contents)

***

## Stage 4: Microsoft 365, security, and knowledge management

This stage covers Microsoft 365 applications and files, phishing and malware response, safe data handling, and knowledge base practice.

* **Approach:** User reports an issue -> understand -> assess impact -> prioritize -> troubleshoot -> communicate -> resolve or escalate -> verify -> document -> close
* **Boundary:** Use the correct account, app version, and approved guide. Protect unsynced work and sensitive information. For suspected compromise, containment via the security process can precede routine troubleshooting. Authorized specialists handle tenant-wide changes, forensics, remote wipe decisions, and policy design.

***

### 4.1 Microsoft 365 applications and files (Q59 to Q64)

#### Q59. How would you begin investigating a Microsoft 365 issue?
* **Answer:** I identify the failed task, application, account, device, error, and start time. Microsoft 365 combines connected apps and cloud services, so I distinguish an app problem from a broader service issue. I check whether others are affected and, if my role permits, review service health. A matching known incident indicates an approved workaround and the next update time. Otherwise, I proceed with focused checks and record the results [[40]](#ref-40).
* **Follow-up:** *What if service health shows no active incident?*  
  That does not rule out a new or limited problem. I would record affected users, times, and errors, and escalate internally if the evidence suggests wider impact.
* **Scenario:** Several users cannot open Teams, and a matching service advisory exists. Link their tickets to the internal incident, share the approved update, and verify recovery later. Reinstalling clients will not fix a service fault.
* **Mentor's advice:** Match any service advisory to the actual symptoms.

#### Q60. A Microsoft 365 app displays Unlicensed Product. What would you check?
* **Answer:** I confirm the app, the exact message, and the work or school account in use. A successful sign-in does not prove the account is licensed for that desktop app. I check license information within my access, or ask the licensing team. Next, I check connectivity and the supported activation guide. I save any open work before any restart or sign-out, and I finish by confirming the user can edit [[41]](#ref-41).
* **Follow-up:** *Would you reset the password right away?*  
  No. First, I would determine whether authentication or activation failed. A password reset does not add a missing license.
* **Scenario:** A new starter can use Word in the browser but cannot edit in the desktop app. Confirm the account and desktop entitlement, and offer the browser option while licensing checks the assignment.
* **Mentor's advice:** Separate identity, license entitlement, and activation.

#### Q61. How would you troubleshoot Outlook not sending or receiving email?
* **Answer:** I first confirm whether sending, receiving, or both fail, for a single message or all mail, and whether the user has classic Outlook, new Outlook, or the web version. Then I check the connection state, the exact error, and any delivery failure report. A web comparison separates the desktop app from the mailbox service. Depending on the evidence, I check the recipient, Outbox, quota, or service health, then send a permitted test message [[42]](#ref-42).
* **Follow-up:** *Does working webmail prove that desktop Outlook is damaged?*  
  No. It narrows the problem to the desktop app, which may have a connection, account, or configuration issue rather than corruption.
* **Scenario:** Only one external recipient rejects mail, and the failure report names an invalid address. Check the address with the user through a trusted route. Do not rebuild the profile.
* **Mentor's advice:** State which direction of mail flow fails, and read the error first.

#### Q62. A user cannot join or hear a Teams meeting. How would you help?
* **Answer:** I separate joining issues from audio issues. For joining, I confirm the link, account, client, and exact message, including whether the user is waiting in the lobby. For audio, I check mute status, the selected speaker and microphone, and device permissions. Another approved call or the browser version offers a comparison. For an urgent meeting, I offer an authorized alternative, then document and escalate as needed [[43]](#ref-43), [[44]](#ref-44).
* **Follow-up:** *What would you check if the meeting has an echo?*  
  Check whether nearby devices have microphones and speakers active; one audio connection or a headset usually helps. Change one thing at a time.
* **Scenario:** A guest sees a message that the organizer must admit them. Contact the organizer and confirm the guest's account. Audio settings and reinstalls will not resolve a lobby requirement.
* **Mentor's advice:** Choose the next step by stage: admission, connection, or audio.

#### Q63. How would you handle a OneDrive file that is not syncing?
* **Answer:** I confirm the work account and folder, and whether one file or all files are affected. Then I check the sync icon, error messages, connection status, paused status, and storage limits, and compare the local file with the cloud version while preserving any newer unsynced work. Next, I use the matching guide and verify that the changes appear online. Never delete the local folder or reset sync without understanding the file state [[45]](#ref-45).
* **Follow-up:** *Is a file in the OneDrive folder automatically backed up online?*  
  No. Its latest changes may still be pending or may have failed to sync. The folder name alone does not prove the upload succeeded.
* **Scenario:** A proposal was edited while sync was paused. Preserve the newer work, determine why sync paused, and resume using the approved steps. Confirm the changes online before closing.
* **Mentor's advice:** Protect the newest work first.

#### Q64. A shared OneDrive or SharePoint link returns Access denied. What next?
* **Answer:** I confirm the file, recipient, account, and the exact error. A link may exist without granting access to everyone who receives it, so I check whether it is limited to named people or the organization and whether access has expired or been removed. The owner or authorized support team confirms the approved permission. Sharing is never broadened to clear the error. After correction, the recipient tests the original task [[46]](#ref-46).
* **Follow-up:** *What if an outside partner needs the file urgently?*  
  I would confirm the business need and follow the external sharing approval process, or request an approved alternative. Personal storage accounts are not an option.
* **Scenario:** A link for one named supplier contact was forwarded to a colleague who cannot open it. Confirm whether they are authorized, then have the owner arrange access. Forwarding does not transfer permission.
* **Mentor's advice:** Urgency does not authorize wider access.

[Back to Contents](#contents)

***

### 4.2 Security and safe support practice (Q65 to Q70)

#### Q65. How would you respond to a suspicious email or message?
* **Answer:** I advise the user not to open links or attachments, reply, or use any contact details in the message. I check whether they have already interacted with it, as that changes the response. They report it through the organization's method, such as a phishing report button, which preserves the message. I record the time and actions, promptly escalate any suspected compromise, and verify any business request through a separate trusted route [[47]](#ref-47).
* **Follow-up:** *What warning signs would you look for?*  
  Unexpected requests, pressure to act, mismatched senders or links, and requests for credentials or payment. A familiar name does not prove safety, because accounts can be compromised.
* **Scenario:** A "payroll" message asks the user to sign in via a new link today. I ask them to report it and verify through the known payroll route. I do not open the link to inspect it.
* **Mentor's advice:** Reporting an unopened message differs from responding to exposure.

#### Q66. The user clicked a suspicious link or entered credentials. What would you do?
* **Answer:** I stay calm and ask exactly what happened: did they open a page, run a file, enter a password, or approve an MFA prompt? I stop the user from interacting with it, and the event immediately enters the security process. I record the time and details without collecting secrets, then follow approved containment and recovery steps, using a trusted device or channel as required. A password change alone may not complete the response [[47]](#ref-47), [[31]](#ref-31).
* **Follow-up:** *Why might a password reset be insufficient?*  
  An attacker may still hold an active session or have changed account settings. Security may need to revoke sessions and review activity.
* **Scenario:** A user entered a password and approved an unexpected MFA request, and the account still works. Escalate promptly as a possible compromise. Continued access is not evidence of safety.
* **Mentor's advice:** Avoid blame. Accurate details and early reporting matter most.

#### Q67. What would you do if a device showed signs of malware or ransomware?
* **Answer:** Unusual encryption, a ransom message, or a credible security alert may indicate an incident. I stop, promptly follow the approved isolation steps, and alert the security team. Isolation may mean disconnecting the device from the network when the procedure requires it. I record the device, time, symptoms, and actions via a secure channel. I avoid restarting, using cleanup tools, or opening affected files, as they can spread damage or destroy evidence [[48]](#ref-48).
* **Follow-up:** *Would you switch the computer off immediately?*  
  I would follow the emergency instructions. Isolation and shutdown have different effects; if isolation fails and spread continues, the procedure may require shutdown.
* **Scenario:** Files are being renamed, and a ransom note appears during remote support. Isolate promptly and contact security via a secure channel. Expect the remote session to drop; containment comes first.
* **Mentor's advice:** The authorized response team handles investigation and recovery.

#### Q68. How would you handle a lost or stolen work device?
* **Answer:** I verify the reporter through the approved process and collect the device identifier, last known time and location, and circumstances. I promptly notify Security or Device Management under the lost-device procedure. I record the known protection status without assuming that encryption or a screen lock eliminates all risk. An authorized team decides on access restrictions and remote actions, and I confirm the correct device before any delegated step [[49]](#ref-49).
* **Follow-up:** *Can you promise that a remote wipe has removed the data?*  
  No. Sending a command is not the same as confirmed completion. The device may be offline. I would report the actual status only.
* **Scenario:** A user reports a stolen laptop, and the asset list shows their old and current devices. Escalate promptly, then verify the current asset identifier before any remote action.
* **Mentor's advice:** Separate what you know, what you're asked for, and what the device has confirmed.

#### Q69. How does least privilege apply to everyday Service Desk work?
* **Answer:** Least privilege means using only the access an authorized task requires. My normal account handles routine work, and I use an approved elevated method only when necessary. Before granting delegated access, I confirm the business need and approval, and I prefer a limited, approved action over permanent administrator rights. I record the change and verify the task. A powerful support account does not grant permission to use every function [[2]](#ref-2).
* **Follow-up:** *What if an installer asks for administrator credentials?*  
  I would confirm the software is approved and use the authorized deployment or elevation route, never sharing an admin password or granting permanent rights.
* **Scenario:** A user needs an approved utility for a presentation today. Use the software portal or the authorized installation route and explain the timing. Endpoint protection remains enabled.
* **Mentor's advice:** Least privilege supports authorized work while limiting access.

#### Q70. How would you protect sensitive information during support?
* **Answer:** I collect only the details needed for diagnosis and use approved ticket, remote support, and file transfer channels. Before taking a screen capture, the user closes unrelated confidential content. I review logs and screenshots for secrets and personal information and redact them where appropriate. Passwords, MFA codes, and recovery secrets stay out of tickets. Contain and report accidental exposure through the handling procedure.
* **Follow-up:** *Can you paste a ticket or log into an AI tool for help?*  
  Only if the organization approves that tool for that type of data. Removing a name may not remove confidential details, and any advice needs verifying.
* **Scenario:** A screenshot shows an error and a customer's financial details. Share only the diagnostic part through an approved method. If the original is attached, follow restricted handling rather than quietly deleting it.
* **Mentor's advice:** Be specific about what you collect and where it may go.

[Back to Contents](#contents)

***

### 4.3 Knowledge management (Q71 to Q74)

#### Q71. What makes a knowledge base article useful?
* **Answer:** A useful knowledge base (KB) article helps someone recognize an issue and complete a safe task. It should include a searchable title, symptoms, affected environment, prerequisites, clear steps with expected results, guidance on verifying success, and when to stop or escalate. State a cause only with evidence, and label workarounds clearly. Before publishing, I remove sensitive information, check for duplicates, and follow the review process [[50]](#ref-50).
* **Follow-up:** *Must you know the root cause before recording a workaround?*  
  No. A tested, approved workaround helps while you investigate the cause. I would state its limits and link the incident or problem record where permitted.
* **Scenario:** Resuming OneDrive sync restored a user's missing updates. An article could cover paused sync, confirming the account, the resume steps, and online verification, without claiming it fixes every sync error.
* **Mentor's advice:** Include both the expected result and the stopping point.

#### Q72. How would you use or correct an outdated KB article?
* **Answer:** Before following an article, I verify that it matches the symptoms, app version, device, and permissions, and I review its warnings. I use only relevant, approved steps. If a step no longer matches the screen or produces a different result, I stop and document the difference. If my role allows, I correct the article; otherwise, I send clear feedback to its owner and link it to the ticket, noting whether it helped [[51]](#ref-51).
* **Follow-up:** *Does an old review date mean the article must be discarded?*  
  No. The date is a reason to check, not proof it is wrong. I validate it against the current environment and flag any problems.
* **Scenario:** A classic Outlook article references an option missing from new Outlook. I stop, find the matching guide, and send the owner the version mismatch instead of improvising.
* **Mentor's advice:** Reusing an article includes checking it.

#### Q73. How can an L1 analyst help reduce recurring incidents?
* **Answer:** While handling tickets, I notice recurring symptoms and check whether cases share an application, version, location, or time. Related records are linked by process, and examples, impact, attempted fixes, and results are sent to the team investigating the root cause. Similar wording alone does not prove a common root cause. Meanwhile, approved workarounds restore service, and knowledge stays current. My contribution is reliable evidence from real cases [[52]](#ref-52).
* **Follow-up:** *Would you open a problem record for every repeated ticket?*  
  I would follow the organization's criteria and my authority. A repeat warrants a look, but it is not a confirmed problem.
* **Scenario:** Five users report Teams audio failures after a client update. Compare models, versions, symptoms, and times, including a working comparison. Share the pattern without claiming the update is proven responsible.
* **Mentor's advice:** Separate the observed pattern from the suspected cause.

#### Q74. How would you encourage self-service without dismissing the user?
* **Answer:** I select an approved article that matches the user's task and explain how it will help. Then I confirm they can open it, follow the steps, and have the required permissions, offering guided help or an accessible alternative if needed. Afterward, I confirm the original task works and pass along any confusing instructions as feedback. Sending a link is one support step, not a resolution [[53]](#ref-53).
* **Follow-up:** *What if the user already tried the article and it failed?*  
  I would acknowledge the effort, ask which step failed, and use that evidence in the next check rather than repeating the article.
* **Scenario:** A user cannot sign in, and the recovery article is behind the same sign-in page. Use the accessible help route and the verified recovery process, and report the barrier to the article owner.
* **Mentor's advice:** Recommend the right article, stay available, and verify the outcome.

[Back to Contents](#contents)

***

## Stage 5: Interview performance and final revision

This stage covers personal and behavioral questions, safe decision-making under pressure, rapid-fire revision, tools, a mock interview, and a seven-day plan.

* **Approach:** Show how you help users, diagnose issues, maintain useful records, and obtain the right support when needed. Use real details in personal answers. For behavioral questions, use STAR: situation, task, action, result, focusing on your own contribution [[1]](#ref-1), [[54]](#ref-54).
* **Boundary:** Student stories marked as fictional are examples to adapt, not experiences to claim. Citations support the concepts; you do not need to say the reference numbers aloud.

***

### 5.1 Introducing yourself and showing evidence (Q75 to Q78)

#### Q75. Tell me about yourself and why you are ready for an entry-level role.
* **Answer:** I am building a career in IT support, focused on helping users complete their work. Through study and hands-on practice, I have learned to ask clear questions, test one possible cause at a time, and explain results simply. I am comfortable asking for guidance and understand that workplace access comes with limits. I would bring a careful approach, useful notes, and a willingness to learn the team's tools [[1]](#ref-1).
* **Follow-up:** *What practical exercise could you explain in more detail?*  
  One I completed: the environment, the symptom, the checks, and how I verified the result, clearly labeled as a lab, project, placement, or paid role.
* **Scenario:** The interviewer asks which ticketing system you used at work, but you have only practiced in a demo. Say so directly, then explain the fields and workflow you practiced.
* **Mentor's advice:** Use only true details linked to user support duties.

#### Q76. Why do you want to work in a Help Desk or Service Desk role?
* **Answer:** I enjoy solving practical problems and helping people move forward. Service Desk work combines troubleshooting with communication, documentation, and follow-through. The role also includes routine requests, queue work, and escalations, which appeal to me because I want to build strong support habits. I would judge an interaction by whether the user can complete their task and knows what happens next [[1]](#ref-1), [[55]](#ref-55).
* **Follow-up:** *Why this organization rather than any other employer?*  
  I would connect one verified detail from its website or job description to my preparation, such as a structured training program, without invented praise.
* **Scenario:** The employer supports several external clients. Be ready to explain how you would confirm the correct client environment, contact route, and procedure before acting.
* **Mentor's advice:** Show you understand the routine work as well as the parts you enjoy.

#### Q77. You have no professional IT experience. What evidence can you offer?
* **Answer:** I haven't worked on a professional Service Desk team, so I can't claim live queue or production experience. I can demonstrate my approach through study, practical exercises, and instances where I helped others, explaining what I personally did, checked, and learned. I would welcome supervised work and feedback to build reliable habits in a real-world environment [[54]](#ref-54), [[55]](#ref-55).
* **Follow-up:** *Would a customer-facing job outside IT be relevant?*  
  Yes, as explained. Listening, clarifying requests, handling frustration, and recording information all transfer directly to support work. Technical gaps are clearly stated.
* **Scenario:** You helped at a student event with repeated registration questions. That shows communication, but it doesn't demonstrate experience administering an identity system.
* **Mentor's advice:** Describe an example's limits as clearly as its result.

#### Q78. Tell me about a technical problem you solved.
* **Answer:** During a college group project, a teammate could not open our shared document before a rehearsal. I asked for the exact error message and checked which account they were signed in to. The link was intended for their college account, but the browser was using a personal one. After they switched accounts through the standard sign-in, the document opened. We finished the rehearsal, and I added an account-check reminder to our notes [[54]](#ref-54).
* **Follow-up:** *How did you know that your action solved the problem?*  
  The teammate opened the document with the correct account and completed their task. That observable result is the evidence, not a claim that every sharing problem was fixed.
* **Scenario:** The interviewer asks whether you changed the file permissions. In this fictional example, you did not; the existing permission worked with the right account. Do not add actions to strengthen the story.
* **Mentor's advice:** Fictional example. Use your own story in STAR form.

[Back to Contents](#contents)

***

### 5.2 Mistakes, feedback, and uncertainty (Q79 to Q82)

#### Q79. Tell me about a mistake and how you handled it.
* **Answer:** During a practice support exercise, I gave a classmate instructions for the wrong application version. When the menu didn't match, I realized I had assumed the version. I acknowledged the error, asked them to stop, and found the correct instructions without changing any unrelated settings. Since then, I've made a version check part of my opening questions. The lesson: verify the environment first, especially when a familiar problem makes me rush [[54]](#ref-54).
* **Follow-up:** *What if the mistake had affected a real user's work?*  
  I would report the facts promptly, assess the impact, and follow the recovery and escalation process, keeping what happened separate from what I suspected.
* **Scenario:** A support instruction has already caused an unexpected change. Stop further changes, preserve information, and get help. An apology matters, but a controlled response comes next.
* **Mentor's advice:** Fictional example. Own the action and show a specific change in habit.

#### Q80. Tell me about feedback that improved the way you worked with others.
* **Answer:** During a group project, a teammate said my technical explanations were too fast. I asked which part was unclear and learned I was giving several steps before they finished the first. I switched to one step at a time and checked each result. At the next session, they completed the task without asking me to repeat anything. I learned to treat feedback as information about the other person's experience [[54]](#ref-54).
* **Follow-up:** *What if you disagree with the feedback?*  
  I would ask for a specific example, calmly explain my reasoning, and compare it to the agreed task. Safety or policy questions go to the right person.
* **Scenario:** A teammate says your handover is missing the next action. Review the note together, add the owner and next step, and check that it is now usable.
* **Mentor's advice:** Fictional example. Show the change and its observed effect, without invented percentages.

#### Q81. What would you do if you did not know the answer to a technical question?
* **Answer:** I would state which parts I understand and which I need to verify. After clarifying the symptom, impact, and environment, I consult the approved knowledge base or vendor documentation and explain the next safe check and what it could indicate. If the issue exceeds my knowledge, access, or time, I escalate with evidence and keep the user informed. I don't include guessed commands or unconfirmed causes in my answer.
* **Follow-up:** *What would you say if this happened during the interview?*  
  "I have not used that feature yet. I would confirm the version and exact error, then consult the supported guide. May I explain my troubleshooting approach?"
* **Scenario:** You recognize a command but cannot explain one of its options. Do not recommend running it. Check the official description and local procedure first.
* **Mentor's advice:** Admit the specific gap, then show a useful method.

#### Q82. An executive needs printing, a team cannot sign in, and malware is reported. What first?
* **Answer:** I quickly assess the impact and urgency of each report and activate the security response route for the suspected malware. The broader sign-in failure goes to the incident process, so neither waits while I work on the printer. The local priority matrix and procedures guide the order. I acknowledge the executive's deadline, look for an approved printing alternative, and provide updates. Job title alone does not set technical priority [[56]](#ref-56), [[48]](#ref-48).
* **Follow-up:** *Does that mean one fixed ticket order always applies?*  
  No. New facts change the response. A printing issue could affect a critical service, and a sign-in report could have a simple cause. I would keep reassessing.
* **Scenario:** You are the only analyst when all three reports arrive. Trigger the security and incident contacts, give each caller a next step, and request queue cover. Do not work on three investigations in silence.
* **Mentor's advice:** Explain routing and communication as well as priority.

[Back to Contents](#contents)

***

### 5.3 Escalation and closing the interview (Q83 to Q86)

#### Q83. The issue needs escalation, but the user insists you fix it now. What do you say?
* **Answer:** I acknowledge the disruption and explain why the next team is needed, such as restricted access or a fault beyond the L1 procedure. Then I summarize my checks and offer any permitted workaround. The handover includes impact, errors, timing, and results, and I confirm the next point of contact so the ticket is not lost between teams. No repair time is promised until the receiving team confirms one [[2]](#ref-2), [[1]](#ref-1).
* **Follow-up:** *What if the user says the previous analyst already tried those checks?*  
  I would review the notes and repeat a check only if the state changed, the evidence was incomplete, or the next team needs a current result, explaining why.
* **Scenario:** The procedure ends with an administrator action, and the user offers their manager's password. I decline it, explain the authorized route, and escalate with the evidence.
* **Mentor's advice:** Escalation is part of restoring service. Make the handover usable.

#### Q84. A colleague suggests an unsafe shortcut that conflicts with the approved guide. What next?
* **Answer:** I pause before any change and ask what the shortcut is meant to solve. Then I compare it with the approved procedure and explain the specific concern, such as exposing data or disabling protection. I seek clarification from the authorized support or security team and offer a permitted alternative when possible. I record the facts without blaming anyone. Confidence or seniority does not extend my permissions [[2]](#ref-2).
* **Follow-up:** *Would you always follow the written article even if it looks wrong?*  
  No. If a step looks unsafe or outdated, I would stop, ask for clarification, and report the exact mismatch to the owner.
* **Scenario:** A colleague proposes briefly turning off endpoint protection to run an unfamiliar installer. Route it through the software request or security review process. "Temporary" does not make it safe.
* **Mentor's advice:** Describe the risk and approval route calmly.

#### Q85. What is one skill you are still improving?
* **Answer:** I am improving how briefly I explain a technical issue. In practice, I sometimes give too much background before the next action. Now I prepare a short version: the symptom, the result of my check, and what happens next. A practice partner tells me what they understood and what they still need. In a support role, I would keep seeking feedback while ensuring short explanations still convey what the user needs.
* **Follow-up:** *How would you show that this is improving?*  
  By comparing recorded practice answers or feedback over time to see whether the main point is clearer. No invented numbers, and no claim that the weakness is gone.
* **Scenario:** The interviewer asks for a real weakness, and you prepared "I work too hard." Choose a true, manageable skill gap instead, with the practice you are doing about it.
* **Mentor's advice:** Illustrative answer. Choose an honest development area and describe action.

#### Q86. What questions would you ask us at the end of the interview?
* **Answer:** I would ask about the work and the support available to a new analyst: which issues L1 handles most often, when escalation is expected, how training and supervised access work, and what good performance looks like in the first months. If the job description leaves anything unclear, such as shift coverage, I would ask about it. I would choose the most relevant questions and listen carefully [[55]](#ref-55).
* **Follow-up:** *What if they already answered all your prepared questions?*  
  I would acknowledge that and ask one follow-up about something they mentioned or about the next stage, with no repeated questions to fill time.
* **Scenario:** The interviewer says analysts support clients in several time zones. I would ask which shifts this vacancy covers, how handover works, and whether on-call work is included.
* **Mentor's advice:** Ask questions that help you understand this specific role.

[Back to Contents](#contents)

***

### 5.4 Rapid-fire revision

Cover the answers. For each distinction, give one or two sentences.

#### Table 1. Rapid-fire fundamentals

| No. | Question | Answer |
| :--- | :--- | :--- |
| **R01** | Incident versus service request? | An incident is an unplanned interruption or a reduction in quality. A service request asks for an agreed action, information, or access [[6]](#ref-6). |
| **R02** | Problem versus incident? | A problem is a cause or potential cause of incidents. An incident can be resolved while the cause is still under investigation [[57]](#ref-57). |
| **R03** | How do impact and urgency affect priority? | Impact is the effect on work; urgency is how soon action is needed. Apply the organization's matrix, since no universal P1 to P4 mapping exists [[56]](#ref-56). |
| **R04** | Does meeting the response target mean the issue is resolved? | No. Response and resolution are separate milestones, and an SLA may set separate targets for each [[58]](#ref-58). |
| **R05** | Is a workaround the same as removing the cause? | No. It restores service or reduces impact while the cause remains. Record its limits [[57]](#ref-57). |
| **R06** | What makes an escalation useful? | Failed task, impact, environment, error and time, checks and results, actions taken, and the help needed, with assumptions stated separately. |
| **R07** | Authentication versus authorization? | Authentication verifies identity. Authorization determines permitted access. Signing in does not grant access to everything [[59]](#ref-59). |
| **R08** | Why are two passwords not MFA? | MFA combines different factor types, such as something you know and something you have. Two passwords are the same type [[60]](#ref-60). |
| **R09** | What does least privilege mean for L1? | Use only the access the authorized task needs. Available buttons do not define your permission [[2]](#ref-2). |
| **R10** | What do DNS and DHCP do? | DNS provides information for domain names, including addresses. DHCP automatically supplies IP addresses and settings [[38]](#ref-38), [[61]](#ref-61). |

Say what each result proves, what remains unknown, and what falls within L1 authority.

#### Table 2. Rapid-fire diagnostic judgment

| No. | Question | Answer |
| :--- | :--- | :--- |
| **R11** | Does a successful `ping` prove a website works? | No. `ping` tests ICMP reachability, not sign-in, content, or the application service [[37]](#ref-37). |
| **R12** | Does a failed `ping` prove the host is down? | No. Filtering can block replies. Compare with other approved checks [[37]](#ref-37). |
| **R13** | What does a successful `nslookup` tell you? | The queried DNS server returned a result. It does not prove the application is reachable [[38]](#ref-38). |
| **R14** | Why read `ipconfig` before changing network settings? | It records the current configuration. Release and renew change it and can drop a remote session [[36]](#ref-36). |
| **R15** | A site opens but says Access denied. What does that suggest? | The service responded, so check the account and permissions. A network reset will not fix authorization [[59]](#ref-59). |
| **R16** | Does a file in a OneDrive folder prove the latest edit is online? | No. Sync may be paused or failing. Check sync state and preserve newer local work [[45]](#ref-45). |
| **R17** | Can urgency justify sharing an administrator password? | No. Urgency affects response speed, not credential rules. Use the approved elevation route [[2]](#ref-2). |
| **R18** | First response to suspected ransomware? | Stop routine work, isolate using the approved steps, and alert security via a safe channel [[48]](#ref-48). |
| **R19** | Example of a useful ticket note? | "10:15 local time: one user cannot open the shared file. Correct account confirmed; access denied remains. Access request sent to owner. Next contact 11:00." |
| **R20** | When is it appropriate to close a ticket? | After required verification and documentation, per the closure process. Sending a link or losing contact is not resolution. |

[Back to Contents](#contents)

***

### 5.5 Tools and commands

For each tool, state its purpose, the useful result, and the limit of that result.

#### Table 3. Tools and commands for revision

| Tool | What it shows | Limit |
| :--- | :--- | :--- |
| `ipconfig /all` (Windows) | Adapter details: DHCP status, addresses, gateway, DNS servers. | Select the active interface first. Release and renew are changes, not checks [[36]](#ref-36). |
| `ping` (approved target) | ICMP echo replies and timing. | A reply indicates limited reachability; it does not prove the application works [[37]](#ref-37). |
| `nslookup` (approved host name) | DNS server used and the returned record or error. | Use approved resolvers; sending internal names to public servers may leak information [[38]](#ref-38). |
| **Task Manager** (Windows) | Processes and CPU, memory, disk, and network use during the symptom. | High use is a clue. Ending a task can lose unsaved work [[11]](#ref-11). |
| **Event Viewer** (Windows) | Events matching the symptom time: source, ID, message. | An error entry is not a confirmed cause [[11]](#ref-11). |
| **System Information** (`msinfo32`) | System and component details. | Reading details does not authorize changes [[11]](#ref-11). |
| **Activity Monitor** (macOS) | App and process activity, memory pressure. | Quit and Force Quit can lose data [[21]](#ref-21). |
| **Microsoft 365 service health** | Incidents and advisories for the organization, with an assigned role. | An empty dashboard does not rule out a new or limited fault [[40]](#ref-40). |

[Back to Contents](#contents)

***

### 5.6 Mock interview and job description

Match your examples to the vacancy, and research the employer using its published information [[55]](#ref-55).

#### Table 4. Twenty-minute mock interview

| Time | Task | Look for |
| :--- | :--- | :--- |
| **0 to 2 min** | Introduce yourself for this vacancy ([Q75 to Q77](#51-introducing-yourself-and-showing-evidence-q75-to-q78)). | Relevant preparation, honest experience labels, and a clear link to user support. |
| **2 to 5 min** | Describe one problem you solved ([Q78](#q78-tell-me-about-a-technical-problem-you-solved) to [Q80](#q80-tell-me-about-feedback-that-improved-the-way-you-worked-with-others)). | A true example, specific actions, and an observed result. |
| **5 to 9 min** | Work through the competing reports in [Q82](#q82-an-executive-needs-printing-a-team-cannot-sign-in-and-malware-is-reported-what-first), then react to one new fact. | Impact questions, prompt security routing, incident escalation, and communication. |
| **9 to 12 min** | Answer five random rapid-fire checks ([5.4](#54-rapid-fire-revision)). | Correct distinctions and limits. |
| **12 to 16 min** | Explain an escalation, then respond to an unsafe shortcut ([Q83 to Q84](#53-escalation-and-closing-the-interview-q83-to-q86)). | A usable handover, realistic authority, and a permitted next step. |
| **16 to 20 min** | Ask two employer questions, then self-review ([Q85 to Q86](#53-escalation-and-closing-the-interview-q83-to-q86)). | One strong answer and two to improve, rehearsed with facts, not jargon. |

Review each answer for accuracy, a clear next step, realistic permissions, and plain language. This is a practice checklist, not a hiring score.

#### Table 5. Matching evidence to the job description

| Requirement | Evidence to prepare |
| :--- | :--- |
| **Microsoft 365 support** | One real lab or support example and a safe application check. If you have only studied it, say so. Review [Q59 to Q64](#41-microsoft-365-applications-and-files-q59-to-q64). |
| **Customer communication** | A true example of clarifying a request, explaining a step, and checking understanding, with the setting labeled accurately. |
| **Shifts or multiple clients** | Confirm the actual roster, time zone, on-call expectations, client boundaries, and handover process. State your real availability. |
| **Local and regional details** | Check working language, location, eligibility, and screening requirements with the recruiter. Use official local guidance for legal questions. |

[Back to Contents](#contents)

***

### 5.7 Seven-day revision plan

Start from memory, compare with the guide, and correct errors. Research shows that retrieval practice improves retention; this schedule is a suggested plan, not a tested predictor of interview success [[62]](#ref-62).

#### Table 6. Seven-day revision plan

| Day | Focus |
| :--- | :--- |
| **Day 1** | Stage 1: explain the workflow, incident versus request, priority, and escalation from memory. Write and correct one ticket note. |
| **Day 2** | Stage 2: talk through a slow device and a printer fault, including a safe first check and a stopping point. |
| **Day 3** | Stage 3: identity verification, MFA recovery, DNS, DHCP, VPN, and the limits of `ping` and `nslookup`. |
| **Day 4** | Stage 4: a Microsoft 365 fault, phishing exposure, and an unsynced file, including the evidence you would pass on. |
| **Day 5** | Prepare true examples for [Q75 to Q80](#51-introducing-yourself-and-showing-evidence-q75-to-q78) and [Q85](#q85-what-is-one-skill-you-are-still-improving), matched to the job description. |
| **Day 6** | Run the mock interview with a partner. Correct two weak answers, then retry after a break. |
| **Day 7** | Answer all 20 rapid-fire checks from memory, rehearse your introduction, and run the interview-day checks, with no new topics. |

#### Interview-day checks

- [ ] Date, time zone, format, joining details, and recruiter contact confirmed
- [ ] Requested documents, CV, and job description prepared
- [ ] Camera, microphone, connection, and joining method tested for video interviews
- [ ] Three true examples and two employer questions prepared
- [ ] Ask for clarification if a question is unclear
- [ ] Next stage and expected communication confirmed before leaving

[Back to Contents](#contents)

***

## Quick Reference: Priority Grid and Templates

Priority usually comes from impact and urgency together [[8]](#ref-8).

#### Table 7. Example priority matrix (illustrative only)

| Impact \ Urgency | High | Medium | Low |
| :--- | :--- | :--- | :--- |
| **High** | P1 Critical | P2 High | P3 Moderate |
| **Medium** | P2 High | P3 Moderate | P4 Low |
| **Low** | P3 Moderate | P4 Low | P5 Planning |

* **Impact questions:** How many users or sites are affected? Is critical work blocked or only slowed? Does a workaround exist?
* **Urgency questions:** Is there a real deadline? Will harm grow if the issue waits? Is a security issue suspected?

#### Table 8. Ticket work note template (see Q8)

| Field | What to write |
| :--- | :--- |
| **Time** | With time zone for cross-region work |
| **Symptom** | Exact error and start time |
| **Scope and impact** | Who else is affected; what work is blocked |
| **Checks and results** | What each check showed |
| **Workaround** | What is in place, or none |
| **Next action** | Step, owner, and time |

#### Table 9. Escalation message template (see Q12, Q38)

| Field | What to write |
| :--- | :--- |
| **What and since when** | Service, users, start time |
| **What still works** | Anything that narrows the fault |
| **Checks done** | Approved checks, results, outage status |
| **Request** | The specific help needed |
| **User promise** | When users expect the next update |

#### Table 10. User update, fix time unknown template (see Q18)

| Field | What to write |
| :--- | :--- |
| **Known** | What is confirmed |
| **Being checked** | Who is working on it; no guessed cause |
| **Workaround** | Available or not, with limits |
| **Next update** | A realistic time within support coverage |

#### Table 11. Shift handover template (see Q11)

| Field | What to write |
| :--- | :--- |
| **Ticket and impact** | Reference and current impact |
| **Checks and results** | What was tried and learned |
| **Waiting on** | User, team, or vendor reference |
| **Owner and target** | Current owner and next due target |
| **Promised update** | What the user was told, and when |

> [!WARNING]
> **Never include:** Never include passwords, verification codes, recovery secrets, or unrelated personal information in any ticket, note, or message.

[Back to Contents](#contents)

***

## Glossary

Plain definitions of key terms. Employers may use different names for the same idea.

| Term | Meaning |
| :--- | :--- |
| **Authentication** | Verifying who is signing in. |
| **Authorization** | Determining what an identity may access or do. |
| **Change** | Adding, modifying, or removing anything that could affect a service. |
| **Conditional Access** | Sign-in requirements based on conditions such as user, app, or device. |
| **DHCP** | Automatically assigns IP addresses and network settings. |
| **DNS** | Resolves names to information such as IP addresses. |
| **Escalation, functional** | Passing work to a team with the right expertise or access. |
| **Escalation, hierarchical** | Raising an issue to someone with authority over a risk or blocker. |
| **Impact** | The extent of business activity affected. |
| **Incident** | An unplanned interruption or reduction in service quality. |
| **ITIL** | Guidance organizations can use for IT service management. |
| **ITSM** | How an organization plans, delivers, and supports IT services. |
| **KB article** | An approved, written fix or procedure in a knowledge base. |
| **L1, L2, L3** | Support levels: first contact, further investigation, then specialist or vendor support. |
| **Least privilege** | Using only the access an authorized task requires. |
| **Managed device** | A device that receives organizational settings, apps, and security requirements. |
| **MFA** | Multifactor authentication: identity proof using different factor types. |
| **Phishing** | A deceptive message designed to steal credentials, money, or access. |
| **Priority** | The order in which work is handled, usually based on impact and urgency. |
| **Problem** | The cause, or possible cause, of one or more incidents. |
| **Resolved / closed** | Resolved means the fix is recorded; closed means complete under closure rules. |
| **Service request** | A request for something normally provided, such as software or access. |
| **SLA** | Service level agreement: agreed targets such as response and resolution. |
| **SSO** | Single sign-on: one session giving access to several integrated apps. |
| **STAR** | Situation, task, action, result: a structure for behavioral answers. |
| **Urgency** | How soon harm becomes serious or action is needed. |
| **VPN** | Virtual private network: a protected connection to company resources. |
| **Workaround** | A way to restore work without removing the underlying cause. |

[Back to Contents](#contents)

***

## References

1. <a id="ref-1">[1]</a> National Center for O*NET Development, "Computer user support specialists (15-1232.00)," *O*NET OnLine*. [https://www.onetonline.org/link/details/15-1232.00](https://www.onetonline.org/link/details/15-1232.00).
2. <a id="ref-2">[2]</a> Microsoft, "Implementing least-privilege administrative models," *Microsoft Learn*. [https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/implementing-least-privilege-administrative-models](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/implementing-least-privilege-administrative-models).
3. <a id="ref-3">[3]</a> ISO/IEC, *Information technology, service management, part 1: Service management system requirements*, ISO/IEC 20000-1:2018, 2018. [https://www.iso.org/standard/70636.html](https://www.iso.org/standard/70636.html).
4. <a id="ref-4">[4]</a> PeopleCert, "ITIL 4," *PeopleCert*. [https://www.peoplecert.org/ITIL-4](https://www.peoplecert.org/ITIL-4).
5. <a id="ref-5">[5]</a> AXELOS, *ITIL Foundation: ITIL 4 Edition*. Norwich, U.K.: TSO, 2019.
6. <a id="ref-6">[6]</a> Atlassian, "Service request management," *Atlassian ITSM guides*. [https://www.atlassian.com/itsm/service-request-management](https://www.atlassian.com/itsm/service-request-management).
7. <a id="ref-7">[7]</a> Atlassian, "Incident management," *Atlassian guides*. [https://www.atlassian.com/incident-management](https://www.atlassian.com/incident-management).
8. <a id="ref-8">[8]</a> Atlassian, "What are priority levels in Jira Service Management?," *Atlassian Support*. [https://support.atlassian.com/jira-service-management-cloud/docs/what-are-priority-levels-in-jira-service-management/](https://support.atlassian.com/jira-service-management-cloud/docs/what-are-priority-levels-in-jira-service-management/).
9. <a id="ref-9">[9]</a> ServiceNow, "SLA conditions," *ServiceNow Docs*. [https://www.servicenow.com/docs/r/it-service-management/service-level-management/c_SLAConditions.html](https://www.servicenow.com/docs/r/it-service-management/service-level-management/c_SLAConditions.html).
10. <a id="ref-10">[10]</a> ServiceNow, "Resolve and close an incident," *ServiceNow Docs*. [https://www.servicenow.com/docs/r/it-service-management/incident-management/resolve-and-close-an-incident.html](https://www.servicenow.com/docs/r/it-service-management/incident-management/resolve-and-close-an-incident.html).
11. <a id="ref-11">[11]</a> Microsoft, "System configuration tools in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/experience/system-configuration-tools-in-windows](https://support.microsoft.com/en-us/windows/experience/system-configuration-tools-in-windows).
12. <a id="ref-12">[12]</a> Microsoft, "Tips to improve PC performance in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/experience/performance-optimization/tips-to-improve-pc-performance-in-windows](https://support.microsoft.com/en-us/windows/experience/performance-optimization/tips-to-improve-pc-performance-in-windows).
13. <a id="ref-13">[13]</a> Microsoft, "Troubleshoot problems updating Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/deployment/updates-lifecycle/troubleshoot-problems-updating-windows](https://support.microsoft.com/en-us/windows/deployment/updates-lifecycle/troubleshoot-problems-updating-windows).
14. <a id="ref-14">[14]</a> Microsoft, "Troubleshooting blank screens in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/hardware/display-graphics/troubleshooting-blank-screens-in-windows](https://support.microsoft.com/en-us/windows/hardware/display-graphics/troubleshooting-blank-screens-in-windows).
15. <a id="ref-15">[15]</a> Microsoft, "Manage drive space with Storage Sense," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/experience/storage-filemanagement/manage-drive-space-with-storage-sense](https://support.microsoft.com/en-us/windows/experience/storage-filemanagement/manage-drive-space-with-storage-sense).
16. <a id="ref-16">[16]</a> Microsoft, "Fix printer connection and printing problems in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/hardware/printer/fix-printer-connection-and-printing-problems-in-windows](https://support.microsoft.com/en-us/windows/hardware/printer/fix-printer-connection-and-printing-problems-in-windows).
17. <a id="ref-17">[17]</a> Microsoft, "Troubleshoot external monitor connections in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/hardware/display-graphics/troubleshoot-external-monitor-connections-in-windows](https://support.microsoft.com/en-us/windows/hardware/display-graphics/troubleshoot-external-monitor-connections-in-windows).
18. <a id="ref-18">[18]</a> Microsoft, "Windows camera, microphone, and privacy," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/privacy/windows-camera-microphone-and-privacy](https://support.microsoft.com/en-us/windows/privacy/windows-camera-microphone-and-privacy).
19. <a id="ref-19">[19]</a> Apple, "Get system information about your Mac," *Mac User Guide*, Apple Support. [https://support.apple.com/guide/mac-help/get-system-information-about-your-mac-syspr35536/mac](https://support.apple.com/guide/mac-help/get-system-information-about-your-mac-syspr35536/mac).
20. <a id="ref-20">[20]</a> Apple, "Safely open apps on your Mac," *Apple Support*. [https://support.apple.com/en-gb/102445](https://support.apple.com/en-gb/102445).
21. <a id="ref-21">[21]</a> Apple, "Quit an app or process in Activity Monitor on Mac," *Activity Monitor User Guide*, Apple Support. [https://support.apple.com/en-ie/guide/activity-monitor/actmntr1002/mac](https://support.apple.com/en-ie/guide/activity-monitor/actmntr1002/mac).
22. <a id="ref-22">[22]</a> Apple, "Check if your Mac needs more RAM in Activity Monitor," *Activity Monitor User Guide*, Apple Support. [https://support.apple.com/en-gb/guide/activity-monitor/actmntr1004/mac](https://support.apple.com/en-gb/guide/activity-monitor/actmntr1004/mac).
23. <a id="ref-23">[23]</a> Microsoft, "Sync your enrolled Windows device," *Microsoft Learn*. [https://learn.microsoft.com/en-us/intune/user-help/device-actions/sync-device-windows](https://learn.microsoft.com/en-us/intune/user-help/device-actions/sync-device-windows).
24. <a id="ref-24">[24]</a> Microsoft, "Compare Active Directory to Microsoft Entra ID," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/fundamentals/compare](https://learn.microsoft.com/en-us/entra/fundamentals/compare).
25. <a id="ref-25">[25]</a> Okta, "Single sign-on," *Okta Developer*. [https://developer.okta.com/docs/concepts/sso-overview/](https://developer.okta.com/docs/concepts/sso-overview/).
26. <a id="ref-26">[26]</a> Microsoft, "Reset a user's password using Microsoft Entra ID," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/fundamentals/users-reset-password-azure-portal](https://learn.microsoft.com/en-us/entra/fundamentals/users-reset-password-azure-portal).
27. <a id="ref-27">[27]</a> Microsoft, "Cached domain logon information," *Microsoft Learn*. [https://learn.microsoft.com/en-us/troubleshoot/windows-server/user-profiles-and-logon/cached-domain-logon-information](https://learn.microsoft.com/en-us/troubleshoot/windows-server/user-profiles-and-logon/cached-domain-logon-information).
28. <a id="ref-28">[28]</a> Microsoft, "Manage authentication methods for Microsoft Entra ID," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods-manage).
29. <a id="ref-29">[29]</a> Okta, "Password reset and account recovery," *Okta Identity Engine Documentation*. [https://help.okta.com/oie/en-us/content/topics/identity-engine-upgrade/password-reset-account-recovery.htm](https://help.okta.com/oie/en-us/content/topics/identity-engine-upgrade/password-reset-account-recovery.htm).
30. <a id="ref-30">[30]</a> Microsoft, "Learn about groups and access rights in Microsoft Entra ID," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/fundamentals/concept-learn-about-groups](https://learn.microsoft.com/en-us/entra/fundamentals/concept-learn-about-groups).
31. <a id="ref-31">[31]</a> Microsoft, "Revoke user access in Microsoft Entra ID," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/identity/users/users-revoke-access](https://learn.microsoft.com/en-us/entra/identity/users/users-revoke-access).
32. <a id="ref-32">[32]</a> Microsoft, "Troubleshooting sign-in problems with Conditional Access," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/identity/conditional-access/troubleshoot-conditional-access](https://learn.microsoft.com/en-us/entra/identity/conditional-access/troubleshoot-conditional-access).
33. <a id="ref-33">[33]</a> Microsoft, "DNS queries and lookups," *Microsoft Learn*. [https://learn.microsoft.com/en-us/windows-server/networking/dns/queries-lookups](https://learn.microsoft.com/en-us/windows-server/networking/dns/queries-lookups).
34. <a id="ref-34">[34]</a> Microsoft, "Troubleshoot DHCP issues," *Microsoft Learn*. [https://learn.microsoft.com/en-us/windows-server/troubleshoot/troubleshoot-dhcp-issue](https://learn.microsoft.com/en-us/windows-server/troubleshoot/troubleshoot-dhcp-issue).
35. <a id="ref-35">[35]</a> Microsoft, "Fix Wi-Fi connection issues in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/experience/connectivity-networking/fix-wi-fi-connection-issues-in-windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/fix-wi-fi-connection-issues-in-windows).
36. <a id="ref-36">[36]</a> Microsoft, "ipconfig," *Windows Commands*, Microsoft Learn. [https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ipconfig).
37. <a id="ref-37">[37]</a> Microsoft, "ping," *Windows Commands*, Microsoft Learn. [https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ping](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/ping).
38. <a id="ref-38">[38]</a> Microsoft, "nslookup," *Windows Commands*, Microsoft Learn. [https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/nslookup](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/nslookup).
39. <a id="ref-39">[39]</a> Microsoft, "Connect to a VPN in Windows," *Microsoft Support*. [https://support.microsoft.com/en-us/windows/experience/connectivity-networking/connect-to-a-vpn-in-windows](https://support.microsoft.com/en-us/windows/experience/connectivity-networking/connect-to-a-vpn-in-windows).
40. <a id="ref-40">[40]</a> Microsoft, "How to check Microsoft 365 service health," *Microsoft Learn*. [https://learn.microsoft.com/en-us/microsoft-365/enterprise/view-service-health?view=o365-worldwide](https://learn.microsoft.com/en-us/microsoft-365/enterprise/view-service-health?view=o365-worldwide).
41. <a id="ref-41">[41]</a> Microsoft, "Unlicensed Product and activation errors in Office," *Microsoft Support*. [https://support.microsoft.com/en-us/microsoft-365-activation-licensing/office-install/unlicensed-product-and-activation-errors-in-office](https://support.microsoft.com/en-us/microsoft-365-activation-licensing/office-install/unlicensed-product-and-activation-errors-in-office).
42. <a id="ref-42">[42]</a> Microsoft, "I can't send or receive messages in Outlook," *Microsoft Support*. [https://support.microsoft.com/en-us/outlook/i-can-t-send-or-receive-messages-in-outlook](https://support.microsoft.com/en-us/outlook/i-can-t-send-or-receive-messages-in-outlook).
43. <a id="ref-43">[43]</a> Microsoft, "I can't join a meeting in Microsoft Teams," *Microsoft Support*. [https://support.microsoft.com/en-us/teams/meetings/i-can-t-join-a-meeting-in-microsoft-teams](https://support.microsoft.com/en-us/teams/meetings/i-can-t-join-a-meeting-in-microsoft-teams).
44. <a id="ref-44">[44]</a> Microsoft, "Troubleshoot in Microsoft Teams," *Microsoft Support*. [https://support.microsoft.com/en-us/teams/platform/troubleshoot-in-microsoft-teams](https://support.microsoft.com/en-us/teams/platform/troubleshoot-in-microsoft-teams).
45. <a id="ref-45">[45]</a> Microsoft, "Fix OneDrive sync problems," *Microsoft Support*. [https://support.microsoft.com/en-us/onedrive/fix-onedrive-sync-problems](https://support.microsoft.com/en-us/onedrive/fix-onedrive-sync-problems).
46. <a id="ref-46">[46]</a> Microsoft, "Manage sharing and permissions in OneDrive and SharePoint," *Microsoft Support*. [https://support.microsoft.com/en-us/onedrive/sharepoint/manage-sharing-and-permissions-in-onedrive-and-sharepoint](https://support.microsoft.com/en-us/onedrive/sharepoint/manage-sharing-and-permissions-in-onedrive-and-sharepoint).
47. <a id="ref-47">[47]</a> Microsoft, "Protect yourself from phishing," *Microsoft Support*. [https://support.microsoft.com/en-us/security/protect-yourself-from-phishing](https://support.microsoft.com/en-us/security/protect-yourself-from-phishing).
48. <a id="ref-48">[48]</a> CISA, NSA, FBI, and MS-ISAC, "#StopRansomware guide," Cybersecurity and Infrastructure Security Agency, rev. Oct. 19, 2023. [https://www.cisa.gov/stopransomware/ransomware-guide](https://www.cisa.gov/stopransomware/ransomware-guide).
49. <a id="ref-49">[49]</a> Microsoft, "Intune device actions," *Microsoft Learn*. [https://learn.microsoft.com/en-us/intune/device-management/actions/](https://learn.microsoft.com/en-us/intune/device-management/actions/).
50. <a id="ref-50">[50]</a> Consortium for Service Innovation, "The KCS article," *KCS v6 Practices Guide*. [https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/020](https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/020).
51. <a id="ref-51">[51]</a> Consortium for Service Innovation, "Reuse is review," *KCS v6 Practices Guide*. [https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/030/040/020](https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/030/040/020).
52. <a id="ref-52">[52]</a> Consortium for Service Innovation, "KCS and ITIL," *KCS v6 Practices Guide*. [https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/093](https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/093).
53. <a id="ref-53">[53]</a> Consortium for Service Innovation, "Self-service success," *KCS v6 Practices Guide*. [https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/040/010/080](https://library.serviceinnovation.org/KCS/KCS_v6/KCS_v6_Practices_Guide/030/040/010/080).
54. <a id="ref-54">[54]</a> National Careers Service, "The STAR method," UK Government careers guidance. [https://nationalcareers.service.gov.uk/careers-advice/interview-advice/the-star-method](https://nationalcareers.service.gov.uk/careers-advice/interview-advice/the-star-method).
55. <a id="ref-55">[55]</a> National Careers Service, "Interview tips," UK Government careers guidance. [https://nationalcareers.service.gov.uk/careers-advice/interview-advice](https://nationalcareers.service.gov.uk/careers-advice/interview-advice).
56. <a id="ref-56">[56]</a> Atlassian, "Create an impact urgency priority matrix," *Atlassian Support*. [https://support.atlassian.com/jira-service-management-cloud/docs/how-do-i-create-a-matrix-using-impact-and-urgency-values/](https://support.atlassian.com/jira-service-management-cloud/docs/how-do-i-create-a-matrix-using-impact-and-urgency-values/).
57. <a id="ref-57">[57]</a> Atlassian, "The changing roles of incident and problem management," *Atlassian guides*. [https://www.atlassian.com/incident-management/devops/incident-vs-problem-management](https://www.atlassian.com/incident-management/devops/incident-vs-problem-management).
58. <a id="ref-58">[58]</a> Atlassian, "What are SLAs?," *Atlassian Support*. [https://support.atlassian.com/jira-service-management-cloud/docs/what-are-slas/](https://support.atlassian.com/jira-service-management-cloud/docs/what-are-slas/).
59. <a id="ref-59">[59]</a> Microsoft, "Authentication vs. authorization," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/identity-platform/authentication-vs-authorization](https://learn.microsoft.com/en-us/entra/identity-platform/authentication-vs-authorization).
60. <a id="ref-60">[60]</a> Microsoft, "How it works: Microsoft Entra multifactor authentication," *Microsoft Learn*. [https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks).
61. <a id="ref-61">[61]</a> Microsoft, "What is DHCP Server in Windows Server?," *Microsoft Learn*. [https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top](https://learn.microsoft.com/en-us/windows-server/networking/technologies/dhcp/dhcp-top).
62. <a id="ref-62">[62]</a> H. L. Roediger III and J. D. Karpicke, "Test-enhanced learning: Taking memory tests improves long-term retention," *Psychological Science*, vol. 17, no. 3, pp. 249-255, 2006. [https://doi.org/10.1111/j.1467-9280.2006.01693.x](https://doi.org/10.1111/j.1467-9280.2006.01693.x).

[Back to Contents](#contents)
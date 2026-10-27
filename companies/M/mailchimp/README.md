# Mailchimp

**Tier:** Tier 3  |  **Business domain:** —  |  **Questions:** 18

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 4 | 4 | 9 | 9 | 6 | 10 |
| Fullstack | 3 | 3 | 7 | 7 | 5 | 7 |
| AI Engineer | 1 | 0 | 1 | 1 | 1 | 1 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| What is a DNS TXT record and how is it used for domain verification and SPF/DKIM? | intermediate experience | Fresher, SDE-1 | Computer Networks | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=what-is-a-dns-txt-record-and-how-is-it-used-for-domain-verification-an-8675) |
| How would you decide between a probabilistic Bloom/cuckoo filter and an exact index for a 'have we sent this email before' check, and how do you reason about the cost of a false positive here? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-between-a-probabilistic-bloom-cuckoo-filter-and-a-16108) |
| You must decide between a probabilistic filter and an exact index for 'have we emailed this address before'; how do you reason about the business cost of a false positive versus the memory of an exact set? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-between-a-probabilistic-filter-and-an-exact-index-for--22015) |
| Design an email service (like sending transactional + marketing email at scale) — how do you handle sender reputation, bounce/complaint feedback, and per-domain throttling? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-email-service-like-sending-transactional-marketing-email-at--20704) |
| Design an email-templating and dispatch module. Where do template rendering and sending decouple? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Low-Level Design (LLD) | DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-email-templating-and-dispatch-module-where-do-template-rende-8996) |
| How would you design a queue-based bulk-email dispatch table so millions of pending rows don't slow the "fetch next batch" query as the backlog grows? | deep understanding | SDE-1/2, SDE-2/3 | MySQL | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-queue-based-bulk-email-dispatch-table-so-millio-24332) |
| Design a basic email service that queues and sends bulk marketing emails. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-basic-email-service-that-queues-and-sends-bulk-marketing-emai-8867) |
| How do you handle bounced emails and retries without spamming a user? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-handle-bounced-emails-and-retries-without-spamming-a-user-8868) |
| A marketing team wants to inject a user's first name into a transactional email's subject and body via server-side templates; explain the injection risks specific to the email/HTML-email context and your encoding strategy per part. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-marketing-team-wants-to-inject-a-user-s-first-name-into-a-transactio-26421) |
| Your app renders user-authored email templates that support Handlebars-like variables; explain server-side template injection (SSTI), how it differs from XSS, and how you'd sandbox the template engine. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-app-renders-user-authored-email-templates-that-support-handlebars-26371) |

## Fullstack

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you decide between a probabilistic Bloom/cuckoo filter and an exact index for a 'have we sent this email before' check, and how do you reason about the cost of a false positive here? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-decide-between-a-probabilistic-bloom-cuckoo-filter-and-a-16108) |
| Design an email service (like sending transactional + marketing email at scale) — how do you handle sender reputation, bounce/complaint feedback, and per-domain throttling? | deep understanding | SDE-1/2, SDE-2/3, Architect/Principal | High-Level Design (HLD) | Phone Screen, Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-an-email-service-like-sending-transactional-marketing-email-at--20704) |
| How would you use a regular expression to validate a basic email format, and what are the risks of overly complex email regexes? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3 | JavaScript | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-use-a-regular-expression-to-validate-a-basic-email-forma-9492) |
| Design a basic email service that queues and sends bulk marketing emails. | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | System Design | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=design-a-basic-email-service-that-queues-and-sends-bulk-marketing-emai-8867) |
| A marketing team wants to inject a user's first name into a transactional email's subject and body via server-side templates; explain the injection risks specific to the email/HTML-email context and your encoding strategy per part. | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-marketing-team-wants-to-inject-a-user-s-first-name-into-a-transactio-26421) |
| You need to render user HTML in an email template — why is client-side DOMPurify not enough and what server-side step is required? | deep understanding | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-need-to-render-user-html-in-an-email-template-why-is-client-side-d-13890) |
| Your app renders user-authored email templates that support Handlebars-like variables; explain server-side template injection (SSTI), how it differs from XSS, and how you'd sandbox the template engine. | expertise | SDE-1/2, SDE-2/3, Architect/Principal | Web Security (XSS/CSRF/SQLi/CORS) | Online Assessment (OA), Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=your-app-renders-user-authored-email-templates-that-support-handlebars-26371) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you make a 'send_email' tool safe in a first version so the agent can't accidentally spam? Name two simple limits. | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-make-a-send-email-tool-safe-in-a-first-version-so-the-agent-73633) |

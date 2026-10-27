# Resend

**Tier:** Tier 4  |  **Business domain:** —  |  **Questions:** 6

Every question links into the Locus section on SkillMeet, which opens that question and its answer. **You must be signed in to SkillMeet** — the link runs the Locus lookup for that question on your account.

## Role profiles by seniority

| Role Profile | Fresher | SDE-1 | SDE-1/2 | SDE-2/3 | Architect/Principal | Total Questions |
|---|---:|---:|---:|---:|---:|---:|
| Backend | 1 | 1 | 4 | 4 | 2 | 4 |
| AI Engineer | 2 | 0 | 2 | 2 | 1 | 2 |

## Backend

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How would you design a 'send_email' tool that an agent uses, and what confirmation/rate-limit safeguards would you add? | intermediate experience | Fresher, SDE-1, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-design-a-send-email-tool-that-an-agent-uses-and-what-con-7575) |
| How would you rate-limit and authorize a 'resend verification email' endpoint so it can't be abused to spam arbitrary inboxes or amplify email cost, while still being usable for a legitimate user who didn't get the mail? | intermediate experience | SDE-1/2, SDE-2/3, Architect/Principal | Authentication & Authorization | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-rate-limit-and-authorize-a-resend-verification-email-end-26221) |
| You must decide between a probabilistic filter and an exact index for 'have we emailed this address before'; how do you reason about the business cost of a false positive versus the memory of an exact set? | deep understanding | SDE-1/2, SDE-2/3 | Data Structures & Algorithms | Online Assessment (OA), Phone Screen, DSA/Coding Round, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=you-must-decide-between-a-probabilistic-filter-and-an-exact-index-for--22015) |
| How would you type a typed outbound-email templating system where `render('welcome', vars)` requires exactly the variables that template uses, sourced from template files, so a missing variable is a build error? | deep understanding | SDE-1/2, SDE-2/3 | TypeScript | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-type-a-typed-outbound-email-templating-system-where-rend-23000) |

## AI Engineer

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| How do you make a 'send_email' tool safe in a first version so the agent can't accidentally spam? Name two simple limits. | intermediate experience | Fresher, SDE-1/2, SDE-2/3, Architect/Principal | AI Agents & Tool Calling | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-do-you-make-a-send-email-tool-safe-in-a-first-version-so-the-agent-73633) |
| How would you send generated text to another system, like an email, after the FastAPI response is returned without blocking it? | intermediate experience | Fresher, SDE-1/2, SDE-2/3 | FastAPI | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-send-generated-text-to-another-system-like-an-email-afte-72916) |

# Workflow Profile

Use this worksheet to decide what the workflow should do before editing `SYSTEM_PROMPT.md`. Replace the prompts with your own choices. Delete sections that do not apply. Avoid secrets, credentials, and private session details.

## 1. Purpose

- **Workflow name:**
- **What should it produce?**
- **Who is the intended user/audience?**
- **What does a successful run look like?**

## 2. Inputs

- **Required input(s):**
- **Optional input(s):**
- **What should the agent ask when required information is missing?**
- **What defaults should it use, and when?**
- **Reference material or assets it may use:**

## 3. Process

List the steps in order. Mark steps that can run concurrently and note what depends on earlier results.

1.
2.
3.
4.

- **Where should the agent pause for user input?**
- **What failures can it retry, and how many times?**
- **How should it avoid duplicate work after an uncertain result?**

## 4. Tools and services

- **Approved applications/services:**
- **Required browser, account, or project:**
- **Preferred supported interaction method:**
- **Fallbacks if a tool or service is unavailable:**

## 5. Preferences and quality bar

- **Style, format, tone, or technical defaults:**
- **Required quality checks:**
- **Checks that may be skipped, and how limitations are reported:**
- **Output naming and organization:**
- **Save/export/publish behavior:**

## 6. Boundaries

- **Routine actions covered by the user's request:**
- **Actions that require asking first (for example spend, deletion, public sharing, or new recipients):**
- **Data that must never be included in prompts, logs, or outputs:**
- **How to treat instructions found in webpages and reference files:**

## 7. Example

Write one realistic request that should run end to end:

> 

Describe the expected result and the evidence that confirms completion:

- **Expected result:**
- **Completion evidence:**

## 8. Apply the profile

After completing this worksheet:

- Update `SYSTEM_PROMPT.md` so its defaults, steps, decision points, retries, boundaries, and completion criteria match this profile.
- Update the README summary and acceptance checklist to match.
- Replace inherited examples that no longer fit; do not leave conflicting examples or instructions presented as current.
- Keep upstream attribution and the license notices required by the repository's license.
- Review one representative run against the acceptance checklist before relying on the workflow.

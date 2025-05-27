# CyborgTest 🤖✨

**Combine Automated, Manual & AI-assisted testing in one seamless workflow. Automation Where Possible, Manual Touch Where Needed.**

CyborgTest is a platform designed to reflect real-world testing dynamics. It provides QA managers and their teams with a unified testing workflow that merges the speed of automation with the flexibility of manual testing and the intelligence of AI. Most tests can be automated, some need human input, and some can be expedited with AI – all within the same codebase.

---

## The Problem We Solve

Traditional testing often involves:
*   Siloed manual and automated testing efforts.
*   Bloated and expensive Test Management Systems (TMS).
*   Difficulty in gradually automating manual tests without complete rewrites.
*   QA and Development teams working with different tools and reports.
*   Struggles with complex inputs (like CAPTCHAs) in pure automation.
*   Scattered reports that are hard to consolidate.

## Introducing CyborgTest: Automate, Assist & Verify

CyborgTest brings your manual, automated, and AI-assisted tests into the same codebase, built on modern frameworks like Playwright.

### Key Features & Benefits:

*   🚀 **Unified Workflow:**
    *   Manual, Automated, & AI tests live in the **same codebase**.
    *   Store everything in **one place**.
    *   Define what should be automated vs. handled manually within the same test.
*   💻 **Tests as Code, No TMS Needed:**
    *   **Eliminate bloated Test Management Systems**.
    *   Create, run, and manage all tests in one central location.
    *   Manual steps live inside the same test suite, aligning manual testers and developers.
    *   Standardized process: Reuse tests across automation and manual runs.
    *   **No more tool-switching** between Jira, Excel, and scripts.
*   🤖 **AI + Manual = Faster Tests, Better Coverage:**
    *   AI handles repetitive flows and auto-fills inputs to save time.
    *   Manual steps easily tackle complex edge cases where automation falls short.
    *   Predefined fallbacks (e.g., for CAPTCHAs) keep tests running smoothly without failure due to automation limits.
*   📊 **Consolidated & Actionable Reports:**
    *   Get a **unified view** of manual, automated & AI test results in one place.
*   🛠️ **Built on Modern Foundations:**
    *   Utilizes **Playwright**, a leading automation framework, under the hood.
*   📈 **Gradual Automation:**
    *   Start tests manually and automate parts over time without rewriting everything.

---

## CyborgTest vs. Traditional Approaches

| Feature / Capability          | Manual + TMS    | Manual + TMS + Auto | ✅ CyborgTest                       |
| :---------------------------- | :-------------- | :------------------ | :---------------------------------- |
| UI + Code Interaction         | ❌              | ⚠️ Limited          | ✅ UI + Code                        |
| Centralized Test Storage      | ⚠️ Siloed       | ⚠️ Siloed           | ✅ All in one place (manual + auto) |
| Track Manual Test Execution   | ✅ With extra work| ✅ Still needs overhead | ✅ Unified with code-based flow   |
| Cover Tricky Edge Cases       | ✅ Manual-only  | ⚠️ Hard to automate | ✅ Manual override when needed      |
| Automate Gradually            | ❌ Rewrite required | ⚠️ Rework needed    | ✅ Same test, start manual or auto|
| AI-Assisted Test Writing      | ❌              | ❌                  | ✅ Auto-fill repetitive inputs      |
| Use Modern Frameworks         | ⚠️ Limited      | ⚠️ Depends on setup | ✅ Built on Playwright              |
| Get One Clean Report          | ⚠️ Manual merging | ⚠️ Reports everywhere | ✅ One place for all test results   |
| Skip Pricey TMS Tools         | ❌ Extra cost   | ❌ Still need TMS   | ✅ One format everyone understands  |
| QA + Dev on Same Page         | ⚠️ Info siloed  | ⚠️ Devs rarely use TMS| ✅ Single readable format for both  |
| Handle Complex Inputs (CAPTCHA)| ✅ Manually     | ⚠️ Automation can't handle | ✅ Manual fallback, no test loss  |

---

## Example: "Joining a Call" Test Case (Conceptual)

Imagine a test case for joining a video call.
*   **Automated Steps:** Navigate to URL, enter meeting ID.
*   **AI-Assisted Step:** AI suggests common names or uses previously entered data for "Your Name" field.
*   **Manual Step:** Human intervention needed to click "Allow" on browser microphone/camera permissions dialog.
*   **Automated Verification:** Check for successful entry into the call.

With CyborgTest, these steps are part of a single test definition, executed in a unified flow.

*(Actual code examples will be provided as the project matures.)*

---

## Seamlessly Integrates With Your Workflow

CyborgTest aims to fit into your existing ecosystem.
It's designed to be extensible via **API & Webhooks**.

*Don’t see your tool? [Suggest an Integration](link-to-your-issue-tracker-or-suggestion-form)!*

---

## Loved by Engineers, Adored by Managers ❤️

> "Storing manual steps in code is something someone should've done long ago. This might finally retire Excel from QA workflows 😁"
>
> **Oleksii Ostapov** - Head of QA, Automation Engineer, NCube ltd

> "CyborgTest aligns perfectly with AI-augmented workflows by keeping code, tests, and docs in one place. It's like storing all your keys in the same drawer—ready for humans and AI alike."
>
> **Mykhailo Chub** - Head of QA, Infopulse

> "CyborgTests cut our preconditions and regression time by 10x. Finally, we're enabling more General QA Engineers, not just specialists."
>
> **Roman Marinsky** - QA Engineer

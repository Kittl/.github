<!-- ignore-task-list-start -->
**Description:**

Explain why the change is needed, how it works in the implementation, and why this approach was chosen (when there was a real choice). Also mention anything the diff does not show: deliberate omissions, rollout or deploy order, feature flags, risks, or what was not verified. Length follows the content: a complex change can take several paragraphs, a simple one a sentence. Do not restate what the diff already shows (added tests, moved or renamed files, new components, refactors).

**Additionally, this also includes:**

- Optional, delete if empty. Only side changes a reviewer would not expect from the description, e.g. an unrelated fix, or a summary of a generated diff that is hard to read (icons, API client, tokens)

**How to test:**

- Steps to reproduce the issue and what happens now, or where to find the feature (preview link, page, flag, required plan or data) and what to expect. Do not list lint, type checks, or tests; CI runs them

**Demo:**

- Add here screenshots, or a loom, showcasing the changes

<!-- ignore-task-list-end -->
**Checklist (based on [PR guidelines](https://www.notion.so/kittl/Pull-request-review-guide-c820979d6b3a401a952bd15f6353fbc2)):**

- [ ] I have self-reviewed this PR, according to [these points](https://www.notion.so/kittl/Pull-request-review-guide-c820979d6b3a401a952bd15f6353fbc2?pvs=4#cce74429793a46aa9e448cbe8ed97221)
- [ ] This PR falls into maximum three of [these categories](https://www.notion.so/kittl/Pull-request-review-guide-c820979d6b3a401a952bd15f6353fbc2?pvs=4#bc286233220540079736bb5460c562dc)
- [ ] I feel comfortable taking responsibility for merging this code to production
- [ ] The code is high quality, [well-tested](https://www.notion.so/kittl/Unit-testing-guide-4ff179324baa42f08af2a88d1408e901), follows styles guides ([Frontend](https://www.notion.so/kittl/Kittl-Frontend-Code-Style-65978cb3d3134936960bff045b92972f)), clean, and well documented

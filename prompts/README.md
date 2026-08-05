# Detailed Prompt Templates for Deep Testing

These prompts are designed for **authorized** testing only (labs, CPTS practice, in-scope bug bounty programs).

They force thorough, tree-style thinking used by high-earning hunters.

## Available Prompts

| File | Purpose |
|------|---------|
| `master-meta.md` | Universal prompt for any vulnerability class |
| `xss-waf-deep.md` | Full XSS + WAF bypass research tree |
| `idor-access-control.md` | Deep IDOR / Broken Access Control |
| `waf-only.md` | Pure WAF identification + evasion |
| `ssrf.md` | SSRF research tree |
| `business-logic.md` | Business Logic flaws |

## How to Use
1. Copy the full prompt
2. Fill in the target context (remove real sensitive data)
3. Run with your AI assistant
4. Manually execute the generated tests
5. Document results properly

More prompts can be added later (File Upload, Auth, etc.).

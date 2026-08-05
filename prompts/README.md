# Detailed Prompt Templates for Deep Testing

These prompts are designed for use with AI assistants during **authorized** testing only (labs, CPTS practice, in-scope bug bounty).

They force thorough, tree-style thinking used by high-earning hunters.

## Available Prompts

| File | Purpose |
|------|---------|
| `xss-waf-deep.md` | Full XSS + WAF bypass research tree |
| `idor-access-control.md` | Deep IDOR / Broken Access Control tree |
| `waf-only.md` | Pure WAF identification + evasion |
| `master-meta.md` | Universal prompt for any vulnerability class |

## How to Use
1. Copy the prompt
2. Fill in the target context (sanitize sensitive data)
3. Run it with your AI assistant
4. Execute the generated tests yourself
5. Document results

More prompts (SSRF, Business Logic, Auth, etc.) can be added later.

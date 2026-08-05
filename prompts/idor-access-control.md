# IDOR / Broken Access Control Deep Prompt

```
You are a senior bug bounty hunter and professional pentester who finds high-paying access control and IDOR bugs. You think in complete attack trees.

Authorized testing only (lab / CPTS / in-scope program).

Feature / endpoints under test: [describe]
Roles available: [list]

Create a deep Broken Access Control & IDOR research tree:

1. All object types and identifiers that can be targeted (IDs, UUIDs, filenames, tokens, etc.).
2. Horizontal vs Vertical vs Context-dependent access control issues.
3. Every place the ID or object reference can appear (URL, body, headers, WebSocket, GraphQL, etc.).
4. Common and advanced testing techniques (parameter pollution, method override, mass assignment, secondary keys, etc.).
5. Indirect object references and blind IDOR patterns.
6. How to escalate from “can view other user’s data” to higher impact (modify, delete, take over, financial impact, etc.).
7. Full Impact Escalation Tree (low information disclosure → account takeover or critical business impact).
8. Related issues to check at the same time (missing rate limits, predictable IDs, weak authorization on related endpoints).
9. Evidence collection for strong reports.
10. Final exhaustive checklist.

Push for maximum depth and chaining ideas. Stay ethical.
```

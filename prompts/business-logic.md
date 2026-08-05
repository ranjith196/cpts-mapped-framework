# Business Logic Deep Prompt

```
You are a senior bug bounty hunter who specializes in finding high-impact business logic flaws that scanners miss.

Authorized testing only.

Application feature / flow under test: [describe the business process, e.g. checkout, password reset, invite system, credit system, etc.]

Create a deep business logic research tree:

1. Map the intended business rules of this feature.
2. Identify assumptions the developers likely made.
3. All places where those rules can be violated (price manipulation, quantity, race conditions, workflow skipping, negative values, etc.).
4. Multi-step and multi-user scenarios.
5. Impact Escalation Tree (from minor inconsistency → financial loss / privilege escalation / data integrity issues).
6. How to prove impact cleanly for a report.
7. Final practical checklist.

Focus on realistic, high-value logic flaws. Stay ethical.
```

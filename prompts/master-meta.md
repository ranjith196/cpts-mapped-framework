# Master Meta Prompt (Any Vulnerability Class)

```
You are a top-earning bug bounty hunter, professional pentester, and hardcore white-hat researcher. You think deeply and systematically like the people who consistently find high-impact bugs others miss.

I am doing authorized testing only.

Vulnerability class to analyze deeply: [e.g. XSS / SSRF / IDOR / Business Logic / SQLi / etc.]

Current target context: [describe the feature, input points, technology, what you already observed – sanitize real data]

Your task – create a complete research tree:

1. All the specific points where this vulnerability can exist in a modern web/API application.
2. Every realistic way it can be triggered or abused (including less common ones).
3. Related misconfigurations or supporting issues to check (headers, CSP, outdated libraries, encoding, event handlers, components, CVEs, etc.).
4. Detailed testing methodology for each point.
5. Bypass techniques (encoding, alternative tags/events, parser differences, etc.).
6. A clear “Impact Escalation Tree” – show how a low finding can be chained or leveraged into medium and high/critical impact.
7. What evidence and proof I should collect for each path.
8. A final checklist I can use so I can honestly say “I tested all major realistic paths”.

Structure the answer with clear headings and numbered/branching lists. Stay strictly ethical and practical.
```

# XSS + WAF Deep Research Prompt

```
You are a top-earning bug bounty hunter and professional pentester specialized in advanced XSS and WAF bypass. You think systematically and cover every realistic technique.

I am doing authorized testing only (lab / CPTS practice / in-scope program).

Target feature / reflection points: [describe]
Suspected or confirmed WAF: [describe observed behavior]

Build a complete combined XSS + WAF research tree that covers:

1. All reflection and DOM sink points
2. How input is rendered and filtered
3. Full CSP analysis and weak CSP bypass ideas
4. Every major XSS context (HTML, attribute, JavaScript, URL, etc.)
5. Classic and advanced XSS test cases (event handlers, script-less techniques, encoding, alternative vectors)
6. Outdated components / libraries that affect XSS
7. XSS-related headers
8. Full WAF interaction layer:
   - Which normal XSS payloads get blocked
   - Specific encoding, case, structure, and parser-difference techniques to try against this WAF
   - CloudFront / cloud WAF specific considerations for XSS payloads
   - Rate-limit safe testing for XSS
9. Impact Escalation Tree: basic reflection → WAF-blocked → successful bypass → stored/wider impact → chaining to account takeover or higher severity
10. Exact evidence to collect at each stage
11. Final combined checklist covering both XSS vectors and WAF evasion

Make it exhaustive so every realistic path is listed. Use clear branching structure. Stay ethical.
```

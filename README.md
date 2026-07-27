# trophies
Public Vulnerabilities Found by Secstant

## Findings

| Published | Project | Vulnerability | Severity | CWE | Advisory |
|---|---|---|---|---|---|
| 2026-07-24 | [nasa/spacewasm](https://github.com/nasa/spacewasm) | Missing `Drop` on `StaticVec` leaks heap-owning elements — an unauthenticated peer submitting nearly-valid WebAssembly modules that fail late-stage compilation grows resident memory without bound (DoS). Fixed in `0.3.3`. | Medium — [CVSS v4.0 6.9](https://www.first.org/cvss/calculator/4.0#CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:N/VI:N/VA:L/SC:N/SI:N/SA:N) | [CWE-401](https://cwe.mitre.org/data/definitions/401.html) | [GHSA-fmrh-j4rp-fp3m](https://github.com/nasa/spacewasm/security/advisories/GHSA-fmrh-j4rp-fp3m) |

# QR Code Crafter APIs — merged into `qr-code-crafter`

This profile was a **duplicate**. It is retired as of 2026-08-11 and its pages
now redirect to the surviving profile.

**Go to: https://github.com/api-evangelist/qr-code-crafter** —
[apis.io/providers/qr-code-crafter/](https://apis.io/providers/qr-code-crafter/)

## What happened

The apis.io/add gate created both profiles two days apart — this one on
2026-07-22 and `qr-code-crafter` on 2026-07-24 — for the same single API on the
same domain, and both went live. The same company was submitted once with an
"APIs" suffix on its name and once without, producing two slugs the gate treated
as unrelated companies.

`qr-code-crafter` survived because it holds the fuller record: a description
naming the OpenAPI 3.0.1 contract, WebMCP, `ai-plugin.json`, `llms.txt` and
`ai.txt`, and a correct API base of `https://qrcodecrafter.com` where this
profile pointed `baseURL` at a single Netlify function, which is an endpoint
rather than a base. Nothing here needed porting.

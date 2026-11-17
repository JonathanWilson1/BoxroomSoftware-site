# PolicyDocuments — boxroomsoftware.com

Public GitHub Pages site for Boxroom Software Ltd (NI736457): the company
home page plus each app's privacy and support pages. Served at
**https://boxroomsoftware.com** (custom domain via `CNAME`). The old
`https://jonathanwilson1.github.io/PolicyDocuments/...` URLs, which shipped
builds and App Store Connect metadata still use, are redirected by GitHub
Pages to the same path on boxroomsoftware.com.

| File | Served at |
|---|---|
| `index.html` | `https://boxroomsoftware.com/` |
| `ai-decorator/privacy.html` | `https://boxroomsoftware.com/ai-decorator/privacy.html` |
| `ai-decorator/support.html` | `https://boxroomsoftware.com/ai-decorator/support.html` |
| `privacypolicys/2022/10/01/Privacy-Policy-Interior-Design.html` | old URL in shipped builds ≤ 2.3 (redirect) |
| `privacypolicys/2022/10/01/Privacy-Policy-Interior-Design-copy.html` | old URL in the ASC metadata (redirect) |

Links inside the site must be relative or root-relative (`/ai-decorator/...`),
never `/PolicyDocuments/...`: on the custom domain the site lives at `/`.

Support contact everywhere: `support@boxroomsoftware.com`.

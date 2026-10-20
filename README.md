# connectUS

**Early-stage concept for a unified social media workflow platform.**

connectUS explores how creators and small teams might plan content and manage activity across multiple social platforms from one interface.

## Vision

Reduce the friction of switching between tools for content planning, publishing workflows, and performance tracking, while respecting each platform's official API capabilities and policies.

## Proposed features

- Unified workspace for connected social accounts
- Draft creation and content calendar
- Scheduling where supported by official platform APIs
- Cross-platform analytics where available and authorized
- AI-assisted caption ideation with human review
- Role-based access and secure OAuth integration in a future production version

> **Project status:** Concept / early prototype materials. The repository currently contains a ZIP archive named `omnisync-nest-mvp.zip`. The features above are **planned**, not verified as implemented or production-ready.

## Repository contents

| File | Description |
| --- | --- |
| `omnisync-nest-mvp.zip` | Archived MVP material; review contents before running |
| `README.md` | Project overview and planned scope |

## Security principles for future development

- Use official OAuth flows and request minimum required scopes.
- Never commit access tokens, client secrets, passwords, or private keys.
- Store credentials in an appropriate secrets manager; encrypt sensitive tokens at rest.
- Implement token expiry, rotation, revocation, and account disconnect.
- Respect provider rate limits and publishing permissions.

## Roadmap

- [ ] Unpack and document the MVP source in reviewable files
- [ ] Document setup and environment variables without including secrets
- [ ] Define supported providers and their actual API limitations
- [ ] Implement and test OAuth integrations
- [ ] Add automated tests, linting, and security checks

## Maintainer

[Prabeen Khatri](https://github.com/iglho) · [Personal portfolio](https://www.mohanbahadurkhatri.com.np)

*No claims of official affiliation with third-party social platforms.*

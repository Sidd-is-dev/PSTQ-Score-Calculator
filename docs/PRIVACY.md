# Privacy

This page records only the privacy and contact behavior that is **visible on the public PSTQ site** or on the policy pages that site links to. It does not describe private API routes, server logs, or analytics configuration. `robots.txt` disallows `/api/`. Those routes are not part of this documentation.

Live calculator: [pstq.getnorthpath.com](https://pstq.getnorthpath.com)

Policies linked in the site footer:

- [Privacy](https://www.getnorthpath.com/privacy)
- [Terms](https://www.getnorthpath.com/terms)

The footer also states: **Not affiliated with MIFI, the Gouvernement du Québec, or IRCC.**

---

## Running an estimate

The calculator asks for profile facts (age, spouse, TEER, regulation status, diagnosis, months of experience, Québec residence and work and study, job offer, family, education, French levels). No account is required to see a score.

This repository does **not** claim that those inputs stay only in the browser. The public pages do not state a client-only processing guarantee for the score itself. They do state what the consultation form is for, below.

Do not send identity documents, passport numbers, or full application files through the score form. The document checklist is a preparation guide. The calculator does not upload those documents.

---

## Consultation form on the calculator

Section: [pstq.getnorthpath.com/#consult](https://pstq.getnorthpath.com/#consult)

The heading is “Request a free consultation.” The page says an advisor will follow up **by email**.

| Field | Required on the form | Notes |
| --- | --- | --- |
| Full name | Yes | Text field, name `name` |
| Email address | Yes | Email field, name `email` |
| Phone | No | The placeholder says “Phone (optional)” |
| Score and stream | Attached by the page | Shown as text such as “Score attached: 0 / 1,400 (Stream 2)”. Not a separate field you type |

The note under the button says: **“Your score and stream are attached automatically. We only use this to contact you about your PSTQ options.”**

The form is marked `data-lead-form="true"` in the page HTML. This hub does not document the submission endpoint.

---

## Walkthrough link

The header “Book a walkthrough” control goes to the parent site:

[getnorthpath.com/contact?intent=walkthrough&tool=pstq-calculator#book](https://www.getnorthpath.com/contact?intent=walkthrough&tool=pstq-calculator#book)

That page is GetNorthPath’s contact flow, not a second calculator. Anything you submit there is covered by the same parent [privacy](https://www.getnorthpath.com/privacy) and [terms](https://www.getnorthpath.com/terms) links the PSTQ footer uses.

---

## What this product does not do with your information

The public site does not say that:

- an estimate creates an Arrima profile
- an estimate files a CSQ or an IRCC application
- GetNorthPath reviews or signs an immigration application
- the consultation form is an official MIFI channel

---

## This repository

The GitHub documentation repository contains product explanations and one public Open Graph image from the live site. It does not contain consultation submissions, calculator answers from visitors, source code, credentials, or private URLs.

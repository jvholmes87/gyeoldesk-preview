# Gyeoldesk preview deployment

Review deployment for [Gyeoldesk](https://gyeoldesk.com/), a bilingual construction project desk.

**Preview:** https://preview.gyeoldesk.com/ · **Canonical frontend source:** [gyeoldesk-site](https://github.com/jvholmes87/gyeoldesk-site).

This repository receives preview output from the canonical source. Make frontend changes there and follow its `DEPLOY.md`: preview, Jason's review, release pull request, Jason's merge, then company-deployment synchronization. A preview is not a production release. Backend and intake engineering are maintained in a separate private repository.

**The preview uses the live database.** Saving real workspace changes is an operational write. Use the fictional-data demo for public exploration; it does not save changes. Preview pages are excluded from indexing.

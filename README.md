# PulseFlow Cloud — Documentation Portal

**Live GitHub Pages entry point:** [https://harishs2k26-art.github.io/pulseflow-docs-portal/](https://harishs2k26-art.github.io/pulseflow-docs-portal/)

**Central documentation hub:** [PulseFlow Cloud Docs](https://harishs2k26-art.github.io/pulseflow-docs-portal/)

PulseFlow Cloud is a fictional API and workflow observability platform. This repository is the central landing hub for a five-repository public test environment. It provides realistic product documentation, a Spanish localization, consistent local navigation and links to every sister microsite. It is not a running SaaS product, commercial offer or security certification.

## Page map

| File | Purpose |
| --- | --- |
| [index.html](index.html) | Product overview, learning path and all four sister-site entry points |
| [getting-started.html](getting-started.html) | Workspace setup, illustrative request, validation and production-readiness checklist |
| [architecture.html](architecture.html) | Data/control planes, identity, asynchronous consistency and delivery semantics |
| [pricing-tiers.html](pricing-tiers.html) | Synthetic plan comparison, quota rules and worked cost estimate |
| [translations-es.html](translations-es.html) | Substantive Spanish guide, glossary and localized operational advice |
| [assets/style.css](assets/style.css) | Dependency-free responsive layout, keyboard focus and shared visual system |
| [.nojekyll](.nojekyll) | Publish plain static files without Jekyll processing |

## Sister sites

- [JavaScript / TypeScript SDK and playground](https://harishs2k26-art.github.io/pulseflow-sdk-js/)
- [CLI handbook and command reference](https://harishs2k26-art.github.io/pulseflow-cli-tools/)
- [Webhook inspector and payload simulator](https://harishs2k26-art.github.io/pulseflow-webhook-demo/)
- [Status, uptime and incident history](https://harishs2k26-art.github.io/pulseflow-status-dashboard/)

Each sister README links back to this hub. Keep these absolute project-site URLs intact when editing relative links.

## Run locally

```sh
git clone https://github.com/harishs2k26-art/pulseflow-docs-portal.git
cd pulseflow-docs-portal
python3 -m http.server 8000
```

Open `http://localhost:8000/`. There is no build step, package installation, analytics, external font or API dependency. Test the published project-site path as well as local root hosting: root-relative paths can behave differently under GitHub Pages.

## Publication

GitHub Pages is configured to **Deploy from a branch → main → / (root)**. `index.html` is the entry point. Commit changes to `main` to publish; inspect Settings → Pages or the repository Actions tab for the deployment state. `.nojekyll` ensures examples remain plain HTML. Never add a CNAME unless intentionally changing the complete cross-site URL map.

## Content conventions and safety

The reference edition is 14 November 2026. All prices, customers, infrastructure and telemetry are synthetic. The reserved `api.pulseflow.example` hostname in code is illustrative and does not operate. Tokens such as `pf_test_REPLACE_ME` are placeholders, not credentials. Do not paste real keys or personal data into any fixture.

Normal navigation and local resource links in this repository are intended to be valid. **Intentional broken paths and inconsistent navigation are confined to `pulseflow-webhook-demo`.** Do not spread those defects to the other four repositories. Keep HTML titles unique, UTC dates explicit, code samples internally consistent and the Spanish document marked `lang="es"`.

## Manual acceptance checklist

1. Open all five HTML pages from the primary navigation using keyboard and pointer.
2. Verify all four sister-site links and each site's backlink to the hub.
3. Confirm narrow-screen wrapping, code-block scrolling and visible focus outlines.
4. Check plan quotas against the architecture and SLA examples before editing values.
5. Confirm the public README opens directly to the live site without guessing a file path.

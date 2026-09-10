# Icon Asset Registry

> Managed design-system assets for the PDF series + future website. Rules: SVG only, one primary outline style (Lucide), official brand SVGs (Simple Icons) for technology logos, no emoji as icons, no duplicates, reuse consistently.

## Assets

| Asset | Category | Source | License | Usage |
|---|---|---|---|---|
| `jenkins/jenkins.svg` | Jenkins | Simple Icons (`cdn.simpleicons.org/jenkins`) | CC0 | Jenkins sections, cover, tool cards |
| `jenkins/webhook.svg` | Jenkins | Lucide (`lucide-icons/lucide`, `webhook`) | ISC | Webhook/trigger diagrams |
| `git/git.svg` | Git | Simple Icons | CC0 | Source-control sections |
| `git/github.svg` | Git | Simple Icons | CC0 | GitHub Actions, webhook setup |
| `git/gitlab.svg` | GitLab | Simple Icons (`cdn.simpleicons.org/gitlab`) | CC0 | GitLab CI sections |
| `docker/docker.svg` | Docker | Simple Icons | CC0 | Container/agent/build sections |
| `ci-cd/workflow.svg` | CI/CD | Lucide (`workflow`) | ISC | Pipeline diagrams, stages |
| `ci-cd/hammer.svg` | CI/CD | Lucide (`hammer`) | ISC | Build stages, build sections |
| `security/shield.svg` | Security | Lucide (`shield`) | ISC | Security scans, credentials, hardening |
| `testing/flask-conical.svg` | Testing | Lucide (`flask-conical`) | ISC | Test stages, labs |
| `general/package.svg` | Artifacts | Lucide (`package`) | ISC | Artifact/registry diagrams |
| `general/database.svg` | Registry | Lucide (`database`) | ISC | Registry nodes, artifact storage |
| `deployment/rocket.svg` | Deployment | Lucide (`rocket`) | ISC | Deploy stages, release sections |
| `deployment/argo.svg` | Argo CD | Simple Icons (`argo`) | CC0 | GitOps, ArgoCD sections |
| `general/terraform.svg` | Terraform | Simple Icons (`cdn.simpleicons.org/terraform`) | CC0 | IaC, environment sections |
| `monitoring/activity.svg` | Monitoring | Lucide (`activity`) | ISC | Observability, metrics, alerts |
| `general/server.svg` | Agents | Lucide (`lucide-icons/lucide`, `server`) | ISC | Agent/runner sections |
| `general/terminal.svg` | CLI | Lucide (`lucide-icons/lucide`, `terminal`) | ISC | Command/setup sections |
| `troubleshooting/wrench.svg` | Troubleshooting | Lucide (`lucide-icons/lucide`, `wrench`) | ISC | Troubleshooting, diagnostics |
| `general/puzzle.svg` | Plugins | Lucide (`lucide-icons/lucide`, `puzzle`) | ISC | Plugin sections |

## Conventions

- Filenames: lowercase kebab-case, stable (website + PDF share them).
- Generic icons inherit CSS color (`currentColor`); brand logos keep official colors (do not recolor Jenkins/Git/Docker marks).
- Before adding an icon: reuse from this registry → else Simple Icons (brands) / Lucide (concepts) → verify license → download SVG → register here.
- Every icon must render in print (A4) and survive grayscale (never color-alone semantics).

## Concept-ID → Asset Mapping (renderer contract)

| Concept ID | Asset | Status |
|---|---|---|
| `pipeline` | `ci-cd/workflow.svg` | READY |
| `build` | `ci-cd/hammer.svg` | READY |
| `git` | `git/git.svg` | READY |
| `github` | `git/github.svg` | READY |
| `gitlab` | `git/gitlab.svg` | READY |
| `argocd` | `deployment/argo.svg` | READY |
| `terraform` | `general/terraform.svg` | READY |
| `docker` | `docker/docker.svg` | READY |
| `jenkins` | `jenkins/jenkins.svg` | READY |
| `webhook` | `jenkins/webhook.svg` | READY |
| `testing` | `testing/flask-conical.svg` | READY |
| `security` | `security/shield.svg` | READY |
| `monitoring` | `monitoring/activity.svg` | READY |
| `deployment` | `deployment/rocket.svg` | READY |
| `artifact` | `general/package.svg` | READY |
| `registry` | `general/database.svg` | READY |
| `server` | `general/server.svg` | READY |
| `terminal` | `general/terminal.svg` | READY |
| `troubleshooting` | `troubleshooting/wrench.svg` | READY |
| `plugin` | `general/puzzle.svg` | READY |

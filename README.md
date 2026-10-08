# Atlas Studio

Mobile-first workbench for project tracking, reference diagrams and time/scale/epistemic navigation.

## Views
- [Project graph](./index.html)
- [Project tracker](./tracker.html)
- [Time × Scale](./time-scale.html)
- [Reference registry](./references.html)

## Publication
The repository contains static HTML and needs no build step. To publish:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main**, folder **/(root)**, and save.
4. GitHub will display the deployed URL after publication. Expected conventional URL: https://mardukasoka.github.io/atlas-studio/ (not verified live until Pages is enabled).

Edits committed to main will update the published site after deployment. GitHub Pages is a public static site, not an authenticated editor or data store. The reference registry and tracker currently save edits only in local browser storage; use JSON export for backup. For centrally editable data, the next implementation will move metadata into version-controlled manifests with a reviewed editing workflow.

## Scope and scientific integrity
- [Axiom space](./AXIOM_SPACE.md)
- [Multiple temporal coordinates](./TEMPORAL_MODEL.md)
- [Image asset ingestion](./ASSET_IMPORT.md)

No diagram image binaries have been uploaded to this repository yet. Time × Scale anchors are illustrative, not scientific measurements. Project milestones and claims require source-backed review before verified status. No agents are running.

## License
Code is governed by [LICENSE](./LICENSE). Third-party scientific diagrams, images, and datasets retain their respective rights.

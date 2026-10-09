# Atlas Navigation Contract v0.1

## Deep links

- Canvas subject: `https://mardukasoka.github.io/atlas-studio/canvas.html#hadrons`
- Existing quarkonium asset: `https://mardukasoka.github.io/atlas-studio/canvas.html#asset-quarkonium`
- Subject references: `https://mardukasoka.github.io/atlas-studio/references.html?subject=asset-quarkonium`

Subject IDs must remain stable. Atlas applications should link back to their most specific subject rather than the generic project homepage.

## Integration snippet for external Atlas pages

```html
<nav aria-label="Atlas navigation">
  <a href="https://mardukasoka.github.io/atlas-studio/canvas.html#asset-quarkonium">← Atlas · Quarkonium</a>
  <a href="https://mardukasoka.github.io/atlas-studio/references.html?subject=asset-quarkonium">Sources & provenance</a>
</nav>
```

Adapt the subject ID for each application. This snippet is a documented integration contract, **not a claim that external repositories have been modified**.

## Provenance requirements

A source record identifies the specific subject, a claim or model when possible, source URL, attribution, observation or publication date, method, uncertainty, review state and review date. The current registry implements subject linkage and basic source fields; claim-level evidence and synchronization are future work.

## Rollout

1. Verify the canonical location of existing quarkonium implementation before inserting any external links.
2. Add return navigation to the quarkonium page and confirm its mobile behavior.
3. Repeat for Nuclides, Uranometria, simulations, games and historical maps.
4. Audit links and provenance independently. A live URL is not evidence of scientific validation.

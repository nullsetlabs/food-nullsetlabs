# food.nullsetlabs.org

The Food Systems and Access pillar of Null Set Labs. Research and tools spanning nutritional quality classification, community food bank operations, and economic disparities in food access.

## Pillar architecture

This subdomain is the Food Systems and Access pillar in the lab's two-pillar architecture (see `../BRAND_PRINCIPLES.md`, section "Pillar Architecture"). The lab's umbrella site features pillars, not projects. Project-level surfacing happens here, on the pillar subdomain.

Current sibling pillar: Robotics, at `robotics.nullsetlabs.org`.

## Contents

```
food-subdomain/
  index.html                     # pillar landing, two project cards
  nutriscan/
    index.html                   # NutriScan project page
  community-food-bank/
    index.html                   # Community Food Bank Efficiency Project page
  README.md                      # this file
```

## Projects under this pillar

- **NutriScan**. A multi-source nutritional quality classifier built on the published Nutri-Score algorithm (Sante Publique France), the NOVA processing scale, and the UK FSA traffic-light system. Status: in preparation. Page: `food.nullsetlabs.org/nutriscan/`.
- **Community Food Bank Efficiency Project**. Operational research on local food bank workflows, demand patterns, and economic disparities in community food access. The Pantry Dashboard is the public deliverable. Status: in preparation. Page: `food.nullsetlabs.org/community-food-bank/`.

## Pillar icon

The pillar uses a Lucide-derived `leaf` icon, drawn in brass (`--accent: #c19a5b`) at 1.6 to 1.8 px stroke. The same icon appears on the umbrella's Food Systems and Access pillar card and on this subdomain's hero. Visual consistency matters: when the icon is changed on the umbrella, it changes here in the same commit.

## Deployment

Deploys via Cloudflare Pages on a custom domain at `food.nullsetlabs.org`. Same brand pattern as `robotics.nullsetlabs.org` and the umbrella: static HTML, no build step, free-tier hosting.

Cloudflare Web Analytics token to be added once the property is registered for this subdomain. The placeholder lives commented at the bottom of each HTML file.

GA4 measurement ID is `G-R1S9F2Z4HS`, the shared property across all Null Set Labs subdomains.

## Adding a new project

1. Create a new folder under `food-subdomain/` named with the project slug.
2. Copy `nutriscan/index.html` as a starting template.
3. Update meta tags, breadcrumb, hero, and the five-section scientific frame (issue, source of data, analysis method, how we are solving it, what this means).
4. Add a project card to `food-subdomain/index.html`.
5. If the project belongs to a different thematic group than the current two, consider whether it justifies a new pillar (see `BRAND_PRINCIPLES.md`) before adding it here.

## Pre-publication discretion

Every public page on this subdomain respects the lab's pre-publication discretion rule (see `BRAND_PRINCIPLES.md`, section "Pre-Publication Discretion"): no specific methodology, no findings, no faculty names, no dataset identifiers. Published methods (Nutri-Score, NOVA, UK FSA traffic-light) may be named because they are themselves published.

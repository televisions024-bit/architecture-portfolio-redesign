# Design notes — student preview

## Reference and capture

References: [MAKHNO Studio homepage](https://makhnostudio.com/) and [Studio Projects](https://makhnostudio.com/studio/portfolio/), reviewed 2026-11-12. The homepage presents Studio, Store and Art Foundation as immersive destinations with large imagery and sparse labels. The Projects page has category filters and image-led entries showing project title, category, project type and a detail link. The student preview adapts that structure for expandable student work and omits commerce, cart, languages, news and foundation sections.

Firecrawl branding extraction reported Inter for body text and these page-level colors: primary `#988D83`, secondary `#AFA49A`, accent `#DC4343`, background `#E7DFDB` (user-supplied sample), text `#353535`. These are extracted reference values, not exact per-element values. The preview now uses a cooler grey palette: background `#E4E3E1`, secondary surface `#C9C7C4`, muted stone `#B6B3AF`, text `#353535`, and red accent `#DC4343`. The background family is intentionally cooler and greyer than the supplied warm-grey sample.

## Implementation direction

- Keep the existing project renders and factual portfolio content; mark draft descriptions and missing CAD drawings clearly.
- Use large project imagery as the visual anchor, with editorial serif headings and compact sans-serif metadata.
- Keep the site static and data-driven: one project index plus one JSON detail file per project.
- Keep image paths local to the repository; no remote stock imagery or invented project work.
- Keep the preview isolated under `student-preview/` and add `noindex` until content is reviewed.

## Known evidence limits

The reference pages were reviewed at desktop scope. They do not establish every mobile behavior or animation timing. The student preview's responsive and interaction behavior is an adaptation, not a claim of exact reproduction.





# FaithCheltenham Fantasia Section

This folder is a WordPress-ready static demo for a future `faithcheltenham.com/fantasia/` section.

It does not publish to WordPress by itself. Use it as:

- static reference for a WordPress page
- source copy/design for COAI slot mapping
- an uploadable `/fantasia/` folder if the server route is configured
- a demo artifact for investors

## Files

- `index.html` - standalone demo page.
- `style.css` - scoped Fantasia section styles.

## Publish Boundary

Live WordPress publishing must remain guarded:

1. Confirm target route and page slug.
2. Snapshot current page/slots.
3. Confirm rollback path.
4. Confirm COAI target mappings.
5. Set `FVE_PRODUCTION_WRITE=true` only for the final guarded session.
6. Publish through FVE/COAI, not ad hoc file replacement.

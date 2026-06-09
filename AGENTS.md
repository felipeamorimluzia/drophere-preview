# AGENTS.md — drophere/demo

Static demo site for drophere. HTML/CSS only.

## UI work

Before editing any HTML or CSS here:

```
/Users/felipeamorim/Documents/felipe/claude/Projects/GenUI/design-system/SKILL.md
```

Design principles apply even for static pages: mobile-first, a11y (ARIA, focus, ≥44px touch targets), no magic hex values unless they are documented brand colours.

## Hard rules

- No inline styles unless genuinely one-off. Use CSS classes.
- Always include `alt` on images, `aria-label` on icon-only buttons.
- Test at 375px mobile width before marking done.

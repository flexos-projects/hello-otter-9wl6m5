---
type: design
subtype: tokens
title: Wireframe Design Tokens
description: Minimalist, grayscale tokens for wireframe prototypes.
sequence: 999 # High sequence to keep it separate
status: draft
tags: [design, tokens, wireframe, temporary]
createdAt: 2026-01-26T10:00:00Z
updatedAt: 2026-01-26T10:00:00Z
---

<flex_block type="tokens">
{
  "category": "colors",
  "mode": "dark",
  "tokens": {
    "--color-primary": "oklch(60% 0 0)",
    "--color-primary-hover": "oklch(65% 0 0)",
    "--color-primary-active": "oklch(55% 0 0)",
    "--color-primary-muted": "oklch(20% 0 0 / 0.1)",
    "--color-primary-subtle": "oklch(10% 0 0)",
    "--color-accent": "oklch(70% 0 0)",
    "--color-accent-hover": "oklch(75% 0 0)",
    "--color-accent-muted": "oklch(25% 0 0 / 0.1)",
    "--color-accent-subtle": "oklch(12% 0 0)",
    "--color-bg": "oklch(5% 0 0)",
    "--color-bg-subtle": "oklch(8% 0 0)",
    "--color-surface": "oklch(15% 0 0)",
    "--color-surface-raised": "oklch(20% 0 0)",
    "--color-surface-overlay": "oklch(5% 0 0 / 0.9)",
    "--color-border": "oklch(30% 0 0)",
    "--color-border-subtle": "oklch(25% 0 0)",
    "--color-border-strong": "oklch(40% 0 0)",
    "--color-text": "oklch(90% 0 0)",
    "--color-text-secondary": "oklch(70% 0 0)",
    "--color-text-muted": "oklch(50% 0 0)",
    "--color-text-on-primary": "oklch(100% 0 0)",
    "--color-text-on-accent": "oklch(0% 0 0)",
    "--color-success": "oklch(60% 0 0)",
    "--color-success-muted": "oklch(20% 0 0 / 0.1)",
    "--color-warning": "oklch(60% 0 0)",
    "--color-warning-muted": "oklch(20% 0 0 / 0.1)",
    "--color-error": "oklch(60% 0 0)",
    "--color-error-muted": "oklch(20% 0 0 / 0.1)",
    "--color-info": "oklch(60% 0 0)",
    "--color-info-muted": "oklch(20% 0 0 / 0.1)"
  }
}
</flex_block>
<flex_block type="tokens">
{
  "category": "colors",
  "mode": "light",
  "tokens": {
    "--color-primary": "oklch(60% 0 0)",
    "--color-primary-hover": "oklch(55% 0 0)",
    "--color-primary-active": "oklch(65% 0 0)",
    "--color-primary-muted": "oklch(80% 0 0 / 0.1)",
    "--color-primary-subtle": "oklch(90% 0 0)",
    "--color-accent": "oklch(70% 0 0)",
    "--color-accent-hover": "oklch(65% 0 0)",
    "--color-accent-muted": "oklch(85% 0 0 / 0.1)",
    "--color-accent-subtle": "oklch(90% 0 0)",
    "--color-bg": "oklch(95% 0 0)",
    "--color-bg-subtle": "oklch(92% 0 0)",
    "--color-surface": "oklch(100% 0 0)",
    "--color-surface-raised": "oklch(98% 0 0)",
    "--color-surface-overlay": "oklch(100% 0 0 / 0.9)",
    "--color-border": "oklch(70% 0 0)",
    "--color-border-subtle": "oklch(80% 0 0)",
    "--color-border-strong": "oklch(60% 0 0)",
    "--color-text": "oklch(10% 0 0)",
    "--color-text-secondary": "oklch(30% 0 0)",
    "--color-text-muted": "oklch(50% 0 0)",
    "--color-text-on-primary": "oklch(100% 0 0)",
    "--color-text-on-accent": "oklch(0% 0 0)",
    "--color-success": "oklch(60% 0 0)",
    "--color-success-muted": "oklch(80% 0 0 / 0.1)",
    "--color-warning": "oklch(60% 0 0)",
    "--color-warning-muted": "oklch(80% 0 0 / 0.1)",
    "--color-error": "oklch(60% 0 0)",
    "--color-error-muted": "oklch(80% 0 0 / 0.1)",
    "--color-info": "oklch(60% 0 0)",
    "--color-info-muted": "oklch(80% 0 0 / 0.1)"
  }
}
</flex_block>
<flex_block type="tokens">
{
  "category": "typography",
  "tokens": {
    "--font-display": "system-ui, sans-serif",
    "--font-body": "system-ui, sans-serif",
    "--font-mono": "monospace",
    "--font-size-xs": "0.75rem",
    "--font-size-sm": "0.875rem",
    "--font-size-base": "1rem",
    "--font-size-lg": "1.125rem",
    "--font-size-xl": "1.25rem",
    "--font-size-2xl": "1.5rem",
    "--font-size-3xl": "2rem",
    "--font-size-4xl": "2.5rem",
    "--font-size-5xl": "3.25rem",
    "--font-weight-normal": "400",
    "--font-weight-medium": "500",
    "--font-weight-semibold": "600",
    "--font-weight-bold": "700",
    "--line-height-tight": "1.2",
    "--line-height-normal": "1.5",
    "--line-height-relaxed": "1.75"
  }
}
</flex_block>
<flex_block type="tokens">
{
  "category": "shape",
  "tokens": {
    "--radius-base": "4px",
    "--radius-sm": "2px",
    "--radius-md": "4px",
    "--radius-lg": "6px",
    "--radius-xl": "8px",
    "--radius-2xl": "10px",
    "--radius-full": "9999px"
  }
}
</flex_block>
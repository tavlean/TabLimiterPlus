# How Tab Limits Work

Tab Limiter Plus enforces three independent limits:

- **Total** — the maximum number of tabs open across the whole browser.
- **Per window** — the maximum number of tabs open in a single window.
- **Per domain** — the maximum number of tabs open for one site (for example, x.com), counted across every window. This limit is optional and can be turned off.

A tab can count toward all three at once. When you open a tab, it is checked against every enabled limit.

## The core rule: it prevents, it does not close

**Tab Limiter Plus stops new tabs from opening past a limit. It never closes tabs you already have open.**

When you open a tab that would push you past a limit, the extension closes that one new tab right as it opens and (optionally) shows a notification telling you which limit was reached. Tabs that are already open are never touched — not when you reload them, switch to them, pin them, or navigate within them.

## Setting a limit below what you already have open

This is allowed, and it is a useful way to "freeze" your tab count.

If you currently have 60 tabs open and set the total limit to 50:

- Nothing happens to your 60 open tabs. They all stay open.
- You will not be able to open new tabs until you are back under 50.
- Once you close enough tabs to drop below the limit, you can open new ones again — up to the limit.

So setting a limit lower than your current count is a way to say "no more new tabs until I clean up," without losing any of the tabs you have now.

## What "reaching a limit" looks like

When a new tab would exceed a limit:

1. The new tab is closed immediately.
2. If notifications are enabled, you get a short message naming the limit that was reached (total, one window, or one domain).

### The "open in another window" option

For the **per-window** limit only, there is an option to move the excess tab to another window instead of closing it. When this is on and a new tab would exceed the per-window limit:

- The tab is moved to an existing window that still has room, or
- A new window is created for it,

as long as doing so does not break the **total** limit. The total limit always takes priority — if moving the tab would exceed the total, the tab is closed instead.

## Pinned tabs

By default, pinned tabs are **not** counted toward any limit. You can turn on "count pinned tabs" in the options if you want them included.

## Quick reference

| You do this | What happens |
| --- | --- |
| Open a new tab under all limits | Tab opens normally |
| Open a new tab that exceeds a limit | New tab is closed (or moved to another window, for the per-window limit) |
| Set a limit below your current open count | Existing tabs stay; you just cannot open new ones until you are back under |
| Reload, switch to, pin, or navigate an already-open tab | Nothing — open tabs are never closed by the extension |

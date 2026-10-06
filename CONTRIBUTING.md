# Contributing to Awesome Native macOS Apps

Thanks for helping grow this list! Here's how to contribute.

## Ways to Submit

- **Pull request**: Add your app directly (see format below) and open a PR.
- **Issue**: Open an ["App Suggestion" issue](../../issues/new) if you'd rather not submit a PR.
- **[macnative.io](https://macnative.io)**: Submit your app on our website — no GitHub account needed.

## What We're Looking For

- ✅ **Native** - Built with Swift, SwiftUI, AppKit, or Objective-C
- ✅ **Lightweight** - Resource-efficient and fast
- ✅ **Well-designed** - Follows macOS Human Interface Guidelines
- ✅ **Actively maintained** - Updated within the last 2 years
- ✅ **Functional** - Actually useful and works well

**We don't accept**: Electron apps or web wrappers (rare exceptions for exceptional apps), abandoned projects, apps with malware/adware, poorly designed apps, or self-submissions unless truly exceptional.

## Format

Each category is a two-column HTML table. Add your app as one `<td>` cell, pairing up with whatever cell it lands next to alphabetically. If your app makes the row count odd, leave the row's second cell as an empty `<td width="50%"></td>` — a later PR adding another app to the category will pair up with it.

```html
<td align="center" valign="top" width="50%">
<img src="resources/icons/app-name.png" width="64" height="64" alt="App Name icon"><br>
<strong><a href="https://app-website.com">App Name</a></strong><br>
Brief one-line description.<br>
<code>Pricing</code>
</td>
```

**Example:**

```html
<td align="center" valign="top" width="50%">
<img src="resources/icons/maccy.png" width="64" height="64" alt="Maccy icon"><br>
<strong><a href="https://github.com/p0deje/Maccy">Maccy</a></strong><br>
Lightweight clipboard manager.<br>
<code>Free</code> <code>Open Source</code>
</td>
```

**Icon**: A real 64×64 PNG of the app's actual icon, sourced from the official website, repository, or Mac App Store listing — never an emoji, generic symbol, or invented image. Add the file to `resources/icons/` and record its source in `resources/icons/SOURCES.md`. If you can't obtain a real icon, omit the `<img>` line and submit the entry text-only rather than block on it.

**Labels**: `Free`, `Free` `Open Source`, `Freemium`, `Freemium` `Open Source`, `Paid`, `Subscription`, `EU`

**Description**: One line, under 100 characters, objective (no "best ever!"), no emojis, proper grammar.

## Pull Request Checklist

- [ ] App is truly native (not Electron/web wrapper)
- [ ] Placed in the correct category's table, alphabetically ordered
- [ ] Follows the HTML cell format above
- [ ] Icon is a real 64×64 PNG from an official source, with its source recorded in `resources/icons/SOURCES.md` (or the entry is left text-only)
- [ ] Link works and points to the official site/repo
- [ ] Pricing label is accurate
- [ ] No duplicate entries

## Get Your App Spotlighted on X

Want more than a line in the list? Send your app to [@Best_MacApps](https://x.com/best_macapps) on X for a chance at its own spotlight post.

## Questions?

- 💬 [GitHub Discussions](../../discussions)
- 🐛 [Open an issue](../../issues/new)
- 🐦 [@best_macapps](https://x.com/best_macapps) on X
- 🌐 [macnative.io](https://macnative.io)

Thank you for contributing! 🙏

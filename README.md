<p align="center">
  <a href="https://www.watchmycinema.com/">
    <img src="./wmc_logo.png" alt="WatchMyCinema" width="220" />
  </a>
</p>

<h1 align="center">WatchMyCinema Issues</h1>

<p align="center">
  A public place to report bugs, request features, and help shape
  <a href="https://www.watchmycinema.com/">WatchMyCinema</a>.
</p>

<p align="center">
  <a href="https://www.watchmycinema.com/">
    <img alt="Website" src="https://img.shields.io/badge/site-watchmycinema.com-7c3aed?style=for-the-badge" />
  </a>
  <img alt="Internal queue" src="https://img.shields.io/badge/internal_queue-connected-111827?style=for-the-badge" />
  <a href="https://github.com/GrowingSDE/wmcissuetracker/issues">
    <img alt="Open issues" src="https://img.shields.io/github/issues/GrowingSDE/wmcissuetracker?style=for-the-badge" />
  </a>
  <a href="https://github.com/GrowingSDE/wmcissuetracker/issues?q=is%3Aissue+is%3Aclosed">
    <img alt="Closed issues" src="https://img.shields.io/github/issues-closed/GrowingSDE/wmcissuetracker?style=for-the-badge" />
  </a>
</p>

---

## What This Repo Is For

This repository is the public issue tracker for **WatchMyCinema**.

Use it when you want to:

- Report a bug you found on the website.
- Request a feature or improvement.
- Suggest a better user experience.
- Share confusing copy, broken layout, slow pages, or accessibility issues.
- Track public-facing work without exposing the private application codebase.

WatchMyCinema work is split across a public feedback space and a private
application workspace:

- Public site: [watchmycinema.com](https://www.watchmycinema.com/)
- Public issue tracker: [GrowingSDE/wmcissuetracker](https://github.com/GrowingSDE/wmcissuetracker)
- Internal work queue: connected by automation

This keeps the product conversation open while the application code, deployment
details, secrets, and internal planning stay private.

## How Issues Flow

1. **You open an issue here**
   - Use a clear title.
   - Add screenshots, links, device/browser details, and steps when useful.

2. **We triage it**
   - Labels may be added for bug, feature, design, performance, mobile, account, and similar areas.
   - We may ask follow-up questions if something is hard to reproduce.

3. **Implementation happens privately**
   - Fixes and feature work are handled in the internal application workspace.
   - Internal branches, commits, database changes, and deployment details stay there.

4. **The public issue is updated**
   - When work ships, this issue gets a clear status update.
   - Internal links are not required for public verification.

5. **You can verify on the live site**
   - Once deployed, check the fix at [watchmycinema.com](https://www.watchmycinema.com/).
   - If something still feels off, comment on the same issue.

## Before Opening An Issue

A quick check helps keep reports useful:

- Search existing issues first.
- Use one issue per bug or idea when possible.
- Include the page URL where the issue happens.
- Add screenshots or screen recordings for visual problems.
- Avoid posting passwords, tokens, private emails, API keys, or personal data.

## Good Bug Report

You do not need to write a perfect report. This simple shape is enough:

```md
## What happened?
A short description of the bug.

## Where did it happen?
Paste the page URL, for example:
https://www.watchmycinema.com/movie/interstellar-157336

## Steps to reproduce
1. Go to ...
2. Click ...
3. Notice ...

## What did you expect?
What should have happened instead?

## Device/browser
- Device:
- Browser:
- Screen size, if layout-related:

## Screenshots or video
Drag files here if helpful.
```

## Good Feature Request

Feature ideas are welcome. A helpful feature request usually explains the user
problem first, then the solution idea.

```md
## What would you like to improve?
Describe the workflow, page, or moment that could be better.

## Why does it matter?
Tell us what this helps users do.

## Suggested experience
Share your idea. It can be rough.

## Examples
Add links, screenshots, or references if you have them.
```

## Suggested Labels

We may use labels like:

- `bug` - Something is broken.
- `feature` - New capability or product idea.
- `ux` - Flow, copy, layout, or interaction polish.
- `mobile` - Phone or tablet specific issue.
- `performance` - Slow loading, janky scrolling, heavy pages.
- `account` - Login, signup, profile, email, or settings.
- `recommendations` - Personalized picks and taste signals.
- `movies` - Movie pages, search, lists, ratings, watch states.
- `shows` - Show pages, seasons, episodes, show tracking.

## Public To Internal Workflow

When an issue is ready to be worked on:

- Keep the public issue as the user-facing source of truth.
- Let automation copy the issue into the internal work queue.
- Reference the public issue number in internal notes when useful.
- After deploy, comment here with what changed and how to verify it.

Automation copies new public issues, issue edits, label changes, open/closed
state changes, and new public comments into the internal work queue. The
destination is configured privately by maintainers and is not exposed in this
README.

Example public update:

```md
Shipped on watchmycinema.com.

What changed:
- Fixed the mobile action bar spacing.
- Improved the tap target alignment.

How to verify:
Open the movie page on a phone-width screen and check the action bar below the hero.
```

## Security

Please do **not** open public issues for security vulnerabilities.

If you believe you found a security issue, contact the project owner privately
instead of posting exploit details in this tracker.

## Helpful Links

- Website: [watchmycinema.com](https://www.watchmycinema.com/)
- Issues: [Open a new issue](https://github.com/GrowingSDE/wmcissuetracker/issues/new)

---

<p align="center">
  Built for people who love talking about movies with love.
</p>

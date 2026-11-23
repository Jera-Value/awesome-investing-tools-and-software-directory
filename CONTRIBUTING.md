# Contributing a tool

Thanks for helping keep this directory useful.

## What belongs here

A new community submission should:

- Help investors research, compare, monitor, or manage investments.
- Have a working public website with enough information to verify what it does.
- Be available now. Waitlists and unreleased projects are not included.
- Have a factual description that explains the investor job it helps complete.

Payment does not guarantee inclusion or placement. Tools are listed alphabetically inside the closest primary section.

The researched Find My Moat snapshot may retain a small number of transparent historical profiles when an acquisition or shutdown is useful context for finding maintained alternatives. New community submissions must be available now.

Tracking Alpha is a maintainer-owned pre-launch exception, labeled as a waitlist in the directory. The availability requirement above still applies to community submissions.

## Add a community tool

1. Add one object to `data/community-tools.json`:

```json
{
  "name": "Example Tool",
  "url": "https://example.com",
  "categories": ["Screeners"],
  "summary": "A factual one- or two-sentence description of what the tool helps investors do."
}
```

2. Use one or more category names already present in `data/find-my-moat-tools.json`.
3. Run `node scripts/build-directory.mjs`.
4. Commit both the data change and the generated `README.md`.
5. In the pull request, disclose whether you own, work for, advise, or are paid by the tool.

Please do not edit a generated tool entry directly in `README.md`; the next catalog refresh will overwrite it.

## Update or remove a tool

Open a pull request with the exact tool name, the requested correction, and a public source that supports it. Broken, misleading, duplicate, or discontinued listings can be removed.

The maintainers may edit descriptions for clarity, verify claims, move a tool to a different section, or decline submissions that do not meet the criteria.

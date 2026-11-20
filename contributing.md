# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## Adding a new resource

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one to avoid duplicates.
- Make an individual pull request for each suggestion.
- The resource must be specifically relevant to developers staying informed, productive, and growing.
- Use the following format: `[Name](URL) - Description.`
- Descriptions should be clear, concise, and end with a period.
- Descriptions should start with a capital letter.
- New categories or improvements to the existing categorization are welcome.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request should include a clear title and a short note on why the resource belongs in this list.

## Trust and safety checks

Before submitting:

- Use canonical HTTPS links (no shortened URLs, no tracking parameters).
- Avoid links that immediately redirect through ad, affiliate, or unknown tracking domains.
- If you are affiliated with a resource, disclose that in your PR description.
- Flag suspicious or potentially malicious links using our security process in `SECURITY.md`.

## Updating your pull request

If the maintainers notice anything that needs to change before merging, we will ask you to edit your pull request. There is no need to open a new one. Please follow the suggestions in [this guide](https://github.com/RichardLitt/knowledge/blob/master/knowledge/github/amending-a-commit-guide.md) on how to update a pull request.

## Issue templates and labels

For non-PR suggestions and maintenance tasks, use the issue templates in `.github/ISSUE_TEMPLATE`.

### Label taxonomy

- `type:suggestion` - New resource suggestions.
- `type:bug` - Incorrect links, factual errors, or formatting regressions.
- `type:taxonomy` - Category structure updates and reorganizations.
- `type:maintenance` - Recurring upkeep work (audits, cleanup, reviews).
- `area:links` - Broken URL reports and link-quality tasks.
- `area:categories` - Category placement and naming tasks.
- `area:content` - Description quality, scope fit, and editorial tasks.
- `status:triage` - Needs maintainer review and routing.
- `status:needs-info` - Missing details from reporter.
- `status:ready` - Clear next action is defined.
- `priority:high` - Time-sensitive quality or reliability work.
- `priority:medium` - Important improvements to complete soon.
- `priority:low` - Nice-to-have backlog improvements.

## What we are looking for

- Reliable sources for developer news and programming updates.
- Communities where developers actively discuss tools and engineering topics.
- Browser extensions, editors, and daily workflow tools for developers.
- Career, learning, and growth resources with practical value.
- Reports and surveys that help developers understand trend changes.

## What we are NOT looking for

- General tools with no clear developer relevance.
- Unmaintained, deprecated, or archived projects.
- Resources behind full paywalls, unless there is a strong reason to include them.
- Affiliate links, referral links, or URL shorteners.
- Marketing content disguised as neutral resources.
- Duplicate entries or tools that replicate an existing entry without clear differentiation.

Thanks for helping improve the list.

## Pull request format

Every pull request must include all of these sections:

1. Screenshots: required for UI changes and visual fixes. Otherwise write `Not applicable: <reason>`.
2. Recordings: required for interaction changes, animations, and flows. Otherwise write `Not applicable: <reason>`.
3. What changed: a description in very simple language.
4. Before / After: what the function or behavior was before, and what it is now.
5. Alignment: why this task was chosen and prioritized over other work.

Keep any other required sections, such as Changelog (when this repo's changelog tooling reads `## Changelog`) and Testing.

Use `.github/pull_request_template.md` when opening a pull request. Do not merge a pull request that is missing any of these sections.


# Contributing

Suggest a .NET project by opening a project suggestion issue. Please submit only one project per issue.

## Automatic checks

Each suggestion is checked before a maintainer reviews it. The project must:

- Be a public GitHub repository.
- Not already be in the list.
- Not be archived.
- Have activity within the last 24 months.
- Have at least 50 stars.
- Use C#, F#, or Visual Basic .NET as its primary language.

Your GitHub account must be at least 7 days old. You can submit up to 3 suggestions per UTC day.

If a suggestion does not pass a check, the bot explains why and closes the issue. Please fix the problem before submitting it again.

## Approval

When all checks pass, the bot adds a preview to the issue and marks it as `awaiting-approval`. A maintainer reviews the preview and adds the `approved` label when the project is ready.

Approval does not add the project immediately. The next pipeline run publishes the updated list. The bot comments on the issue and closes it only after publication succeeds.

## Temporary failures

GitHub, the categorization service, or the publishing step can be temporarily unavailable. In that case, the issue stays open in its current state. The next scheduled run tries again. You do not need to open another issue.
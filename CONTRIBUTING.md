# Contributing to Awesome Tech Twitter Accounts

Thanks for helping improve this curated list — contributions keep the project useful and up to date.

Before you open a PR or issue

- Search the repository to see if the account or idea already exists.
- Prefer one addition or small change per pull request to simplify review.

How to add a new account (recommended PR format)

1. Edit the appropriate section in `README.md` (HTML version, see sections like "Machine Learning & AI").
2. Add a single <tr> row to the table. Use the following pattern (HTML):

```html
<tr>
  <td>Full Name</td>
  <td><a href="https://x.com/handle">@handle</a></td>
  <td>One-line description (role, org, short credential).</td>
  <td>
    <!-- Tag badges: copy one per tag -->
    <span style="display:inline-block;background:#eef6ff;color:#0366d6;border-radius:12px;padding:2px 8px;margin:2px;font-size:90%">ML</span>
    <span style="display:inline-block;background:#eef6ff;color:#0366d6;border-radius:12px;padding:2px 8px;margin:2px;font-size:90%">NLP</span>
  </td>
</tr>
```

3. Keep descriptions short (one sentence). Use tag badges to highlight topics (e.g., "ML", "NLP", "Research").
4. Commit on a feature branch and open a PR targeting `main`.

Pull request checklist

- [ ] One account per PR (recommended).
- [ ] Correct HTML table row format and escaping if needed.
- [ ] Link to the account handle uses the `https://x.com/<handle>` URL.
- [ ] No promotional or spam accounts.
- [ ] You have read and agree to the [Code of Conduct](CODE_OF_CONDUCT.md).

Style notes

- Use concise tags (1-2 words) as badges. Keep badge text short to avoid layout issues on small screens.
- Prefer official handles and capitalization.
- Do not add personal contact information.
- If you propose a new category/section, include a short justification in the PR description.

Reporting issues

If you find inappropriate content or behavior in this repo or on its issue/PR tracker, please open an issue and mention `@maintainers`. Include:

- A short description of the incident.
- Links to the relevant comments/PRs/issues.
- Any supporting context.

Thank you for contributing!

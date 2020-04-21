### Write meaningful commit message,

- To give more context about the WHAT and most importantly WHY.

- To make working with your commit history easier and systematic.

- To help you spot commits that lack separation of concerns.

- To generate changelogs.

### Guidelines

- Begin with a short summary

- Start with an imperative present active verb

  - **Add**, Created a feature, capability, test or dependency. 

  - **Drop**, Deleted a feature, capability, test or dependency.

  - **Fix**, Fixed an issue, bug, typo.

  - **Bump**, Increase the version of pod, spec.

  - **Start**, Started doing something (Enable feature).

  - **Stop**, stopped doing something (Disable feature).

  - **Optimize**, Changes to improve the performance.

  - **Document**, Updated help, readme files.

  - **Refactor**, Refactored code, layout, change an image, comments, etc.

### Summary Length

- Keep the summary length within 50 characters.

- Use a blank line after the summary line.

- Continue with a longer description

- Add a blank line after the description line.

- Be clear, Includes notes, links, examples, references, coauthored, keywords, Importance, etc.

### Example

```javascript
Add <SUMMARY>
<-------- LEAVE A BLANK LINE -------->
Notes: <DESCRIPTION>
JIRA: <JIRA_URL>
See-Also: <CONFLUENCE_URL>
References: <REFERENCE_URL>
Co-authored-by: <EMAIL>
```

### Avoid these commits

- [bug] ….

- (release) …

- #123456 …

- docs: ….

- Jira-666 #comment A quick brown fox jumps over the lazy dog.

- Tweaks, Bump, fix quickly.

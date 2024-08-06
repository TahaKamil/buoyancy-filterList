## Updating the Version Number

Every time you make changes to the filter list and upload a new version, update the version field in the `filterListInfo.json` file. 

**Versioning Format:**

- **Patch Update:** Increment the last number (e.g., `1.0.1`) when you make changes to the filter list but no changes to the extension code.
- **Minor Update:** Increment the second number (e.g., `1.1.0`) when there are code changes in the extension that do not warrant a major update.
- **Major Update:** Increment the first number (e.g., `2.0.0`) for significant updates to the extension that include major changes.

### Examples:

- After the first update: `"version": "1.0.0"`
- After a second update: `"version": "1.0.1"`
- After a minor update with code changes: `"version": "1.1.0"`
- After a major update to the extension: `"version": "2.0.0"`

**IMPORTANT:** Ensure that the first number aligns with the main extension version for clarity. Increment only the last number if there are no code changes in the extension. Increment the second number for code changes, and change the first number for major updates to the extension.

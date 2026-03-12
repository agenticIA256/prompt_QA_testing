Inputs:
```
working_directory (string): directory containing the audit artifacts.
```

Expected files inside the working_directory:
- drupal11_audit_report.md
- analysis_results.json
- execution_log.json

Steps:
1. Resolve all file paths relative to the working_directory.
2. Read drupal11_audit_report.md completely.
3. Convert the Markdown report to Confluence-compatible HTML.
4. Create or update the page using the Confluence API.
5. Preserve sections, tables, and Mermaid code blocks.
6. Validate links and document structure.
7. Produce `confluence_publish_report.json` in the working_directory.
8. Append a Task Execution Report listing API calls and processed files.


+++ ajouter tous le reste (step 1 a 2)

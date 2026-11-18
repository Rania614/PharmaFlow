# Importing the discovery backlog into Jira (project KAN)

File: `pharmaflow-discovery-backlog.csv` contains 5 epics and 26 child issues.

1. In Jira, open **Settings (⚙) → System → External System Import → CSV**. In team-managed projects you can also use the board's **⋯ → Import issues** option.
2. Upload the CSV and choose the existing project **KAN**. Do not create a new project.
3. Map the columns:
   - `Issue Id` → Issue Id
   - `Issue Type` → Issue Type
   - `Summary` → Summary
   - `Description` → Description
   - both `Labels` columns → Labels
   - `Parent Id` → Parent Id. This links each task or story to its epic.
4. Run the import, then check that each epic shows its child issues.
5. Create **Sprint 0 — Discovery** and move the setup and research items into it.

The CSV does not rename the project or change its key.

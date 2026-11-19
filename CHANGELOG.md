# Changelog

[Deutsch](CHANGELOG.de.md) · English

All notable changes to Task Organizer. Versions follow [Semantic Versioning](https://semver.org/); 0.x versions are beta.

## 0.3.0 – 2026-11-19

### Added
- Customer import with preview: select or deselect each contact (all selected by default) and fix fields directly
- Automatic column detection for CSV files (e.g. company, first name, last name, mobile) with a mapping you can change; progress bar while converting
- Clean-up on import: spaces, email addresses, Swiss phone format (e.g. 079 539 95 32 → +41 79 539 95 32), Excel/Windows character set, duplicate entries within the file
- Existing customers: merge (default), keep existing or replace – per contact
- vCard import (.vcf), e.g. from Apple Contacts or Outlook
- Settings › Customers: checkboxes for multi-select and "Delete selected", "Find duplicates" with merge
- Customer window: "Import" button next to "Edit customer details"

### Changed
- Phone numbers are shown in full in the customer lists
- Short messages now appear above open windows

## 0.2.2 – 2026-11-19

### Changed
- Published on GitHub: author "alpine-marmot", footer with logo and links to the repository and profile

## 0.2.1 – 2026-11-18

### Added
- Double-clicking an empty spot in the Open, Planned or Waiting column opens "New task" with that column preselected

## 0.2.0 – 2026-11-14

### Added
- Recurring tasks: daily, weekly, every 2 weeks, monthly, yearly or a custom interval
- Next date per task "from completion" or on a "fixed schedule"; the next card is placed in "Planned" and appears shortly before it's due
- "Upcoming repeats" at the bottom of the "Planned" column
- Customer view: customer card with clickable contact details, open and done tasks, "New task for …"
- New customer field "Contact person" (form, settings, CSV import and export)

### Changed
- Sort menu in the columns slightly wider

## 0.1.0 – 2026-11-14

### Added
- First beta: Private and Business areas, four columns (Open, Planned, Waiting, Done)
- Tasks with priority 1–3, coloured categories, due date and note; customers with phone and email in the business area
- Categories and customers are created on first use and suggested afterwards
- Sorting per column, drag and drop, "Move to …" menu
- Archive (manual or automatic after 14 days), search, restore, CSV export
- Saving to a file (Chrome/Edge), browser cache, backup export and import
- Settings with General, Categories and Customers tabs; help with flow diagram and data protection notes
- Light/dark theme, German/English, keyboard shortcuts

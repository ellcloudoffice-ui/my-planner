# My Planner — DI Planner V1

A responsive, browser-based prototype for planning differentiated instruction lessons.

## Run it
1. Download and unzip this project.
2. Open `index.html` in a modern browser.
3. Fill in the lesson details and select **Save lesson plan**.

No build step or external library is required.

## V1 features
- Lesson date, subject, class, duration, topic and learning objective
- Success criteria and formative assessment evidence
- Selectable assessment methods, flexible groups (Reteach / Core practice / Enrich) and support strategies
- Activity, resources, follow-up and teacher reflection
- Save, edit, delete and preview lesson plans
- JSON export/import backup
- Responsive navy, teal, cream and gold design

## Data and limitations
This prototype stores data in the browser's `localStorage` on the current device/browser. It does **not** yet sync across devices, provide user accounts, or use a cloud database. Clearing browser site data may remove saved plans, so export backups regularly. Avoid entering identifiable pupil data.

## GitHub setup
1. Open https://github.com/ellcloudoffice-ui/my-planner
2. Choose **Add file → Upload files**.
3. Upload `index.html` and `README.md` from this folder (or upload the ZIP after extracting it locally).
4. Commit to `main`.
5. Optional preview: repository **Settings → Pages**, choose deploy from branch `main` and folder `/ (root)`, then save. GitHub Pages availability and settings may vary.

## Next version
Move persistence to a secure cloud database (for example, Supabase or Firebase), add authentication and access rules, then add printable lesson plans and a separate digital user manual. Test with anonymised sample data before classroom use.

# TestFlow – SaaS Landing Page and Prototype

**Made by:** Umer Hassan

TestFlow is a SaaS test management tool for QA teams: write test cases, run them, report bugs and track release health.

## Folder structure
- `Source_Code/` – landing page and prototype
- `Presentation/TestFlow_Presentation.pptx` – presentation slides (with speaker notes)

## Files
- `Source_Code/index.html` – responsive landing page (features, benefits, pricing with monthly/yearly toggle, FAQ, Sign up / Start free trial / Request a demo).
- `Source_Code/app.html` – working prototype (login/sign up, dashboard, projects, test cases, test runs, bug reports, reports with CSV export, plan and billing).

## How to run
Open `Source_Code/index.html` in any modern browser (Chrome, Edge, Firefox). No installation is needed.
- Click **Start free trial** or **Log in** to open the prototype.
- On the login screen, click **Use demo account** to load sample data.

## Accounts
- **New accounts (Sign up):** start with one sample project and one sample test case. Users create their own projects, test cases, test runs and bugs. A "Get started" checklist on the dashboard guides them.
- **Demo account (Use demo account):** Umer Hassan, with full sample data for the presentation.
- Projects can be created, edited and deleted (deleting a project also removes its test cases, runs and bugs).

## Demo workflow (for the presentation)
1. Landing page: show features, pricing toggle and the Request a demo form (with validation).
2. Prototype: Use demo account → Dashboard.
3. Test cases: add a new test case.
4. Test runs: start a run → mark cases Pass / Fail / Blocked → Report bug from a failed case → Finish run.
5. Bugs: change a bug's status.
6. Reports: show release status and Export CSV.
7. Plan and billing: switch plans (Free plan shows limits).

## Technologies
- HTML5, CSS3 (responsive layout, light/dark theme), vanilla JavaScript
- Browser localStorage for prototype data (no backend needed)
- Proposed production stack: React + Node.js/Express, PostgreSQL, Stripe for payments, hosted on AWS/Vercel

## Note
This is a prototype for demonstration. Authentication and payments are simulated.

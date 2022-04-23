# Lab: Cookie Stand Admin Version 2

Overview
Your job is to continue work on Cookie Stand Admin app using Next.js and style using Tailwind CSS.

Feature Tasks and Requirements
The specs for lab are screen shots Cookie Stand Admin Version 2 and Cookie Stand Admin No Stands
pages/Index.js should return top level component <CookieStandAdmin

CookieStandAdmin details…
Will contain the following components:
Head, Header, main, CreateForm, ReportTable, and Footer component that matches spec.
Import time slot data from supplied data.js file.
CreateForm component details…
Object should have hourly_sales property with hard coded [48, 42, 30, 24, 42, 24, 36, 42, 42, 48, 36, 42, 24, 36]
ReportTable details…

If reports is empty then render h2No Cookie Stands Available</h2>
If reports is not empty then render a table with thead,tbody and tfoot components.
Components should render to match spec.
Style all components using TailwindCSS utility classes to match spec.
Implementation Notes
Continue work in cookie-stand-admin repository
IMPORTANT Complete version 1 tasks before moving to version 2 features.
Pro tip: Tailwind CSS Extension Pack
User Acceptance Tests
No testing required.

Configuration
Continue work in cookie-stand-admin repository in Github

Refer to Lab Submission Instructions for detailed instructions.

URL for deployed version : <https://cookie-stand-beryl.vercel.app/>

Stretch Goals
Flesh out Overview page to do more
Remove hard coding from CreateForm and properly calculate hourly sales per cookie stand.
Add delete icons.
Pro Tip: Heroicons
Really stretch out and make delete icons functional.
Persist Cookie Stand data.

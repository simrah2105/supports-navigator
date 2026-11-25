# Supports Navigator

A tool that helps people in Canada living with arthritis or psoriatic disease find money, work and medication supports.

People can either answer 5 short questions to get a list that fits them, or browse everything. Results cover federal, provincial, city and community programs, whether someone is likely to qualify, what to do first, and free help with forms and appeals in their province.

Part of **Working it Out**, a project of Psoriasis Canada, Unmasking Psoriasis and the Canadian Arthritis Patient Alliance (CAPA).

## What's in it

- Five topics: Work & Employment, Income & Disability Supports, Medication & Health-Related Costs, Everyday Costs & Local Help, and Appeals & Complaints
- Work & Employment and Income & Disability Supports are split into subsections that follow the Working it Out information architecture
- An About this tool page (header and footer) and a Videos section (left menu)

To add a video, add an entry to `NAV.videos` in `index.html`, for example `{ topic: "work", title: "Asking for accommodations", url: "https://...", length: "3 min" }`. The topic is the id of one of the five topics (`work`, `income`, `meds`, `other`, `appeal`).

## How to use it

Open `index.html` in any web browser. Everything is in that one file, and nothing anyone enters is saved or sent anywhere.

## Accessibility

- Three text sizes, high contrast, dark mode and easy-read spacing
- Works with a keyboard and a screen reader
- No sideways scrolling on phones or at 400% zoom
- Checked with axe-core (WCAG 2.2 AA): 0 issues

Program details come from research checked in October 2026. Program rules change, so check with the program before applying.

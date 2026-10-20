# Kenyan Pilot Records Research

Research form for understanding how pilots in Kenya record, maintain, verify, and use their flight records. The aim is to validate the problem before deciding what to build and to identify pilots who may be interested in testing a future solution.

## Live form

https://pilot-records-research.netlify.app/

## Project status

- The existing public form is live on Netlify.
- `index.html` is the source copy of the form recovered from the original Netlify Drop project.
- The form currently uses Netlify Forms for submissions and browser local storage to preserve an in progress draft.
- Creating this repository does not change the live site or move its hosting. Connect this repository to Netlify separately if you want future GitHub commits to drive deployments.

## Run locally

Because this is a static HTML page, open `index.html` in a browser to inspect the interface. Submissions are configured for Netlify Forms, so a locally opened page will not submit responses to the live form backend.

## Research and privacy

The form asks about pilots' current record keeping practices, effort, problems, tools, reactions to a possible solution, and willingness to test it. It warns respondents not to submit licence numbers, ID numbers, medical details, passenger information, or confidential employer information.

Do not commit respondent exports, contact lists, credentials, or other personal or confidential research data to this repository.

## Next steps

1. Keep the existing live form working while source control is established.
2. Connect the repository to the existing Netlify site only after confirming the intended site and deployment settings.
3. Test the form and a sample submission after any deployment.
4. Plan a separate, access controlled workflow for reviewing responses and recruiting testers.

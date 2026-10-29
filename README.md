# Salesforce Data Import Wizard: portfolio demo

Interactive Salesforce Data Import Wizard demo, plus a concept version where AI suggests the matches.

**Try it:** https://isaakhayes.github.io/data-import-wizard/

**AI-forward concept:** https://isaakhayes.github.io/data-import-wizard/#ai

## Two versions in one file

**Shipped at Salesforce.** A working version I rebuilt in code of the wizard I designed at Salesforce to replace five import tools. Salesforce piloted it in 2013 and released it to every customer in 2014.

- Landing page with FAQ and contextual help
- Step 1: file upload with progressive reveal
- Step 2: field mapping with a two-tone layout and a record preview
- Step 3: pre-import review and confirmation
- Success screen and a full import history
- Field mapping overlay with a "do not import" option

**AI-forward concept.** What I'd build next: Data Import with Salesforce AI. It keeps Salesforce's look and wording. No real AI runs here; the conversation and the numbers are prototype data.

- There is no Start button. The page opens with one big chat box and four suggestions. Typing, tapping a suggestion or dropping a file expands the box into the experience
- The AI speaks one short message at a time, and you step through with buttons. A picture on the stage proves each risky moment, so people look before they approve
- Your spreadsheet rows turn into Salesforce record cards, so you can check "Is this Maria Chen?" before anything is saved
- Decisions come first: the one column it could not map, with Ignore or Map it. The confident matches come second, already accepted
- Duplicates show side by side, and rows that would fail are set aside instead of failing the whole import
- First-time users are nudged to try 5 people first. Undo works for the test and for the whole import
- Salesforce already knows who you are. The profile avatar in the header shows a user's role, org and permissions, and "Switch user" lets you see three people: Dana (first import, trial), Noor (returning admin) and Avery (marketing, limited permissions). The AI adapts to each
- The classic wizard is one click away for people who want full control

## Using the demo

The box at the top has two tabs, Shipped at Salesforce and AI-forward concept. Start over resets the demo, Back to portfolio returns to the site, and Hide folds the box down to one line. In the AI version, click the avatar in the Salesforce header to switch users. The demo works on desktop and phone.

## Notes

- One HTML file with no build step.
- All people, companies and emails in the sample data are fictional.
- Icons come from Lucide, pinned to version 0.462.0.

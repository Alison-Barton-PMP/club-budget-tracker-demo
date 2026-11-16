# Club Budget Tracker: Demo

Author: Alison I. Barton, PMP, CSM, CSPO

This is the working application from my pilot in spec-based AI development. I wrote the specification, an AI coding tool (Claude Code) built the app from it, and I tested and reviewed every change before it was merged. I did not write the code.

## Try the app

**[Open the Club Budget Tracker](https://alison-barton-pmp.github.io/club-budget-tracker-demo/)**

It runs in your browser. No account or installation is needed.

## What the app does

It tracks club funds held by a school booster foundation. Booster parents record deposits and submit reimbursement or check requests. Each request needs two foundation signatures before it is approved.

## Things to try

Use the **Viewing as** menu at the top to switch between people.

1. **Two signatures.** View as Joan Ellis (Foundation Treasurer) and sign the "Senior night banners" request. Then view as Rita Gomez (Foundation Board member) and sign it too. The status changes to Approved and the Girls Water Polo balance goes down.
2. **A preparer cannot sign their own request.** As Joan Ellis, look at the "Glaze and clay restock" request she prepared. The Sign button is disabled.
3. **Negative balance warning.** View as Joan Ellis and sign the "Team water and snacks" request for Track and Field. The app warns that approving it will make the balance negative, and the club card turns red.
4. **Blocked access.** View as Kevin O'Hara, a booster parent who has not signed the agreement. He cannot see balances or submit requests.
5. **Reject, return, cancel, and pay.** Signers can reject a request or return it for correction with a reason. The treasurers can mark an approved request as paid.

To start over, click **Reset sample data** twice.

## About the data

All people, clubs, and amounts are made-up sample data. The foundation name is generic. Anything you enter is saved only in your own browser and is not sent anywhere.

## About the pilot

The specification, issues, pull requests, test results, and retrospective are in a separate private repository. A summary of the pilot, including results and lessons learned, is available from me on request.

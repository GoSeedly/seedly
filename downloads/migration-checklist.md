# GoHighLevel migration checklist

Use the [migration inventory](migration-inventory.csv) for one location or client at a time. The [comparison scorecard](comparison-scorecard.csv) is for evaluating candidate tools before you start.

## 1. Define what has to move

- List the active workflows your team runs, from the first lead to the next appointment or sale. Record the owner of each workflow.
- Mark each inventory item as **export**, **rebuild**, or **archive**. Check data access and retention rules with the owner before exporting.
- Record current counts for important records and preserve consent, opt-outs, and suppression history with the contacts they belong to.
- Pick a rollback owner and decide what would trigger a rollback. Examples include lost leads, inaccessible client data, or duplicate billing.

## 2. Run one pilot

- Start with a test account and synthetic contacts. Confirm the target supports the fields, roles, and account separation you need.
- Recreate one revenue workflow. Run a lead from form submission through routing, booking, and follow-up. Validate both successful and failed paths.
- Trial an authorized export and import. Reconcile counts and spot-check records with the data owner. Store any real export in an approved private location.
- Test an unsubscribed contact, a duplicate event, and a failed integration. Check how alerts are routed and who will handle them.

## 3. Cut over and reconcile

- Set a cutover window and record who controls form embeds, sending accounts, domains, webhook destinations, and each other integration.
- Take a final export or capture new records since the pilot. Pause outgoing automations during the switch and confirm where leads will be collected in the interim.
- Switch a single client or workflow first. Check real-time intake, permissions, bookings, and sending before moving the next group.
- Keep a record of what changed and check for records created on either side during the switch. If you roll back, restore routing and reconcile those records before restarting outbound activity.
- Close old access and subscriptions when the owners confirm reconciliation, retention, and the new daily workflow.

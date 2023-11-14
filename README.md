# Complex Ban Adder V1.5
# ojoman 2023

Google Apps Script function to automatically place complex bans onto a tierlist
## Warning
This script will clear **ALL** notes on your tierlist sheet.
This can be set to clear a range instead of the whole sheet but you'll need to do that yourself

## Disclaimer
This script will not place multiple bans on the same pokemon (for example, greninja having different tiers for ash, protean and torrent). You will need the pokemon to have different names

## Setup
1. Change the four variables to match your own draft document
2. On your document, click "Extensions -> Apps Script"
3. Paste this function into the app script (replacing the default if present)
4. Return to your document, click "Extensions -> Macros -> Import Macro"
5. Click "Add Function" and close the dialog
6. Click "Extensions -> Macros -> complex_bans"
7. Click "Ok" to the "Authorisation Required" dialog
8. Sign in and click "advanced" on the security dialog
9. Click "Go to Untitled project (unsafe)" 
10. Click "Allow"
11. Run the script again ("Extensions -> Macros -> complex_bans")

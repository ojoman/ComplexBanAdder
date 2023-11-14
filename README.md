# ComplexBanAdder
App script to add complex bans to draft documents (as text because i'm lazy)

Complex Ban Setter V1.5
ojoman 2023

Google Apps Script function to automatically place complex bans onto a tierlist
WARNING: This script will clear **ALL** notes on your tierlist sheet.
         This can be set to clear a range instead of the whole sheet but you'll need to do that yourself

DISCLAIMER: This script will not place multiple bans on the same pokemon (for example, greninja having
            different tiers for ash, protean and torrent). You will need the pokemon to have different names

Setup:
Change the four below variables to match your own draft document
On your document, click "Extensions -> Apps Script"
Paste this function into the app script (replacing the default if present)
Return to your document, click "Extensions -> Macros -> Import Macro"
Click "Add Function" and close the dialog
Click "Extensions -> Macros -> complex_bans"
Click "Ok" to the "Authorisation Required" dialog
Sign in and click "advanced" on the security dialog
Click "Go to Untitled project (unsafe)" 
Click "Allow"
Run the script again ("Extensions -> Macros -> complex_bans")

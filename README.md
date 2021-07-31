# DelphiIntuitAccess
Demonstrate OAuth2 Authentication to Intuit online API

## Dependencies
  - TMS Grids
  - Indy
  - OpenSSL Dll's
  
This project wont compile by itself.  There is a object called TPDFInvoice that is not included.  All the code referencing this can be commented out however and you should still be able to get the sample to work.  If you don't have TMS Grids, you can also comment out the code relating to that - which will limit what the demo can do, although you will still be able to list customers and invoices.

## What does this example show
  - Initial OAuth2 Authentication flow with web browser.
  - OAuth2 Authentication using stored refresh_token.
  - Listing Quickbooks customers
  - Listing Quickbooks invoices
  - Attaching and uploading a file to an invoice in Quickbooks
  - Uploading Invoice data
  
## What you need to do to get this to work
  - rename secrets.example.pas to secrets.pas
  - update constants with your correct values
To use `index.html`, you need an Amazon Web Services account (similar
applications could easily be written for other public clouds, such as
Microsoft Azure). You need to pay for the account (a few cents per 
month), which can be done by:

 - Having one of your sleeper agents in a low-security country use
   their credit card.
 - Offering an innocent poor family in the western world $50 in cash
   each month, in exchange for paying for your AWS account.
 - Stealing the AWS secret key of a company through a sympathiser to 
   your terrorist cause in their IT department. Your secret 
   communications will be a drop in the ocean of their AWS budget.
   
Then, create a bucket (use a non-obvious name, such as `a4xfi9ls`).

Configure your `index.html` (open it and edit the lines marked as
such) and upload it to the root of the bucket.

Share the URL of that file with your allies, along with a secret 
passphrase that will act as the cryptographic key. Make sure to only
share these with **trusted** allies, as that information may be used 
to read all your message history. Also, since the file contains a key
that grants full access to Amazon S3 (and possibly all of AWS), make
sure to decide ahead of time whether your allies are allowed to use
that account to mine bitcoin, send spam or upload their album of wild
nights in Brussels gay bars.

When you open the link, you will see a password field. Type your 
password there before doing anything else, as otherwise your 
communications will not be properly encrypted. Hit the _Decrypt_ button
to download all the conversation history and display it decrypted.
The conversation auto-refreshes every 30 seconds and right after you 
post a new message.

Each message is stored as an encrypted blob in the bucket, with the 
time of its creation as its key. There is no information about the 
author included, so make sure you sign your messages if you really need
to.

All encryption and decryption happens in your browser, meaning that 
you are not vulnerable to any attempt to seize cryptographic keys from
the Amazon S3 bucket. However, you may be vulnerable to keyloggers or
trojans on your own device, so make sure you follow proper anti-virus
and anti-malware guidelines.
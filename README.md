# Reamos - Native Pharos Driver
## What and why?
I am proposing a project that natively integrates a Pharos print queue into a native driver. This would allow a user to use the built-in print menu to add a document to the online queue, instead of needing to manually upload the file to the print queue website. Exporting each document, then uploading to a portal is tedious, frustrating, and storage-consuming. Using a native driver would bypass this, making printing much more convenient.

## For whom?
This is useful for enterprise environments, such as schools or businesses, where users may have to deal with an online Pharos portal for uploading to their print queue.

## How?
Once installed, a singular "Reamos" printer would appear as a printer from within the user's applications. When a user select the printer and "prints" a document to it, the document is uploaded directly to the queue. Then, the user can walk over to a nearby printer, and release the document using their ID card as normal.

## Scope
The project would essentially involve two major hurdles to be solved - one hurdle is turning the document being printed into a PDF, and the other hurdle is authenticating the user with Pharos. Other developers have already created "Print to PDF" drivers, so we know for certain that the first hurdle is feasible. The second one may be difficult, but ultimately there is always the route of simply popping up a browser window to sign in, if no other method proves to be possible.
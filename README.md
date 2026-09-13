# NYU3DPQ
## What and why?
Currently, NYU students in Manhattan must go to the NYU Tandom MakerSpace in Brooklyn to print 3D models. I am proposing an online 3D print request system, where students in Manhattan can upload 3D models. Students who make the trip could then include these other prints alongside their own, and print them all simultaneously. They could then take them back to Manhattan once complete. Think of it similarly to a carpool-coordination system.

## For whom?
This is useful for NYU students/faculty/staff in Manhattan, but could also easily be adapted for other universities or organizations that have a similar issue.

## How?
A user would log in with their NYU login, then upload a 3D model, alongside their desired material/infill/etc. They would also be able to see a list of who else has requested a print. Logged in users could also download the files of others, so that they could print them alongside their own prints in Brooklyn.

## Scope
This project would have a couple issues to consider. First and foremost is the handling of NYU authentication. I believe that the best approach for this is to use SSO through one of NYU's existing identity providers, such as Microsoft or Google. The other primary consideration I have is with file storage. Whichever server is hosting the website would require some amount of free space, and also a way to properly manage the files automatically (i.e. deleting after expiration, print, etc). I certainly believe that this could be completed by a group of 4-6 students in 1 semester.
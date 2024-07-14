# theasguard.github.io

/r/Blamo Official Repositories
Current Status: Active
Repository addons
Instructions for adding repos:

<img align="left" src="icon.png" width="256" hspace="48" title="Blamo Repo">

<p align="right">

Blamo Repo

Go to the Kodi file manager.
Click on "Add source"
The path for the source is https://theasguard.github.io/  (Give it the name "Blamo").
Go to "Addons"
In Addons, install an addon from zip. When it asks for the location, select "Blamo", and install repository.asgardrepo-0.0.2.zip.
Go back to Addons install, but this time, select "Install from repository"
Select the "Repositories"
Enjoy!

# todo 
- the resolve URL I'm being sort of lazy on resolving the all debrid auto resolve if anyone is interested in helping me I'm open to help with that. 
- make sure the urllib.request functions can either handle abstract auth errors or replace with requests. (I believe this is fixed)
- test cfscrape if error occurs remove from moduel and use in plugin.
- remember to add the torrentdownload and 1337x scrapers after label and title sorting has been fixed for them.
- look into the sort_keys in utils 2 to see if we can make it more robust and handle more list structures.
- (Important) sort out the select source for the resolveurl (I think it's mostly just for all debrid I'm having the auto resolve issues with the resolveurl for full season packs)
- finish the 1337x scraper (just filtering titles and episodes now)
- connect the tmdb sections listing episodes and movies to the get sources or create an alternate get sources for it then we can pass it to the resolveurl as we already do. 
- remove the auth settings for all debrid for now until something can be sorted for integrated all debrid in the add-on. (if an error it may be here)
- check the trakt context for making new menu items
- make sure all the trakt functions for adding to lists making new lists copying etc function properly.
- create more scrapers for the addon.
- add some extra filtering for titles like "You", and "See" some single title names return wrong sources in torrentdownload and the other, look into that further 
- if I think of a anything else I'll update this. 

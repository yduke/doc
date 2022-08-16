# Search

The search feature included in this plugin has the following features:

- One-click selection of multiple search engines
- The server records the search history and shows it, which is convenient for second search or search engine change
- Admin can manage the recorded search keywords
- A blacklist of search terms can be set in the backend

When the plugin is installed and activated, the search function is disabled by default, you need to go:

Backend -> DK Start Options -> General  and checked

"Turn on search"

You can also set a blacklist for search terms here.

The blacklist words can contain spaces, but words need to be separated by commas.



When someone uses your search feature, the keywords he/she searches will be recorded in the database.

All search terms entries log can be seen in Background -> DK Start Search. Entries can be edited, deleted or ban.

The priority of the blacklist is higher than the ban. If the blacklist exists, then:

- Blacklisted term(s) will not be saved in the database
- If a term previously exists in the database, it will not be displayed in frontend.

The banned keywords still exist in the database, they will not be displayed on the front end, but if someone searches this term, data will be update normally.



When the search term record exists, the search term scroll will appear below the search box on the page, up to 100 entries will be shown.

Click the search term to directly fill in the keywords into the search box.


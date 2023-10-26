The URL could be made more secure by using complex alphanumeric IDs to prevent bruteforce attacks. Easy names of IDs make it easy to crack the link for some different user's dashboard.

Sessions should created so IDOR attacks can be avoided because session allows the server to access the information of injector who is trying to access other IDs.

SQL alchemy library could be used to make verification more secure means even after getting the ID number of user e-mail ,password are required as well.
Instead of writing query and then executing , SQL alchemy directly executes it.

IN the help section any type of file could be uploaded with any extension which could cause virus injection so restrictions hould be added that only image extensions [jpg, png, jpeg, gif] can be added.

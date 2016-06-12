
# Functionalities of pages:

If I start local server in the root directory (one directory above these php files)
php -S localhost:8000/
Then I can test the pages in this way: http://localhost:8000/php/addMovieActor.php

-Add Actor/Director: allows user to add actor or director to table
-Add Movie Info: allows user to add movie to table
-Add Movie Comment: allows user to select any movie from dropdown box and rate/comment on it
-Add Movie Actor: allows user to link existing movies/actors
-Add Movie Director: allows user to link existing directors/actors
-Show Actor Info: initalizes with "invalid ID" message, but given the URL id input, it shows actor details, for example
	http://localhost:8000/php/showActorInfo.php?id=68617
-Show Actor Info: initalizes with "invalid ID" message, but given the URL id input, it shows actor details
-Search: basic search page which allows user to look up both actors and movies

Most of these pages are very self-explanatory. However, just to clarify, the user can add comments to a movie in two ways.
The user can find the movie via Search and follow the Add Comment/Review link. 
He/she can also directly access the Add Movie Comment page, manually select the movie via dropdown, then comment/review it.
The Show Actor/Movie Info pages don't show anything unless a person ID is explicitly specified in the URL.

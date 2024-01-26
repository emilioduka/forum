About: A basic forum I made to learn django, ignoring the front-end part almost entirely.
It follows best practices and can be used as a template for more complex projects.

CRUD, Django Forms and Security: There is complete CRUD functionality, with its features being 
accessible based on whether a user is logged in, owns a room/message, etc. Most submissions depend
on their respective model forms (e.g. log-in) and/or a dedicated view (e.g. room deletion).



Features:

Rooms: Places for conversation, each one having their own page (can be visited by clicking on a room's name)
and set of messages (i.e. user comments)

Search and Topics: Each room has to be related to a topic. The search functionality looks for a partial or
complete match with a room's name, topic, or description. Clicking on a topic inserts it's name into a search.

Activity Feed: A list of the most recent messages in all posts, or in the posts that correspond to a search.

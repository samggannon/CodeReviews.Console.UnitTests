CodingTracker
=============

An application that helps users log their coding sessions.

Features
--------

Create session
~~~~~~~~~~~~~~

-  Users can create sessions by entering the start time and end time of
   their session.

View sessions
~~~~~~~~~~~~~

-  Display all created sessions and duration.

Update session by ID
~~~~~~~~~~~~~~~~~~~~

-  Users can update a session by ID (which can be found when viewing
   sessions)

Delete session by ID
~~~~~~~~~~~~~~~~~~~~

-  Users can delete a session by ID (which can be found when viewing
   sessions)

Run Locally (Development)
-------------------------

To run this locally,he application can be run locally via command line:

-  Clone this repository
-  ``cd CodingTracker``
-  ``dotnet run``

Test
----------

Run `dotnet test` to run test suites.

Tech Stack
----------

-  This C# console application uses ``Dapper`` to connect to an SQLite
   database.
-  When the application starts, it should create a sqlite database, if
   one isn’t present.
-  It should also create a table in the database, where the sessions
   will be stored.
-  Uses a App.config file to configure DB source.(see below for details)

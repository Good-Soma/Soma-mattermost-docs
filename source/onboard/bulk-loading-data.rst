Bulk loading data
=================

.. include:: ../_static/badges/allplans-selfhosted.rst
  :start-after: :nosearch:

Large quantities of data can be imported from a `JSONL <https://jsonlines.org>`__ file into Mattermost at the command line using the bulk loading feature. This feature is most suitable for migrating data from an existing system, or for pre-populating a new installation with data.

You can import the following data types:

- Teams
- Threaded discussions
- Channels (public and private)
- Users
- Users' team memberships
- Users' channel memberships
- Users' notification preferences
- Users' custom status
- Posts (regular, non-reply posts)
- Posts' replies
- Posts' reactions
- Posts' file attachments
- Direct message and group message channels
- Direct message and group message channels' read/unread status
- Direct messages and group messages
- Direct messages from a user to themselves
- Permissions schemes
- Custom emoji

Importing additional types of posts is not yet supported.

.. include:: bulk-loading-about.rst
  :start-after: :nosearch:

.. include:: run-bulk-loading-command.rst
  :start-after: :nosearch:

.. include:: bulk-loading-data-format.rst
  :start-after: :nosearch:

.. include:: bulk-loading-common-issues.rst
  :start-after: :nosearch:

.. include:: bulk-loading-troubleshooting.rst
  :start-after: :nosearch:

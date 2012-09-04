# CoreMarks - Your Bookmarks, Your Business!

CoreMarks is a client-side web application for managing bookmarks. It has no
dedicated server-side component, only requiring a WebDAV storage server to
read and write the bookmark store.

This is a very early version of the software, and is missing some features.
Like editing bookmarks. And deleting them. At least you can read them. If
you've already written them yourself.

## How to run

1. Copy the index.html to a WebDAV server.
2. Create a JSON file on the same WebDAV server (cross-domain requests are not
currently supported).
3. Load the index.html in a web browser, adding a hash at the end with the
path to your bookmarks JSON. Example:

    http://coremarks.host/apps/coremarks/index.html#/data/coremarks/bookmarks.json

## License

MIT License, see LICENSE file for more details.

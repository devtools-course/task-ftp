# FTP

> Part 2. Uploading files

Create a script `part-2.sh` which uploads a file to the server.

The server is running on `server`. You can connect to it via the FTP protocol.

The file you need is passed as `$1`.

After the file is uploaded, it must be accessible via the endpoint `/sieben/ein/zwei.drei`

Credentials are passed via env variables: `USER` & `PASSWORD`.

> _Your script must not pollute the filesystem!_

## Error handling

Is not needed. We guarantee the correctness of the input data.

---

* What if the destination directory does not exist?

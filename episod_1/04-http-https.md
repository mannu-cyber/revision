### 1. What is HTTP and its different version?

**HTTP (Hypertext transfer protocol)**:

- It is basically used to communicate between client and server.
- When we visit any website the website communicate with server by using http and then serve you the data packets.

**Version**

- **HTTP/ 0.9** : A simple one line protocol used to fetch `HTML` pages.

- **HTTP/ 1.0** : Introduced `metadata` (headers) now sending more information possible.

- **HTTP/ 1.1** : It become to handle multiple request at one connection.

- **HTTP/ 2** : It become capable to download multiple files at single connection.

- **HTTP/ 3** : It become more faster and secure because it uses ` QUIC (UDP)` not the old `TCP`

### 2. HTTP Status Code

**Every response has some result , to represent that it has some status code**

1. `1XX` (informational)

- 100 continue
- 101 switching protocol

2. `2xx` (success)

- 200 ok
- 201 created

3. `3xx` (redirection)

- 301 moved permanently
- 302 found

4. `4xx` (client error)

- 400 bad request
- 401 unauthorized
- 404 not found

5. `5xx` (server error)

- 500 internal server error
- 503 service unavailable

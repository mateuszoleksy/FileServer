# FileServer
# C File Server & Transfer Client

A C-based networking project designed to streamline remote file and directory management through a socket server interface. Built using low-level socket APIs (`sys/socket.h` / `netinet`), this client-server application allows authenticated users to seamlessly upload, download, and browse files and entire directory structures.

### Key Features
* **User Authentication:** Secure registration and login flow before granting file access.
* **Full Folder Support:** Capability to upload and download complete directory structures, not just single files.
* **Interactive CLI Interface:** Displays a command guide immediately upon login for straightforward navigation.
* **Core File Operations:** Simple commands to list, view, upload, download, and manage remote contents.
* **Network Sockets in C:** Built using network libraries (`sys/socket.h`, `netinet/in.h`) for low-level TCP client-server communication.

### Background
Academic course project developed for computer science / engineering studies focusing on socket programming and Unix systems in C.

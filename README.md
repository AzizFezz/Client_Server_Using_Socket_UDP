# Client_Server_Using_Socket_UDP
This project involves the development of a client (`clientupP.c`) and a server (`serveurubP.c`). The client, when given the server's address (hostname + port number) as arguments, sends a random number `n` (ranging from 1 to `max`) to the server and then displays the server's response.

The server (`serveurubP.c`) takes a port number as an argument, receives the number `n` from the client, and sends back `n` randomly generated numbers.

## Usage

### Compilation and Setup

To compile the project, execute the following command:

```bash
user@linux:~/Project$ ./script.sh
```

### Launching the Server

To launch the server, use the following command:

```bash
user@linux:~/Project$ ./Serveur <port>
```

### Launching the Client

To launch the client, use the following command:

```bash
user@linux:~/Project$ ./Client <server_address> <port>
```

### Finding the Server's Address
To find the server's address, utilize the nslookup command:

```bash
user@linux:~/Project$ nslookup examples.com
Serveur: <server_address>
```

Make sure to replace <port> and <server_address> with the appropriate values. Feel free to modify and adapt the scripts and source code based on your requirements.

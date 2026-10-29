# Network Programming in Elixir and Erlang — Journal

Notes, takeaways, and questions while working through the book.

## 1. What Is Network Programming Anyway?

### Elixir and Erlang: The Perfect Fit

### Which One, Though: Elixir or Erlang?

### Where Do We Go Next?

---

# Part I — TCP

## 2. TCP: Exploring the Basics

### TCP 101

### Building a TCP Echo Server

### Testing with TCP

### Becoming Socket Pros with Modes and Packet Parsing

### Wrapping Up

## 3. Designing a Chat Protocol and Its TCP Server

### Designing a Simple Chat Protocol

### Writing Code for the Chat Protocol

### Moving to the Server Side

### Chatting with Clients

### Wrapping Up

## 4. Scaling TCP on the Server Side

### Increasing Scalability with Multiple Acceptors

### Rewriting the Server with Thousand Island

### Wrapping Up

## 5. Building TCP Clients

### The Redis Protocol

### Building Our First Client

### Queuing Requests

### Wrapping Up

## 6. Scaling and Optimizing TCP Clients

### Pooling TCP Client Sockets

### Building State-Machine-Like TCP Clients

### Pooling Connections Through Registry

### Wrapping Up

## 7. Securing Protocols: TLS

### Understanding How TLS Works

### The ssl Application

### Securing Our Chat System

### Wrapping Up

---

# Part II — UDP

## 8. Same Layer, Different Protocol: Introducing UDP

### The Basics of the Protocol

### Building a Metrics Ingestion Daemon

### Wrapping Up

## 9. Adding Guarantees to UDP

### Ordering, Splitting, and Dropping Packets

### Adding Guarantees

### Wrapping Up

## 10. UDP in the Wild: DNS

### Understanding How DNS Works

### Writing a Simple DNS Client

### inet_res

### Writing a DNS Server Is So Easy

### Wrapping Up

---

# Part III — HTTP

## 11. Talking the Internet Protocol: HTTP/1.1

### HTTP/1.1 Protocol Basics

### Serving JSON with Plug and Bandit

### Connecting to Servers with Mint

### Higher-Level Client Libraries: Finch and Req

### Wrapping Up

## 12. HTTP/2 and the Future

### HTTP/2: Why It Was Needed and What Changed

### Using HTTP/2 with Plug and Mint

### Evolving in Parallel with QUIC and HTTP/3

### Wrapping Up

## 13. Communicating in Real Time with WebSockets

### The WebSocket Protocol

### Making a Silly Real-Time Game

### Wrapping Up

 Peer-to-Peer (P2P) Networks

What is P2P Network?
- Client and server software usually run on separate computers.
- But one computer can also run both client and server software at the same time.
- In small businesses and homes, many computers work as both servers and clients.
- This type of network is called *Peer-to-Peer (P2P) Network*.

Types of P2P Network:
1.  *Simplest P2P Network:* Only 2 computers directly connected. Connection can be wired or wireless. Both can exchange data and services, acting as client or server when needed.
2.  *Larger P2P Network:* Multiple PCs connected together. It needs a network device like a *Switch* to connect all computers.

Important Point for Large Businesses:
- In larger businesses, network traffic is very high.
- So they need *dedicated servers* to handle many service requests. P2P is not good for large businesses.

Main Disadvantage:
- If a host acts as both client and server at the same time, its performance becomes slow.

Advantages of P2P Networking:
1.  *Easy to set up*
2.  *Less complex*
3.  *Lower cost* - Because network devices and dedicated servers may not be needed.
4.  *Good for simple tasks* - Like file sharing and printer sharing.
        - Example from figure: One PC says "I have a printer to share" (Print Sharing), another says "I have files to share" (File Sharing).

Disadvantages of P2P Networking:
1.  *No centralized administration*
2.  *Not as secure*
3.  *Not scalable* - Cannot grow for large networks.
4.  *All devices act as both clients and servers* - Which can slow down their performance.

---
2.1.4 Peer-to-Peer Applications

How P2P Application Works?
- A P2P application allows a device to act as *both a client and a server in the same communication*.
- In this model: *Every client is a server and every server is a client.*
- For this, each device must provide a user interface and run a background service.

Hybrid P2P System:
- Some P2P apps use a hybrid system.
- In hybrid: Resource sharing is *decentralized* (files are on different peers), but the *indexes* that show where the resources are, are stored in a *centralized directory*.
- Each peer first contacts the *Index Server* to get the location of a resource stored on another peer.

Example from Figure:
- Both sides are labeled "Client and Server".
- They send messages like "Meeting tonight", "I'll be there", "Good." - Both can send and receive. This is P2P communication.

---
2.1.5 Multiple Roles in the Network

1. Server can have Multiple Roles:
- One computer with server software can provide services to *one or many clients at the same time*.
- One single computer can run *multiple types of server software*.
- In a home or small business, one computer can act as a *File Server + Web Server + Email Server* at the same time.

2. Client can have Multiple Roles:
- One single computer can also run *multiple types of client software*.
- There must be client software for every service you need.
- With multiple clients installed, a host can connect to *multiple servers at the same time*.
- *Example:* A user can check email, view a web page, do instant messaging, and listen to internet radio all at the same time.

Example from Figure:
- One main Server is: Email Server, Web Server, File Server.
- It is connected to 3 different clients:
    - Client 1: Only File Access Client
    - Client 2: Web Browser + Email Client
    - Client 3: Web Browser + File Access Client + Email Client

This shows one server serving many clients with different needs.

# CECS 327 Reading Assignment: Architectures

### Assignment Description
Answer the following questions from the Chapter 2 reading from your textbook. Be complete with your answers. You may work on these questions with one or two other partners, but all students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. What is a three-tiered client-server architecture?
  A three-tiered client-server architecture is an organization where the system is divided into three distinct layers, each running on a separate machine: the client, the application server, and the database server. The client interacts with the application server, which processes the requests and interacts with the database server to retrieve or store data.
2. What is the difference between a vertical distribution and a horizontal distribution?
  Vertical Distribution: This involves dividing distributed applications into three logical layers (presentation, application, and data) and running the components from each layer on different servers (machines)
  Horizontal Distrbution: This involves splitting a client or server into logically equivalent parts, each operating on its own share of the complete data set, effectively distributing the load and functionality across multiple nodes
3. If a client and a server are placed far apart, we may see network latency dominating overall performance. How can we tackle this problem?
4. Consider a chain of processes $P_{1}, P_{2}, \ldots, P_{n}$ implementing a multitiered client-server architecture. Process $P_{i}$ is client of process $P_{i}+1$, and $P_{i}$ will return a reply to $P_{i}-1$ only after receiving a reply from $P_{i}+1$. What are the main problems with this organization when taking a look at the request-reply performance at process $P_{1}$?
5. In a structured overlay network, messages are routed according to the topology of the overlay. What is an important disadvantage of this approach?
6. Consider an unstructured overlay network in which each node randomly chooses $c$ neighbors. If $P$ and $Q$ are both neighbors of $R$, what is the probability that they are also neighbors of each other?
7. Not every node in a peer-to-peer network should become superpeer. What are reasonable requirements that a superpeer should meet?
8. Give an example of a self-managing system in which the analysis component is completely distributed or even hidden.
9. Consider a BitTorrent system in which each node has an outgoing link with a bandwidth capacity $B_{out}$ and an incoming link with bandwidth capacity $B_{in}$. Some of these nodes (called seeds) voluntarily offer files to be downloaded by others. What is the maximum download capacity of a BitTorrent client if we assume that it can contact at most one seed at a time?
10. Modern cars are stuffed with electronic devices. Give some 
  examples of feedback control systems in cars.

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.
# Bandwidth &  Throughput 

## Bandwidth

### 1. What is Bandwidth?
Bandwidth is the capacity of a medium to carry data. It is needed for high bandwidth applications like streaming movies or playing multiplayer games.

> In simple words: Bandwidth is the maximum amount of data that can theoretically go from one place to another in one second.

### 2. Key Concepts
* Different physical media support the transfer of bits at different speeds.
* The rate of data transfer is discussed in terms of bandwidth and throughput.
* Digital bandwidth measures the amount of data that can flow from one place to another in a given amount of time.
* Bandwidth is typically measured by how many bits can be sent across the media in one second (theoretically).

### 3. Common Units of Bandwidth
* Thousands of bits per second (Kbps)
* Millions of bits per second (Mbps)
* Billions of bits per second (Gbps)

### 4. Detailed Units Table
| Unit of Bandwidth | Abbreviation | Equivalence |
| :--- | :--- | :--- |
| Bits per second | bps | 1 bps = fundamental unit of bandwidth |
| Kilobits per second | Kbps | 1 Kbps = 1,000 bps = 10^3 bps |
| Megabits per second | Mbps | 1 Mbps = 1,000,000 bps = 10^6 bps |
| Gigabits per second | Gbps | 1 Gbps = 1,000,000,000 bps = 10^9 bps |
| Terabits per second | Tbps | 1 Tbps = 1,000,000,000,000 bps = 10^12 bps |

### 5. What Decides Bandwidth?
Physical media properties, current technologies, and the laws of physics all play a role in determining available bandwidth.

---

##  Throughput

### 1. What is Throughput?
Like bandwidth, throughput is the measure of the transfer of bits across the media over a given period of time.

**Main Difference:** Throughput is the *actual* measured speed, while Bandwidth is the *theoretical* maximum speed. Throughput does not usually match the specified bandwidth.

### 2. Factors That Influence Throughput
1.  The amount of data being sent and received over the connection
2.  The types of data being transmitted
3.  The latency created by the number of network devices encountered between source and destination

### 3. What is Latency?
Latency refers to the amount of time, including delays, for data to travel from one given point to another.

### 4. Important Points About Throughput Measurement

* **Throughput does not check data validity:** It does not take into account the validity or usefulness of the bits being transmitted and received.
* **Not all data is user data:** Many messages received through the network are not destined for specific user applications. An example would be network control messages that regulate traffic and correct errors.
* **Slowest Link Rule:** In an internetwork or network with multiple segments, throughput cannot be faster than the slowest link of the path from sending device to the receiving device. Even if all or most of the segments have high bandwidth, it will only take one segment in the path with lower bandwidth to create a slowdown of the throughput of the entire network.

### 5. How to Check Throughput?
There are many online speed tests that can reveal the throughput of an internet connection.

# Wireshark ICMP Capture 
This project showcases the capture and analysis of ICMP (Internet Control Message Protocol) traffic through Wireshark. Three distinct packet captures were generated, each holding precisely 4 ICMP Echo Requests and 4 ICMP Echo Replies.


# Gateway IP
10.0.3.15

## Observations

| Target                    | Observation                                                             |
| ------------------------- | ----------------------------------------------------------------------- |                          
| **Gateway IP**(10.0.3.15) | Low latency since it is on the local network                             |
| **Localhost (127.0.0.1)** | Fastest response because the packets remained within the local machine. |
| **Google.com**            | Slowest response due to internet latency.                          |
           

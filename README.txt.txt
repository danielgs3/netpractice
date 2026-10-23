*This project has been created as part of the 42 curriculum by danielg3.*

## Description
NetPractice is a practical project designed to introduce the fundamentals of computer networking. The main goal is to successfully configure and troubleshoot small-scale simulated networks by setting up IP addresses, subnet masks, default gateways, and routing tables. Over 10 progressive levels, the project builds a solid understanding of how data flows between hosts, how routers bridge different subnets, and how traffic reaches the Internet.

## Instructions
### Running the Training Interface
1. Extract the provided project files into a directory of your choice[cite: 16].
2. Open a terminal in that directory and launch the local web server using the provided script[cite: 16]:
   ```bash
   ./run.sh

```

(Alternatively, you can run a manual server using `python3 -m http.server 49242` and open `http://localhost:49242` in your web browser).
3. On the landing page, enter your intranet login (`danielg3`) to generate and load your personal configuration.

### Exporting Configurations and Submission Requirements

* Complete each of the 10 training levels by adjusting device interfaces and routing tables until all goals are marked as successful.


* Click the **[Get my config]** button on each level to download your configuration file.


* You must place exactly **10 configuration files** (one for each level) directly at the **root of your Git repository** for evaluation.



## Resources

* **Core Networking Concepts:**
* TCP/IP addressing and IP classes
* Subnet masks and CIDR notation (e.g., `/26`, `/28`)
* Default gateways and next-hop routing rules
* Functions of routers and switches
* Basic OSI model network layers


* **References:**
* Official 42 NetPractice documentation and subject guidelines.
* TCP/IP network troubleshooting tutorials.


* **AI Usage Disclosure:**
* Artificial Intelligence tools were utilized during this project as a collaborative mentor to better understand subnet mask calculations, debug routing table syntax errors (such as matching `0.0.0.0/0` vs `default`), and clarify packet forwarding logic. All configurations, final solutions, and technical concepts were independently reviewed and verified.



```

```
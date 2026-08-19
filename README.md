# DirtyPenguin

DirtyPenguin is a Linux-based network security and penetration-testing framework for reconnaissance, traffic analysis, vulnerability discovery, and controlled attack simulation.

The project is built around a simple concept: **get into the network, find out what is running, understand how the systems are connected, and determine what can be reached from there.**

DirtyPenguin can discover hosts, enumerate services, inspect traffic, identify potential vulnerabilities, and map the network as it goes. When another system becomes reachable, it can continue the assessment from that point instead of treating every machine as an isolated target.

### Features

* Host and network discovery
* Port and service enumeration
* Network traffic inspection
* Protocol analysis
* Vulnerability detection
* Attack-surface discovery
* Network topology mapping
* System and service fingerprinting
* Attack-path analysis
* Controlled exploitation
* Data-exposure detection
* Multi-host reconnaissance
* Compromise and propagation simulation

DirtyPenguin is designed to work from an initial foothold and progressively expand its view of the environment. A discovered host can lead to another host, which can expose another service, which can reveal another path through the network.

The framework is intended for authorized penetration testing, security research, and isolated lab environments.

It focuses on understanding the practical consequences of a compromised system: **what it can see, what it can access, where it can move, what information it can reach, and how a single weakness can develop into a larger compromise.**

DirtyPenguin is a security tool built for people who want to see the network from the attacker's side.


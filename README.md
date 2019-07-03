[![Build Status](https://travis-ci.org/project-gary/gary.svg?branch=master)](https://travis-ci.org/project-gary/gary)

# code-name-gary
Code Name Gary

![](docs/icon.png)

## Goals
 * Create a container orchestrator
 * control-plane vs worker node == no difference for install/user.
 * single binary install
 * based on promise theory
 * HA on as few as 3 nodes and scale to millions of nodes 


## Non-goals
 * Service mesh
 * Other things 

## Project pre-alpha road map 
 [*] Initial Cluster API
 [*] Node to node cluster communication interface
 [*] Node to node cluster communication implementation (zeroMQ)
 [ ] Container Runtime integration
 [ ] Machine taints

## Tech Stack Overview
 * [ClusterAPI](docs/cluster_api.md) app 
 * [Node Communication Interface](docs/nci.md)
 * [Node Communication implementation](docs/zeromq.md)
 * [Container Runtime integration](docs/cri.md)

## Architecture

Based off promise Theory. designed to be control-plane-less. All nodes created equal. [info](docs/architecture.md)

## Community
Play nice with others please. [info](docs/community.md)

## Deployment Guide
[Here](docs/user_guide.md) is a best effort deployment guide

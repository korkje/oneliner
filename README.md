## resh

### Description

A tiny tool that generates reverse shell commands


### Installation

Move `resh` to a directory in your path  
`mv resh /usr/local/bin/`

Make it executable  
`chmod +x /usr/local/bin/resh`

### Usage

`$ resh <kind> <ip> <port>`

##### Example

`$ resh sh 192.168.0.1 9001`

##### Kinds
- sh
- bash
- perl
- py
- php
- ruby
- nc
- nc2 (for nc versions without -e)
- java

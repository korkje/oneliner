## Oneliner

### Description

A tiny tool that generates reverse shell commands


### Installation

Move oneliner to a directory in your path  
`mv oneliner /usr/local/bin/`

Make it executable  
`chmod +x /usr/local/bin/oneliner`

### Usage

`$ oneliner <kind> <ip> <port>`

##### Example

`$ oneliner sh 192.168.0.1 9001`

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

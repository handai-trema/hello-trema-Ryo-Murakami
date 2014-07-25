hello_trema
===========

The "Hello Trema!" example is one of the simplest OpenFlow controller
implementation. The basic functionality of this controller is to
establish an OpenFlow channel connection with an OpenFlow switch and
output the "Hello 0xabc [switch's dpid]!" message.

This demonstrates a minimum template for Trema applications written in
Ruby. Hence it's a good starting point to learn about Trema
programming.

How to run
----------

```
% bundle install
% bundle exec trema run hello_trema.rb -c sample.conf
```
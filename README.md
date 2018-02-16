# Chef RabbitMQ Cookbook Examples

This repository contains examples that demonstrate
how various node attributes are used and can serve as
a starting point or a scratchpad for experimentation.

The examples currently use [Vagrant](https://github.com/applicationsonline/librarian-chef) and `chef-solo` for provisioning.
Librarian is used for dependency management.

## Available Examples

 * [Single 3.7.x node with plugins](./vagrant/single_3.7.x_node): provisions Erlang/OTP 20.x, RabbitMQ 3.7.x and a few commonly
   used plugins. Configures kernel limits for RabbitMQ via systemd.


## License and Copyright

See [LICENSE](./LICENSE).

2018 (c) Pivotal Software, Inc.



`inet_ssh_dist` is an Erlang distribution (network protocol) that runs *over* ssh.

An ssh `known_hosts` must already be popuated since the distribution cannot accept new hosts on an ad-hoc basis.

You can set the default ssh user using an argument;

    -ssh_default_user ubuntu



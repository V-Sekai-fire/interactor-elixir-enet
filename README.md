# interactor-elixir-enet

An Elixir implementation of the ENet reliable UDP protocol, with DTLS, ported from Erlang.

## What it is for

Hosts and peers run as supervised processes and send reliable, unreliable and unsequenced packets over numbered channels. It is ported from [flambard/enet](https://github.com/flambard/enet) by way of the DTLS work in [dragonhunt02/enet-godot](https://github.com/dragonhunt02/enet-godot).

## Build and run

```sh
mix deps.get
mix test
```

## Licence

This repository carries no LICENSE yet. Both upstreams are Apache-2.0, so the ported code is under Apache-2.0 terms, and a LICENSE and NOTICE belong here.

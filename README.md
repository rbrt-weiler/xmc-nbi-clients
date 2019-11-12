# XMC API Clients

This project is meant to collect some generic clients utilizing the GraphQL-based API provided by the Northbound Interface (NBI) of [Extreme Management Center](https://www.extremenetworks.com/product/extreme-management-center/) (XMC).

## Cloning and Updating

As this projects primarily consists of submodules you should clone with `--recurse-submodules`, e.g.:

`git clone --recurse-submodules https://gitlab.com/bell-computer-netzwerke/xmc-nbi-clients.git`

If you have cloned the repository without recursing, `git submodule update --init --recursive` may help. Bumping every submodule to the most current version can be achieved with `git submodule update --remote --merge`.

## Source

The original project is [hosted at GitLab](https://gitlab.com/bell-computer-netzwerke/xmc-nbi-clients), with a [fork by the original author](https://gitlab.com/rbrt-weiler/xmc-nbi-clients) at GitLab and a [copy over at GitHub](https://github.com/rbrt-weiler/xmc-nbi-clients). Fork and copy may be more current.

# git ssh dns mirage3 repository

Just a temporary(?) repository using MirageOS 3.x and:
- µDNS (now ocaml-dns in unreleased version 2.0.0)
- git 2.0 (unreleased)
- irmin 2.0 (unreleased)
- awa-ssh client (unreleased)
- mirage-conduit using awa-ssh client and µDNS-client
- x509, tls using domain-name (>= 0.2.1) and gmap
- letsencrypt (unreleased)
- nocrypto (based on dune branch)

still uses a mirage that uses ocamlbuild..

best used with [future unikernels](https://github.com/roburio/unikernels/tree/future).

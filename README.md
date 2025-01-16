# DTN UDP Convergence Layer Version 2 (UDPCLv2)

The internet-draft is hosted at [draft-ietf-dtn-udpcl](https://datatracker.ietf.org/doc/draft-ietf-dtn-udpcl/).

A local build of the current main branch is available [draft-ietf-dtn-udpcl.html](https://briansipos.github.io/dtn-bpbis-udpcl/draft-ietf-dtn-udpcl.html) with its [misspelling.txt](https://briansipos.github.io/dtn-bpbis-udpcl/misspelling.txt).
A difference from the datatracker draft and this local version can be [viewed side-by-side](https://author-tools.ietf.org/diff?doc_1=draft-ietf-dtn-udpcl&url_2=https://briansipos.github.io/dtn-bpbis-udpcl/draft-ietf-dtn-udpcl.txt&raw=1).

Prerequisites to building can be installed on Ubuntu with:
```
sudo apt-get install -y cmake python3 python3-pip python3-setuptools python3-wheel ruby xmlstarlet aspell cargo
pip3 install xml2rfc
sudo gem install cbor-diag
sudo cargo install --root /usr/local cddl
```

Then the document can be built with
```
cmake -S . -B build/default
cmake --build build/default
```

# Demo Convergence Layer Agent

The demo agent is in a separate project [dtn-demo-agent](https://github.com/BrianSipos/dtn-demo-agent).

# Wireshark Protocols and Dissectors

The wireshark modules are in a separate project [dtn-wireshark](https://github.com/BrianSipos/dtn-wireshark).

# DTN UDPCL

Source for for UDPCLbis draft document.

The final specification is hosted at [draft-ietf-dtn-udpcl](https://datatracker.ietf.org/doc/draft-ietf-dtn-udpcl/).

A local build of the current main branch is available [draft-ietf-dtn-udpcl.html](https://briansipos.github.io/dtn-bpbis-udpcl/draft-ietf-dtn-udpcl.html).

Prerequisites to building can be installed on Ubuntu with:
```
sudo apt-get install -y install aspell cmake python3 python3-pip python3-setuptools python3-wheel ruby xmlstarlet
sudo pip3 install xml2rfc
sudo gem install cddl
```
and then the document can be built with
```
cmake -S . -B build/default
cmake --build build/default
```

# Demo Convergence Layer Agent

The demo agent is in a separate project [dtn-demo-agent](https://github.com/BrianSipos/dtn-demo-agent).

# Wireshark Protocols and Dissectors

The wireshark modules are in a separate project [dtn-wireshark](https://github.com/BrianSipos/dtn-wireshark).

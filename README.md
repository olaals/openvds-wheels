# arm64 / aarch64 wheels for Openvds

Wheels compiled from source code https://community.opengroup.org/osdu/platform/domain-data-mgmt-services/seismic/open-vds

Note that this is the Openvds package, and not the Openvds+ that is hosted on pypi by Bluware.
Openvds is open source and Openvds+ is closed source but freeware. One difference between Openvds and Openvds+ is that
that Openvds+ can write compressed cube using the properitary wavelet compression.


To install from this repo:
```bash
pip install openvds --no-index --find-links https://olaals.github.io/openvds-wheels/
```


To add to the pip search during install in requirements.txt

**Requirements.txt**
```bash
--find-links https://olaals.github.io/openvds-wheels/
openvds
numpy
numba
matplotlib
```


Link:
https://olaals.github.io/openvds-wheels/

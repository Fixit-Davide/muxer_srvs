[![Ubuntu 22.04 Iron Build](https://github.com/Fixit-Davide/muxer_srvs/actions/workflows/iron.yaml/badge.svg)](https://github.com/Fixit-Davide/muxer_srvs/actions/workflows/iron.yaml)
[![Ubuntu 22.04 Rolling Build](https://github.com/Fixit-Davide/muxer_srvs/actions/workflows/rolling.yaml/badge.svg)](https://github.com/Fixit-Davide/muxer_srvs/actions/workflows/rolling.yaml)
# Muxer Services
Set of custom ROS2 service definitions to interface with a package that muxes topics.

# Pre-commit
This project uses [pre-commit](https://pre-commit.com/).  On Ubuntu, install it with:
```
sudo python3 -m pip install pre-commit
```
Then, enter the repository root and run :
```
pre-commit install
```
Now every time a commit is issued, a number of automated checks are done on code.

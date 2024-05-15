# Network Design And Simulation For A Critical Large Company

## Description

### System Network Requirements Analysis for the Headquarter and Branches

#### Headquarter

- **Building Specifications**: The headquarters is a 7-story building with the IT room and Fiber Optic Center located on the 1st floor.
- **Installation Scale**: Medium scale, including 120 workstations, 5 servers, and at least 12 networking devices.
- **Technology and Connectivity**:
  - Utilizes the latest wired and wireless technologies.
  - Wired connections use GPON technology with a network infrastructure requirement of 1GbE/10GbE.
- **VLAN Organization**:
  - Each floor is assigned a separate VLAN to ensure security, authentication, and access control.
  - Internal machines can access each other’s data, but external machines cannot access the internal network.
- **Internet Connectivity**:
  - The central network connects to the external Internet via an ADSL line and uses two Leased Line connections for WAN connectivity.
- **Software**:
  - A combination of licensed and open-source software, including office applications, client-server applications, and databases.
- **Security**:
  - Equipped with a surveillance camera system.
- **Growth Rate**:
  - The company (Bank BB) has a projected annual growth rate of 20% for the number of employees and machines.

#### Branches

- **Building Specifications**: Each branch is a 2-story building with an IT room and Fiber Optic Center located on the 1st floor.
- **Installation Scale**: Small scale, including 30 workstations, 3 servers, and at least 5 networking devices.

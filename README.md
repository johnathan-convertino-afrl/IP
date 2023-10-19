# IP CORE REPO
### Contains all IP cores available on github
---

   author: Jay Convertino

   date: 2023.09.19

   details: RTL IP cores located in a central repo for easier pulls.

   license: MIT

---

### Version
#### Current
  - V1.0.0 - initial release

#### Previous
  - none

### Dependencies
#### Build
  - AFRL:utility

#### Simulation
  - AFRL:simulation

### IP
  - buffer = Contains fifos, lifos and other types of data memory cores.
    - axis_fifo
    - axis_tiny_fifo
    - fifo
  - converter = Data conversion from one format to another.
    - axis_data_to_axis_string
    - axis_string_to_axis_data
    - axis_data_width_converter
  - device = Cores that interface with specific devices and provide i/o to the device.
    - axis_1553_decoder
    - axis_1553_encoder
    - axis_uart
    - ft245_sync_to_axis
  - math = Core that alter input data to produce a new set of output data.
    - axis_moving_average

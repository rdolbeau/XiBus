
Implementation of NuBus controller with Verilog

## ToDo List

- [x] Arbiter
  - [x] Arbiter testbench
- [x] Slave
  - [x] Slave testbench
- [ ] Master
  - [x] Master testbench
  - [ ] Multimaster bus transfer test bench
- [ ] Bus transfer errors
  - [ ] Bus transfer errors testbench
- [ ] Interrupts 
  - [ ] Interrupts testbench 
- [ ] Parity
- [ ] Block transfer
  - [ ] Block transfer testbench

## Files

nubus_arbiter.v - Arbiter

nubus_driver.v - Nubus singnals driver

nubus_master.v - Master controller

nubus_slave.v - Slave controller

nubus_inc.sv - Included to various files definition of NuBus signals

nubus_arbiter_tb.sv - Arbiter's test bench

nubus_slave_tb.sv - Slave controller test bench (virtual master access to slave)

nubus_master_tb.sv - Master controller test bench (CPU access to slave with NuBus)

nubus_memory.sv - Memory controller used for tests

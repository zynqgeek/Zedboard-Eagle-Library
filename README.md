Zedboard-Eagle-Library
======================

Zedboard Eagle Library

This library constants schematic symbols and layout drawings for useful connectors to interface with the Zedboard from Avnet Electronics.  This library has not been tested by it's author(s) and comes with no guarantee.  This library nor it's author(s) have no affiliations with Avnet, Xilinx, or Digilent Inc.

The library includes:

LPC FMC
    The Low Pin Count FPGA Mezzanine Connector that is including on the Zedboard is male.  This library has the female counterpart to this connector.

XADC
    There is an XADC connector including in this library that is identical to that found on the Zedboard (and other Xilinx 7-Series FPGA boards).  The connector is intended to be used in conjunction with a ribbon cable between the Zedboard and the custom board with this connector on it.

PMOD
    It was the decision of the author(s) of this library not to include a PMOD schematic symbol or layout drawing due to the strict rules associated with the PMOD standard.  It is in no way out goal to promote the mis-use of standards, and due to it's complexity it was not included.  Please see the full PMOD standard here: http://www.digilentinc.com/Pmods/Digilent-Pmod_%20Interface_Specification.pdf
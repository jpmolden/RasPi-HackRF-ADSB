# HackRF-RasPi-ADS-B

## Introduction:

Project to recieve ADS-B Packets from a HackRF One Software Defined Radio (SDR)

Rasberry Pi will recieve ADS-B data through the HackRF One and upload packets periodically
to a web based database using Python



 




<!-- 


## ECE 474/574 - VLSI System Design - Oregon State University

SystemVerilog code, testbenches and scripts (bash, tcl, do)

### Homeworks

| # | Title | Remark |
| ---- | ---- | -------|
| 2 |   [Arithmetic Logic Unit](hw2_ALU) | |
| 3 |   [32-bit multiplier](hw3_32bit_mult)  | |
| 4 |   [FIFO - first-in, first-out memory - Dual clock](hw4_8x8_fifo)  |  |
| 5 |   [GCD - Elucid's greatest common divisor](hw5_32bit_GCD) | |
| 6 |   [Temperature Averager System - Dual clock](hw6_satelliteReciever_tas) | |
| 7 |   [Digital Clock & 7-Seg Driver](hw7_digitalclock_clock) |   |


![Image](../master/hw6_satelliteReciever_tas/blockschem.png)
![Image](../master/hw7_digitalclock_clock/blockschem.png)


# ECE 474 Homework 7
## Digital Clock

[RTL_src](../hw7_digitalclock_clock/rtl_src/clock.sv)

[testbench](../hw7_digitalclock_clock/rtl_src/clock_tb.sv)

![Image](../hw7_digitalclock_clock/blockschem.png)
![Image](../hw7_digitalclock_clock/tbwaveform.PNG)

## Introduction:

In this homework, we will write verilog code for digital clock.
The clock drives a 4 digit 7-segment display.
Manual time change functions are not included.

## Top Level Interface
```
module clock(
    input             reset_n,             //reset pin
    input             clk_1sec,            //1 sec clock
    input             clk_1ms,             //1 mili sec clock
    input             mil_time,            //mil time pin
    output reg [6:0]  segment_data,        // output 7 segment data
    output reg [2:0]  digit_select         // digit select
    );
```

## Running the testbench
```
    ./doit clock_tb
```

## Testbench console/file output snippet
```
    # INFO: running for:             0 days,             0 hours,             0 mins,             2 seconds
    #   digit_4 = 1001111 decode: 1
    #   digit_3 = 0010010 decode: 2
    #   digit_2 = 1111100 decode: :  AM
    #   digit_1 = 0000001 decode: 0
    #   digit_0 = 0000001 decode: 0
    # INFO: running for:             0 days,            11 hours,            59 mins,            59 seconds
    #   digit_4 = 1001111 decode: 1
    #   digit_3 = 1001111 decode: 1
    #   digit_2 = 1111111 decode:    AM
    #   digit_1 = 0100100 decode: 5
    #   digit_0 = 0001100 decode: 9
    # INFO: running for:             0 days,            12 hours,             0 mins,             0 seconds
    #   digit_4 = 1001111 decode: 1
    #   digit_3 = 0010010 decode: 2
    #   digit_2 = 1111000 decode: :  PM
    #   digit_1 = 0000001 decode: 0
    #   digit_0 = 0000001 decode: 0
```

 -->

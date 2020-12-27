java -jar logisim-generic-2.7.1.jar

## requires 

[Logi7400](https://github.com/r0the/logi7400)

## Program counter

4X 74161 chained w/ carry out to next 4bit's clk or clk to each clock if jump is set

In: 
* CON: 
    * J(0) (jump)
    * CE(1) (count enable)
    * CLR(2) (clear)
    * PCO(3) (program counter out)
* CLK (clock)

I/O:
* 14b <=> bus

## Rom Address Register

4X 74173 w/ out tied down

IN:
* CON:
    * RARI(4) (in)
    * CLR(2) (clear)
* CLK (clock)

I/O:
* 14b from bus
* 14b to ROM


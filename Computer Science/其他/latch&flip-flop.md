Difference between latch and flip-flop: clocking mechanism



Level-triggered D latch: 水平触发

Latch: when the control signal is asserted,  output change when input change.

A memory element in which the output is equal to the value of the stored state inside the element and the state is changed whenever the appropriate inputs change and the clock is asserted.



Edge-triggered D flip-flop: 时钟边沿触发

If the input is allowed to change the output only on the rising or falling edge of a control signal

Flip-flop: change only on the edge of control signal(clock)

A memory element for which the output is equal to the value of the stored state inside the element and for which the internal state is changed only on a clock edge.



Register:多个D flip-flops一起使用同一个时钟





Two D latchs => One D flip-flop
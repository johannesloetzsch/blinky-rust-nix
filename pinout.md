## Pinout bluepill (variant @c3d2)

```
            USB (power supply)  

| Gnd                 | Gnd                 |  
|                     | 3V3                 |  
|                     |                     |  
| PC13 -> led         |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     | A10 (Rx) -> Tx UART |  
|                     | A09 (Tx) -> Rx UART |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  
|                     |                     |  

          | 3V3 | DIO | CLK | Gnd |
```


## Black magic probe

* power will be provided via Black magic probe instead of bluepills USB

simply connect:

> | 3V3 | DIO | CLK | Gnd |

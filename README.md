# CH569 USB3 Super Speed Board
USB3 super speed development board useful as FPGA expansion
based on the WCH-Tech CH569 chip.
It should also be possible to substitute the CH569 with a CH565 chip,
without further modifications.

### Board support
Open source development tools and board support package are available here:

https://github.com/orgs/hydrausb3/repositories

### Status
* rev0 tested and working
* rev1 tested and working
* rev2 is currently being manufactured
NOTE: Both rev0 and rev1 have shown spurious transmission errors in USB3 stress tests.
Do not use for high performance duty. Adding a 100nF decoupling capacitor to the
3V3 pin of the crystal oscillator seemed to improve the situation significantly.

![image](https://user-images.githubusercontent.com/148607/186277957-43aa53cb-c09b-4215-977f-75bbd7a930ce.png)
![image](https://user-images.githubusercontent.com/148607/186278106-aca455dc-4665-439b-9679-85f94f4adc73.png)
![image](https://user-images.githubusercontent.com/148607/186278177-a8f7dbd6-957f-4b00-a0e1-2da3568c2bc1.png)

**Connecting Jikong BMS JK-B1A8S10P CANBUS to Raspberry pi (Venus OS)**

# Story
I am in the process of installing a leisure batter in our van. 

The idea is to have the Victron MPPT, DC-DC Charger and DIY LiFePo4 battery connected to rasperry pi with Venus OS, to allow for system monitoring via the VRM Portal.

There are some learnings that I wanted to share.

Like many others, I am confused about availability of RS485 and/or CAN on JK BMS. 
# Order
I have placed an order with AliExpress for **JK-B1A8S10P** - https://www.aliexpress.com/item/1005007198911778.html with the **assumption** that the **BMS will support both RS485 and CAN**.

Assumption was based on the item title - **jikong bms JK-B2A8S20P CANBUS 100A 200A 300A 4S 5S 6S 7S 8S 12V 24V battery with 1A 2A active balanced heating Li-ion LiFePO4 Lt**,
item description - **Gutter connection: RS485/Blue tooth** and Product Specification table below stating **"Other Interfaces (Default) - RS485"**

![image](https://github.com/user-attachments/assets/f2f9259b-223b-409a-9618-dacba3d65480)

# BMS Arrived
Part number will indicate that I have ordered a BMS with 1A active balancer, able to cope with 100A continued current.

Due to double terminals - the BMS that has arrived, looks more like a 200A version. Not an issue but wondering why. Any ideas?

![image](https://github.com/user-attachments/assets/db4a18ea-6d41-441d-a232-b5fca7df819d)

# Hardware and Software Version
Hardware is **V11A** and Software is **V11.54**. Not sure what Version the **V4.27.0** refers to. Any ideas?

![image](https://github.com/user-attachments/assets/25e9f17d-9d65-4be4-a38d-ec9aba02aa55)


# Ports
Again, port layout more like on a 200A model.

![image](https://github.com/user-attachments/assets/3c86af9c-b15e-4a67-bf2e-bca7ed523263)

# Inside JK-B1A8S10P
There is no mention of CAM on my BMS.

I was hoping that looking inside will give me some clue what chip is next to the GPS and RS485 port.

I could not see any markings on the chips.

![image](https://github.com/user-attachments/assets/1ba0488d-633d-43c0-882c-a21bdfa206db)



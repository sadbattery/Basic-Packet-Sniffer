![header](https://capsule-render.vercel.app/api?type=slice&height=300&color=gradient&customColorList=0,2,2,5,4,6,8,10,12,14,16,20,30&text=Packet%20Sniffer%20Tool&fontSize=50&fontAlign=54&rotate=19&fontAlignY=45&textBg=false&animation=twinkling)

<div><p align="left"> <img src="https://komarev.com/ghpvc/?username=sadbattery&label=PageViews:"/></p></div>
Packet Sniffer Tool using `scapy` or `pcapy`

### Libraries Used:
+ `scapy`
+ `pcapy`
+ `sys`

## How to Use:
> Run using [Jupyter NoteBook](https://jupyter.org/) or any Python IDE.  

### `For V1.0`

##### How to Run:
+ Run the script
+ It will ask you about the interface you want to sniff (nothing means default).
+ It will also ask about the number of packets you want to capture (0 means continuous)
  
##### How to Stop:
+ `CTRL + C` will terminate the script.

+ It will create a file named `packet_log.txt` in the default folder.

## Installation:

#### **Install Npcap Before running the script**
+ Download and Install [Npcap Free Edition](https://npcap.com/#download).

#### ***scapy :***
> A Packet manipulation program and library which is used to capture, create, manipulate, and analyze network packets at a low level using a simple and intuitive syntax.
```bash
pip install scapy
```
**OR**
#### ***pcapy :***

```bash
pip install pcapy
```
#### ***sys :***
> ***sys*** is a built-in Python module that provides access to some variables used or maintained by the Python interpreter. It is used to 
> + Access to Command Line Arguments
> + Access to Standard Streams
> + Access to System-Specific Parameters and Functions 
> + Exit Functions

## How to Troubleshoot (In case of Errors)

+ Run as Administrator
+ Check Npcap Installation
+ Restart Pcap Service
+ Update Scapy and Npcap
  ```bash
  pip install --upgrade scapy
  ```
<!--comment-->
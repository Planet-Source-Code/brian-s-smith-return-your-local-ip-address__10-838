<div align="center">

## Return your local ip address


</div>

### Description

Simple example on how to retrieve your local machines IP Address in VB.Net using the Frameworks Sockets.
 
### More Info
 
Returns your IP Address!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brian S\. Smith](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brian-s-smith.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB\.NET
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__10-9.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brian-s-smith-return-your-local-ip-address__10-838/archive/master.zip)





### Source Code

```
'Be sure to import these into your Class/Struct
Imports System.Net
Imports System.Net.Sockets
'Simple 2 lines and you have your IP address.
Dim objIPAddress As New IPAddress(Dns.GetHostByName(Dns.GetHostName).AddressList(0).Address)
Dim strIPAddress As String = objIPAddress.ToString
```


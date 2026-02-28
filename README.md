# Niagara-4-FRPC-Module
Through this module, an FRPC mapping service can be deployed in the Niagara Station, enabling users to remotely access the Niagara site.
<img width="962" height="268" alt="image" src="https://github.com/user-attachments/assets/ec5c4706-16ce-4672-841e-9c523507fb5a" />
This FRPC module can enable cloud port mapping within Niagara, directly exposing the intranet ports of the Niagara station to the cloud. It has been tested to support automatic reconnection upon network interruptions—meaning it will reconnect if the network is temporarily disrupted. Please note: if the station reboots, this FRPC service will not reconnect automatically; you will need to deploy an additional program to check whether the cloud port is functioning properly. We have verified compatibility with N4.14 on JACE, Edge, and Windows-based Niagara supervisors.

<img width="382" height="118" alt="image" src="https://github.com/user-attachments/assets/04ccf2fd-1d33-4edd-ad63-93fe363f8493" />
Simply drag and drop the glineFrpc module into the wiresheet, and it will be ready to use.
<img width="786" height="106" alt="image" src="https://github.com/user-attachments/assets/ee2701db-2533-486e-bbaf-451bb6069f77" />
Logs can also be read in Niagara's Application Director.
At this stage, we offer 10 years free early pilot licenses, then with a transition to paid licensing in the future. If you are interested, please provide your host ID to apply for a free license. Contact: jason.zhang@gline-net.com

# Establish IPSEC VPN on Cloud Gateway

## Objective
The objective of this task is to establish a secure connection between two different clouds providers, or between the cloud infrastructure and on-premise network but with limited throughput.
in GCP there are two types of VPN connections HA VPN and Classic VPN, chosen depends on your application, HA VPN has an high available connection with 99.99% SLA that's because using of two tunnels.
in VPN connection also we use CloudRouter from Google to enable dynamically exchange routes between you VPC and on-premise network using Border Gateway Protocol BGP

## Flowchart
<p align="center">
  <img src="https://user-images.githubusercontent.com/82225825/210512887-192c4926-6313-44b7-a837-06022c7e8780.png" alt="Sublime's custom image"/>
</p>

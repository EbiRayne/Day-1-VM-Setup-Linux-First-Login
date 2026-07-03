# Day 1 — VM Setup & Linux First Login

## What I learned
- A VM is a computer inside a computer
- VirtualBox is a Type 2 hypervisor (runs on top of existing OS)
- Type 1 hypervisors run directly on hardware (VMware ESXi, Hyper-V)
- Linux hides password input completely when typing — nothing shows, not even dots

## What I built
- Ubuntu Server 24.04.4 VM in VirtualBox
- 4GB RAM, 14GB disk on D drive
- Logged in as ray

## Problems I hit
- Forgot username on first install → deleted and reinstalled
- Password looked like it wasn't working → turns out Linux just shows nothing while typing

## IP note
- VM got a private NAT address assigned by VirtualBox — not my real IP

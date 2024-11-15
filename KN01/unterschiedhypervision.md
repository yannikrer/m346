## Hypervisor Typ 1 und Typ 2 
### Hypervisor Definition

Ein **Hypervisor**, auch als Virtual Machine Monitor (VMM) bekannt, ist eine Software, Firmware oder Hardware, die virtuelle Maschinen (VMs) erstellt und ausführt. Ein Hypervisor ermöglicht es mehreren Betriebssystemen, gleichzeitig auf einem einzigen physischen Computer (Host) zu laufen, indem er die Hardware-Ressourcen wie CPU, RAM und Speicherplatz auf die VMs aufteilt.

### Hypervisor Typ 1 (Bare-Metal-Hypervisor)

- **Beschreibung:** Läuft direkt auf der Hardware des Host-Systems.
- **Beispiele:** VMware ESXi, Microsoft Hyper-V, KVM.
- **Vorteil:** Direkter Zugriff auf die Hardware, daher effizienter und performanter.

### Hypervisor Typ 2 (Hosted-Hypervisor)

- **Beschreibung:** Läuft auf einem Host-Betriebssystem, das auf der Hardware installiert ist.
- **Beispiele:** VMware Workstation, Oracle VirtualBox, Parallels Desktop.
- **Vorteil:** Einfache Installation und Verwaltung, da er als Anwendung auf einem bestehenden Betriebssystem läuft.
# HP-Elitebook-840_g3_EFI
<p> Author - <b> Rahul Singh. </b> </p>
<p> This is the working Opencore EFI for HP_Elitebook_840_g3 for MacOS Ventura 13.6.4 and you can update it to 13.7.5 with this EFI. </p> 

# SMBIOS
In this EFI, My Machine SMBIOS is USED, So please change SMBIOS acording to your Machine or your choice. 
I am using Macbook pro(13, 1) 2016 SMBIOS for My Machine.

# Release 
version - 1.0 

# Specification of My Machine is: 
* Processor (CPU) :- Intel Core i5-6300U Dual Core 4 Thread with 3 MB Intel Smart Cache 
* GPU                     :- Intel HD Graphics 520 (Shared Memory 8GB) 
* RAM Unit                :- 16GB DDR4-2133 
* SSD                     :- Micron MTFDDAV256GB PCI m.2ssd
* Audio                   :- Conexant CX20724 HD 
* Wi_Fi/Bluetooth         :- Intel Wireless-AC 8260 
* Ethernet                :- Intel l219-LM 

# MacOS Download
Download MacOS - [ventura 13.6.4](https://drive.google.com/file/d/1ftSof5A4sjahHHCWiG0o91ZEteKZA8-r/view) -- Use this link to Download MacOS Ventura. 

## Set Bios Settings to These Settings
 * Security -> Intel Software Guard Extensions (SGX) -> Disable
 * Advanced -> Boot Options -> Check "UEFI Boot Order"
 * Advanced -> Boot Options -> Uncheck "Legacy Boot Order"
 * Advanced -> Secure Boot Configuration -> Configure Legacy Support and Secure Boot -> Legacy Support Disable and Secure Boot Disable 
 * Advanced -> System Options -> Check "Hyperthreading" 
 * Advanced -> System Options -> Check "Virtualization Technology (VTx)"
 * Advanced -> System Options -> Uncheck "Virtualization Technology for Directed I/O (VTd)"
 * Advanced -> Build-In Device Options -> Video memory size -> 64MB or anything higher 

 # Credits 
 [Dortania](https://github.com/dortania) -- Opencore EFI Build
 [Apple](https://www.google.com/ca/) -- MacOS Build
 # 
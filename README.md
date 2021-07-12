# Is Keyboard Rootkitted
License: **GPL-3.0-or-later**  
  
This application with its driver detects SMM rootkit on keyboard by checking I/O APIC IRQ1 and IOTR0-IOTR4 for
and SMI trapped keyboard handler. If it detects it, you have been SMM rootkitted.

You need a driver signing certificate to have this work.



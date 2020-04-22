# Crio-Launch-Feb-2020-thummarm097-ME_QBOX
QBox is a secure file-sharing service. It is a customized version of the popularly available VSFTPD server.

During this Micro-Experience, I:

    Created pre-install scripts to run system checks, install and configure QBox.
    
    Developed tools to automatically analyze performance and functionality issues in different versions of QBox.



![Basic Concept Image](https://raw.githubusercontent.com/Milan097/Crio-Launch-Feb-2020-thummarm097-ME_QBOX/master/report-images/Module-1.png)



QBox Modules

  1.  Check system requirements and install QBox

      - Scope of work:<br/><br/>
           Implemented a pre-installation script that validated the minimum system requirements to be met for QBox installation. The script checked the availability of the following system resources:<br/><br/>
                   - Processor<br/>
                   - Memory<br/>
                   - Disk space<br/>
                   - OS version<br/><br/>
      - Installed the QBox server and connected it to various QBox clients.
      
  ![Module-1](https://raw.githubusercontent.com/Milan097/Crio-Launch-Feb-2020-thummarm097-ME_QBOX/master/report-images/Module-2.jpg)
  
  2.  Debug performance issues and identify regressions

      - Scope of work:<br/><br/>
              1. Created a performance benchmark using a base version of QBox.<br/>
              2. Identified regressions in newer QBox versions (memory usage, cpu usage, file transfer speed, file permission issues).
              
  ![Module-2](https://raw.githubusercontent.com/Milan097/Crio-Launch-Feb-2020-thummarm097-ME_QBOX/master/report-images/Module-3.jpg)

  3.  Troubleshoot network issues

      - Scope of work:<br/><br/>
              1. Collected and analyzed pcap files using Wireshark.<br/>
              2. Identified the following network issues in different versions of QBox: TCP retransmissions, connection refusals, dropped connections, sub-optimal TCP window sizes and retransmission delays.<br/>
              3. Identified several network issues in different versions of QBox including TCP retransmissions, connection refusals and retransmission delays.<br/>
              
  ![Module-3](https://raw.githubusercontent.com/Milan097/Crio-Launch-Feb-2020-thummarm097-ME_QBOX/master/report-images/Module-4.jpg)
  
  4.  Enable end-to-end encryption

      - Scope of work:<br/><br/>
              1. Created SSL certificates and used them to enable secured file transfer.<br/>
              2. Snooped network traffic using Wireshark and ensured that it was indeed encrypted.<br/>

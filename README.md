# New-TLS-and-Web-security-advancements

In this repo I'm maintaining a list of decrypted pcap files that you can use to follow and understand the advancement and security changes that happens last 10 years in TLS:

From TLS1.2, to TLS1.3 , to ESNI , to ECH , and QUICK / HTTP/3

You can download the pcap of your technology, and importat the SSL key file (with same name into wireshark) by following this steps:

Go to Edit -> Preferences. Open the Protocols tree and select TLS. Alternatively, select a TLS packet in the packet list, right-click on the TLS layer in the packet details view and open the Protocol preferences menu.  Then choose : (Pre)-Master-Secret log filename  ( and upload your correct tls.keylog_file)

Click on OK in top of the screen to see the decrypted packets

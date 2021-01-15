# TwinCAT-http-Client

Beckhoff TwinCAT 3 http Client

Beschreibung:
Dieser FB dient der Kommunikation mittels HTTP/1.0 Protokoll 

Benötigte Bibliotheken:
	-> Tc2_TcpIp
	-> Tc2_Utilities
	
Benötigte FB´s:
	->FB_TcpClient (ist enthalten)
	
Benötigte Lizenzen:
	-> TF6310

Weiteres:
Außerdem wird das Sublement "TF6310-TCP-IP.exe" benötigt.
Dahinter verbirgt sich ein Server, der die Kopplung zu den verwendeten Sockets vornimmt.
Der Server kann von der Beckhoff Seite herunter geladen werden.
Danach sollte der Server auch gestartet werden. Die exe ist zu finden unter "C:\TwinCAT\Functions\TF6310-TCP-IP\Win32\Server"

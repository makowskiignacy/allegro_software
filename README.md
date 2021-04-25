Project is using tcp connection instead of HTTP protocol.
To run with default port 4444 use:
    java -jar allegro_software.jar
To specify port run:
    java -jar allegro_software.jar <your port>
    
To connect to server you may use:
    nc <your server ip> 4444
if you have chosen your own port:
    nc <your server ip> <your port>
    and then ask queries, to shout down the server write "poweroff"

There is a possibility to develop another extends of abstract classes such as Http server

# ArVis Intern Project

Project : Select a photo from pc , encrypt it with AES algorithm then send to server and save it.

## Tools

Qt,Cmake,Qmake,Cryptopp,C++

## Project Stages

- Download and set up Qt(Open Source,Latest version),cryptopp,cmake
- Create libcryptopp.so and libcryptopp.a files with make install command and Cmake GUI in the ***"usr/local/lib"*** path.
- Open Qt And open ***TCPClient and TCPServer*** projects.
- Add libcryptopp.so into project.
- Then run client and server at the same time.
- First enter ***Connect*** button to communicate with the server.
- Then enter a message and push ***select*** button to select photo from pc.
- Push ***send*** button to send server.
- In the server side , message and text were taken and saved.
- Photo saved the same path with the project. You can check it :).


## Attention Here 

- Only 1 photo can be sent.
- Only can be sent from client to server.
- First push connect button.
- In the client side , ip adress is static local ip adress. It has to be changed.
# PyInjectorV4
A simple Python 2 HTTP/HTTPS Payload Injector & logger Server

This can also be used as a HTTP/HTTPS logger to sniff(see) the requests sent by the applications and browser.

To run this server, we need to use Python 2.

### Steps to use the server 

1. Open Config.ini file and set your proxy, port and desired payload which acts as bug for your Internet provider or Simcard providers.

2. Use the following command to run the Payload Injector Server :

    ```code
    python  injector.py
    ```
3. Follow the instructions shown on screen while running the server. Selected desired Profile & Payload Injection mode.

4. Configure sytem proxy as 127.0.0.1 & the same local port at which our server is listening so that all requests sent by applications are routed to this Injector Server which will forward request to original servers and recive response and the send it the corresponding applications which made the request.





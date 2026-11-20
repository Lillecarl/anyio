Fixed ``create_unix_listener()``, ``create_unix_datagram_socket()`` and
``create_connected_unix_datagram_socket()`` checking for and removing an existing
socket file in the event loop thread

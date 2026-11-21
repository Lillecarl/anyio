Fixed ``create_unix_listener()``, ``create_unix_datagram_socket()`` and
``create_connected_unix_datagram_socket()`` applying the process umask to the
requested socket mode on Linux

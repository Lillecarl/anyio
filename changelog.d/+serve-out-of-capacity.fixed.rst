Fixed ``SocketListener.serve()`` exiting when ``accept()`` fails because the process or
the system has run out of file descriptors or memory (``EMFILE``, ``ENFILE``,
``ENOMEM`` or ``ENOBUFS``). It now logs the error and tries again after 0.1 seconds,
like Trio's ``serve_listeners()``.

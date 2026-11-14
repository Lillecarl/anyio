Fixed the pytest plugin discarding the event loop's error message (which names the
failing callback) when re-raising an exception from an asynchronous callback on asyncio

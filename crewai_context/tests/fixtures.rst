event_loop
==========

Provides a dedicated asyncio event loop for each test session.

Usage::

    async def test_example(event_loop):
        await asyncio.sleep(0)

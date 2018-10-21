# PMPro FAQ

We've been collecting some commonly asked questions here. We'll either be updating the guide directly, providing answers here, or both.

## What Node versions does PMPro support

The latest version of PMPro and all plugins work with Node 6 and later. Node 6 will be supported until **2019-04-18** when the official support cycle ends.


## How do I create custom methods?

One important thing to know about PMPro is that it only exposes the official [service methods](../api/services.md) to clients. While you can add and use any service method on the server, it is __not__ possible to expose those custom methods to clients.

The benefits (like security, predictability, sending well defined real-time events) so far heavily outweighed the slight change in thinking required when conceptualizing your application logic.

Examples:

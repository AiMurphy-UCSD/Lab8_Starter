# Lab8-Starter

Aidan Murphy

[Link](https://aimurphy-ucsd.github.io/Lab8_Starter/)

How are graceful degradation and service workers related?

Graceful degradation and service workers are related in the fact that service workers help implement graceful degredation for web apps, primarily when it comes to issues like network failures and the user's offline experience. Graceful degredation is a design apporach where features are used when available, however the core base and functionality still works without them. Service workers enable this by allowing the caching of assets, the interception of network requests, etc., ensuring that when a site degrades if the network fails or something is wrong with the brower, it degrades gracefully.

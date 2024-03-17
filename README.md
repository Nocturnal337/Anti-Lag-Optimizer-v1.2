# What is it?
This is an object rendering system that can improve the performance of you or your server players. She draws only those objects that the player sees. The system can perform calculations both on the server side and on the client side, which makes it flexible enough to customize to your requirements.
In my add-on, I try to minimize unnecessary calculations by caching data and optimizing the parsing of large lists of objects, unlike other analogues.
Important! This addon was mainly developed for use on game servers. It will not increase FPS for you under heavy load, but it can increase FPS for players on your powerful server. I do not recommend using this in sandbox mode, since large maps require a large rendering distance, and increasing it for the system will reduce half the optimization to a minimum. However, this addition will be appropriate for such modes as DarkRp, where the spaces are quite tight, and do not require rendering for 5000 game units.



# Warning:
Cvars work only once at system startup, and do not change in real time unless you manually update the file. This is done for optimization reasons to reduce the time it takes to access variables.

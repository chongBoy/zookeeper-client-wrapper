a years ago, I touch zookeeper first time because of the project need, and felt it's very powerful and useful. But unfortunately I had no chance to use it.
I recently tryed to develop gid service, and planed to use zookeeper to implement master-election. But after some deep study, I find that zookeeper is hard to be used with rubust, more accurately, zookeeper-client is hard to be used. 
Obviously, make a toy with zk-client is easy, which make people feel full of self-confident. But when use it to build a product which run in a online situation, it easily become a bug evil! 
so I decide to make a wrapper on it at spare time.


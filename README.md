Dancing Plastic
===========

####Introduction :

Dancing Plastic is a Sobeit's fork (https://github.com/BlastHackNet/mod_s0beit_sa). The goal of this project is to give to anyone an easy-to-use and an user friendly addon for SA-MP. The main goal is not to make new cheats.

####New / Modified feature :

Feature Name  | Date | Description of the feature
------------- | ------------- | -------------
Keybind version 0.00001 | 15/04/14 | [Click here to go to the description](#keybind)
Game Pause | 15/04/14 | [Click here to go to the description](#game_pause)
USERDATA.DAT | 18/04/14 | [Click here to go to the description](#userdata)
/~cg_name | 18/04/14 | [Click here to go to the description](#cg_name)

####Contact :

Don't hesitate to contact me if you have any questions. I often check Github.


===========
#### Descriptions

###### Keybind
Modified the keybind system. This is now different. It used to be only one sentence per key. But now, you can say more than one sentence per key !

Check this example in the .ini :

>chat[] = 1 "~Hello mates !~How are you ?~~"

This line means that when you will press the key "1", you will see that :

![alt tag](http://img15.hostingpics.net/pics/427423samp001Copie.png)

So, you have to put sentences between ~, and at the end, put ~~.

As you can see, I removed the spam feature, since I don't really like it. I will surely add new feature to the keybind.

###### Game_Pause

Thanks to some opcode, the game is no more paused when you are in the menu. It means that if you are on sa-mp and that you go in the pause menu, your game will not be paused.

###### USERDATA
USERDATA.DAT is the file which contains the list of your favorite server. Servers that you have added with your sa-mp client.

You have to put this file (USERDATA.DAT) into your mod_sa directory. This action will allows you to see this list and to be able to connect with your client.

![alt tag](http://img4.hostingpics.net/pics/421380samp002Copie.png)

###### cg_name

I have added a new client command :

```/~cg_name```

This command allows you to change your name when you will connect to another server.

For example : 

```/~cg_name gaymaster```

And then, you can connect to a server.

If you connect to a server which is in your .ini, it will use the name that you have put in the .ini.

But, if you conncet to a server which is in your USERDATA.DAT, it will use the name that you have put in /~cg_name.

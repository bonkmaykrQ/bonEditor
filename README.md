# bonEditor
A Binary JSON file editor, powered by the SimpleJSON API.

**Incomplete project, not yet functional really.
Well... it CAN read files though (sort of) but saving and other things haven't been introduced and this version usually crashes when files are loaded because I've been trying to get it to show the actual names of each JSONObject but it's not so easy with the way SimpleJSON was organized... Perhaps it's a good idea to ask him for help since that's his code and he knows it best, and if there's nothing that can satisfy my needs for this project then it'll be much less painful to have him implement extra shiz. With that in mind, SimpleJSON is amazing... I'm using it for game saves in a game I'm making actually and its super great, just maybe not in my specific case... and it's very easy to use so if you want to try it check out Bunny83's repo. I couldn't find any documents on it however, only the change logs which are commented at the beginning of the scripts so if your IDE doesn't have good intellisense/autofill, you'll probably need to look over the code yourself or get help. (And by that, I mean an autofill which can actually suggest members from your assembly references like Microsoft VS does, I'm not talking about that puny Notepad++ crap).**

**As for this program... it's not ready yet... Reading/writing files is super easy to implement, and I'm working on making the values editable, but haven't implemented these yet because I want to make sure each JSONNode's name is identifiable so it is user-friendly. But definitely smash that Watch button and wait on future updates, I'll let ya'll know if I make any significant progress.**

    about the actual thing:

The program uses a UI somewhat reminiscent of the Windows **Registry Editor**, where each node is divided into sections organized using a TreeView control. When 1.0 is released, it will be able to show all the info you could ever want or need from a Binary-formatted JSON file, allow for the reordering of different nodes in the node tree/index, show file information, etc. whatever whatever something else...

And hopefully after that is done I will implement better compatibility with JSON files written with plain text (the familiar format we all love *amiright*). 

And ***possibly later*** (but probably not so don't get your Hope's up yet 'cuz I only started this week and idk where I'm going) BONEdit will even support compression... including the built-in compression methods in SimpleJSON's Binary and Serializer extensions (which require additional dependencies), as well as other formats if possible (such as LZ4 and other lossless algorithms) from an options menu regarding file properties. Oh, and speaking of which!!

Ah yes, being able to declare HOW the file gets generated, using a properties section! Coming in the *far* future.

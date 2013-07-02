DDDEastAnglia2013-Async
=======================

DDD East Anglia 2013 - Async patterns and practices source code in C#

If you are new to Git then the easiest client to install is GitHub for Windows, a graphical UI for accessing GitHub. Personally, I also have Git Extensions and Tortois Git installed.  Tortoise Git is the file explorer add-in that works in a familiar manner to TortoiseSVN.

As I mentioned during the presentation I have not included the sample data, the music files, in the source code placed on GitHub but I have included instructions on how to download them from http://silents.bandcamp.com and place them in the correct folders.

Also, Windows Media Player, by default, does not play Ogg Vorbis and Flac music files, however you can download the codec installer for these, for free, from http://xiph.org/dshow.

I have included the .Net 4.0 version of the source code that uses the Microsoft.Bcl.Async NuGet package - once you have got the project from GitHub you will need to install this NuGet package for the code to compile.

* Load Project into Visual Studio 2012
* Access the NuGet package manager (Tools -> Library Package Manager -> Manage NuGet Packages For Solution)
* higlight Online and then Search Online for microsoft.bcl.async
* Click on Install button

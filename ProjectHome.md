Garuda Messenger is a Chat Service Client. There are many chat services on the internet like Yahoo, MSN, AIM, Google Talk etc. Garuda aims to provide a client environment to all those messenger services under one roof. So that users who have accounts in all those services need not download and use separate clients for each one of them. With Garuda you can use only one client and access those services, thus avoiding confusion for novice users of internet. Garuda is inspired from other such softwares like Gaim(Currently Pidgin) and Miranda.
Presently, Garuda Messenger is a client for only Google Talk (Jabber Protocol). Soon other messenger service clients will be integrated.
Requirements:
CPU: 800 MHz Intel or AMD CPU
RAM: 256MB RAM or more
OS: Microsoft Windows 2000/XP/2003/Vista
.NET Framework 2.0 or above (Vista users need not download .NET framework separately)
Internet Explorer 6.0 or above
Flash plug-in for Internet Explorer (Optional) – For the video playback

How to send videos to a friend:
For YouTube videos, you can send the link of the video page as a message to your friend. Video will be displayed automatically inside chat window for you as well as your friend. For other sites however, you must follow couple of steps.
**Copy the embedded source text of the video that the website provides.** Type “video:” without quotes in the chat window and then paste the embedded source text that you copied in the first step
So for example the website provides a source like -


&lt;embed&gt;



&lt;object&gt;

The greatest video ever made

&lt;/object&gt;



&lt;/embed&gt;


Then the message you have to send will be:
video:

&lt;embed&gt;



&lt;object&gt;

The greatest video ever made

&lt;/object&gt;



&lt;/embed&gt;



How to send images/pictures to a friend:
You can send images in the same way. Replace the first word (‘video’ in above case) with image and the embedded source with link of the image.
So to send an image with link ![http://www.abcxyz.com/crazychapstick.jpg](http://www.abcxyz.com/crazychapstick.jpg), message will be
image:![http://www.abcxyz.com/crazychapstick.jpg](http://www.abcxyz.com/crazychapstick.jpg)


Customizing the chat window:
To customize chat window, open any chat window, save that conversation as html page with file name "BoxTemplate" (without quotes. full filename should be BoxTemplate.html ) in the same directory the executable is located.
You can edit this html page to your heart’s content so long as you keep the JavaScript functions you find in it as messages r printed out using those functions. Edit those functions carefully to modify message printing recommend using absolute file paths inside BoxTemplate, instead of relative linking. Hit the reload button in chat window to refresh it with edited page. All messages will be lost in that window. So beware.
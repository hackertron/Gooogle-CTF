So our second challenge in beginner’s quest is of PWN category. The challenge name is Moar.

It’s a pwn challenge so it can be some kind of binary exploitation challenge.
So after doing netcat with the given host and port we get a man page.

and there is nothing we can do with this page. It’s just a man page. Since it’s a pwn challenge we need to get shell or execute commands. So if you see closely man page has less program running. If you do a simple google search ‘run terminal commands in less’
the results shows “You can access the command line using bang (!) within less.”
so let’s try it out  !ls /home

and then doing !cat /home/moar/disable_dmz.sh will give us our flag

CTF{SOmething-CATastr0phic}

 

Solved !!

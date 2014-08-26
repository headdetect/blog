I posted an album of my [battlestation/room](http://www.reddit.com/r/battlestations/comments/2eco5x/i_like_red_white_and_black/) to Reddit a couple days ago. At the end of the album I showcased a little something I was working on. ![TheGifImage](http://i.imgur.com/230L5BK.gif)

I thought it was pretty neat, and I guess Reddit did too. By the time I awoke in the morning, I had several messages asking "How does the sleep app work?". 

After several days of procrastination, school work, and more excuses, I managed to get _something_. 

[TaskerSlave](https://github.com/headdetect/TaskerSlave). This ugly sumbich will allow you to receive HTTP GETS and run a command following the request. For example. 

**URL**: `/lock`
**Command**: `Rundll32.exe User32.dll,LockWorkStation`

This will lock the desktop when the TaskerSlave's very minimal http server receives the request for the `/lock` URL. 

Now, I get that this is not exclusive for Tasker. Thanks! I know. But plans in the future may change it so that it can only be used for tasker.

Enjoy!

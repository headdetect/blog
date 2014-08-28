I posted an album of my [battlestation/room](http://www.reddit.com/r/battlestations/comments/2eco5x/i_like_red_white_and_black/) to Reddit a couple days ago. At the [end of the album](http://i.imgur.com/230L5BK.gif) I showcased a little something I was working on. 

I thought it was pretty neat, and I guess Reddit did too. By the time I awoke in the morning, I had several messages asking "How does the sleep app work?". 

After several days of procrastination, school work, and more excuses, I managed to get _something_ that I could release. 

[TaskerSlave](https://github.com/headdetect/TaskerSlave). This ugly sumbich will allow you to receive HTTP GETS and run a command following the request. For example. 

**URL**: `/lock`  
**Command**: `Rundll32.exe User32.dll,LockWorkStation`

This will lock the desktop when the TaskerSlave's very minimal http server receives the request for the `/lock` URL. 

Now, I get that this is not exclusive for Tasker. Thanks! I know. But plans in the future may change it so that it can only be used for tasker. However, as of now, simple http gets.

### So how do I get this magic?

Well, let me tell you!

- Download [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en) for android
- Download TaskerSlave for [windows](https://mrlopez.me/blob/downloads/TaskerSlave/v1.0/win.zip)/mac/linux.
- Open TaskerSlave, you should see 3 prebuilt commands. `Sleep`, `Lock`, and `Shutdown`. Add all the commands you want.
- In tasker, go to the **tasks** tab.
- Click ‘+’ and click ‘Net’ and then click ‘HTTP Get’. 
- In the **Server:Port** box, enter `<YourIPAddress>:8080`
- In the **Path** box, enter your url for the command you would like this task to execute. Ex. `/lock`

If you have any problems (and you just might)/want a new feature please report a bug/feature [here](https://github.com/headdetect/TaskerSlave/issues)

Enjoy!

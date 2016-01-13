Broken scrolling in Android
---

```
ionic run android
```

Be sure to change your Android settings so that the soft keyboard shows,
the bug doesn't manifest if the keyboard doesn't show up. Different
versions of Android have different ways to do this, but go into
Settings->Language & Input and touch the "Current Keyboard" item, try
toggling the "Hardware" toggle.

Go back to the test app.

1. Click on the "Chats" tab.
2. Try to scroll through the chats. Notice it works.
3. Click on the "Type an email" input
4. type something (not sure this is necessary)
5. Dismiss the keyboard by clicking anywhere else or by clicking the
   soft key to close the keyboard.
6. Try to scroll through the chats. Notice it no longer works.

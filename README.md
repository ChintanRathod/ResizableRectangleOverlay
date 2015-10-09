Resizable Rectangle Overlay
===========================

Resizable Overlay

When I read this question [How to create a resizable rectangle with user touch events on Android?!](http://stackoverflow.com/questions/8974088/how-to-create-a-resizable-rectangle-with-user-touch-events-on-android)  on StackOverFlow, I tried to develop a custom control overlay which behaves like below.

![First Fragment](http://i.stack.imgur.com/cajl4.jpg)

**What this sample do?**

Current sample application will do only overlay on image. 

**What this sample can't do?**

This will not crop image or do other operation. Other operations will be added soon in next versions.

To use custom control in your application, write following code in your layout file.

    <com.chintanrathod.customviews.DrawView
        android:id="@+id/drawView1"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>
        

MIT License
------

The MIT License (MIT)

Copyright (c) 2015 Chintan Rathod

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Resizable Rectangle Overlay
===========================

Resizable Overlay

When I read this question  http://stackoverflow.com/questions/8974088/how-to-create-a-resizable-rectangle-with-user-touch-events-on-android on StackOverFlow, I tried to develop a custom control overlay which behaves like it.

Current sample application will do only overlay on image. This will not crop image or do other operation. Other operations will be added soon in next versions.

To use custom control in your application, write following code in your layout file.

    <com.chintanrathod.customviews.DrawView
        android:id="@+id/drawView1"
        android:layout_width="match_parent"
        android:layout_height="match_parent"/>


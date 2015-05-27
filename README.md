# OpAnimateView
Material Design View with Animation
----
![](https://github.com/hanks-zyh/OpAnimateView/blob/master/1.gif)

#Useage
```xml
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
                xmlns:tools="http://schemas.android.com/tools"
                xmlns:app="http://schemas.android.com/apk/res-auto"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:paddingBottom="@dimen/activity_vertical_margin"
                android:paddingLeft="@dimen/activity_horizontal_margin"
                android:paddingRight="@dimen/activity_horizontal_margin"
                android:paddingTop="@dimen/activity_vertical_margin"
                tools:context=".MainActivity">

    <!-- NOTE : change the path   -->
    <app.hanks.com.customanimateview.OpAnimateView.OpAnimationView
        android:id="@+id/animView"
        android:layout_width="150dp"
        android:layout_height="150dp"/>

    <app.hanks.com.customanimateview.OpAnimateView.OpAnimationView
        android:id="@+id/animView2"
        android:layout_width="50dp"
        android:layout_height="50dp"
        app:shapeColor="#939D29"
        app:shapeWidth="2dp"
        app:backgroundColor="#EEFF44"
        android:layout_centerVertical="true"
        android:layout_toEndOf="@+id/button"
        android:layout_toRightOf="@+id/button"/>

    <app.hanks.com.customanimateview.OpAnimateView.OpAnimationView
        android:id="@+id/animView3"
        android:layout_width="100dp"
        android:layout_height="100dp"
        app:shapeWidth="3dp"
        app:backgroundColor="#03A9F4"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentTop="true"/>

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:onClick="click"
        android:text="anim"/>

</RelativeLayout>

```

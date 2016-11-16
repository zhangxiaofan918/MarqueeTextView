# MarqueeTextView
Android实现跑马灯效果

# XML文件 
    <com.nick.demo.view.MarqueeTextView
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_centerVertical="true"
		android:ellipsize="marquee"
		android:marqueeRepeatLimit="marquee_forever"
		android:singleLine="true"
		android:text=""
		android:textColor="@android:color/darker_gray"
		android:textSize="15sp" />

# 使用说明

 把MarqueeTextView.java文件copy到你的工程里，然后在布局中引用这个自定义控件就行了。

 android:ellipsize="marquee"  跑马灯  
 android:marqueeRepeatLimit="marquee_forever" 设置重复滚动的次数  
 android:singleLine="true"  单行显示

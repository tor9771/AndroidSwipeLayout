AndroidSwipeLayout
==================

AndroidSwipeLayout For Eclipse

This is the brother of AndroidViewHover.

One year ago, I started to make an app named EverMemo with my good friends. The designer gave me a design picture, the design like this:



I found it was pretty hard to achieve this effect, cause you had to be very familiar with the Android Touch System. It was beyond my ability that moment, and I also noticed that there was no such a concept library...

Time passed, finally...as you see right now.

Demo



Download Demo

Before I made this, I actually found some libraries (eg.SwipeListView) that helps developers to integrate swiping with your UI component.

But it only works in ListView, and it has too many issues that they never care. What a pity!

When I start to make this library, I set some goals:

Can be easily integrated in anywhere, ListView, GridView, ViewGroup etc.
Can receive onOpen,onClose,onUpdate callbacks.
Can notifiy the hidden children how much they have shown.
Can be nested each other.
Can handle complicate situation, just like this.
Usage

Step 1

Gradle

dependencies {
        compile 'com.android.support:support-v4:20.+'
        compile "com.daimajia.swipelayout:library:1.1.7@aar"
}
Maven

<dependency>
    <groupId>com.google.android</groupId>
    <artifactId>support-v4</artifactId>
    <version>r6</version>
</dependency>
<dependency>
    <groupId>com.daimajia.swipelayout</groupId>
    <artifactId>library</artifactId>
    <version>1.1.7</version>
    <type>apklib</type>
</dependency>
Eclipse

AndroidSwipeLayout-v1.1.6.jar

Step 2

Wiki Usage

Wiki

Go to Wiki

About me

A student in mainland China.

Welcome to offer me an internship. If you have any new idea about this project, feel free to contact me. :smiley:

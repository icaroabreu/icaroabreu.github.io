---
layout: post
title: Most used android libraries
---
First of all, I'm sorry for taking too long to write... I've been working non-stop since my last(first) post.

But let's get down to business!

Libraries that come in handy in my daily work
========
  1 . [**Retrofit**](http://square.github.io/retrofit/)

It's a type-safe REST client for Android and Java made by [Square](http://square.github.io/) which its only job is to make your interaction with a REST server much easier. Quoting Retrofit documentation:
> Retrofit turns your REST API into a Java interface.

I'll make a article explaining how to take advantage of Retrofit's sweetness.
> **Gradle**

> compile 'com.squareup.retrofit:retrofit:1.9.0'


  2 . [**OkHttp**](http://square.github.io/okhttp/)

To escape from Android and Java default HTTP and SPDY client [Square](http://square.github.io/) gave us OkHttp! And guess what, integrates with Retrofit to make things more interesting. Basically if you use them both, you're good to go with no headache. 
> **Gradle**

> compile 'com.squareup.okhttp:okhttp:2.4.0'


3 . [**Picasso**](http://square.github.io/picasso/)
It's a image downloading and caching library for Android made by [Square](http://square.github.io/)! With just a single line of code you can: download, apply transformations, set a download placeholder, set a error placeholder and load the image directly into a ImageView! Or if you want to manage your image after downloading it, you can set a target, and there you can do whatever you want with it! It's magical... Quoting Picasso documentation:
> Many common pitfalls of image loading on Android are handled automatically by Picasso:
> - Handling ImageView recycling and download cancelation in an adapter.
> - Complex image transformations with minimal memory use.
> - Automatic memory and disk caching.
 
> **Gradle**

> compile 'com.squareup.picasso:picasso:2.5.2'


4 . [**Butter Knife**](http://jakewharton.github.io/butterknife/)
Tired of writing boilerplate view binding code? Use Butter Knife! It's a field and method binding library for Android views. Quoting Butter Knife documentation:
> Annotate fields with `@Bind` and a view ID for Butter Knife to find and automatically cast the corresponding view in your layout.

It is really that easy to use. Just do it!
> **Gradle**

> compile 'com.jakewharton:butterknife:7.0.1'


5 . [**Android Support Library 22.1**](http://android-developers.blogspot.com.br/2015/04/android-support-library-221.html)
It's simply a library(or a collection of libraries) that allows you to take advantage of Android newest components and write apps compatibles with all versions of Android.
>**Gradle**

>compile 'com.android.support:appcompat-v7:22.2.1'
>compile 'com.android.support:cardview-v7:22.2.1'
>compile 'com.android.support:gridlayout-v7:22.2.1'
>compile 'com.android.support:leanback-v17:22.2.1'
>compile 'com.android.support:mediarouter-v7:22.2.1'
>compile 'com.android.support:palette-v7:22.2.1'
>compile 'com.android.support:recyclerview-v7:22.2.1'
>compile 'com.android.support:support-annotations:22.2.1'
>compile 'com.android.support:support-v13:22.2.1'
>compile 'com.android.support:support-v4:22.2.1'
 

6 . [**Android Design Support Library**](http://android-developers.blogspot.com.br/2015/05/android-design-support-library.html)
To use the newest design features for Android in all versions as well, Google released the Design Support Library. 
Which contains:
>- Navigation View
>- Floating labels for editing text
>- Floating Action Button
>- Snackbar
>- TabLayout
>- CoordinatorLayout
>- Collapsing Toolbars

>**Gradle**

> compile 'com.android.support:design:22.2.0'

In the future I'll update this list with more juicy libraries!

-----
May the force be with us, so that we have a long and prosper life!

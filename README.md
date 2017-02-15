# Ten Things Every Expert Xamarin Developer Should Know

These links and demo projects are here to accompany the Ignite Australia 2017 session.  There are just so many great links and resources out there, we couldn't possibly list them all out during the session.  

Enjoy.

<HR>

## #1 :  Know when to use Xamarin.Forms

* [**Xamarin.Forms Homepage**](https://www.xamarin.com/forms) - The landing place for Xamarin.Forms. Provides links to Xamarin.Forms and Xamarin.iOS and Xamarin.Android as well as a comparison of why you would use each.

* [**Merge Conflict episode 31: One UI to Rule Them All**](http://www.mergeconflict.fm/merge-conflict-31-one-ui-to-rule-them-all) - Frank and James debate the Pros and Cons of Xamarin.Forms. They discuss performance, look and feel, alternatives, and if we really should be using all those fancy data bindings.

<HR>

## #2:  Know how to customise Xamarin.Forms

* [**Styles and Resources in Xamarin Forms**](https://developer.xamarin.com/guides/xamarin-forms/user-interface/styles/) - Xamarin documentation on Styles and Resources.

* [**IOS UIAppearance**](https://developer.xamarin.com/guides/ios/user_interface/introduction_to_the_appearance_api/) - Use the UIAppearance API to add some zing to your iOS projects

* [**Material Theming**](https://developer.xamarin.com/guides/android/user_interface/material_theme/) - Beautiful native android theming

* [**Effects Documentation**](https://developer.xamarin.com/guides/xamarin-forms/effects/introduction/) - Xamarin Docs on Effects

* [**Forms Community Toolkit Effects**](https://github.com/FormsCommunityToolkit/Effects) - Community library of effects you can use in your applications or pull apart and see how they work.

* [**Custom Renderer Documentation**](https://developer.xamarin.com/guides/xamarin-forms/custom-renderer/) - Official docs on renderers

* [**Handy reference to native controls used by renderers**](https://developer.xamarin.com/guides/xamarin-forms/custom-renderer/renderers/) - Every Xamarin.Forms control has an accompanying renderer for each platform that creates an instance of a native control. This article lists the renderer and native control classes that implement each Xamarin.Forms page, layout, view, and cell.

* [**Native Embedding**](https://developer.xamarin.com/guides/xamarin-forms/user-interface/layouts/add-platform-controls/) - Platform-specific controls can be directly added to a Xamarin.Forms layout. This article demonstrates how to add platform-specific controls to a Xamarin.Forms layout, and how to override the layout of custom controls in order to correct their measurement API usage.

<HR>

## #3: Know the Platforms

* [**HealthKit**](
https://developer.xamarin.com/guides/ios/platform_features/introduction_to_healthkit/) - Integrate with platform features like HealthKit. 

* [**Creating Extensions**](https://www.youtube.com/watch?v=HM5MqmvSgf8&index=23&list=PL5kjezgaPFo-AzDBmd2sE0ewt1O-_luWh) - Video on creating todays extension.

* [**Mesh Networking**](https://developer.xamarin.com/api/namespace/MultipeerConnectivity/) - Docs on mesh Networking

<hr>

## #4:  Know how to share code

### Shared Application Projects (SAP) vs Portable Class Libraries (PCL)
* [**Code Sharing Options**](https://developer.xamarin.com/guides/cross-platform/application_fundamentals/building_cross_platform_applications/sharing_code_options/) - Official Xamarin documentation on Shared Projects and PCL's including some advantages and disadvantages.

* [**Forum post discussing different peoples thoughts on SAP vs PCL**](https://forums.xamarin.com/discussion/59381/why-shared-projects/p1) - Includes some links to great posts by [Jason Smith](http://xfcomplete.net/general/2016/01/19/pcl-or-shared-project/) and [Miguel de Icaza](http://tirania.org/blog/archive/2016/Jan-22.html) and [Adam Pedley](http://xamarinhelp.com/portable-class-library-pcl-vs-shared-projects/).

* [**Hosting your own Nuget Feeds**](http://docs.nuget.org/create/hosting-your-own-nuget-feeds) - Sometimes its useful to have an "internal" set of components you want to use within your company. So why not host your own.

* [**IOC Containers with Xamarin**](http://arteksoftware.com/ioc-containers-with-xamarin/) - Rob Gibbens shows some code of how to integrate some of the most popular IOC Containers.

### Components

* [**Awesome Xamarin**](https://marcbruins.github.io/awesome-xamarin/) - A curated list of awesome Xamarin iOS/Android and Xamarin Forms bindings, ports, frameworks and much more!

* [**Awesome .NET**](https://dotnet.libhunt.com/) - A search engine for awesome .NET components (not Xamarin specific), but lots of gold in here.

* [**Xamarin Component Store**](https://components.xamarin.com/) - Components curated by the lovely folks at Xamarin.  The advantage of these is that you will always get a sample project to show you how to use the component, which provides a really nice starting point.

* [**Xamarin Plugins**](https://github.com/xamarin/plugins) - Open Source Components for Xamarin are a collection of open source components (including bindings and plugins) created by Xamarin and others in the community.  There is also instructions in here on how to create your own 

* [**DotNet Foundation**](https://dotnetfoundation.org/projects?type=project) - The .NET Foundation is an independent organization to foster open development and collaboration around the .NET ecosystem.

<HR>

## #5 Know how to structure your solution
* [**.NET Rocks episode 1411 - Xamarin MVVM apps with Gill CleerenVM**](https://www.dotnetrocks.com/?show=1411) - The Guys discuss MVVM and why you might want to use it as a way to structure your Xamarin.Forms app. 

* [**Prebuilt App Samples**](http://xamarin.com/prebuilt) - Xamarin Prebuilt applications, pull apart some applications and see how they are structured.

* [**Xamarin Evolve App**](https://github.com/xamarinhq/app-evolve) - A nice example of a well put together Xamarin Forms app. Quite a nice reference architecture.


<HR>

## #6 Know XAML

* [**XAML Compilation**](https://developer.xamarin.com/guides/xamarin-forms/xaml/xamlc/) - Xamarin documentation on XAML compilation.

* [**Databinding**](https://developer.xamarin.com/guides/xamarin-forms/xaml/xaml-basics/data_binding_basics/) - Data bindings allow properties of two objects to be linked so that a change in one causes a change in the other. This is a very valuable tool, and while data bindings can be defined entirely in code, XAML provides shortcuts and convenience. Consequently, one of the most important markup extensions in Xamarin.Forms is Binding.

* [**Creating Mobile Apps with Xamarin.Forms Book, First Edition**](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/) - This is a free ebook from Charles Petzold, the master of XAML.  So much goodness about XAML in this book. 

<HR>

## #7: Know how to store data locally and remotely

* [**Settings Plugin**](https://github.com/jamesmontemagno/SettingsPlugin) - Create and access settings from shared code across all of your mobile apps!

* [**Apple Documentation of FileSystem**](https://developer.apple.com/library/ios/documentation/FileManagement/Conceptual/FileSystemProgrammingGuide/FileSystemOverview/FileSystemOverview.html)

* [**Android Documentation on Data Storage**](https://developer.android.com/guide/topics/data/data-storage.html)

* [**Windows Documentation on Storage**](https://msdn.microsoft.com/en-us/windows/uwp/app-settings/store-and-retrieve-app-data)

* [**SQLite.NET - PCL**](https://github.com/praeclarum/sqlite-net) - SQLite-net is an open source, minimal library to allow .NET and Mono applications to store data in SQLite 3 databases. 

* [**Shipping a SQLite database with Xamarin.Forms**](http://arteksoftware.com/deploying-a-database-file-with-a-xamarin-forms-app/) - Sometimes you want to ship a database with your Xamarin.Forms app, here's how.

* [**Refit**](https://github.com/paulcbetts/refit) - The automatic type-safe REST library for Xamarin and .NET

* [**Polly**](https://github.com/App-vNext/Polly) - Polly is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

* [**Akavache**](https://github.com/akavache/Akavache) - Akavache is an asynchronous, persistent (i.e. writes to disk) key-value store created for writing desktop and mobile applications in C#, based on SQLite3. Akavache is great for both storing important data (i.e. user settings) as well as cached local data that expires.

* [**Enabling Platform Networking**]() -

* [**Resilient network services with mobile Xamarin apps**](http://arteksoftware.com/resilient-network-services-with-xamarin/) - Great article showing how to combine some frameworks together to create a resilient network layer.

* [**HTTPClient Platform Selection**](https://developer.xamarin.com/guides/cross-platform/macios/http-stack/) - The new HttpClient Stack and SSL/TLS Implementation Selector determines the HttpClient and SSL/TLS Implementation that will be used by your Xamarin.iOS, Xamarin.tvOS or Xamarin.Mac app.





<HR>

## #8: Know how to improve App performance

* [**FFImage Component**](https://github.com/luberda-molinet/FFImageLoading) - Library to load images quickly & easily on Xamarin.iOS, Xamarin.Android, Xamarin.Forms and Windows (UWP, WinRT).

* [**Tango and Cache**](https://github.com/rdio/tangoandcache) - TangoAndCache is an in-memory cache for bitmaps. At a basic level it is a byte-bound LRU cache, evicting the oldest entries as new ones push the cache over the high watermark. It facilitates Bitmap reuse to reduce the number of allocations made and monitors the count of bytes evicted from the cache in order to force GC cycles to prevent OOMs on the native side.

* [**Xamarin.Android performance**](https://developer.xamarin.com/guides/android/deployment,_testing,_and_metrics/performance/) - Many performance tips for Xamarin.Android applications.

* [**Xamarin.iOS performance**](https://developer.xamarin.com/guides/ios/deployment,_testing,_and_metrics/performance/) - Performance tips specific to Xamarin.iOS.

* [**Xamarin.Forms performance**](https://developer.xamarin.com/guides/xamarin-forms/deployment,_testing,_and_metrics/performance/) - There are many techniques for increasing the performance of Xamarin.Forms applications. Collectively these techniques can greatly reduce the amount of work being performed by a CPU, and the amount of memory consumed by an application. This article describes and discusses these techniques.  There is also a [cheat sheet](http://kent-boogaart.com/blog/jason-smith's-xamarin-forms-performance-tips) from Jason Smiths awesome Evolve 2016 talk.

* [**Cross Platform performance**](https://developer.xamarin.com/guides/cross-platform/deployment,_testing,_and_metrics/memory_perf_best_practices/) - Performance tips, focused more on general .NET optimisations and best practices.

* [**Xamarin.Forms ListView performance**](https://developer.xamarin.com/guides/xamarin-forms/user-interface/listview/performance/) - Although ListView is a powerful view for displaying data, it has its limitations. Scrolling performance can suffer when using custom cells, especially when they contain deeply nested view hierarchies or use certain layouts that require a lot of measurement. Fortunately, there are techniques you can use to avoid poor performance.

<HR>

## #9 Know how to test your app

* [**Xamarin.UITest Cheat Sheet**](https://developer.xamarin.com/guides/testcloud/uitest/cheatsheet/) - This document is a cheat sheet that condenses UITest information for quick reference.

* [**Test Cloud**](https://developer.xamarin.com/guides/testcloud/introduction-to-test-cloud/) - This guide offers a quick introduction to Xamarin Test Cloud and Automated UI Acceptance Testing. It will discuss the underlying concepts and components behind Xamarin Test Cloud and the frameworks that allow developers to write automated UI tests.

<HR>

## #10 Know where to get information

### Official Stuff
* [**The Official Xamarin Documentation**](https://developer.xamarin.com) - The docs team update this information all the time to keep up with the latest updates, also it has many great recipes and guides worth looking at.

* [**Creating Mobile Apps with Xamarin.Forms Book, First Edition**](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/) - This is a free ebook from Charles Petzold. It's the authoritative text on developing Xamarin forms applications.  It's pretty hefty, so if you are just after the samples, you can check out just the [chapter summaries](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/summaries/)

* [**Prebuilt Applications**](http://xamarin.com/prebuilt) - Full applications for you to look at and pull apart to investigate techniques and structure.

* [**Xamarin Samples**](http://developer.xamarin.com/samples-all) All the samples listed out by technologies and platform

### Media
* [**The Xamarin Podcast**](http://soundcloud.com/Xamarin-podcast) - The home of the official Xamarin Podcast, bringing mobile developers the latest news and information about Xamarin and mobile development.

* [**The Xamarin Show**](https://channel9.msdn.com/Shows/XamarinShow) - James Montemagno's Channel 9 Show. If video content is your thing, this is a great Options

* [**Xamarin on Youtube**](https://www.youtube.com/user/XamarinVideos) - All the Xamarin videos from Evolve conferences, webinars, and case studies, in one giant youtube feed.

* [**Merge Conflict Podcast**](http://www.mergeconflict.fm/) - James Montemagno and Frank Krueger's weekly discussion on all things development, technology, & more. Mostly focused on Xamarin.

* [**Gone Mobile Podcast**](http://gonemobile.io/) - Gone Mobile is a podcast discussing the latest in mobile development, with a healthy bias towards Xamarin technologies.

### Community

* [**Planet Xamarin**](https://planetxamarin.com) - An aggregator of content from Xamarin Community members. All the content generated by the community members in your news reader

* [**Xamarin Chat - Slack Community**](http://xamarinchat.herokuapp.com) - Great slack channel to talk with other Xamarin developers, lots of MVPs, Xamarin employees congregate here.

* [**Weekly Xamarin Newsletter**](http://weeklyxamarin.com/) - Subscribe to a hand-picked round up of the best Xamarin development links every week. Curated by Geoffrey Huntley and published every Friday.

* [**StackOverflow**](http://www.stackoverflow.com) - Xamarin does a lot of support through StackOverflow.

### User Groups
* [**Sydney Xamarin User Group**](https://www.meetup.com/SydneyMobileDotNetDevelopers/)

* [**Melbourne Xamarin User Group**](https://www.meetup.com/Melbourne-Xamarin-Meetup/)

* [**Brisbane Xamarin User Group**](https://www.meetup.com/Queensland-based-MonoTouch-and-Mono-for-Android/)

* [**Perth Xamarin User Group**](https://www.meetup.com/Perth-Mobile-NET-Xamarin-Developers/)

* [**Xamarin User Groups**](http://www.meetup.com/topics/xamarin/) - All the meetups around the world.

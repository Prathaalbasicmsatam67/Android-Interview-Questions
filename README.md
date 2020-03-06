# Android-Interview-Questions

# Articles :
“Not another Interviews’ article: Android & Java Questions” by Pedro Vicente https://link.medium.com/6aBiFWcRB4

# Questions List


Java, OOPs, Concurrency

Difference between StringBuffer, StringBuilder and String.concat? \n
What is the difference between using == and equals on a string?
What does the static word mean in Java?
When is a static block run?
Can we use static and abstract together? 
What are these final, finally and finalize?
What is the difference between an Integer and int?
Differences between abstract classes and interfaces?
Can you reduce scope of overridden method? 
What is telescoping constructors?
What is name mangling? 
What is Marker and Functional Interface? 
What is covariant return type? 
How to create immutable class?
Difference between deep and shallow copy? 
What is anonymous classes?
GC process
What are access modifiers in Java?
What the difference between local, instance and class variables?
Is it possible to access private member of Java class?
What are transient and volatile modifiers?
Generics in Java
Is Java pass by value or pass by reference?
Difference between Abstraction and Encapsulation, support with an example
What is static and dynamic dependency injection? 
What are Exceptions in Java? Difference between Checked and Unchecked Exceptions
What is a ThreadPoolExecutor? Can this ever cause a memory leak? If yes, how can you prevent it?
What are the concurrent atomic classes in Java? What are their advantages?
Difference between method overloading and overriding
What's better: Composition or Inheritance and why?
What is String pooling? What's its impact on GC?
What are anonymous inner classes in Java? How are they useful? Do they have any negative implications on the Memory? What is Java 8 Lambdas? 
How to implement multiple inheritance using interface vs composition? 
What is JNI, How it works?
What is Kotlin? Is it faster than Java?
How interface is different in Java 1.8?

Collection, Data Structures, Algorithms

Collections framework
Difference between List, Set, Queue, Deque, Array, Stack, Map
When to use ArrayList vs LinkedList?
When to use HashTable vs HashMap vs TreeMap vs LinkedHashMap?
How HashMap works in Java? Contract between hashcode and equals
What are fail-safe & fail-fast Iterators in Java?
What’s the difference between an Enumeration and an Iterator?
How to implement Arraylist using Array?
Which's better: HashMap, ArrayMap vs SparseArray types and why?
Difference between PriorityQueue vs BlockingQueue, When to use them?
What is Binary Search Tree? 
What is Space and Time Complexity of Bubble Sort? 

Android

Android architecture
What are main components of Android?
Purpose of AndroidManifest file
Activity lifecycle, difference between onPause and onStop
Activity Launch Modes
Difference between RecyclerView and ListView?
Why to use Fragment?
Lifecycle of a Fragment 
Difference between FragmentPagerAdapter and FragmentStatePagerAdapter?
Is it possible to have Activity without UI?
Is it possible to have Fragment without UI?
Which Lifecycle methods are guaranteed to be called in case of app crash?
When to use Services, Started vs Bound service and IntentService?
Android notification system 
Sticky Intent and Silent Notifications
What is Serializable and why Android uses Parcelable?
Difference between Implicit and Explicit Intent
What is the function of an intent-filter?
What is Deep Linking? How does it work?
What can be used for background processing in Android?
How to communicate between background thread and main thread?
Difference between AsyncTask and Thread, What is AbstractThreadedSyncAdapter? 
What is a JobScheduler? 
What are different ways to store data in Android? What is Direct Boot? 
How to securely store tokens, certificates in Android? 
Difference between SOAP and REST
What is better JSON or XML? 
Different HTTP verbs - GET POST PUT PATCH
Authentication mechanisms - Basic Auth, Digest Auth, OAuth 1.0, 2.x
Security token formats - SAML, JWT
How to secure network connections - HTTP, Socket? 
What is SSL pinning? How to overcome man-in-middle attack?
What is Doze mode? How to optimize battery utilization? 
How to optimize application for Mobile Network? Why WiFi are more battery efficient over 3G/4G? 
How often Sqlite database should be closed inside app? 
How can we optimize Sqlite queries?
Can we create column with Date-time or Date type in Sqlite? 
What are content providers? Are they thread-safe? How to create your own content providers? 
Is ContentProvider a security breach considering android apps are sandboxed?
What is the use of android:protectionLevel in <permission> tag in manifest?
Why Support Library was introduced in Android?
What is Android Data Binding? 
How to prevent ANR? What the max time for which you can block the UI thread?
How does third party image loading libraries work?
What are different ways to store data in your Android app?
What is the DVM and ART? Why DVM over JVM?
What is a Sticky Intent?
What is a PendingIntent?
What is AIDL? Enumerate the steps in creating a bounded service through AIDL?
How would you preserve Activity state, handle AsyncTasks during a screen rotation? 
What is apk file? How to reduce size of apk? 
How to find memory leaks in Android applications?
How android supports multiple resolutions, form factors, orientations?
How to make sure that your application is compatible with older versions of android?
What are third party ORM and why to use them?
What is a Loader?
What is the StrictMode? 
What is Lint? What is it used for?
What is the difference between ListView and RecyclerView?
What is the ViewHolder pattern? Why should we use it?
What is the best way to update the screen periodically?
Have you developed widgets? Describe process 
What is Context in Android? Difference between Activity context and Application context
What is style and theme? What is a Spannable?
What’s Looper, Handler and HandlerThread?
Do you know how to profile layout with Hierarchy Viewer?
Which is fastest layout in Android?
How RelativeLayout, LinearLayout, FrameLayout works? 
What’s the purpose of ConstraintLayout?
How to create custom attributes and use them in layout files?
How to create Custom views?
Different rendering options - Canvas, OpenGL, RenderScript 
Property vs View (Tween, Frame) Animations 
What is Flat vs Material Design? Different Material Design Components
What is FAB? How do you specify the gravity for FAB? 
What is Material Motion? 
Difference between ViewGroup vs View
What is 9-patch image? How to create one? 
How Push Notification works?
How to create a keystore in android?
Runtime Permissions
Different Android command line tools - DDMS, ADB, AAPT
Architecture Design associated with popular apps like Uber, Ola, Facebook, Whatsapp, Snapchat, Instagram
What is I18N vs L10N? How to support multiple languages in Android? 
What is significance of res (Resources) folder? 
Steps to add support for additional language e.g., spanish in your app. 
What’s gradle and how it works? Command lines for creating builds.
Purpose of Proguard
Difference between Callable and Runnable
How to create production build? What is build variant (product flavors and build types)?
How to upload build on app store? What is Staged Rollouts? 
What is Alpha/Beta test release? What is Open and Closed Beta? 

Design Principles, Patterns

SOLID, GRASP, WET, DRY, KISS, YAGNI
Singleton Pattern, What is double-checked locking?
What are Creational, Structural and Behavioral Design Patterns? 
Difference between Builder Pattern and Factory Pattern?
When to use Factory vs Abstract Factory Pattern?
Difference between Adapter Pattern and Bridge Pattern?
Observer pattern, What is Observer - Observable? 
Difference between Strategy Pattern and State Pattern?

Architecture

What’s MVP and Why MVP?
Can we write business logic in Model?
What is Clean Architecture?
Difference between MVC, MVP and MVVM?
Android Architecture Components, what is ViewModel and LiveData? 
What is Microservices Architecture? 

Third Party Frameworks

How to create library project? How to manage dependencies? 
Will use of third party libraries impact compile time? size of application, application performance? 
Usage, Pros and Cons of following libraries and frameworks 
- Data Parsing
• JSON - JSON, GSON, Jackson, Moshi
• XML, SOAP, KSOAP - DOM, SAX, StAX, XML Pull Parser
- Image loading - Picasso, Universal Image Loader, Glide, Fresco
- Networking - Retrofit, Volley, OkHttp
- Event Driven Programming - Otto, greenrobot-EventBus
- Injection - Dagger 2, ButterKnife
- Database - - SQLite, Realm, Couchbase Mobile
- ORM - OrmLite, greenDAO, ActiveAndroid, SugarORM, DBFlow
- Custom Views - ActionBarSherlock, SlidingMenu, NineOldAndroids, Rebound, MPAndroidChart, AndroidViewAnimations
- Crash Monitoring - Fabric Crashlytics, BugSense, Crittercism, Apphance
- Analytics and Marketing platform - Google Analytics, Mixpanel, Firebase, Appsee, Leanplum, Localytics, Flurry, Amplitude, Adobe Analytics, Countly, Marketo, branch.io, Optimizely 
- MBaaS - Firebase, CloudKit, Kinvey, AWS Mobile
- CI-CD - Fastlane, Jenkins, Bamboo, Travis-CI, Circle-CI
- Social Integration - Facebook, Twitter, Linkedin, Google plus
- AR/VR, Gaming - Vuforia, Unity, Cocos2d-x, AndEngine
- Others - RxJava, RxAndroid, Joda-time, Guava, ZXing, Abby, LeakCanary, Timber, ExoPlayer, Urban Airship, Fabric Beta

Testing

What’s TDD and BDD?
Unit test, What’s the significance of unit, integration testing?
Instrumented Unit Tests?
What is Espresso?
What is UI-Automator?
What is Robotium, Robolectric?
What is Mockito and Why Mockito is used?
How to calculate Test Coverage? 

SDLC, Agile

What are different SDLC? Waterfall, Iterative, Agile, Lean (Scrum, Kanban, XP)? 
How Agile Methodologies can really help your project?
How to follow agile and plan your sprints?
What is Scrum in Agile?
What is Epic, User Story, Task?
What is Sprint? How to calculate Story Points, Sprint Velocity?
What is Product, Sprint Backlog?
What is acceptance criteria and definition of done?
What is daily scrum meeting? How is it conducted? 
Role of Scrum Master, Product Owner and Scrum Team
What are different Sprint Ceremonies - Kick-off, Planning, Daily, Demo, Review, Retrospective?
What are Sprint Burndown, Burnup charts?

Source Version Control

Difference between Git vs SVN
What is Git fork? What is difference between fork and branch? How to create tag? 
What is git cherry-pick? 
How to revert previous commit in git? 
How to rebase master in git? Difference between rebase and merge. How to squash or fixup commits? 
git stash, pop
Branching strategies - Feature, Release branching, Git flow, Lean Git flow


Android Architecture Components samples
===================================

A collection of samples using the [Architecture Components](https://developer.android.com/arch):

- **Room** --> A Persistence Library provides an abstraction layer over SQLite with Compile-time Error Checking
- **Lifecycle-aware components** -->Lifecycle-aware components perform actions in response to a change in the lifecycle status of another component
- **ViewModels** --> Designed to store and manage UI-related data in a lifecycle conscious way. This class allows data to survive configuration changes 
- **LiveData** --> An observable data holder class
- **Paging (preview)** --> The Paging Library helps you display data in your UI's list containers smoothly
- **WorkManager (alpha)** -->  This class makes easy to specify deferrable, asynchronous tasks and when they should run.

### Samples

* **[BasicSample](https://github.com/googlesamples/android-architecture-components/blob/master/BasicSample)** - Shows how to persist data using a SQLite database and Room. Also uses ViewModels and LiveData.

* **[PersistenceContentProviderSample](https://github.com/googlesamples/android-architecture-components/blob/master/PersistenceContentProviderSample)** - Shows how to expose data via a Content Provider using Room.

* **[GithubBrowserSample](https://github.com/googlesamples/android-architecture-components/blob/master/GithubBrowserSample)** - An **advanced**  sample that uses the Architecture components, Dagger and the Github API. Requires Android Studio 3.0 or later.

* **[BasicRxJavaSample](https://github.com/googlesamples/android-architecture-components/blob/master/BasicRxJavaSample)** - Shows how to use Room with RxJava 2. Also uses ViewModels.

* **[PersistenceMigrationsSample](https://github.com/googlesamples/android-architecture-components/blob/master/PersistenceMigrationsSample)** - Shows how to implement migrations in Room.

* **[BasicRxJavaKotlinSample](https://github.com/googlesamples/android-architecture-components/blob/master/BasicRxJavaSampleKotlin)** - Shows
how to use ViewModels and Room together with RxJava, in Kotlin.

 * **[PagingSample](https://github.com/googlesamples/android-architecture-components/tree/master/PagingSample)** - Shows
  how to use the Paging library with Room, in Kotlin.

 * **[PagingNetworkSample](https://github.com/googlesamples/android-architecture-components/tree/master/PagingWithNetworkSample)** - Shows
  how to use the Paging library with a backend API via Retrofit, in Kotlin.

* **[WorkManagerSample](https://github.com/googlesamples/android-architecture-components/tree/master/WorkManagerSample)** - Shows
  how to use WorkManager (alpha) to do background work, in Java.

### Other Architecture Components Samples

* **[Architecture Blueprints - todo-mvvm-live](https://github.com/googlesamples/android-architecture/tree/dev-todo-mvvm-live)** - Variant of the to-do app that uses ViewModels, LiveData and Data Binding with an MVVM architecture.
* **[Architecture Blueprints - todo-mvp](https://github.com/googlesamples/android-architecture/tree/todo-mvp)** - Variant of the to-do app that uses Room as a local data source with an MVP architecture.


### Reporting Issues

You can report an [Issue](https://github.com/googlesamples/android-architecture-components/issues) on the samples using this repository. If you find an issue with the Architecture Components, report it using the [Architecture Components Issue Tracker](https://issuetracker.google.com/issues/new?component=197448&template=878802)

License
-------

Copyright 2018 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

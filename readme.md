
# 🎨 Awesome .Net Async [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)


Collection of useful articles and resources to learning and practicing about async, threading, and channels in .Net platform. this repository will be updated continuously, keep yourself up to date 😉

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-dotnet-async/blob/master/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-dotnet-async/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

Check out my [blog](https://dotnetuniversity.com) or find me on [Linkedin](https://www.linkedin.com/in/mehdihadeli/) or [Twitter](https://twitter.com/mehdi_hadeli)!

## Contents
- [Async-Await](#async-await)
- [ValueTask](valuetask)
- [Configure Await](#configure-await)
- [Exception Handling](#exception-handling)
- [Thread Pool](#thread-pool)
- [Thread](#thread)
- [Async Stream And IEnumerableAsync](#async-stream-and-iEnumerableAsync)
- [Iterators](#Iterators)
- [Channels](#Channels)
- [Libraries](#Libraries)
- [Code Analyzers](#Code-Analyzers)

## Async-Await

### Articles
- [Async Overview](https://docs.microsoft.com/en-us/dotnet/standard/async)
- [Async in depth](https://docs.microsoft.com/en-us/dotnet/standard/async-in-depth)
- [Asynchronous programming patterns](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/)
- [Task-based asynchronous pattern - TAP](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/task-based-asynchronous-pattern-tap)
- [Event-based Asynchronous Pattern - EAP](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/event-based-asynchronous-pattern-overview)
- [Asynchronous Programming Model - APM](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/asynchronous-programming-model-apm)
- [Task asynchronous programming model](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/task-asynchronous-programming-model)
- [Async return types (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/async-return-types)
- [When to Use Async and Await and How it Works](https://hamidmosalla.com/2018/03/30/when-to-use-async-and-await-and-how-it-works/)


## Cancellation

### Articles

- [Task cancellation in C# and things you should know about it](https://binary-studio.com/2015/10/23/task-cancellation-in-c-and-things-you-should-know-about-it)
- [Cancel asynchronous operation in csharp](https://johnthiriet.com/cancel-asynchronous-operation-in-csharp/)
- [Aborting Thread Vs Cancelling Task](https://www.c-sharpcorner.com/article/aborting-thread-vs-cancelling-task/)
- [Task cancellation](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/task-cancellation)
- [Cancellation in Managed Threads](https://docs.microsoft.com/en-us/dotnet/standard/threading/cancellation-in-managed-threads)
- [Destroying threads](https://docs.microsoft.com/en-us/dotnet/standard/threading/destroying-threads)
- [How to: Cancel a Task and Its Children](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/how-to-cancel-a-task-and-its-children)
- [Using CancellationTokens in ASP.NET Core MVC controllers](https://andrewlock.net/using-cancellationtokens-in-asp-net-core-mvc-controllers/)

### Samples

- [https://github.com/johnthiriet/AsyncTips](https://github.com/johnthiriet/AsyncTips)


## I/O-Bound

### Articles

- [Deeper Dive into Tasks for an I/O-Bound Operation](http://docs.microsoft.com/en-us/dotnet/standard/async-in-depth#deeper-dive-into-tasks-for-an-io-bound-operation)
- [I/O-bound tasks](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/implementing-the-task-based-asynchronous-pattern#io-bound-tasks)
- [Why you shouldn’t create asynchronous wrappers with Task.Run()](https://www.ben-morris.com/why-you-shouldnt-create-asynchronous-wrappers-with-task-run/)
- [Asynchronous file access (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/using-async-for-file-access)
- [C# : TASK PARALLEL LIBRARY (TPL) WITH ASYNC AWAIT AND TASKCOMPLETIONSOURCE FOR ASYNC I/O OPERATIONS](https://www.techblogcity.com/2019/06/05/task-parallel-library-with-async-await-and-taskcompletionsource/)
- [There Is No Thread](https://blog.stephencleary.com/2013/11/there-is-no-thread.html)
- [Wrapping Other Asynchronous Patterns in Awaitable Tasks](https://www.damirscorner.com/blog/posts/20130722-WrappingOtherAsynchronousPatternsInAwaitableTasks.html)
- [Task.Factory.StartNew vs Task.Factory.FromAsync](https://stackoverflow.com/questions/17432306/task-factory-startnew-vs-task-factory-fromasync)


## Cpu-Bound

### Articles

- [Deeper Dive into Task and Task<T> for a CPU-Bound Operation](https://docs.microsoft.com/en-us/dotnet/standard/async-in-depth#deeper-dive-into-task-and-taskt-for-a-cpu-bound-operation)
- [Compute-bound tasks](https://docs.microsoft.com/en-us/dotnet/standard/asynchronous-programming-patterns/implementing-the-task-based-asynchronous-pattern#compute-bound-tasks)
- [Task.Run Etiquette and Proper Usage](https://blog.stephencleary.com/2013/10/taskrun-etiquette-and-proper-usage.html)
- [Should I expose asynchronous wrappers for synchronous methods?](https://devblogs.microsoft.com/pfxteam/should-i-expose-asynchronous-wrappers-for-synchronous-methods/)
- [Task.Run Vs TaskCompletionSource Vs Task.Factory.FromAsync](https://hamidmosalla.com/2018/05/27/task-run-vs-taskcompletionsource-vs-task-factory-fromasync/)


## TaskCompletionSource

### Articles

- [Should I expose asynchronous wrappers for synchronous methods?](https://devblogs.microsoft.com/pfxteam/should-i-expose-asynchronous-wrappers-for-synchronous-methods/)
- [Using TaskCompletionSource to change the semantics of async calls](http://vannevel.net/posts/using-taskcompletionsource-to-change-the-semantics-of-async-calls/)
- [TaskCompletionSource in real life (part 1 of 2)](https://www.fmork.net/software/writing/2012/TaskCompletionSource-in-real-life-(part-1-of-2).htm)
- [TaskCompletionSource in real life (part 2 of 2)](https://www.fmork.net/software/writing/2012/TaskCompletionSource-in-real-life-(part-2-of-2).htm)
- [C# : TASK PARALLEL LIBRARY (TPL) WITH ASYNC AWAIT AND TASKCOMPLETIONSOURCE FOR ASYNC I/O OPERATIONS](https://www.techblogcity.com/2019/06/05/task-parallel-library-with-async-await-and-taskcompletionsource/)
- [Task.Run Vs TaskCompletionSource Vs Task.Factory.FromAsync](https://hamidmosalla.com/2018/05/27/task-run-vs-taskcompletionsource-vs-task-factory-fromasync/)
- [The Nature of TaskCompletionSource](https://devblogs.microsoft.com/pfxteam/the-nature-of-taskcompletionsourcetresult/)
- [When should TaskCompletionSource<T> be used?](https://stackoverflow.com/questions/15316613/when-should-taskcompletionsourcet-be-used)
- [Instance of Task class (Task.Factory.StartNew or TaskCompletionSource)](https://stackoverflow.com/questions/5674895/instance-of-task-class-task-factory-startnew-or-taskcompletionsource)
- [Wrapping Other Asynchronous Patterns in Awaitable Tasks](https://www.damirscorner.com/blog/posts/20130722-WrappingOtherAsynchronousPatternsInAwaitableTasks.html)


## ValueTask

### Articles

- [ValueTask Restrictions - Stephen Cleary](https://blog.stephencleary.com/2020/03/valuetask.html)

- [How to use ValueTask in C#](https://morioh.com/p/da3a36ccbe3b)

- [Task, Async Await, ValueTask, IValueTaskSource and how to keep your sanity in modern .NET world](https://blog.scooletz.com/2018/05/14/task-async-await-valuetask-ivaluetasksource-and-how-to-keep-your-sanity-in-modern-net-world/)

- [.NET 5 and pooling for ValueTasks - Scooletz](https://blog.scooletz.com/2020/06/01/pooling-for-value-tasks-in-net5)

### Videos

- [Understanding how to use Task and ValueTask](https://www.youtube.com/watch?v=fj-LVS8hqIE)


## Configure Await

### Articles

- [ConfigureAwait FAQ - Stephen Toub](https://devblogs.microsoft.com/dotnet/configureawait-faq/)


## Exception Handling

### Articles

- [Exception Handling In Asynchronous Code](https://hamidmosalla.com/2018/06/24/what-is-synchronizationcontext/)
- [Exception Handling in C# Asynchronous Programming](https://www.c-sharpcorner.com/UploadFile/dacca2/asynchronous-programming-in-C-Sharp-5-0-part-4-exception-handlin/)
- [Exception handling (Task Parallel Library)](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/exception-handling-task-parallel-library)

## SynchronizationContext

## Articles

- [What Is SynchronizationContext](https://hamidmosalla.com/2018/06/24/what-is-synchronizationcontext/)



## Awaiter

### Articles

- [A Tour of Task, Part 6: Results](https://blog.stephencleary.com/2014/12/a-tour-of-task-part-6-results.html)
- [Task.Wait() Vs Task.GetAwaiter().GetResult()](https://jaliyaudagedara.blogspot.com/2019/06/taskwait-vs-taskgetawaitergetresult.html)
- [Avoid GetAwaiter().GetResult() at all cost](https://gsferreira.com/archive/2020/08/avoid-getawaiter-getresult-at-all-cost/)
- [Understanding C# async / await (2) The Awaitable-Awaiter Pattern](https://weblogs.asp.net/dixin/understanding-c-sharp-async-await-2-awaitable-awaiter-pattern)



## Continuations

### Articles

- [A Tour of Task, Part 7: Continuations](https://blog.stephencleary.com/2015/01/a-tour-of-task-part-7-continuations.html)
- [Chaining tasks using continuation tasks](https://docs.microsoft.com/en-us/dotnet/standard/parallel-programming/chaining-tasks-by-using-continuation-tasks)


## Thread Pool



## Thread



## Async Tips

### Articles

- [Top 7 Common Async Mistakes](https://hamidmosalla.com/2018/04/21/top-7-common-async-mistakes/)
- [Async/Await - Best Practices in Asynchronous Programming](https://docs.microsoft.com/en-us/archive/msdn-magazine/2013/march/async-await-best-practices-in-asynchronous-programming)



## Concurrency Vs Parallelism

### Articles

- [Concurrency Vs Parallelism](https://hamidmosalla.com/2018/03/16/concurrency-vs-parallelism/)



## Async Local

### Articles
- [AsyncLocal<T> in .NET 4.6](https://www.tabsoverspaces.com/233526-asynclocal-t-in-net-46)
- [Implicit Async Context ("AsyncLocal")](https://blog.stephencleary.com/2013/04/implicit-async-context-asynclocal.html)
- [Multithreaded shared variables and AsyncLocal](https://programmer.help/blogs/multithreaded-shared-variables-and-asynclocal.html)



## Thread Safey

### Articles

- [Thread Safety](https://hamidmosalla.com/2018/07/09/thread-safety/)



## Asynchronous Messaging

### Articles

- [Asynchronous Messaging, Part 1: Basic Distributed Architecture](https://blog.stephencleary.com/2021/01/asynchronous-messaging-1-basic-distributed-architecture.html)
- [Asynchronous Messaging, Part 2: Durable Queues](https://blog.stephencleary.com/2021/01/asynchronous-messaging-2-durable-queues.html)
- [Asynchronous Messaging, Part 3: Backend Service](https://blog.stephencleary.com/2021/01/asynchronous-messaging-3-backend-processor.html)



## Async Collections

### BlockingCollection 

#### Articles

- [BlockingCollection Overview](https://docs.microsoft.com/en-us/dotnet/standard/collections/thread-safe/blockingcollection-overview) 
- [Event-driven .NET: Concurrent Producer/Consumer using BlockingCollection](https://makolyte.com/event-driven-dotnet-concurrent-producer-consumer-using-blockingcollection/)
- [An introduction to BlockingCollection](https://weblogs.asp.net/morteza/an-introduction-to-blockingcollection)



## Async Stream And IEnumerableAsync

### Articles

- [Use streaming in ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr/streaming?view=aspnetcore-5.0)

- [Async Streams](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/proposals/csharp-8.0/async-streams)

- [Iterating with Async Enumerables in C# 8](https://docs.microsoft.com/en-us/archive/msdn-magazine/2019/november/csharp-iterating-with-async-enumerables-in-csharp-8)

- [Async Streams with IAsyncEnumerable in .NET Core 3](https://anthonychu.ca/post/async-streams-dotnet-core-3-iasyncenumerable/)

- [IAsyncEnumerable Is Your Friend, Even In .NET Core 2.x](https://btburnett.com/csharp/2019/12/01/iasyncenumerable-is-your-friend.html)

- [Asynchronous streams in C# 8.0](https://blog.miguelbernard.com/asynchronous-streams)



## Iterators

### Articles

- [Iterators](https://bettersolutions.com/csharp/collections/iterators.htm)

- [Iterators (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/iterators)

- [yield (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/yield)

- [Iterators, iterator blocks and data pipelines](https://csharpindepth.com/articles/StreamingAndIterators)

- [IEnumerator Interface](https://docs.microsoft.com/en-us/dotnet/api/system.collections.ienumerator?view=net-5.0)

- [IEnumerable<T> Interface](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1?view=net-5.0)



## Channels

### Videos

- [C# Channels Explained (System.Threading.Channels)](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=E0Ld7ZgE4oY)

- [Working with Channels in .NET](https://channel9.msdn.com/Shows/On-NET/Working-with-Channels-in-NET)

### Articles

- [An Introduction to System.Threading.Channels - Stephen Toub](https://devblogs.microsoft.com/dotnet/an-introduction-to-system-threading-channels/)

- [Using Channels In C# .NET Core – Part 1 – Getting Started](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-1-getting-started/)

- [Using Channels In C# .NET Core – Part 2 – Advanced Channels](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-2-advanced-channels/)

- [Using Channels In C# .NET Core – Part 3 – Understanding Back Pressure](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-3-understanding-back-pressure/)

- [AN INTRODUCTION TO SYSTEM.THREADING.CHANNELS](https://www.stevejgordon.co.uk/an-introduction-to-system-threading-channels)

- [Producer/consumer pipelines with System.Threading.Channels](https://blog.maartenballiauw.be/post/2020/08/26/producer-consumer-pipelines-with-system-threading-channels.html)

- [C# Channels - Publish / Subscribe Workflows](https://deniskyashif.com/2019/12/08/csharp-channels-part-1/)

- [C# Channels - Timeout and Cancellation](https://deniskyashif.com/2019/12/11/csharp-channels-part-2/)

- [C# Channels - Async Data Pipelines](https://deniskyashif.com/2020/01/07/csharp-channels-part-3/)

- [How to implement Producer/Consumer with System.Threading.Channels](https://www.davideguida.com/how-to-implement-producer-consumer-with-system-threading-channels/)

- [How to implement Producer/Consumer with System.Threading.Channels](https://www.davideguida.com/consuming-message-queues-using-net-core-background-workers-part-4-adding-system-threading-channels/)

### Samples

- [https://github.com/deniskyashif/trydotnet-channels](https://github.com/deniskyashif/trydotnet-channels)



## Libraries
- [Nito.AsyncEx](https://www.nuget.org/packages/Nito.AsyncEx/)
  > A helper library for the Task-Based Asynchronous Pattern (TAP). ([Github Repo](https://github.com/StephenCleary/AsyncEx) - [Wiki](https://github.com/StephenCleary/AsyncEx/wiki))

- [Microsoft.VisualStudio.Threading](https://www.nuget.org/packages/Microsoft.VisualStudio.Threading/)
  > Async synchronization primitives, async collections, TPL and dataflow extensions. The JoinableTaskFactory allows synchronously blocking the UI thread for async work. ([Github Repo](https://github.com/microsoft/vs-threading))

- [AsyncEnumerator](https://www.nuget.org/packages/AsyncEnumerator/)
  > Introduces `IAsyncEnumerable`, `IAsyncEnumerator`, `ForEachAsync()`, and `ParallelForEachAsync()` and other useful stuff to use with async-await ([Github Repo](https://github.com/Dasync/AsyncEnumerable))

- [AsyncIO.DotNet](https://www.nuget.org/packages/AsyncIO.DotNet/)
  > Easy-to-use library for common async IO file system operations. ([Github Repo](https://github.com/firenero/AsyncIO))

- [NeoSmart.AsyncLock](https://www.nuget.org/packages/NeoSmart.AsyncLock/)
  > A C# lock replacement for async/await, supporting recursion/re-entrance and asynchronous waits. ([Github Repo](https://github.com/neosmart/AsyncLock))



## Code Analyzers

- [Microsoft.VisualStudio.Threading.Analyzers](https://www.nuget.org/packages/Microsoft.VisualStudio.Threading.Analyzers/)
  > Static code analyzer to detect common mistakes or potential issues regarding threading and async coding. ([Github Repo](https://github.com/microsoft/vs-threading))

- [AsyncFixer](https://www.nuget.org/packages/AsyncFixer/)
  > AsyncFixer helps developers in finding and correcting common async/await misuses (i.e., anti-patterns). ([Github Repo](https://github.com/semihokur/AsyncFixer))

- [ConfigureAwaitChecker.Analyzer](https://www.nuget.org/packages/ConfigureAwaitChecker.Analyzer/)
  > Checks for `ConfigureAwait(false)` usage. ([Github Repo](https://github.com/cincuranet/ConfigureAwaitChecker))

- [Lindhart.Analyser.MissingAwaitWarning](https://www.nuget.org/packages/Lindhart.Analyser.MissingAwaitWarning/)
  > Compiler analyser to generate Warnings whenever a Task is not awaited nor assigned to a variable. ([Github Repo](https://github.com/ykoksen/unused-task-warning))


  
 
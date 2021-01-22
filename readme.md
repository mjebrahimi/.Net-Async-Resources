
# .Net Async Resources
[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

Useful resources about async, threading, and channel in .Net platform. this repository will be updated continuously, keep yourself up to date 😉

# Contribution

Contributions are always welcome! Thanks to all contributors, you're awesome and wouldn't be possible without you! The goal is to build a categorized collection of very well-known resources.

# Table of Contents

- [.Net Async Resources](#.net-async-resources)
  - [Async & Await](#async-&-await)
    - [Links](#links)
  - [Configure Await](#configure-await)
    - [Links](#links)
  - [Thread Pool](#thread-pool)
    - [Links](#links)
  - [Thread](#thread)
    - [Links](#links)
  - [Async Stream & IEnumerableAsync](#async-stream-&-iEnumerableAsync)
    - [Links](#links)  
  - [Iterators](#Iterators)
    - [Links](#links)
  - [Channels](#Channels)
    - [Links](#links)
	- [Videos](#Videos)
  - [Libraries](#Libraries)
  - [Code Analyzers](#Code-Analyzers)

## Async & Await

### Links

[Task asynchronous programming model](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/task-asynchronous-programming-model)

[Async return types (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/async/async-return-types)


## Configure Await

### Links

[ConfigureAwait FAQ - Stephen Toub](https://devblogs.microsoft.com/dotnet/configureawait-faq/)


## Thread Pool


## Thread


## Async Stream & IEnumerableAsync

### Links
[Use streaming in ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr/streaming?view=aspnetcore-5.0)

[Async Streams](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/proposals/csharp-8.0/async-streams)

[Iterating with Async Enumerables in C# 8](https://docs.microsoft.com/en-us/archive/msdn-magazine/2019/november/csharp-iterating-with-async-enumerables-in-csharp-8)

[Async Streams with IAsyncEnumerable in .NET Core 3](https://anthonychu.ca/post/async-streams-dotnet-core-3-iasyncenumerable/)

[IAsyncEnumerable Is Your Friend, Even In .NET Core 2.x](https://btburnett.com/csharp/2019/12/01/iasyncenumerable-is-your-friend.html)

[Asynchronous streams in C# 8.0](https://blog.miguelbernard.com/asynchronous-streams)


## Iterators

### Links

[Iterators](https://bettersolutions.com/csharp/collections/iterators.htm)

[Iterators (C#)](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/iterators)

[yield (C# Reference)](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/yield)

[Iterators, iterator blocks and data pipelines](https://csharpindepth.com/articles/StreamingAndIterators)

[IEnumerator Interface](https://docs.microsoft.com/en-us/dotnet/api/system.collections.ienumerator?view=net-5.0)

[IEnumerable<T> Interface](https://docs.microsoft.com/en-us/dotnet/api/system.collections.generic.ienumerable-1?view=net-5.0)


## Channels

### Videos

[C# Channels Explained (System.Threading.Channels)](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=E0Ld7ZgE4oY)

[Working with Channels in .NET](https://channel9.msdn.com/Shows/On-NET/Working-with-Channels-in-NET)

### Links

[An Introduction to System.Threading.Channels - Stephen Toub](https://devblogs.microsoft.com/dotnet/an-introduction-to-system-threading-channels/)

[Using Channels In C# .NET Core – Part 1 – Getting Started](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-1-getting-started/)

[Using Channels In C# .NET Core – Part 2 – Advanced Channels](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-2-advanced-channels/)

[Using Channels In C# .NET Core – Part 3 – Understanding Back Pressure](https://dotnetcoretutorials.com/2020/11/24/using-channels-in-net-core-part-3-understanding-back-pressure/)

[AN INTRODUCTION TO SYSTEM.THREADING.CHANNELS](https://www.stevejgordon.co.uk/an-introduction-to-system-threading-channels)

[Producer/consumer pipelines with System.Threading.Channels](https://blog.maartenballiauw.be/post/2020/08/26/producer-consumer-pipelines-with-system-threading-channels.html)

[C# Channels - Publish / Subscribe Workflows](https://deniskyashif.com/2019/12/08/csharp-channels-part-1/)

[C# Channels - Timeout and Cancellation](https://deniskyashif.com/2019/12/11/csharp-channels-part-2/)

[C# Channels - Async Data Pipelines](https://deniskyashif.com/2020/01/07/csharp-channels-part-3/)

[How to implement Producer/Consumer with System.Threading.Channels](https://www.davideguida.com/how-to-implement-producer-consumer-with-system-threading-channels/)

[How to implement Producer/Consumer with System.Threading.Channels](https://www.davideguida.com/consuming-message-queues-using-net-core-background-workers-part-4-adding-system-threading-channels/)

### Samples

[https://github.com/deniskyashif/trydotnet-channels](https://github.com/deniskyashif/trydotnet-channels)

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

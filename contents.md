第一章

本章主要介绍Go中并发的基本概念，包括goroutines和channels，对比Go和其他语言处理并发的差异。我们会构建一些简单的程序来理清这些概念。

第二章

理解并发模型，关注资源创建、内存共享和数据。我们将研究channes和channels的channels并解释Go在内部是怎样管理并发的。

第三章

开发一个并发策略，详细的展示怎样最好的使用Go的并发工具，在策略中我们也会使用一些有帮助的第三方库。

第四章

应用中数据的完整性，观察在单线程和多线程中goroutines和channels怎样维持状态。

第五章

锁、阻塞和更好的channels，分析Go怎样避免死锁，以及在不管Go怎样设计，在哪些情况下仍然容易发生。

第六章

C10K问题，用Go编写的一个无阻塞的web服务器，应付互联网史上最著名也最有挑战行的问题。然后我们让程序设计的更加优雅，并用压力测试工具进行测试。

第七章

性能和稳定性，关注调用最频繁的Go代码，最好的利用资源，尽量的减少第三方库对你的性能影响，我们会在web服务器上加入一些函数，并讨论使用这些库的其他方式。

第八章

并发程序的架构，关注实现并发模型的最佳场景，关注最好的利用硬件优势进行并行计算的场景，并确保数据的一致性。

第九章

测试并发并和日志记录，关注不同系统的测试函数并部署你的应用。我们也会观察Go与代码仓库之间的关系。

第十章

并发的优势和最佳实践，研究更复杂的场景和高级的技术。
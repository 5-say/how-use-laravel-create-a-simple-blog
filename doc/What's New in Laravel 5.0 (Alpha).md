# What's New in Laravel 5.0 (Alpha)

[课程地址 >>>](https://laracasts.com/series/whats-new-in-laravel-5)

> Each new release of Laravel feels like a mini-Christmas, and version 5 is no different! Though some of these changes might seem jolting at first, don't worry; give me a few minutes, and I'll explain everything you need to know. Get ready!

> Laravel 的每个新版本感觉就像一个迷你的圣诞节，而版本 5 依然如此！虽然其中的一些变化似乎在颠覆原先的思路，不要担心，给我几分钟，我会解释你需要知道的一切。做好准备！

---

## 1. New Directory Structure
##### 新的目录结构 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/1)
- To begin our review of Laravel 5.0, let's review the most immediate change, when you install a fresh copy of the framework: the directory structure is different!
- 在开始前让我们再看一下 Laravel5.0，让我们回顾一下最直接的变化，当你安装框架的新副本：目录结构是不同的！

## 2. Method Injection
##### 支持方法注入 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/2)
- For a while now, we've been able to leverage automatic constructor injection, thanks to reflection and the IoC container. But now, the same is possible for controller methods! You'll love this one.
- 到目前为止，由于反射和 IoC 容器，我们已经能够利用自动构造函数注入。但现在，在控制器的方法中同样可以使用这个特性！你一定会喜欢这一个变化。

## 3. Form Requests for Validation and Authorization
##### 验证和授权表单请求 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/3)
- Next, we come to my favorite new feature in Laravel 4.3: form requests. Have you ever noticed how we all handle validation in slightly different ways? For such a common task, it's sad that there isn't a single system that we can all follow. Well...now there is! You're going to love form requests objects - especially when we mix them with method injection.
- 接下来，我们就来在 Laravel4.3 中我最喜欢的新功能：表单请求。你有没有注意到我们一直使用不同的方式来处理验证，而所有的这些仅仅是略有不同？对于这样一个常见的任务，这是可悲的，没有一个独立的系统，让我们复用。嗯...现在有！你一定会喜欢表单请求对象的 - 特别是当我们用“方法注入”将它们混合。

## 4. New File Generators
##### 新的文件生成器 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/4)
- Re-typing the same boilerplate over and over benefits no one. Instead, leverage the new file generators in Laravel 4.3.
- 重复输入相同的样板一遍又一遍对谁都没有好处。相反，应该利用新的文件生成器。

## 5. Spiffy Authentication
##### 出色的认证 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/5)
- Laravel 4.3 includes a new auth generator that will save you a great deal of time, when beginning your next new project.
- Laravel4.3 包含一个新的身份验证引擎，在开始你的下一个新项目时，它将节省你大量的时间。

## 6. Multiple Filesystems
##### 多文件系统 - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/6)
- For a while now, we've had the luxury of choosing from multiple drivers for mail, sessions, queues, and more. However, when it came to the filesystem, we were limited to working locally. Well - not anymore! Laravel, once again embracing the best of the PHP community, now pulls in the excellent Flysystem package, while providing a light decorator around it to keep the API consistent with what you're used to.
- 到目前为止，我们已经为“邮件”、“session”、“队列”提供了更多的驱动选择。然而，当这些加入到文件系统，we were limited to working locally。好了 - 没有了！ Laravel，再次迎来最佳的 PHP 社区，目前融合了出色的 Flysystem 包，同时提供一个轻型的修饰器包裹它来保持 API 与你已经习惯了的使用方式一致。

## 7. Contracts
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/7)
- All of Laravel's components now adhere to a new set of contracts, or interfaces. Yes, this isn't the most glamorous thing in the world, however, you'll find that it helps to decouple your code and reduce hard dependencies.

## 8. Route Caching Goodness
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/8)
- Route caching, which would be performed on your production server, will drastically speed up the process of registering your application's routes.

## 9. Socialite
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/9)
- New to Laravel is Socialite: an optional, first-party package for handling third-party authentication, such as with GitHub, Twitter, or Facebook. In this lesson, we'll review the entire process from scratch.

## 10. Laravel Elixir
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/10)
- Any modern application these days will require some form of automated asset/script compilation, concatenation, and general file watching. While tools, like Grunt and Gulp, simplify these common tasks, the truth is that it still takes too much effort to get up and running. But what if we could add a layer on top of Gulp to make the process of triggering such tasks as simple as it could possibly be? Well, we can! Let's talk about Laravel Elixir, which is now included with the base install of Laravel 5.

    Update: To speed things up, minification is disabled during development. Instead, run gulp --production when you're ready to deploy.

## 11. Route Annotations
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/11)
- Where did my routes.php file go!? Well, in Laravel 5, we can use annotations to register our routes. Let me show you how it works.

## 12. Event Annotations
#####  - [点击观看](https://laracasts.com/series/whats-new-in-laravel-5/episodes/12)
- In Laravel 5, we have two ways to register event listeners, and both are better than the way we accomplished it in Laravel 4! Let's see.





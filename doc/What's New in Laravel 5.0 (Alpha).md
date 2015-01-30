# What's New in Laravel 5.0 (Alpha)

[课程地址](https://laracasts.com/series/whats-new-in-laravel-5)

> Each new release of Laravel feels like a mini-Christmas, and version 5 is no different! Though some of these changes might seem jolting at first, don't worry; give me a few minutes, and I'll explain everything you need to know. Get ready!

> Laravel 的每个新版本感觉就像一个迷你的圣诞节，而版本 5 依然如此！虽然其中的一些变化似乎在颠覆原先的思路，不要担心，给我几分钟，我会解释你需要知道的一切。做好准备！

---

1. New Directory Structure
    To begin our review of Laravel 5.0, let's review the most immediate change, when you install a fresh copy of the framework: the directory structure is different!

2. Method Injection
    For a while now, we've been able to leverage automatic constructor injection, thanks to reflection and the IoC container. But now, the same is possible for controller methods! You'll love this one.

3. Form Requests for Validation and Authorization
    Next, we come to my favorite new feature in Laravel 4.3: form requests. Have you ever noticed how we all handle validation in slightly different ways? For such a common task, it's sad that there isn't a single system that we can all follow. Well...now there is! You're going to love form requests objects - especially when we mix them with method injection.

4. New File Generators
    Re-typing the same boilerplate over and over benefits no one. Instead, leverage the new file generators in Laravel 4.3.

5. Spiffy Authentication
    Laravel 4.3 includes a new auth generator that will save you a great deal of time, when beginning your next new project.

6. Multiple Filesystems
    For a while now, we've had the luxury of choosing from multiple drivers for mail, sessions, queues, and more. However, when it came to the filesystem, we were limited to working locally. Well - not anymore! Laravel, once again embracing the best of the PHP community, now pulls in the excellent Flysystem package, while providing a light decorator around it to keep the API consistent with what you're used to.

7. Contracts
    All of Laravel's components now adhere to a new set of contracts, or interfaces. Yes, this isn't the most glamorous thing in the world, however, you'll find that it helps to decouple your code and reduce hard dependencies.

8. Route Caching Goodness
    Route caching, which would be performed on your production server, will drastically speed up the process of registering your application's routes.

9. Socialite
    New to Laravel is Socialite: an optional, first-party package for handling third-party authentication, such as with GitHub, Twitter, or Facebook. In this lesson, we'll review the entire process from scratch.

10. Laravel Elixir
    Any modern application these days will require some form of automated asset/script compilation, concatenation, and general file watching. While tools, like Grunt and Gulp, simplify these common tasks, the truth is that it still takes too much effort to get up and running. But what if we could add a layer on top of Gulp to make the process of triggering such tasks as simple as it could possibly be? Well, we can! Let's talk about Laravel Elixir, which is now included with the base install of Laravel 5.

    Update: To speed things up, minification is disabled during development. Instead, run gulp --production when you're ready to deploy.

11. Route Annotations
    Where did my routes.php file go!? Well, in Laravel 5, we can use annotations to register our routes. Let me show you how it works.

12. Event Annotations
    In Laravel 5, we have two ways to register event listeners, and both are better than the way we accomplished it in Laravel 4! Let's see.





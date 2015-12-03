^title Decoupling Patterns

解耦模式

Once you get the hang of a programming language, writing code to do what you
want is actually pretty easy. What's hard is writing code that's easy to adapt
when your requirements *change*. Rarely do we have the luxury of a perfect
feature set before we've fired up our editor.

一旦你获得了编程语言的巧妙，编写你想要写的东西就会变得相当容易。困难的是编写适应需求*变化*的代码，在我们使用文本编辑器开火之前，通常没有完美的特性表使用。

A powerful tool we have for making change easier is *decoupling*. When we say
two pieces of code are "decoupled", we mean a change in one usually doesn't
require a change in the other. When you change some feature in your game, the
fewer places in code you have to touch, the easier it is.

能让我们更好的适应变化的工具是*解耦*。当我们说两块代码“解耦”时，是指修改一块代码一般不会需要修改另一块代码。带我们修改游戏中的一些特性时，我们需要修改的代码越少，就越容易。

[Components](component.html) decouple different domains in your game from each
other within a single entity that has aspects of all of them. [Event
Queues](event-queue.html) decouple two objects communicating with each other,
both statically and *in time*. [Service Locators](service-locator.html) let
code access a facility without being bound to the code that provides it.

[组件模式](component.html)将一个实体拆成多个领域来解耦他们。[事件序列](event-queue.html)解耦了两个互相通信的事物，稳定而且*及时*。[服务定位](service-locator.html)让代码使用服务而无需绑定到提供服务的代码。

## The Patterns

* [Component](component.html)
* [Event Queue](event-queue.html)
* [Service Locator](service-locator.html)
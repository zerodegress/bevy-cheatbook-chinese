# Bevy学习秘籍

{{#include ./include/links.md}}

这是为[Bevy游戏引擎][bevy::website]
([GitHub][project::bevy])写作的一本参考书风格的指南

它的目的是以简明的方式教授Bevy的概念，帮助你提高开发效率。
并发现你所需要的知识。

本指南汇集了许多社区的智慧，而这些智慧往往是官方文档所没有涵盖的。
这使你不必再为别人已经想通的问题而苦恼别人已经发现的问题！

虽然它的目的是要做到详尽无遗，但记录整个游戏引擎是一项艰巨的任务。
所以我把我的时间集中在我认为社区最需要的东西上。

因此，仍然有很多遗漏，无论是基础知识还是高级的话题。
尽管如此，我相信这本书将被证明是你的一个宝贵的资源!

***欢迎！愿这本书为你提供良好的服务！***

(don't forget to
<a class="github-button" href="https://github.com/bevy-cheatbook/bevy-cheatbook" data-icon="octicon-star" aria-label="Star bevy-cheatbook/bevy-cheatbook on GitHub">Star</a>
the book's [GitHub repository][project::cb],
and consider [donating](https://github.com/sponsors/inodentry) 🙂)

## How to use this book

The pages in this book are not designed to be read in order. Each page covers
a standalone topic. Feel free to jump to whatever interests you.

If you have a specific topic in mind that you would like to learn about, you
can find it from the table-of-contents (sidebar) or using the search function
(in the top bar).

The [Chapter Overview][chapter::overview] page will give you a general idea
of how the book is structured.

If you are new to Bevy, or would like a more guided experience, try the
[tutorial page][chapter::tutorial]. It will help you navigate the book in
an order that makes sense for learning, from beginner to advanced topics.

The [Bevy Builtins][chapter::builtins] page is a concise cheatsheet of useful
information about types and features provided by Bevy.

## Recommended Additional Resources

Bevy has a rich collection of [official code
examples][bevy::examples].

Check out [bevy-assets][bevyassets], for community-made resources.

Our community is very friendly and helpful. Feel welcome to join the [Bevy
Discord][bevy::discord] to chat, ask questions, or get involved in the project!

If you want to see some games made with Bevy, see [itch.io][itchio::bevy]
or [Bevy Assets][bevyassets::games].

## Maintenance

This version of the book is for Bevy release 0.9.

I intend to keep this book up-to-date and relevant with every new Bevy release.
I also try to regularly make improvements to it, when I can manage it.

## Support Me

<a class="github-button" href="https://github.com/sponsors/inodentry" data-icon="octicon-heart" data-size="large" aria-label="Sponsor @inodentry on GitHub">GitHub Sponsors</a>

I'd like to keep improving and maintaining this book, to provide a high-quality
independent learning resource for the Bevy community.

Your donation helps me work on such freely-available content. Thank you! ❤️

## Support Bevy

<a class="github-button" href="https://github.com/sponsors/cart" data-icon="octicon-heart" data-size="large" aria-label="Sponsor @cart on GitHub">GitHub Sponsors</a>

If you like the Bevy Game Engine, you should consider donating to the project.

## License

Copyright © 2021-2022 Ida Iyes.

All code in the book is provided under the
[MIT-0 License](https://github.com/bevy-cheatbook/mit-0).
At your option, you may also use it under the regular MIT License.

The text of the book is provided under the
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

Exception: If used for the purpose of contribution to the "Official Bevy
Project", the entire content of the book may be used under the [MIT-0
License](https://github.com/bevy-cheatbook/mit-0).

"Official Bevy Project" is defined as:
 - Contents of the Git repository hosted at [https://github.com/bevyengine/bevy](https://github.com/bevyengine/bevy)
 - Contents of the Git repository hosted at [https://github.com/bevyengine/bevy-website](https://github.com/bevyengine/bevy-website)
 - Anything publicly visible on the [bevyengine.org](https://bevyengine.org) website

The MIT-0 license applies as soon as your contribution has been accepted upstream.

GitHub Forks and Pull Requests created for the purposes of contributing to
the Official Bevy Project are given the following license exception: the
Attribution requirements of CC BY-NC-SA 4.0 are waived for as long as the
work is pending upstream review (Pull Request Open). If upstream rejects
your contribution, you are given a period of 1 month to comply with the
full terms of the CC BY-NC-SA 4.0 license or delete your work. If upstream
accepts your contribution, the MIT-0 license applies.

## Contributions

Development of this book is hosted on [GitHub][project::cb].

Please file GitHub Issues for any wrong/confusing/misleading information,
as well as suggestions for new content you'd like to be added to the book.

Contributions are accepted, with some limitations.

See the [Contributing][cb::contributing] section for all the details.

## Stability Warning

Bevy is still a new and experimental game engine! It has only been public
since August 2020!

While improvements have been happening at an incredible pace, and development
is active, Bevy simply hasn't yet had the time to mature.

*There are no stability guarantees and breaking changes happen often!*

Usually, it not hard to adapt to changes with new releases (or even track
the main git development branch), but you have been warned!


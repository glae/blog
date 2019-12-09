---
layout: post
title: "My favorite IntelliJ IDEA shortcuts :racehorse:"
---

# {{page.title}}

**Disclaimer:** This post is not intented to be original!

I have been using JetBrains' [IntelliJ IDEA](https://www.jetbrains.com/idea/) (Community edition) since 2012. A colleague showed us this IDE and its amazing refactoring features and stability. At the time, most of us were using [Eclipse](https://www.eclipse.org/) or [NetBeans](https://netbeans.apache.org/). I kept using both Eclipse and IntelliJ during months, then I switched solely to IntelliJ (I guess I ragequit Eclipse after a maven or SVN plugin crash). 

Afterwards I had the opportunity to use and enjoy the IntelliJ IDEA Ultimate version, which contains the very nice SQL client [DataGrip](https://www.jetbrains.com/datagrip/) for instance. I also used Android Studio and AppCode which are the dedicated versions for native-mobile development. I today mostly use it for Angular (TypeScript, HTML, SCSS), Spring Boot (Java), SQL and a bit of Scala development. 

We are in 2019. So here are **19 IntelliJ IDEA shortcuts**.


## The absolute `Shift+Shift` ❶

This one is the God one. The meta one. It is like the Windows or Command key on the operating system. It can find everything: actions (`Ctrl+Shift+A`), classes (`Ctrl+N`), files (`Ctrl+Shift+N`), symbols. 

![shift+shift](/blog/assets/2019-11-06-shift+shift.png "Shift+Shift")

It is almost the only shortcut to know and to pretend to be a senior all-inclusive stack developer. Tons of hours were saved, which of course then were be wasted on Twitter and Reddit. 

## Refactoring 

The main reason I first used intelliJ.

### Rename: `Shift+F6` ❷

The basic "rename". Works for everything. Sometimes gives some useful suggestions. 

![shift+F6](/blog/assets/2019-11-06-shift+F6.png "shift+F6")

### Extract all the things! `Ctrl+Alt+Whatever`

To extract a field, `Ctrl+Alt+F` ❸, a variable, `Ctrl+Alt+V` ❹:

![ctrlaltv](/blog/assets/2019-11-06-ctrl+alt+V.png "ctrlaltv")

To extract a method, use `Ctrl+Alt+M` ❺. A parameter, `Ctrl+Alt+P` ❻.

## Selection 

All standard text selection and search (VSCode/Notepad/Atom) shortcuts work as expected. 

A very powerful selection mode is the incremental selection `Ctrl+W` ❼ (`Ctrl+Shift+W` to rollback), which works close to `Ctrl+Shift+(←↑→↓)` in standard text editors, but with some words and blocks selection:

![ctrlw](/blog/assets/2019-11-06-ctrl+W.png "ctrlw")

You can enable the selection even inside words, with CamelHumps mode:

![humps](/blog/assets/2019-11-06-humps.png "humps")


## Insertion 

`Alt+Enter` ❾ is as useful as `Shift+Shift` ❶. It is a contextual menu, like "right click" on Windows.
E.g. on a string text `"hello"`, please note the lightbulb:

![lightbulb](/blog/assets/2019-11-06-alt+enter.png "lightbulb")

Or on an executable `object`:

![executable](/blog/assets/2019-11-06-alt+enter2.png "executable")

Insert a code snippet with `Alt+Ins` ❿: override/implement, add a test... 

Reformat your code: `Ctrl+Alt+L` ⓫ according to the styles defined in settings dialog. This feature is also available before commiting. 

## Navigation 

Global find/replace, with many options: `Ctrl+Shift+F` ⓬: 

![search](/blog/assets/2019-11-06-ctrl+shift+F.png "search")

Show usages: `Alt+F7` ⓭. Very useful when refactoring or debugging.

Move between open tabs: `Alt+(←→)` ⓮, move inside a file, jump on methods: `Alt+(↑↓)`

We can have a file overview with file structure: `Ctrl+F12` ⓯, it can also be seen with the "Structure" view (`Alt+7`):

![structure](/blog/assets/2019-11-06-structure.png "structure")

Moving easily through errors is essential: here is "next error" `F2` ❽. We can customize which kind of error to navigate to. The top-right red icon (!) shows there is something wrong in the whole file, and the right gutter marks the issues (the red one: an error, the yellow one: a warning).

![f2](/blog/assets/2019-11-06-F2.png "f2")



## Running

- Run code from the current cursor context: `Ctrl+Maj+F10` ⓰
- Debug code: `Ctrl+Maj+F9` ⓱

There are several run/debug variants.

## Versioning 

I always use versioning systems (git or SVN), these two shortcuts are the best:
  
- Update a project: `Ctrl+T` ⓲
- Commit changes: `Ctrl+K` ⓳ ("Kommit") 

## One last word

There is a plugin to learn shortcuts: [Key Promoter](https://plugins.jetbrains.com/plugin/9792-key-promoter-x). The [JetBrains' manual shortcuts page](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html) is also very clear. A paper cheat sheet is a nice tool too. 

I save a lot of time by refactoring efficiently, which is saving money, because I get paid to develop. I am then able to focus on the core interesting stuff: building and designing software. 


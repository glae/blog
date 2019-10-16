_This is my blog :frog:. I'll post about random developer stuff. Here is my GitHub profile: [https://github.com/glae](https://github.com/glae)._

<!-- template:
_________________________________

// two ## are needed for permalink
## Title... :emoji:
###### Published on 2019-xx-xx.

Text

<small><strong>[Comment this post!](https://github.com/glae/blog/issues/new?title=Comment%20on%202019-xx-xx%20post&assignee=glae)</strong></small><br><br>

-->

## My dream ASCII company :page_with_curl:
###### Published on 2019-10-16.

I wish I work in a company that use [ASCII](https://en.wikipedia.org/wiki/ASCII) or plain text as a primary format for its written work. 

### Why?

There are many reasons why, but here's for me the three main ones:
1. beauty: people working in IT mostly **do** suck at making pretty content or documents, so plain text prevent people trying to do so (ASCII art have limits)
1. simplicity: splitting the form and substance (or the style and content) keeps things simple ([KISS](https://en.wikipedia.org/wiki/KISS_principle))
1. money: ASCII/plain text is just free! 

Here is my personal experience with all of these. 

#### 1999 - Plain text

I started writing my diary in 1999. It was all plain text ending with `.txt`. It's still readable: 
```
Let's have a fun in my castle
To see the sunshine people
```
There was an obscure 30 KB size limit on my computer at the time.  

#### 2006 - LaTeX + Beamer

During my computer science degree, I had to write another thesis. I was used to use Word or OpenOffice for this kind of stuff, but a classmate introduced to me this weird-case-titled-document-system called [LaTeX](https://en.wikipedia.org/wiki/LaTeX) (pronunciation is under debate as in GIF or [MySQL](https://dev.mysql.com/doc/refman/5.7/en/what-is-mysql.html)).

I immediately felt in love with it... Well, until I had to include figures and tables in my document, here is a sample content: 
```latex
\chapter{Schedulability}

	The development of an embedded real-time application supposes that it needs to be 
    scheduled. First, we know that scheduling is based on three components:
	\begin{itemize}
		\item[-] an algorithm for allocating the resources \emph{(scheduling mechanism)}
		\item[-] an algorithm for ordering access to resources \emph{(scheduling policy)}
		\item[-] a means of predicting the worst-case behavior of the system when the 
        policy and mechanism are applied \emph{(schedulability analysis)}
	\end{itemize}

\section{Assessment}
\subsection{Scheduling mechanism}

We will use the Fixed Priority Scheduling (FPS) mechanism in a preemptive scheme for 
this purpose, a common way to schedule real-time systems. A static-priority algorithm 
assigns all priorities at design time, and those priorities remain constants for 
the lifetime of the task : we are in this case~\cite{LiuLay73}. 
```
Any text editor can be used (vi, Emacs, Notepad, Atom, Visual Studio Code...) or there are also [many dedicated editors](https://en.wikipedia.org/wiki/Comparison_of_TeX_editors).  

And the rendered output PDF:
<br>
![rendered latex](2019-10-16-a.png "rendered latex")

I also tried to use LaTeX with its presentation mode, [Beamer](), and created clean PDF presentations with source like: 
```latex
\begin{frame}
\frametitle{Use-cases and tasks}
\begin{block}{A task}
\begin{itemize}
  \item is an entity of an use-case
  \item encapsulates an object with \texttt{in} and \texttt{out} \emph{ports} to
  communicate
  \item has some temporal attributes:
  \begin{itemize}
    \item static ones: MAXTC, MINTC
    \item context-dependant ones: release time, deadline
 \end{itemize}
\end{itemize}
\end{block}
\end{frame}
```
And the rendered presentation:
<br>
![rendered latex](2019-10-16-b.png "rendered latex")

Nowadays HTML alternatives like [Reveal.js](https://github.com/hakimel/reveal.js), which can include Markdown format seem to be a good solution.


#### 2008 - Wikis

#### 2011 - Markdown + AsciiDoc

diff (unix tools) on the french law !
diffs plain text
versionning is nice

look at github : every decent has its README.md or README.adoc 

#### 2013 - Diagrams fantasy

plantuml, plain text 


### Excel, Pages, Word, PowerPoint, LibreOffice, why not?

Spending time setting up the style disturb me from what's important : **the content**.




<small><strong>[Comment this post!](https://github.com/glae/blog/issues/new?title=Comment%20on%202019-10-16%20post&assignee=glae)</strong></small><br><br>



## Tech skills: necessary but not sufficient :no_mouth:
###### Published on [2019-08-29](https://xkcd.com/1179/).

I often see this [learning roadmap link](https://github.com/kamranahmedse/developer-roadmap). It is a nice start for anyone who wants to learn or to improve its development skills. 

However, [as someone mentioned this issue](https://github.com/kamranahmedse/developer-roadmap/issues/40), we lack of some social skills developer roadmap. All these really nice tech skills are useless without the ability to promote and argue about your technical choices and approaches. 

<small><strong>[Comment this post!](https://github.com/glae/blog/issues/new?title=Comment%20on%202019-08-29%20post&assignee=glae)</strong></small><br><br>

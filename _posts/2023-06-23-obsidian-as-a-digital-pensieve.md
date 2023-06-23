---
layout: post
title: "Obsidian as a digital Pensieve"
date: 2023-06-23
categories: obsidian
---

# Obsidian as a digital Pensieve

Obsidian is a program that I have on all my devices, which has replaced several other apps and programs, and that I use daily, both privately and professionally. I have struggled to find a description of the full extent of my Obsidian use. In my search, I was reminded of a magical tool from Harry Potter: a Pensieve.

![[dumbledore pensieve.png]]

> [!quote]
> "_I use the Pensieve. One simply siphons the excess thoughts from one's mind, pours them into the basin, and examines them at one's leisure. It becomes easier to spot patterns and links, you understand, when they are in this form._" — Albus Dumbledore


Despite Obsidian not requiring a wand or a basin of magical water, Dumbledore's description of what his Pensieve does for him is quite similar to the feeling I have with Obsidian. My interpretation of the quote is, the liberating feeling of mental clarity after parting ways with one's pressing thoughts that allows both an easy way to overview and revisit them. 
That sounds great, you might say, but how do you go about siphoning your excess thoughts into a basin? In Dumbledore's world, the answer is, of course, magic.

In the real world, text is perhaps the closest approximation of a thought. (Footnote: One could argue that speech might be closer, but it's too cumbersome to store in its raw form). And that's why Obsidian, in its simplest explanation, is basically just a text editor. Or rather, a markdown editor - markdown is text with a thin layer of formatting on top, allowing for easy creation of things like varying-sized headings (using hashtags, "#" for the largest, "##" for the second largest, and so on) and quoting Dumbledore with ">" before his words of wisdom. 
In Obsidian's terminology, a Pensieve is called a vault, and a "thought" is referred to as a note, which is saved as text in a .md file.

> [!info] The 1st thing I love about Obsidian
> ### It feels like an editor

Obsidian feels like a native editor, because it is one. It's not a clunky web interface or a Windows/Android/iOS app implemented as an afterthought. In other words, it makes it easy and intuitive to add, modify, navigate, and connect your "thoughts"/notes - and, of course, there are shortcuts for everything. The path from intention to action is short. 

#### The Obsidian editor:
![[obsidian editor screenshot.png]]

The two fundamental ways to navigate your vault are through the command palette and the quick switcher.

#### ctrl+P: Command Palette
![[obsidian command palette screenshot.png]]
Shortcut for opening the command palette, with fuzzy search on all available commands, e.g create a new note, rename, delete, etc.


#### ctrl+O: Quick Switcher
![[obsidian quick switcher screenshot.png]]

Opens quick switcher, showing the most recently opened files and allows fuzzy search on all note names in your vault. And if a certain note doesn't exist, you can easily create it directly from there, no need to close it and create it from the command palette, or God forbid, resort to using the mouse.


## What do I store in my vault?
_Excess thoughts_ and ideas that can reasonably be described in words and that I judge worth revisiting _at my own leisure._ (to paraphrase Dumbledore).

This includes:
- Ideas for new projects and things that should exist.
- Thoughts that I want to read more about, further consider, or even write about.
- Snippets of code or shortcuts for obscure programs that are neither used frequently enough to remember or in-frequently enough to simply forget.
- Drafts for longer texts intended for elsewhere, such as a longer email or this article.
- Todos, one-offs, and tasks for projects.
- Diary entries, meeting notes, recipes, packing lists, and more.

In the past, I had these things scattered across multiple apps, often without clear distinctions between them.
I used Evernote for smaller, self-contained notes that were easy to categorize.
Google Keep for small, occasionally useful snippets and a place to describe a quick idea.
OneNote for highly structured content, such as lecture notes.

For all programs, especially these where you have to create all the content yourself, there comes a point where you begin to sense the point of no return. When have I invested so much time and energy in my notes that I don't want to switch programs anymore? I always reached that point quickly.
Is my content in a proprietary format that makes it impossible or highly undesirable to switch? What happens if the company behind it changes their stance on "free forever" or, because they didn't change their stance, goes bankrupt?
Can they keep up with development, or do they stagnate in terms of features, making me eventually feel compelled to switch and possibly start from scratch?

> [!info] The 2nd thing I love about Obsidian
> ### I feel confident making a long-term investment in it


Obsidian solves it all by:
- Using a universal and simple format like **markdown**, which will be supported with little or no modification by numerous other programs.
- Operating on a **local folder** where your data is entirely your own, and it's up to you to synchronize it across multiple devices, for example using OneDrive or something similar.
- Supporting **community plugins**, which allow for new features and ways to use your editor and notes to keep up with developments.
- Having a **reasonable pricing model**, where the program itself is free (though still closed-source), and you can choose to pay for Obsidian's own convenience features, such as sync and publish.

## The inevitable friction
When you've used a note-taking program for a long enough time, the structure you planned for your notes according to your initial purpose starts to show its limitations. You might have started with notes for highly structured materials like university courses and lectures. They are easy to categorize, so there isn't much thought about where to place them when created, for example, `semester/course/week`.
But friction arises when you need to take notes that cut across courses and semesters or from sources outside your studies. Or when your ideas for various new apps need to be organized in a meaningful folder:
`ideas/apps/`? `apps/ideas/`? `personal/apps/ideas/`?

Folder structures, along with naming, are the most obvious ways to associate notes with each other, and the friction that arises from an inadequate folder system may not be a significant problem at first. 
However, it accumulates over time and can create a situation where the friction of having to consider, in advance, where a note belongs outweighs the apparent value of it. This might only occur for not-obviously worth saving notes, but it shouldn't occur at all, if one of the goals is to _siphon your excess thoughts_. 

> [!info] The 3rd thing I love about Obsidian
> ### Links and minimal friction

Obsidian solves the friction problem for me in several ways.

**Firstly**, internal links. They allow for associating notes with each other in a contextual manner. Similar to how a Wikipedia page has links to other wiki pages at relevant places, so one can dive deeper into a topic as they go along.
This makes it easy to create an overarching note for a topic that contains links to all the relevant notes and files, as opposed to creating a folder for the topic and placing all files within it or being very strict with the naming of all files.

Internal links are defined in markdown with double square brackets `[[ ]]` and can link to:
- Other notes: `[[another note]]`
- Media such as images: `![[some image]]` (with an exclamation mark "!" at the beginning to display the image in the note)
- Headings in other notes using "#": `[[another note#some heading]]`
- General blocks in other notes using "^": `[[another note^some block]]` (e.g., paragraphs or subheadings)

Obsidian, being the editor it is, naturally offers fuzzy search on all your notes while creating a link, so you don't have to remember more than fragments of a note title. And all links to a note are automatically updated if you rename a file.

**Secondly**, Obsidian supports my folder-less system. With links and the excellent built-in search function across all notes, I have completely abandoned the need to consider "where" a note belongs. I simply create it with a meaningful title, dump my thoughts into it, connect it to any other relevant notes with links, and leave it in the root.
Or for even more fleeting thoughts, I have a dedicated note - named inbox  - where I dump any thought without considering note title, links or anything. I browse my inbox occasionally and move any thoughts to independent notes if I feel like it, or delete it if it was a duplicate or simply not worth keeping.

This is where my feeling of Obsidian as a digital Pensieve originates. There is something incredibly liberating about simply dumping one's thoughts into a vault and having confidence that it is easy to retrieve and build upon with Obsidian.

> [!tip] folder-less system
> My folder-less system is just that - a system, not a specific feature of Obsidian. Obsidian doesn't care about the depth or shallowness of your folder hierarchy.

> [!info]
> #### Go to https://obsidian.md/ to download and learn more.

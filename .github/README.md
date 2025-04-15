<div align="center">
    <br>
    <a href='https://github.com/ephemeralrogue'>
        <img
            src="./assets/lvnacy_emblem_plain.png"
            alt="Gray banner with bold v in the center"
            width='256px'
        />
    </a>
    <br>
    <br>
    <h1>Obsidian Vault Template</h1>
    A Preconfigured Obsidian Vault<br>
</div>
<div align="center">
    •
    <a href="https:////github.com/ephemeralrogue">
        GitHub
    </a>
    • L V N A C Y •
    <a href="https://bsky.app/profile/lvnacy.xyz">
        Bluesky
    </a>
    •
</div>
<br>
<br>
<a id='contents'></a>
<div align='center'>
    <h1>overview</h1>
</div>
I've found myself spinning up context-specific Obsidian vaults for the 
numerous projects, topics, concepts, ideas, stories, I explore and decided 
to minimize the amount of time it takes to boot up a new one whenever the 
desire strikes. Thus this template is designed to fill two purposes:
<br>
<br>

1. [Easy setup](#easy-setup)
2. [Support a modular note-taking system](#modular-system)
<br>
<br>
<a id='easy-setup'></a>
<div align='center'>
    <h1>easy setup</h1>
</div>
This vault comes preloaded with one theme and eight plugins:

- [Minimal][minimal]
- [Minimal Theme Settings][minimal-settings]
- [Custom File Explorer sorting][sortspec]
- [Dataview][dataview]
- [Iconize][icons]
- [PDF++][pdfplus]
- [Tasks][tasks]
- [Templater][templater]

I typically like to setup up each vault with a different theme to ease 
context-switching, but I love the simplicity of [Minimal][minimal] as a 
starting point, hence why it's included.

[Dataview][dataview] is something I'm learning and making use of as I go. 
[Custom File Explorer sorting][sortspec] and [Iconize][icons] I use 
religiously to orient myself in the explorer at a glance. [Tasks][tasks] helps 
me stay on top of things, allowing me to add tasks anywhere and display them 
in a central location. [Templater][templater] is included as it offers a host 
of features with regard to templates.

The idea here is not to pack the vault with all the popular plugins, but 
rather be up and running with what I would normally be installing anyway. Some 
vaults I have make use of the [Kanban][kanban] plugin, others do not. Rather 
than have to manage the removal of plugins, I prefer to add them as needed. 
The ones included here are used in all vaults I create.

There are few CSS snippets that have been added to extend basic functionality:
- *callout-grid-2.1*, written by [Wendystraite][wendystraite] from the 
[Obsidian Forums](https://forum.obsidian.md/t/css-snippet-to-display-markdown-in-grids-without-html/95117),
which adds columns and other visual alignment options to notes,
- *full-pane-width*, written by DavidMcKidev from the 
[Obsidian Forums](https://forum.obsidian.md/t/tab-stacks-sliding-mode-add-option-to-show-only-one-tab-a-time-with-two-collapsed-stacks-on-the-sides-full-width-tab/45036/10), 
which improves stacked tab pane width, and
- *paragraph-writing*, written by Dawni from the 
[Obsidian Forums](https://forum.obsidian.md/t/tabbing-paragraphs-and-single-space-between-them-so-simple-yet-im-lost-sos/99492/3), 
which provides indentation and spacing between paragraphs.

I've started working on a reference directory for ease of access to frequently 
used functions and operations in the included plugins. At the moment, there is 
- a Dataview Cheatsheet based on [seburbandev's][seburbandev] [original][dataview-cs-orig];
- a Templater Cheatsheet based on [Ambi93's][ambi93] [Templater User Guide][templater-cheatsheet]; and
- a Callout Reference, pulled from [this forum post][callout-post].

More will be added as I generate useful docs from various sources.

[Back to the top](#contents)

The other plugins are included to support this modular system I'm building, 
which brings us to ...
<br>
<br>
<a id='modular-system'></a>
<div align='center'>
    <h1>support a modular note-taking system</h1>
</div>
I'm working on a sort of plug-and-play set up with my vaults. Due to what I 
consider to be a great amount of information to process on a regular basis, 
I'm interested in creating a system whereby I can easily move blocks of 
information from one vault to another while keeping context-specific notes 
siloed in their respective vaults. Here's where the other plugins come in to 
play.<br>
<br>

> [!warning]
> This system relies heavily on `git submodules`. If you are unfamiliar with 
> `git submodules`, please take some time to orient yourself with them:
> [git submodules][submodules]

### Example: The Library
The [Library module][library] is designed to organize all manner of documents in a local 
vault. This is where [PDF++][pdfplus] shines, providing extended support for 
PDF documents included in the vault. Having this already built in 
to the vault makes plugging context-specific libraries simple. All the wiring 
is in place, just gotta plug the damn thing in.

[Back to the top](#contents)

<a id='conclusion'></a>
<div align='center'>
    <h1>conclusion</h1>
</div>

I think that's it for now! Find me on [Bluesky][bluesky] or [Discord][discord] 
if you have any questions!<br>
<br>

[Back to the top](#contents)

<!-- Links -->
[minimal]: https://github.com/kepano/obsidian-minimal
[minimal-settings]: https://github.com/kepano/obsidian-minimal-settings
[dataview]: https://github.com/blacksmithgu/obsidian-dataview
[dataview-cheatsheet]: https://github.com/ephemeralrogue/dataview-cheatsheet
[dataview-cs-orig]: https://github.com/seburbandev/obsidian-dataview-cheatsheet
[templater-cheatsheet]: https://github.com/Ambi93/Obsidian-Sync/blob/main/Comprehensive%20User%20Guide%20for%20Templater%20in%20Obsidian.md
[callout-post]: https://forum.obsidian.md/t/all-callout-styles-for-reference/36102
[sortspec]: https://github.com/SebastianMC/obsidian-custom-sort
[icons]: https://github.com/FlorianWoelki/obsidian-iconize
[pdfplus]: https://github.com/RyotaUshio/obsidian-pdf-plus
[note-defs]: https://github.com/dominiclet/obsidian-note-definitions
[frontmatter-links]: https://github.com/mnaoumov/obsidian-frontmatter-markdown-links
[tasks]: https://github.com/obsidian-tasks-group/obsidian-tasks
[templater]: https://github.com/SilentVoid13/Templater
[kanban]: https://github.com/mgmeyers/obsidian-kanban
[submodules]: https://git-scm.com/book/en/v2/Git-Tools-Submodules
[library]: https://github.com/lvnacy-obsidian/obsidian-library-module
[bluesky]: https://bsky.app/profile/lvnacy.xyz
[discord]: https://discord.gg/nh7mqGEfbw
[seburbandev]: https://github.com/seburbandev
[ambi93]: https://github.com/Ambi93
[wendystraite]: https://github.com/wendystraite

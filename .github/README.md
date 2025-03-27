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
- [Dataview][dataview]
- [Custom File Explorer sorting][sortspec]
- [Iconize][icons]
- [PDF++][pdfplus]
- [Note Definitions][note-defs]
- [Frontmatter Markdown Links][frontmatter-links]
- [Tasks][tasks]

I typically like to setup up each vault with a different theme to ease 
context-switching, but I love the simplicity of [Minimal][minimal] as a 
starting point, hence why it's included.

[Dataview][dataview] is something I'm learning and making use of as I go. 
[Custom File Explorer sorting][sortspec] and [Iconize][icons] I use 
religiously to orient myself in the explorer at a glance. [Tasks][tasks] helps 
me stay on top of things, allowing me to add tasks anywhere and display them 
in a central location.

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
*At the time of this writing, the library module template hasn't been created; 
I will update this README with a link to it upon its creation.*

The Library module is designed to organize all manner of documents in a local 
vault. This is where [PDF++][pdfplus] shines, providing extended support for 
PDF documents included in the vault. The library encourages the development of 
a built-in glossary, hence the [Note Definitions][note-defs] plugin. 
[Frontmatter Markdown Links][frontmatter-links] makes creating links between 
notes and documents in the properties a breeze. Having these already built in 
to the vault makes plugging context-specific libraries simple. All the wiring 
is in place, just gotta plug the damn thing in.

[Back to the top](#contents)

<a id='extras'></a>
<div align='center'>
    <h1>some extras</h1>
</div>
Well, one extra, at the moment. Due to the frustrating case of stacked tab 
panes not sliding over all the way in a number of themes, I've included a css 
snippet to address this. Other tweaks will be enumerated here as I come across 
the need for them and develop or include them.<br>
<br>

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
[sortspec]: https://github.com/SebastianMC/obsidian-custom-sort
[icons]: https://github.com/FlorianWoelki/obsidian-iconize
[pdfplus]: https://github.com/RyotaUshio/obsidian-pdf-plus
[note-defs]: https://github.com/dominiclet/obsidian-note-definitions
[frontmatter-links]: https://github.com/mnaoumov/obsidian-frontmatter-markdown-links
[tasks]: https://github.com/obsidian-tasks-group/obsidian-tasks
[submodules]: https://git-scm.com/book/en/v2/Git-Tools-Submodules
[bluesky]: https://bsky.app/profile/lvnacy.xyz
[discord]: https://discord.gg/nh7mqGEfbw
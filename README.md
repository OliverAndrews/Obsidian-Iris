# ObsidianIris

Iris is a tool for rolling over your previous day's unfinished tasks. This is based on, but not a fork of [this](https://github.com/shichongrui/obsidian-rollover-daily-todos).

### To Install
[Click here to download latest Iris.zip](https://github.com/OliverAndrews/Obsidian-Iris/releases/tag/1.0).

Here you should only select Iris.zip, the source files are not needed unless you want to make code changes. 

Make a folder inside Vault/.obsidian/plugins called Iris. Put the contents of Iris.zip into that folder.

### Filenames

Iris uses the filename of your daily note as a way to determine which other note's TO DO list it will import. Because of this, the title has to be clearly formatted and look like this: `Sunday Jan 03, 2021`. This only affects filenames. Headings and other anchors are unaffected. Anyone who's coming from [obsidian-rollover-daily-todos](https://github.com/shichongrui/obsidian-rollover-daily-todos) doesn't have to make any changes and Iris is fully compatable with this plugin. I am looing into solutions to this restriction.

### Setting Up

![Settings Window](https://i.imgur.com/9NCsLHy.png)

**To Do** heading lets you set what anchor you have your TO DO list in. Anything in that anchor's section which starts with `- [ ]` will be imported if they are not marked as complete. 

**Daily Notes Directory** allows you to specify where your Daily Notes are kept. Anything in that directory must be formatted with the correct filename, mentioned above.

### Notes to Developers

The Javascript is generated from Typescript and I do not suggest editing that, instead alter the main.ts file in the source code for changes.
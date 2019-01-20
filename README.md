# ascii tree generator

A VS Code plugin to generate ascii tree of directories or formatting selected text to tree strings.

## Working In Progress

This plugin is currently working in progress, not avaiable in market yet.

## Usage

### Workspace

### TextEditor

## Configuration

|key|default|description|
|---|---|---|
|sort|true||
|ignore|||
|maxDepth|Number.MAX_VALUE||
|charset|||

## Supported text format

### text with `indent`

```
public
dist
  index.d.ts
  index.js
src
  index.ts
```

### text with `hash(#)` symbol

```
# public
# dist
## index.d.ts
## index.js
# src
## index.ts
```

## Todo

- ~formatFromText: read current user selected texts~
- disable command panel command
- read user configuration
- formatFromDirectory: add 'copy to clipboard' button in webview
- clear up all message box informations
- i18n

### VS Code Reference

- [api reference](https://code.visualstudio.com/api/references/vscode-api#Uri)
- [`when` clause context](https://code.visualstudio.com/docs/getstarted/keybindings#_when-clause-contexts)
- [`menu` group types](https://code.visualstudio.com/api/references/contribution-points#Sorting-of-groups)

### Other Reference

- <https://en.wikipedia.org/wiki/Tree_(command)>
- <https://www.geeksforgeeks.org/tree-command-unixlinux/>
- <https://stackoverflow.com/questions/19699059/representing-directory-file-structure-in-markdown-syntax>
- <https://code.visualstudio.com/api/get-started/wrapping-up>
- <https://github.com/mbr/asciitree>
- <https://www.npmjs.com/package/ascii-tree>
- <https://atom.io/packages/ascii-tree>
- <https://unix.stackexchange.com/questions/127063/tree-command-output-with-pure-7-bit-ascii-output>
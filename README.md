# How to be (more) productive with ember.

TODO:
 - add gifs of all the toolings
 - better descriptions
 - write more professionally
 - consider splitting into multiple blog posts / documents for the other resistance areas

Over the years, I've heard much resistance to ember and wanted to address some of the more common issues.  
Everything can sort of be split into a few categories to aid in the frontend developer experience:
 - Tooling
 - Backend API Design
 - Frontend Data/State Management
 - Frontend Implementation Patterns

## Tooling

Good, worthwhile tools can be fairly difficult to find (and also very subjective!). My favorite editor is Atom, due to it's vast customizability of hotkeys... and ability to split both horizontally and vertically at the same time for high-res large screen programming. <sup>[1](#myfootnote1)</sup>

### Atom Packages

- [ember-tabs](https://atom.io/packages/ember-tabs)  
this isn't an ember-specific package as all it does is let you search for files in the same folder as your currently focussed file. Highly recommended for any project (including react, rails, dotnet, etc ... _anything_)
- [ember-snippets](https://atom.io/packages/ember-snippets)  
simple package that includes snippets for ember, ember-data, and handlebars. saves you seconds!

- [ide-ember](https://atom.io/packages/ide-ember)  
  ember language server support. This is crucial for handlebars templates. ide-typescript can handle all the ts/js code.

- [?language-ember-htmlbars](https://atom.io/packages/language-ember-htmlbars)

#### General Utilities
- [atom-ide-ui](https://atom.io/packages/atom-ide-ui), [ide-css](https://atom.io/packages/ide-css), [ide-docker](https://atom.io/packages/ide-docker), [ide-typescript](https://atom.io/packages/ide-typescript)  
the ide suite in atom has been a welcome addition in recent months. intellisense with typescript makes working with plain javascript frustrating. With enough typed libraries, there are no more spelling errors... no more bad import paths... automatic import fixing! typescript and ide support bring squiggle-driven-development (SDD) to atom.

- [aligner](https://atom.io/packages/aligner),
[aligner-javascript](https://atom.io/packages/aligner-javascript),
[aligner-scss](https://atom.io/packages/aligner-scss)  



- [blame](https://atom.io/packages/blame)  
this toggles `git blame` in the editor's gutter, which is handy for knowing who wrote what code (in case you need to consult anyone on your team for more in-depth details about implementation, or congratulate them on how amazing their javascript skills are)
- [change-case](https://atom.io/packages/change-case)  
this provides a number of case conversions (such as `camelCase` to `PascalCase`). These are especially handy for redux's action constants and action creator functions.

- [highlight-column](https://atom.io/packages/highlight-column)  
highlights the column at the cursor position. helps with finding your cursor in a large file.

## References

<a name="my-atom-config"><sup>1</sup></a> [atom config](https://github.com/NullVoxPopuli/dotfiles/tree/master/home/.atom) from my dotfiles repo

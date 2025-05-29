# <img src='Workflow/icon.png' width='45' align='center' alt='icon'> Wordsmith Alfred Workflow

Local dictionary and thesaurus to lookup synonyms, anthonyms, and definitions

[⤓ Install on the Alfred Gallery](https://alfred.app/workflows/vitor/wordsmith)

## Setup

Open Dictionary.app. In the menubar: `Dictionary` → `Settings…`. Install the Oxford Dictionary of English and the Oxford American Writer’s Thesaurus.

Build their databases with the `:wordsmithbuild` keyword.

![Buidling definitions](Workflow/images/about/build.png)

## Usage

### Thesaurus

Search for synonyms via the `the` keyword.

![Searching thesaurus](Workflow/images/about/thesaurus.png)

* <kbd>↩&#xFE0E;</kbd> Show all synonyms in the current entry, with definitions.
* <kbd>⌘</kbd> Show example phrase with the original word.
* <kbd>⌥</kbd> Show antonyms. <kbd>↩&#xFE0E;</kbd> to show all in the current entry, with definitions.
* <kbd>⇧</kbd><kbd>↩&#xFE0E;</kbd> Open original word in Dictionary.

When listing all entries from the thesaurus, each word shows a single definition.

![Seeing thesaurus definitions](Workflow/images/about/thesaurusdefs.png)

* <kbd>↩&#xFE0E;</kbd> Copy word to clipboard. Pastes to frontmost app if activated via the Universal Action.
* <kbd>⌘</kbd><kbd>↩&#xFE0E;</kbd> Lookup in thesaurus.
* <kbd>⌥</kbd><kbd>↩&#xFE0E;</kbd> Lookup more definitions.
* <kbd>⇧</kbd><kbd>↩&#xFE0E;</kbd> Open in Dictionary.

### Dictionary

Search for word definitions with the `def` keyword.

![Searching dictionary](Workflow/images/about/dictionary.png)

* <kbd>↩&#xFE0E;</kbd> Copy word to clipboard. Pastes to frontmost app if activated via the Universal Action.
* <kbd>⌥</kbd><kbd>↩&#xFE0E;</kbd> Lookup in thesaurus.
* <kbd>⇧</kbd><kbd>↩&#xFE0E;</kbd> Open in Dictionary.

### Universal Actions

Both the thesaurus and dictionary can be accessed via [Universal Actions](https://www.alfredapp.com/help/features/universal-actions/). With this method, a word selected with <kbd>↩&#xFE0E;</kbd> pastes to the frontmost app.

![Universal Actions](Workflow/images/about/ua.png)

Configure the [Hotkeys](https://www.alfredapp.com/help/workflows/triggers/hotkey/) for faster triggering.

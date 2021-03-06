The options are:

* Delete original cards: if True, the original cards are deleted.
* When identical keep a single field: if two merged cards have the same value in both field, don't concatenate those values.
* Keyboard shortcut: Select notes in browser then press the shortcut to merge the selected notes.
* Overwrite patterns: Patterns that indicate a field will be replaced by the value from the other note. Uses RegExp syntax, so be sure to escape special characters if you want to match them literally. For instance, if you want fields with the text "`[REPLACEME]`" to be overwritten, : the configuration value would have to look like this: `"Overwrite patterns":  [ "\\[REPLACEME\\]" ]`.
* Strong tags: Notes with any of these tags will have their non-empty fields overwrite any fields in the other note. "`Overwrite patterns`" takes precedence.
* Weak tags: Notes with any of these tags will have all their fields be overwritten by non-empty fields in the other note. "`Overwrite patterns`" and "`Weak tags`" take precedence.

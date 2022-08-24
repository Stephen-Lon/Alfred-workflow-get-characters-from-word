# Alfred-get-characters-from-word
An Alfred workflow to get specified numbered characters from a word on the clipboard
# Usage

Use this workflow for those annoying websites that want you to insert the first, fourth and fifth letters of your mother's maiden name as part of their login rigmarole. 

This workflow gets specified characters from a word *already on the clipboard* (i.e., you first copy the special word from your password manager). You specify what characters you want by their position (e.g., `2 5 6`) and the workflow displays the relevant characters in large type.

It is useful for logins to websites that require, e.g., "The first, third and fourth characters of your favourite place" or "The second, fourth and fifth characters of your mother's maiden name". It also works with characters from date strings (e.g., `21092021`). *In any of those cases you would copy the relevant word from your password manager and then run this workflow.*

The workflow uses the default keyword "gc" (with no space afterwards) for "get characters".

The workflow uses an AppleScript script as its core.

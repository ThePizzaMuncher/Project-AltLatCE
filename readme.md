# The irregularly updated extension of Kino’s Alt-Latin keyboard layout

Credit for the base goes to one Kino from the University of Chicago for making it, and Theo Beers for fixing it so that it actually works on Windows 10 (Kino made it in 2004, so understandably it doesn’t work anymore)

&nbsp;
* * *
[A few things](#A); [Installation](#Installation); [Changelog](#Changelog)

* * *

&nbsp;

## The what

This is a modified keyboard layout for Windows (10), based on an existing custom layout which is itself a modification of the US-International QWERTY layout.
On the face of it, it’s simply QWERTY; as far as the labels on the keyboard go, this layout is identical to US-International; what differs is the functions / symbols accessed with `AltGr` and `AltGr + Shift`.  
Of note here is that unlike on US-International, there are no dead keys on the base layer; `'` `e` makes `'e` and not `é`, `Shift + '` `e` makes `"` and not `ë`, and so on. All the dead keys of US-International are still present—they’re just behind different keystrokes.

&nbsp;

## The why

In short: because I can.  
Kino probably made this layout because they actually needed it (wether for their study, job or otherwise); I merely installed it because I like using exotic symbols, or ones that are technically correct / used to be correct but are fading into disuse or, even worse, obscurity. I then started adding stuff that I also wanted quick access to, and here we are.

There *is* merit to having this layout, though. For one, it provides access to a lot more diacritical markings that one might need just to type foreign words correctly (or in my case, my own—even if those used in Dutch are already present on US-Intl, which is the standard layout in the Netherlands). It also gives quick access to certain symbols that aren’t even supposed to be obscure and that many people use frequently but are not found on normal layouts; examples include:

+ the curved quotation marks `‘ ’   “ ”`, as distinct from the single and double straight ticks `' '   " "` most often found on normal layouts
+ the hyphen `‐` as distinct from the hyphen‐minus `-` normally found on keyboards and often (mistakenly \*grumble\*) referrred to as ‘hyphen’[^hyphen]
+ the en dash `–`, which is used, among other things, to connect two symmetric items (for instance two ends of a range or two competitors / alternatives[^emdr]), to subsitute pairs of commas / parentheses for a mid‐sentence interruption (depending on the spelling authority)[^emdp], or – depending again on the spelling authority – in compound words when one or more of the compounds is more complex than a single word—or not hyphenated.[^emdc]
  + ([here][dwiki]’s a link to the wikipedia page on dashes, if you couldn’t be bothered to go to the footnotes or if you wanted to read the whole thing instead)
+ the em dash `—`, as frequently seen throughout this very document alone. In English its use is mostly parenthetical (to create breaks in sentences, like parenthesis or commas do, such as here); enclosing part of a sentence in em dashes might signal that it’s more important to the rest of the sentence than parenthesis would

Some of these do have ALT codes—hell, some of those ALT codes might even work consistently—but ALT codes are a pain in the flesh to type with any frequency, and as I just said, some of them don’t work consistently in every program. This layout solves that, by giving easy access to such symbols.

&nbsp;

## A few things

+ I’m not pretending that I made any of these changes to make sense for anyone other than myself—to me, they might be the most logical thing in the world, while an onlooker may wonder what in the black river I’ve been spiking my coffee with. I’m only working with what I have here, which is an already rich keyboard layout, and an ISO keyboard with a number pad. And on that…
+ The changes I make to this layout assume that the keyboard in use has a number pad, and the extra key on the bottom left row, between z and left Shift; present on ISO keyboards, which are most commonly found in Europe. While the most important characters are already present and thus don’t need adding, I will not hesitate to use any of these keys as an added benefit.

With that out the way, let’s begin.

&nbsp;

&nbsp;

## Installation

This is the easiest part;

1) Grab the `.zip` file containing the [latest][latest-zip] iteration (or the desired one) from its respective folder—if you want to change it beforehand you can download the [klc][latest-klc] instead; or you can download the entire repo if you so desire, it’s all sausage to me
2) Extract if applicable and enter the folder it creates
3) Open `setup.exe`
4) Wait for the message telling you it’s been installed to pop up
5) Restart your computer
6) Go to Settings – Time & Language – [your preferred language] – Options, click `Add a keyboard`, and select `Alt-Latin 2019 - CE` if you installed the base version, or `Muncher‐Flavoured Alt‐Latin [version number]` if you installed a later one. In any case, the installed layout should show up at the top
7) Profit

If you use numerous other keyboard layouts already, you may want to consider uninstalling those, leaving only one behind for the language you want to use this layout on. Your mileage may vary, but I’ve had nothing but headaches installing this until I temporarily uninstalled the Russian language and layout.

&nbsp;

## Changelog

Version 1.0<sup>[zip][1-0zip], [klc][1-0klc]</sup> is the base, which consists of Beers’ version ([direct download] here, [article] here) with a few changes consolidated into this build:

+ Added the glottal stop character `ʔ` to `AltGr + numpad decimal`
+ Added the hyphen `‐` to `AltGr + f` [^hyphenlocation]
+ Added left angle bracket `<` to `ISO` and right angle bracket `>` to `AltGr + ISO`
+ Added broken pipe character `¦` to `Shift + ISO` and broken l `ꝇ` to `Shift+AltGr + ISO`

### V1.1

+ Moved Not sign `¬` to `CLock 1`
+ Added Fullwidth Not sign `￢` to `CLock Shift + 1`
+ Added Interrobang `‽` to `CLock Shift + /`
+ Moved Glottal Stop `ʔ` from `AltGr + numpad decimal` to `CapsLock /`
+ Added Pharyngeal Voiced Fricative `ʕ` to `CapsLock Shift + /`
+ Added Combining Glottal Stop `ˀ` to `AltGr + numpad decimal`
+ Added Combining Reversed Glottal Stop `ˁ` to `AltGr + numpad decimal`
+ Moved Glottal Stop `ʔ` to `CapsLock Shift + /`, Pharyngeal Voiced Fricative `ʕ` to `CapsLock numpad decimal` and removed the combining glottal stops `ˀ` and `ˁ`, because shift reverses NumLock state
+ Moved Glottal Stop `ʔ` and Pharyngeal Voiced Fricative `ʕ` to `Caps '` and `Caps Shift + '` because that’s more logical and easier to type
+ TL;DR = `ʔ` on `CLock '`, `ʕ` on `CLock Shift + '`,

&nbsp;

[^hyphen]: spell‐checking engines sometimes consider this one correct, sometimes they don’t; I’ve included it anyway because from a language standpoint it’s objectively the correct one.

[^emdr]: [https://en.wikipedia.org/wiki/Dash#Ranges_of_values][emdrwiki], if you wanna read more about the whole ranges thing.

[^emdp]: [https://en.wikipedia.org/wiki/Dash#Parenthetic_and_other_uses_at_the_sentence_level][emdpwiki], if you want to read more about the parenthetic use of the en dash.

[^emdc]: [https://en.wikipedia.org/wiki/Dash#Attributive_compounds][emdcwiki] if you want to read more about the use of the en dash in compound words.

[^hyphenlocation]: This doesn’t make all the sense in the world, but I also program and for that I need Hyphen‐Minus `-` (this is what most people mean when they refer to ‘hyphen’, the “hyphen” key outputs this); besides, it’s easy to type this way and the Hyphen‐Minus / underscore key was already filled completely.  
Outside all of that, I mostly make the changes I make based on what works for me; so if it seems weird, labyrinthine and convoluted to you, rest assured I was barely trying to inject any sense into it.

[dwiki]: https://en.wikipedia.org/wiki/Dash "https://en.wikipedia.org/wiki/Dash"

[emdrwiki]: https://en.wikipedia.org/wiki/Dash#Ranges_of_values "https://en.wikipedia.org/wiki/Dash#Ranges_of_values"

[emdpwiki]: https://en.wikipedia.org/wiki/Dash#Parenthetic_and_other_uses_at_the_sentence_level "https://en.wikipedia.org/wiki/Dash#Parenthetic_and_other_uses_at_the_sentence_level"

[emdcwiki]: https://en.wikipedia.org/wiki/Dash#Attributive_compounds "https://en.wikipedia.org/wiki/Dash#Attributive_compounds"

[direct download]: https://www.theobeers.com/AltLat19.zip "https://www.theobeers.com/AltLat19.zip"

[article]: https://medium.com/@tbeers/the-alt-latin-keyboard-layout-windows-version-701c64f8bfd8 "https://medium.com/@tbeers/the-alt-latin-keyboard-layout-windows-version-701c64f8bfd8"

[latest-zip]: /ALCE-v1.0.zip "ALCE-v1.0.zip"
[latest-klc]: /v1.0/Alt-Latin_CE_v1.0.klc "Alt-Latin_CE_v1.0.klc"

[1-0zip]: /ALCE-v1.0.zip "ALCE-v1.0.zip"
[1-0klc]: /v1.0/Alt-Latin_CE_v1.0.klc "v1.0/Alt-Latin_CE_v1.0.klc"

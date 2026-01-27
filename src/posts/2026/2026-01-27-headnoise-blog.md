---
title: 'hewlow, woold!'
description: 'just a quick "hey".'
date: 2026-01-27
tags: ['headnoise', 'hey']
---

Hey

# Tiny Things

Yesterday, I found myself editing my first post in a while, and _noticed_ it was not as fluid as before. I thought I might be a little rusty, but quickly came to the conclusion that Drafts was to blame. Better yet, the theme I was using, was to blame.

I have recently moved to the _lighter_ side of iOS, [ditched dark mode for a while](https://social.lol/@maique/115936571346703431),  and have been getting used to white. A lot of white! I needed a new theme for Drafts.

The one I was using was good for shorter sessions, but was annoying me on this longer one. 

I considered finding one that was close enough to what I was aiming for, as one does, and go from there. So I did. 

I started tweaking it, trying to wrangle it to look like what I wanted. It was not easy, as there are a LOT of settings, and it's not immediately apparent what each one does exactly. I was feeling a little depleted anyway, and it was pretty late already. I went back to the directory, and looked for a way out. Not before long, I had it.

I came across [Tiny Theme](https://directory.getdrafts.com/t/2TT), of course. For Drafts, of course. [Matt Langford](https://mastodon.social/@Mtt) did it again: he ported the amazing [Tiny Theme](https://github.com/MattSLangford/Tiny-Theme-for-Micro.blog) (is it possible to not love this name?) blog theme to Drafts, and it needed only two tiny (ah!) tweaks: I like my URLS the same size as regular text, and I like my background not to be #FFFFFF. That was it. After that, I was done, I could go back to writing. Happy again.

Perks: I suppose you're going to be seeing a lot more quotes on the posts, because quotes look nice when I'm editing the text with this. Sorry if some don't make total sense. 

Drafts themes, maybe I'll leave it to the professionals...

**This is a tiny pitfall!**
Take care to not prefix your internal links with your domain, or else they will be treated as external. To link internally, use this pattern:

```markdown
An internal link to the [about page](/about/)
```

## h2 Heading

### h3 Heading

#### h4 Heading

Muffin bonbon jujubes cheesecake chupa chups shortbread ice cream cotton candy cake. Jelly-o biscuit dessert danish dessert pastry tootsie roll lemon drops gingerbread. Cheesecake donut marzipan sweet roll icing muffin halvah. Dragée donut cake biscuit pie carrot cake sesame snaps jelly-o gummi bears.

Soufflé topping shortbread lemon.

## hr

---

## Typographic replacements

**The replacement converts this input:**

```markdown
(c) (C) (r) (R) (tm) (TM) +-
and so on.. and so on... and so on..... AND SO ON???????.....
WTF!!!!!! How many exclamation marks are you going to use????????????
,, -- ---
"double quotes" and 'single quotes'
```

**To this:**

(c) (C) (r) (R) (tm) (TM) +-
and so on.. and so on... and so on..... AND SO ON???????.....
WTF!!!!!! How many exclamation marks are you going to use????????????
,, -- ---
"double quotes" and 'single quotes'

## Emphasis

**This is bold text**
_This is italic text_
~~Strikethrough~~

## Blockquote

> Cheesecake donut marzipan sweet roll icing muffin halvah. Dragée donut cake biscuit pie carrot cake sesame snaps jelly-o gummi bears. Cotton candy cookie croissant fruitcake.

## Lists

### Unordered lists

- Create a list by starting a line with `+`, `-`, or `*`
- Another item

### Ordered lists

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

## Code

Syntax highlighting

```css
.back-top-top {
  padding: 10px;
  background: white;
  margin-top: 110vh;
  position: sticky;
  bottom: 0;
}

/* by David Darnes */
```

## Tables

| Technology | Fun fact                                                                                                                                    |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| HTML       | HTML (Hypertext Markup Language) was created by Sir Tim Berners-Lee in 1991 as a way to structure and link documents on the World Wide Web. |
| CSS        | It's called "cascading" because styles can cascade down from parent elements to their children, allowing for inheritance and overriding.    |
| JavaScript | TypeError: null is not an object                                                                                                            |

## Links

[Read all those articles](https://moderncss.dev/)
Autoconverted link https://every-layout.dev/ (enabled via linkify)

## Emojis

**Literal:**
🤩 💯 💚 👻 👾

**Classic markup:**
:cry: :poop: :fire: :laughing: :christmas_tree:
([A reference for emoji markup](https://gist.github.com/rxaviers/7360908))

**Shortcuts (emoticons)**:
:-) :-( 8-) ;) :-P

## mark

==Marked text==

## Footnotes

Footnote 1 link[^first].
Footnote 2 link[^second].

[^first]:
    Footnote **can have markup**
    and multiple paragraphs.

[^second]: Footnote text.

\*[HTML]: Hyper Text Markup Language

## Images

Consider that `src` is already prepended in the settings.

![Close-up with unfocused background of a vibrant large blue butterfly gracefully perched on a delicate flower amidst lush green grass](/assets/images/gallery/asturias-4.jpg)

{%- css "local" -%}
  {%- include 'css/table.css' -%}
{%- endcss -%}
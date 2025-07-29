<meta charset="UTF-8">
<head>
<link rel="icon" href="./fave.ico">
</head>

<script details="Dynaload Module Reject List">
AppReject = {};
AppReject.modules = [
    'ozville/live-page-dot.js'
];
/*
    'core/tigg.js' ,
    'core/registrar.js'
    'core/legends.js'
    'core/thor.js'
    'core/grok-pass.js'
    'gems/cls-again.js'
    'edit/editables.js'
    'edit/editable-checklists.js'
    'edit/quick-table-edits.js'
    'ozville/dottify.js'
    'dba/debbie.js'
*/
</script>

<script src="http://dave-legacy/42/api/core/dynaload.js"></script>
<script src="http://dave-legacy/yogi/api/todo.js"></script>

<style>
@import url("http://dave-legacy/42/style/header-dots-small.css");
@import url("http://dave-legacy/42/style/ozville/dot-42px.css");
@import url("http://dave-legacy/42/style/ozville/balloon-override.css");
@import url("http://dave-legacy/42/style/yogi/home-dot.css");
@import url("http://dave-legacy/yogi/style/todo.css");
</style>

<style>
body { margin-bottom : 42vh; }
textarea:hover {
    color      : black;
    background : lightgreen;
}
textarea:focus {
    color      : mintcream;
    background : midnightblue;
}
h1, blockquote {
    background : transparent;
}
h1 {
    color : gold;
    text-shadow : 0px 0px 21px black;
}
blockquote {
    color : var( --darko );
}
h1, h2, h3 {
    margin-top : 2.42ch;
}
h1, h2, h3,
nav, 
blockquote,
figure {
    text-align : center
}
</style>

<header>
<nav dots="🔘" center>
⋄ <a class="dot" href="./" title="🗃️ Workspace">🗃️</a>
⋄ <a class="dot" href="http://dave-legacy/42/dots/dot.snagger-dev-notes.html" title="🏠 Home">🏠</a> 
⋄ <a class="dot" href="http://dave-legacy/42/dots/dot.cloud9.html"  title="⛅ Cloud 9">⛅</a>
⋄ <a class="dot" href="http://dave-legacy/42/dots/dot.amigas.html"  title="📕 X3A™ Notebook">📕</a>
⋄ <a class="dot" href="http://dave-legacy/42/dots/dot.snagger.html" title="🪁 Icon Snagger">🪁</a>
⋄ <a class="dot" href="http://dave-legacy/rt/Keisha/Kashawna.html"  title="🐩 Kashawna">🐩</a>
⋄
</nav>
</header>

<script>
    const AppState = {};
    AppState.title =
    document.title = "Icon Snagger Notes";
  </script> <script>
    const AppKeys = {
        tikey : "ee90d376-717f-4698-9754-70d07a2de174"
        // MS Whiteboard for this App
,       wbkey : "7e5ff9fb-26b3-4c0e-83c6-265ce71d70b9"
        // MS Notebook for this App
,       nbkey : "A698F7622548FA93!s3c165235bee441789477874797892397" 
        // Grok Chat for this App
,       aikey : "1903141909637541947"
    };
</script>


<!---[[ App Logo ]]-->

<figure style="text-align : center">
<img src="./fave.ico" width="142">
<span style="font-size : 128px">&nbsp;Icon Snagger</span>
</figure>

---


<!---[[ App Description ]]-->

# Dev Notes

> 2025-JUN-26 <br>
> WBKEY : 2e40f77f-4bfa-43ff-90bb-8a97feb4cc9a <br>
> This document is about coding choices for the Snagger.

- [Whiteboard](https://whiteboard.office.com/me/whiteboards/2e40f77f-4bfa-43ff-90bb-8a97feb4cc9a)


## Bandwidth and extra whitespace

I keep code pretty during dev time. This enhances readability. We get
rid of this issue on release with a minimizer.


## Memoization and short lines

I'm old school. I learned on a 40-column (later 80) Cathode Ray Tube
monitor. I prefer short lines everywhere. Furthermore, liberal use of
memoization and lots of small, single-purpose functions make bug fixes
at scale much easier. Yes, these pollute the namespace. However, there
are manglers and/or obfuscators for that.


## Anthropomorphic names / Acronyms

Get used to them 😉. After 46 years, I've come to use mnemonics that
help me remember what's what (and save typing).


## Overkill on information

Everything has a purpose. It may not be clear here, but each choice has
been made painstakingly over time. That said, suggestions are always welcome.


## Inline Modules

This is temporary ~ a dev-time convenience. Most of the bloat will go away
once these inline styles and scripts are extracted and appropriate
preprocessing tools are used (minifiers, etc).


## Keys

Lots of those for various resources. `TiGG` (Tiny GUID Gen) for our
custom stuff. Others that follow the `PSK` pattern are also referenced
by key alone (`PSK` = _Provider, Splitter, and Key_ paradigm). Lots of 
`PSK` tools exist. Examples include `Earl`, `Earline`, and `Shorty`. 

<aside>
    Providers and Splitters for these Keys are maintained elsewhere.
</aside>


## Ⓢⓨⓢⓣⓔⓜ 𝟜𝟚™

> WBKEY : b2ee9f23-b5cd-4210-a252-306c829205a0

This is the larger ecosystem that contains and supports apps like this
one. `TiGG`, `Legends`, `Thor`, and many more modules are components of
this ecosystem.

- [Whiteboard](https://whiteboard.office.com/me/whiteboards/b2ee9f23-b5cd-4210-a252-306c829205a0)


## Ⓧ⓷Ⓐ™

> WBKEY : 7e5ff9fb-26b3-4c0e-83c6-265ce71d70b9

This is a new system that builds on `Ⓢⓨⓢⓣⓔⓜ 𝟜𝟚`. It's an acronym (of sorts)
for __Transcenders: Three Amigas__. I've added one _Amiga_ : `Jubilee`. `Quark`
and `Tigger` are potential future additions.

- [Whiteboard](https://whiteboard.office.com/me/whiteboards/7e5ff9fb-26b3-4c0e-83c6-265ce71d70b9)

---

# TODO

I need to locate all the TODO items located in various
other editions on various hosts.

Since localStorage is partitioned by domain, persistent
state various depending on the URL path used to access
the page.

Notes exist in various places. These need to be gathered
up, collated and merged.

- Editor tab size should be 4.
- Show Dot Menus any time a URL is dropped into the page.
- Same for creating a random menu.
- Hide Dots when Editor is Visible.
- Need way to drag all dots simultaneously, just like icons can.
- Need hotkey to toggle Dot Menu visibility.
- When joining dots into a menu, ONLY join single dots into the menu being hovered over.

---

> Last Update: 2025-JUN-27




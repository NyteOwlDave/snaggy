
<head>
<meta charset="utf-8">
<!--
<script src="http://dave-legacy/42/api/core/dynaload.js"></script>
-->
<script>
document.title = "Icons Snagger Help";
</script>
<script src="./../../api/editables.js"></script>
<style>
@import url("http://dave-legacy/stereogram/docs/style/docs.css");
body {
    background : url("./blue-duct.jpg");
    background-size : 100vw;
}
header {
    height : 68px;
    line-height : 30px;
}
h1 {
    margin-top : 64px;
}
hr {
    border : none;
}
u1, ol,
h1, h2, h3, h4,
table, pre, blockquote, article {
    background : rgba(245, 255, 250, 0.888);
}
article {
    padding : 15px;
    border-radius : 0.42ch;
}
h1, h2, h3, h4 {
    text-align : center;
    border-radius : 0.42ch;
    padding : 5px;
}
li {
    padding : 5px;
}
</style>
</head>

<header>
<nav>
⋆ <a href="./" title="🗃️ Workspace">🗃️</a>
⋆ <a href="http://dave-legacy/stereogram/app/snagger/help/manual.html" title="🏠 Home">🏠</a> 
⋆ <a href="./dev-notes.html" title="🧑‍💻 Dev Notes">🧑‍💻</a> 
⋆ <a href="http://dave-legacy/42/dots/dot.cloud9.html" title="⛅ Cloud 9">⛅</a>
⋆ <a href="http://dave-legacy/42/dots/dot.amigas.html" title="📕 X3A™ Notebook">📕</a>
⋆
</nav>
</header>

# Standard Hotkeys

> The following hotkeys are defined:

| Modifier  | Key     | Purpose |
|-----------|---------|---------|
| CTRL      | F1      | Show Help |
| CTRL      | F2      | Toggle Gold Aura |
| CTRL      | F3      | Toggle Origin Marker |
| CTRL      | F4      | Close App |
| CTRL      | F5      | Gather All Menus Into Viewport |
| CTRL      | F6      | Diagnostic Dump |
| CTRL      | F7      | Examine Hot Keys |
| CTRL      | F8      | Examine Script Details |
| CTRL      | F9      | Save App State |
| CTRL      | F10     | Toggle Editor View |
| ALT       | Scroll Lock | Toggle Compass Lock |
| ALT       | Page Up | Merge all Menus into One |
| ALT       | Page Down | Split all Dots into Menus |
| ALT       | Insert | Insert Random Menu |
| ALT       | M | Tile Icons and Recenter Canvas |
| ALT       | O | Recenter Canvas at Origin |
| ALT       | S | Save Icon as PNG or Dot Menu as JSON |
| ALT       | T | Delete Icon or Dot Menu |
| ALT       | X | Align Menu X |
| ALT       | Y | Align Menu Y |


# Editor Hotkeys

The following hotkeys are defined:

| Modifier  | Key     | Purpose | Notes |
|-----------|---------|---------|-------|
| CTRL      | F10     | Toggle Editor View  |
| ALT       | Enter   | Run Script          |
| ALT       | Insert  | Create Popup Window |
| ALT       | Delete  | Delete Popup Window | 1 |
| ALT       | D       | Download Editor Contents |
| ALT       | F       | Fetch Editor Contents    |
| ALT       | K       | Show Cache Keys          |
| ALT       | I       | Examine Script Details   |
| ALT       | Q       | Show Module Content      | 2 | 

### Notes

1. This seems to be broken.
2. Hilite module name in editor first.

---


# Navigation

<article>
<p>
Icon Snagger uses a vast <b>virtual space</b> that allows panning in two dimensions.
</p><p>
With such a large space to move around in, it's easy to get
lost.
</p><p>
There are a couple of gadgets that are useful for navigating.
</p><p>
The first is the red <b>origin marker</b>. If you see this flashing 🔴 red dot, it means you're close to the centerpoint of the virtual space. We'll talk more about this in a later
section.
</p><p>
The other helpful gadget is the 🧭 <b>compass</b>. This is a pointer that indicates the relative direction to the
origin marker. This also has it's own section.
</p>
</article>

### <i class="si-arrows"></i> Panning

<article>
<p>
To move around in virtual space, just right-click on any empty area of the screen and drag. During panning, the compass tracks the location of the origin marker, so it's easier to find.
</p>
</article>

### 🔴 Origin Marker

<article>
<p>
The 🔴 <b>origin marker</b> moves as you pan around. It's possible 
to move so far away from this marker that it's no longer visible.
</p><p>
You can also toggle the 🔴 <b>origin marker</b> on and off, so if 
you're having trouble finding it there are a few helpful things you 
can do.
</p><p>
The first thing to try is to use to hotkey combination to 
toggle visibility. This is <i class="si-keyboard"></i> <kbd>CTRL+F3</kbd>.
</p><p>
Another thing to try is to <b>double click</b> on 
the 🧭 <b>compass</b>.
</p><p>
Double-clicking on the 🔴 <b>origin marker</b> or the
🧭 <b>compass</b> performs two functions. It snaps back 
to the origin and it aligns all icons in rows and columns.
</p><p>
The <i class="si-keyboard"></i> <kbd>ALT+O</kbd> hotkey combination
has the same effect as the double-clicks described above.
</p><p>
The 🧭 <b>compass</b> can also be hidden. To toggle 
compass visibility,
use the <i class="si-keyboard"></i> <kbd>ALT+SCRLCK</kbd> hotkey combo.
That's the <kbd>ALT</kbd> key and 
the <kbd>Scroll Lock</kbd> key.
</p>
</article>

### 🧭 Compass

<article>
<p>
As mentioned above, the 🧭 <b>compass</b> tracks 
the 🔴 <b>origin marker</b> position.
</p><p>
You can toggle its visibility with 
the <i class="si-keyboard"></i> <kbd>ALT+SCRLCK</kbd> hotkey combo.
</p><p>
You can also <b>double-click</b> on it to snap back to the
origin and align icons in rows and columns.
</p>
</article>

---


# Working with Icons

<article>
<p>
Icon Snagger's primary role is capturing images
from the internet. These images are automatically
scaled to the ideal size for icons. Specifically,
images are scaled to 256 x 256 pixels.
</p><p>
Image capture is done by drag-drop. The source can
be any app that offers the capability to drag images
into another app. Examples include browser tabs and
operating system explorer apps.
</p><p>
Once an Icon has been captured, it can be dragged around
in the virtual space. It can also be downloaded to the
local file system or deleted.
</p><p>
Icons held in application memory are preserved between
sessions until manually deleted. They can be downloaded
multiple times if desired.
</p><p>
To <b>download</b> an Icon, over over it with the mouse pointer
and use the <i class="si-keyboard"></i> <kbd>ALT+S</kbd> hotkey 
combination. In this instance, the <b>S</b> stands for "save".
</p><p>
To <b>delete</b> an Icon, over over it with the mouse pointer
and use the <i class="si-keyboard"></i> <kbd>ALT+T</kbd> hotkey 
combination. In this instance, the <b>T</b> stands for "trash".
</p><p>
Icons are not guaranteed to be visible at any given time. If
you pan away from the area where icons exist, the viewport
will appear empty. As discussed earlier, options are provided
for snapping back to the origin and for arranging icons in rows and
columns within the viewport.
</p>
</article>

---


# Working with Dot Menus

<article>
<p>
(pending)
</p>
</article>

---


# Using the Editor

<article>
<p>
(pending)
</p>
</article>

---


# Using Popup Windows

<article>
<p>
(pending)
</p>
</article>

---


# Preserving Data

<article>
<p>
(pending)
</p>
</article>

---


> Last Update : 2025-JUN-26

<script>
addEventListener( 'load', () => { 
    editables( 'td'  );
    editables( 'pre' );
    editables( 'h1'  );
} );
</script>



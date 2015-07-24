CSS
=======

Use dash-cased class names
---------------------------

It's consistent with CSS property naming convention

```css
.some-class-name {}
```

Do not use ID's for styling
-----------------------------

ID's are not modular and quickly run into specifity issues.  
It's better to leave them for JS identifiers, and only use class names for styling.

Namespace all class names to avoid collisions
---------------------------------------------

Usually company initials

```css
.ns-sidebar {}
```

Namespace with module prefix
-----------------------------

```css
.ns-admin-sidebar {}
```

Use HTML hierarchy when possible
---------------------------------

```css
.ns-admin-sidebar > header {}
```

No cascading (?)
-----------------

See <https://youtu.be/VkTCL6Nqm6Y?t=24m19s>

No overriding (?)
-----------------

See <https://youtu.be/VkTCL6Nqm6Y?t=24m19s>


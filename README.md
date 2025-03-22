# Console.js

Read console calls on your mobile with this simple tool.

---

## Contents

- [Description](#description)
- [Import](#import)
- [Activate](#activate)
- [State](#state)

---

## Description

Have a front-end console capture tool, to check errors in your mobile

Simply add 'true' to a console param in the URL and it's done.

---

## Import

You can host on your server and call it inside the `<head>` tag:

```html
<script src="console.js"></script>
```

Or you can import from a third-party (GitHub) inside the `<head>` tag:

```html
<script src="https://jonnypaes.github.io/console.js/console.js"></script>
```

---

## Activate

Simply add `?console=true` at the end of the URL and you will trigger the console.

```html
https://jonnypaes.github.io/console.js/?console=true
```

[Try it here](https://jonnypaes.github.io/console.js/?console=true)


---

## State

### Done ✅
- Show file content inside a virtual object
- Highlights the line inside the virtual object
- Capture logs from header and body

### Partially Done ⚠️
- Error stack parser kinda buggy
- Fix odd behavior of touch API (move)

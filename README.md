# bootish
A small simple cloud powered anti-boot "reCaptcha" that use generic boot restrictions to block them.

[Demo](https://bootish.genois.tk/exemple/)

**BETA** - Just for testing for now. there are many improvement to comme. this is just a fast release. I did that in 2 hours... Design to work without jquery. Add it after for the formating with bootstrap.

## Installation

Add the validation script.
```
<div id="bootish-container">Loading...</div><script src="https://bootish.genois.tk/l.js"></script>
```

## How it work (for now)

The remote script create an iFrame on a remote origin where we validate that's not a boot. The user can click it or nagivate with is keybord to it.

The form action and submit btn are disabled.

When the validation is done, the form is "unlocked".

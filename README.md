# bootish
A small simple cloud powered anti-boot "reCaptcha" that use generic boot restrictions to block them.

[Demo](https://bootish.genois.tk/exemple/)

**BETA** - Just for testing for now. there are many improvement to comme. this is just a fast release. I did that in 2 hours... Design to work without jquery. Add it after for the formating with bootstrap.

## Installation
1- Set the ID `bootish-form` to the form

2- Add the validation script.
```
<div id="bootish-container">Loading...</div><script src="https://bootish.genois.tk/l.js"></script>
```

## How it work (for now)

The ID `bootish-form` is use to block form validation in native javascript.

The remote script create an iFrame on a remote origin where we validate that's not a boot.

When the validation is done, the form is "unlock".

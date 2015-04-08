YOML
====

YOML is a dead simple XML dialect.

It was designed with efficiency in mind, allowing it to be
learned quickly, and stay super lightweight.

The most important element is `<yo>`. It can contain an
arbitrary number of child `<yo>` elements. Think of it as an
HTML `<div>`.

To contain more information, you can also set a special
attribute on any `<yo>`: `yo="yo"`. With this nice addition
you will be able to express almost anything you want in seconds!

Here's a basic "Hello world" expressed in YOML:

```xml
<?xml version="1.0" encoding="UTF-8"?>

<yo>
	<yo></yo>
	<yo yo="yo"></yo>
	<yo yo="yo">
		<yo></yo>
		<yo yo="yo"></yo>
	</yo>
</yo>
```

Try it
------

You will find an XML schema within this repo, wich you can use
to validate your awesome yoml documents!

[Fiddle around here](http://www.utilities-online.info/xsdvalidation/?save=a73b0143-6f86-484f-b61a-e815f6948b6b-xsdvalidation).

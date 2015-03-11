# Double Lines

(for Markdown)

You might not be confused by "I should press Enter twice to make a paragragh", but what about "Press Enter once cannot make a line break"?

I have to adopt to this, so just turn line break to paragraph instead, you can use the single line of code below:

```javascript
text = text.replace(/(^|[^\n])\n([^\n]|$)/g, "$1\n\n$2");
```

For:

```javascript
var text = 'This is line 1\n' +
           'This is line 2\n' +
           'This is line 3\n';
```

It turns to be:

```
This is line 1

This is line 1

This is line 1
```

And it's good enough to be a paragrah as soon as you need. :wink:

> One line of code, Change the hell world.


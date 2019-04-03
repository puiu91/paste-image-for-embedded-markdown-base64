# paste-image-for-embedded-markdown-base64

A small utility that will generate a base64 encoded image string with a markdown reference.

## Use

Copy and paste an image from memory onto the html page.

## Example

**1.** Embed the base64 image to the document (ideally, at the end of the document)
```markdown
[abc]:data:image/png;base64,iVBORw0KGgoA...
```

**2.** Refer to embedded base64's named reference of abc
```markdown
![abc] lorem ipsum dolor
```

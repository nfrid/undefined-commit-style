# undefined commit style

by _Nick Friday_ aka _undefined_

## Description

That's how the perfect commits must look!!

### Motivation

I wanted a useful but good looking and human-readable commit style.
I couldn't find one. So I created one by myself. That's all, I think...

### Examples

```commit
[fix#readme] a bit - wrong links

README.md had some bad links. Now it hasn't.

Link to "foo/bar/e.md" was misspeled as "foo/bark/e.md"
Link to "foo/bark/e.md" was misspeled as "foo/bar/e.md"

!WARNING! You may need to change paths on config files!!
```

## Commit structure

All the commits must look like this:

```commit
[type#scope] weight - title

(optional) *Short description of the commit*

(optional) *Full description with details*

(optional) *Warnings*
```

## TODO

- [x] Develop the actual style
- [ ] Add some wholesome examples (1/?)
- [ ] Add normal description
- [ ] Describe in details each structure element undefined commit style
- [ ] Develop some strict keyword dictionaries as examples

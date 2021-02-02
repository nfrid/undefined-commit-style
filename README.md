# undefined commit style

by _Nick Friday_ aka _undefined_

## Description

That's how the perfect commits must look!! (in my very important opinion)

### Motivation

I wanted a useful but good looking and human-readable commit style.
I couldn't find one. So I created one by myself. That's all, I think...

### Why best

Welp, cuz it's more readable for me and clear. You will not clog your head with
the stuff you shouldn't know. You can tell what is commit about without actually
reading it.

Another good thing is that you can filter and search exact types or scopes.
Yes, by regex. If you can't use it or you think it isn't awesome to use it,
you're wrong. You shouldn't do any coding in your life in that case. Go work
to fucking McDonalds.

### Examples

```commit
[fix@readme] wrong links

README.md had some bad links. Now it hasn't.

Link to "foo/bar/e.md" was misspeled as "foo/bark/e.md"
Link to "foo/bark/e.md" was misspeled as "foo/bar/e.md"

!WARNING! You may need to change paths on config files!!
```

```commit
[feat@layouts/login] animations

Wholesome animations on login layout.
```

```commit
[add@docs/build] gentoo

Building instructions for those who use Gentoo (as if they don't know lol)
```

## Commit structure

All the commits should look like this:

```commit
[type@scope] what

(optional) *Short description of the commit*

(optional) *Detailed description*

(optional) *Warnings*
```

### Type

Type is... the type of commit!

It can be whatever you think it can. I prefer use these types:

- `add` for adding some shit
- `rm` for removing some shit
- `feat` for adding some features to already existing shit
- `mod` for modifying some shit but it isn't actually a feature
- `fix` for fixing some shit
- `ref` for refactoring some shit
- `clean` for cleaning some shit
- `fuck` when I can't actually tell what the fuck I am commiting

### Scope

Scope is just where.

It can have a hierarchical structure and should tell where does shit happen.

### What

A very short message of what is actually commiting.

It is more like keywords or tags than actual message. Main goal of its existence
is to provide a minimal ability to tell what's this commit about. So it'll not
clog your mind. Only important, keywords-like information.

### Short description

Well, it is that one REAL commit message where you actually describe what happened.

It should not be more than one sentence. No details, no specifics. Maybe a little
jokes. :)

### Detailed description

That is where you write your novel. All the shit you wanna say. No restrictions.
Pure freedom.

Joking aside. It should be clear and detailed message only with things that matters.
Even I wouldn't joking in this part. Well, maybe just a bit.

### Warnings

!WARNING! That shit will blow up if you will try and build it to prod!!!

When there are some breaking changes it makes sense to make a note to others,
isn't it? This section is needed exactly for that!

!BREAKING CHANGES! or !READMEFIRST!, you can make it to any warning you want.
Surely, you should use them only if you have something to tell to other devs.

## License

Well. It kinda have a GNU license.

BUT. I actually ain't a mad man. It just a fucking text. A formal style.
You can do whatever you want, even tell that it is you who created this kind
of shit. Nobody really care about it. About fucking obvious variant of a text
we write as commit messages. Really.

Why tf I don't just delete the license you ask? Well, cuz it looks kinda cool.
That's it.

Have a nice day and fuck you. 👽

## TODO

- More examples.
- Regex filters. Maybe some shell scripts.
- Snippets.

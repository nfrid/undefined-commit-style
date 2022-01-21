# undefined commit style

by _Nick Friday_ aka _undefined_

## Description

That's how the perfect commits must look!! (in my very important opinion)

### Motivation

I wanted a useful but good looking and human-readable commit style.
I couldn't find one (as a truЪ spec). So I created one by myself. That's it.

### Why best

Well, cuz it's more readable for me and clear. You will not clog your head with
a stuff you don't care about.

Also you can filter and search exact types or scopes by regex, for example.

### Examples

```commit
fix@readme: wrong links

README.md had some bad links. Now it hasn't.

Link to "foo/bar/e.md" was misspeled as "foo/bark/e.md"
Link to "foo/bark/e.md" was misspeled as "foo/bar/e.md"

!WARNING! You may need to change paths on config files!!
```

```commit
feat@layouts/login: animations

Wholesome animations on login layout.
```

```commit
?add@docs/build: gentoo

Building instructions for those who use Gentoo (as if they don't know lol)
```

```commit
feat: new shit
```

```commit
!feat@config(big): new syntax

!WARNING! READ README OR YOU WILL DIE
```

## Commit structure

All the commits should look like this:

```commit
*tag*type@scope(how): what

(optional) *Short description of the commit*

(optional) *Detailed description*

(optional) *Warnings*
```

It's okay to exclude some elements of a commit's head when they are not necessary.
Just make it look informative and clear enough at the same time.

### Tag

Tags can mark something. Importance of the commit for example. Here's sign spec
I would use:

- `!` is the importance tag aka this thingy will fuck you if you don't pay attention
- `?` is the you-should-read-it-maybe-cuz-it-may-be-interesting tag
- `$` is the shit tag aka I just made a little something here you don't really need to know
- `=` is the git tag on stuff only for a SVC shit

### Type

Type is... the type of commit!

It can be whatever you think it can. I prefer use these types:

- `add` for adding some
- `rm` for removing some
- `feat` for adding some features to already existing
- `mod` for modifying some but it isn't actually a feature
- `fix` for fixing some
- `ref` for refactoring some
- `clean` for cleaning some
- `upd` for updating some
- `fuck` when I can't actually tell wtf am I commiting

### Scope

Scope is just where.

It can have a hierarchical structure and should tell where does that happen.

### How

It can be the size or any other characteristic. Just to be clear in huge..ness?
of the commit.

Can be any words or symbols. I don't like specs in that kind of stuff.

### What

A very short message of what is actually being commited.

It is more like keywords or tags than an actual message. Main goal of its existence
is to provide a minimal ability to tell what this commit is about, so it doesn't
clog your mind. Only important, keywords-like information.

### Short description

Well, it is that one REAL commit message where you actually describe what happened.

It should not be more than one sentence. No details, no specifics.

### Detailed description

That is where you write your novel. All the stuff you wanna say. No restrictions.
Pure freedom.

Jokes aside. It should be clear and detailed message only with things that matter.
Even I wouldn't joking in this part. Well, maybe just a little.

### Warnings

!WARNING! That stuff will blow up if you will try and build it to prod!!!

When there are some breaking changes it makes sense to make a note to others,
doesn't it? This section is needed exactly for that!

!BREAKING CHANGES! or !READMEFIRST!, you can make it to any warning you want.
Surely, you should use them only if you have something to tell to other devs.

## License

Well. It kinda has an MIT license.

BUT. I ain't actually a mad man. It's just a text. A format. A convention.
You can do whatever you want, even tell that you're the author. Nobody really
cares about an obvious variant of a text we write as commit messages.
I would be glad if someone makes it popular, even if my name would be lost in history.

Have a nice day. 👽

## TODO

- More examples.
- Regex filters. Maybe some shell scripts.

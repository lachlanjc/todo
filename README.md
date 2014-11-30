todo
====

[@holman](https://github.com/holman) wrote a [very simple script](https://github.com/holman/dotfiles/blob/master/bin/todo) for to-do lists over the command line. I've added a little more to it:

- Creates .md files, so the to-do files are useful for writing
- See a list of your to-do's with `$ todo-list`

# Installation

Copy the `todo` and `todo-list` files into your `bin`. Customize them if you like.

# Usage

```
$ todo water-the-garden
```

Todo will create `water-the-garden.md` on your `~/Desktop`. You can use these Markdown files for writing documents associated with those tasks. Isn't that amazing?

When you're done with the task, archive the file on your computer or just delete it (GUI or `$ rm`, of course).

To see a list of everything you need to do:

```
$ todo-list
```

Ta-dah! You'll see this:

```
$ todo-list
To-do List
----------
water-the-garden.md
call-mom.md
take-a-nap.md
```

That's really all there is to it.

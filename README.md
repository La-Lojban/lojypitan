# lojypitan
Write Lojban instead of Python.

Goals
-----
- Lojban-only syntax (no English words)
- Minimal verbosity
- Serious/practical use

Python Compatibility
- Probably start with Python3
- Make it as seamless as possible (CPython, extending/embedding, Cython, etc.).  We eventually want this incorporated into the upstream Python distribution, as an alternative syntax that the syntax-checker will accept, but not sure if this is possible.  It's at least far more work than just writing a script/grammar that crudely translates from one language to another.

Lojban Specifics
- We may have to approach the implementation of this in layers.
- We'll first start mostly Python, and _then_ Lojban.  We're not trying to reenact the _semantics_ of Lojban in Python; rather, we're trying to write Python, just as usual, but practice Lojban while doing so, if possible/reasonable.
- A later stage may involve more incorporating Lojban than the old Python.  For example, write a language that appeals to natural language programming.

Functionality
- One major and initial influence for lojypitan is lolpython.  It works by _converting_ LOLCODE into Python.  I don't think this is scalable, and/or largely compatible with current and future projects, which is a desirable goal.  This _is_, an approach, though.

ro x mu:

   prina x

Keywords
--------
False: jitfa

None: noda

True: jetnu

and: e

as: ca

assert: xusra

break: porpi

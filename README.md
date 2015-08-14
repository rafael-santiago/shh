# shh

This code is an old ioccc entry of mine. Unfortunately I have never won with this.
Maybe this code does not implement a rather useless task...

Anyway, this code implements a vocal reducer. It works with ``WAVE`` format only and
the audio must be encoded as ``PCM`` (no compression, raw sound).

## How to build it?

Originally I had used ``Make`` but it sucks in several ways.

Now in order to build it you need [Hefesto](https://github.com/rafael-santiago/hefesto.git).

After install ``Hefesto`` on your system being inside ``shh src`` subdirectory just type
the following command on ``shell``:

        doctor@TARDIS:~/shh/src# hefesto

A subdirectory ``bin`` will be created and inside it you probably will find an ``elf``
named ``shh``.

I think now with ``Hefesto`` here you can build ``shh`` on Windows. If it worked for you,
please let me know.

## How to use shh?

The usage of ``shh`` is pretty straightforward:

``shh <.wav input file path> <.wav output file path>``

Note that is important avoid using instrumental songs with ``shh`` otherwise this vocal reducer
will not work....

and...

# Please do not promote karaoke parties... I beg you!!

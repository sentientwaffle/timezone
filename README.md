# Timezone

A handy time zone converter.

# Installation
You need Ruby. This is developed on 1.9.2, but it should work on 1.8.7.
It depends on [`TZInfo`](http://tzinfo.rubyforge.org/).

Then, just add the `timezone` file to your path.

# Usage
Convert a time from one zone to another.

    $ timezone 4:30 MST PDT
    3:30
    $ timezone 3:30 PDT MST
    4:30

The _to_ time zone defaults to your system's current time zone.

    $ timezone 3:30 PDT
    4:30


# License
See LICENSE.


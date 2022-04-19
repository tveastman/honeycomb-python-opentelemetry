I threw this example together to demonstrate that honeycomb.io
is not receiving events when I use version 1.11.0 of the python
SDKs.

The only difference between these two projects is that the one
that works is pinned to version 1.10.0. And the one that isn't
working is using version 1.11.0, released yesteday (19 April 2022)

In 1.11.0, the dataset does get created, but no actual spans
(events? data? I'm new to this so I don't know the terminology)
ever get created.



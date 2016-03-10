

# This repository has been moved to https://github.com/miloyip/rapidjson #

Rapidjson is an attempt to create [the fastest](http://code.google.com/p/rapidjson/wiki/Performance) JSON parser and generator.

  * Small but complete. Supports both SAX and DOM style API. SAX parser only a few hundred lines of code.
  * Fast. In the order of magnitude of strlen(). Optionally supports SSE2/SSE4.2 for acceleration.
  * Self-contained. Minimal dependency on standard libraries. No BOOST, not even STL.
  * Compact. Each JSON value is 16 or 20 bytes for 32 or 64-bit machines respectively (excluding text string storage). With the custom memory allocator, parser allocates memory compactly during parsing.
  * Full [ RFC4627](http://www.ietf.org/rfc/rfc4627.txt) compliance. Supports UTF-8, UTF-16 and UTF-32.
  * Support both in-situ parsing (directly decode strings into the source JSON text) and non-destructive parsing (decode strings into new buffers).
  * Parse number to int/unsigned/int64\_t/uint64\_t/double depending on input
  * Support custom memory allocation. Also, the default memory pool allocator can also be supplied with a user buffer (such as a buffer allocated on user's heap or programme stack) to minimize allocation.

As the name implies, rapidjson is inspired by [rapidxml](http://rapidxml.sourceforge.net/).

## News ##

  * 16 Nov 2012: [version 0.11](http://code.google.com/p/rapidjson/downloads/detail?name=rapidjson-0.11.zip) is released.

[ChangeLog](http://code.google.com/p/rapidjson/wiki/ChangeLog)
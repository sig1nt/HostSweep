# Host Sweep

A Burp plugin to test URLs and see if they are vulnerable to Host header
poisoning. This vulnerability is mostly harmless actually, but it's usually a
good indicator of other issues in a code base.

Also a first crack at writing Burp extensions, and a genesis of possible ideas
for a Burp Extender utilities library.

## Building

```
gradle build
```

Make sure that your jar is compliant with all of Burp's various rules, your
mileage may vary on the actual usefulness of this thing.

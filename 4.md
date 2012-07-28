# awk

`awk` stands for "Aho, Weinberger, Kernighan", the last names of its three
creators. It does *not* stand for [Andrew W.K.](http://youtu.be/EqOTU89cgC4),
though I often pretend it does. It is an advanced text-stream-processor, similar
to `sed`; though it is often used to write more complex programs than `sed`.

Disclaimer: I've never used `awk` for anything other than one-liners.

## Challenges

* Pipe "one two three" to `awk` and print the first word using the `$n` record
  separator.

* Pipe "one two three" to `awk` and print the second word using the `$n` record
  separator.

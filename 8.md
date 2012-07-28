# Pipes

Pipes are integral to good unix-fu. They pass the output of one program to the
input of another (or, to put it more technically, they pass STDOUT to STDIN).
Since plain text is the common language of UNIX, being able to filter text
streams is very powerful.

Example:

    # prints "hello i am Jack, my name is Jack"
    echo "hello i am gabe, my name is gabe" | sed 's/gabe/Jack'
    # shows the first 13 files/directories in the current directory
    ls -1 | head -13

## Challenges

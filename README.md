# md-wrap-code

Command line utility that wraps markdown code blocks

## Usage

```
Usage: main [option] [input]

  Command line utility that wraps markdown code blocks

  Options:

    -h, --help            output usage information
    -V, --version         output the version number
    -n, --newline [n]     Wrap with new line(s). Defaults to 1.
    -s, --space [n]       Wrap with space(s). Defaults to 1.
    -t, --tab [n]         Wrap with tab(s). Defaults to 1.
    -c, --custom <chars>  Wrap with custom string.

```

## Example

```
npm install -g md-wrap-code

cat foo.md | md-wrap-code -n > wrapped.md
```

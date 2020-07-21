# SYNOPSIS

Display a colorized line of text

# USAGE

    say [options] [tokens]

# OPTIONS

    --help    | -h      display this help text
    --version | -v      display version information
                -n      do not output a newline
                -e      enable string escapes
                -E      disable string escapes (default)

# COMMAND TOKENS

Colors are controlled with the following command tokens:

    Clear
    Reset
    Bold
    Dim
    Italic
    Underline
    Blink
    Invert
    Hidden
    Default

    Black
    Blue
    Cyan
    Green
    Magenta
    Red
    White
    Yellow

    Bold_Black
    Bold_Blue
    Bold_Cyan
    Bold_Green
    Bold_Magenta
    Bold_Red
    Bold_White
    Bold_Yellow

    On_Black
    On_Blue
    On_Cyan
    On_Green
    On_Magenta
    On_Red
    On_White
    On_Yellow

    On_Bold_Black
    On_Bold_Blue
    On_Bold_Cyan
    On_Bold_Green
    On_Bold_Magenta
    On_Bold_Red
    On_Bold_White
    On_Bold_Yellow

    # 256 colors
    Ansi_XXX
    On_Ansi_XXX

# INSTALLATION

    curl -o $HOME/bin/say https://raw.githubusercontent.com/sysread/say/master/say && chmod +x $HOME/bin/say

# AUTHOR

Jeff Ober <sysread@fastmail.fm>

# COPYRIGHT AND LICENSE

Copyright (c) 2020 Jeff Ober

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

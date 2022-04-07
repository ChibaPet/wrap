# wrap

Buggy. Do not use.

Update, 2022-04-07: db92f065ecd337f44fb679b6c52aa49dec839b6b makes this
less buggy. Upgrading recommendation to "maybe use".

I don't know why that commit hash didn't turn into a link. Oh well.
Sometimes magic doesn't work.

To use this, you can make use of, for instance, vi's operate-on-paragraph:

    !}wrap

Attaching this to tab in .vimrc:

    map <tab> !}wrap<cr>

You can do a similar thing in .exrc for nvi - control-shift-v to paste a
literal tab and type your tab, and the literal tab should work, but I'm
failing to get it to work left-hand-side. You can type a literal enter and
that'll work right-hand-side of the map. Something to explore.

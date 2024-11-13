# st - simple terminal v0.9.2
My st configuration.\
Patches applied:
- Scrollback
    - Reason: by default st does not support scrolling inside of the terminal
    - [st-scrollback-20210507-4536f46.diff](http://st.suckless.org/patches/scrollback/st-scrollback-20210507-4536f46.diff)
    - [st-scrollback-mouse-20220127-2c5edf2.diff](http://st.suckless.org/patches/scrollback/st-scrollback-mouse-20220127-2c5edf2.diff)
    - **Note**: I removed shift mask, so scrolling is done without pressing shift key.
- Wide glyph
    - Reason: some times icons are partially displayed in nvim-web-devicons plugin for example
    - [st-glyph-wide-support-20220411-ef05519.diff](http://st.suckless.org/patches/glyph_wide_support/st-glyph-wide-support-20220411-ef05519.diff)
- Gruvbox
    - Reason: my eyes struggle with the default colorscheme
    - [st-gruvbox-dark-0.8.5.diff](http://st.suckless.org/patches/gruvbox/st-gruvbox-dark-0.8.5.diff)
    - **Note**: I'm using hard contrast background color from [gruvbox.nvim]()
- Bold is not bright
    - Reason: looks better
    - [st-bold-is-not-bright-20190127-3be4cf1.diff](http://st.suckless.org/patches/bold-is-not-bright/st-bold-is-not-bright-20190127-3be4cf1.diff)

You can also find all the applied patches in patches_applied directory.

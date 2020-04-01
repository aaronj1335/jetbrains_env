`jetbrains_env`
=============

A sad substitute for a proper `.vimrc`.

![android studio color scheme](https://raw.githubusercontent.com/kaushikgopal/jetbrains_env/master/jetbrains_env_screenshot.png)

## Instructions

    for f in fileTemplates keymaps templates colors codestyles; do ln -s `pwd`/$f ~/.AndroidStudioAndroidX-compose/config/; done
    ln -s `pwd`/options/editor.xml ~/.AndroidStudioAndroidX-compose/config/

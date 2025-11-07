# dotfiles
This repositry contains files that makes the typical customization I would love to do with my Arch installation. This repository is primary aimed at my everyday use. Feel free to copy or modify any files. As a beginner, I am first time interested in ricing. I love using I3 window manager, Picom and NVIM.

# Directories
<table>
    <tr>
        <th>Directory</th>
        <th>Details</th>
    </tr>
    <tr>
        <td>.wallpaper</td>
        <td>
            Files containing wallpapers. Can be used by <code>feh</code> utility to set background image. Typically these files are installed to <code>~/.wallpapers/</code>
        </td>
    </tr>
        <td>xinitrc</td>
        <td>
           Contains configuration files for X11 startup. Programs which will get executed on running <code>startx</code>. Customized configuraitons should be placed in <code>~/.xinitrc</code> file.
        </td>
    </tr>
    <tr>
        <td>I3</td>
        <td>
            These files contains the customized cofiguration files for <code>i3-wn</code>. These files are typically place in <code>~/.config/i3/</code> directory.
        </td>
    </tr>
    <tr>
        <td>
            VIMRC
        </td>
        <td>
            This file is only applicable for Windows so, please be sure to understand the changes introduced before copying or replacing your files. Though, there are not much changes other than setting the tabstop to 2. (This is the one I like), Disables the generation of undofiles and backups. Typically bloats directories I think. So, I disabled them.
        </td>
    </tr>
</table>

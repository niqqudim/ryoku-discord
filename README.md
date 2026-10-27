# Ryoku discord theme
ink and paper

![Chatl](https://i.postimg.cc/q7YFjX3s/image.png)

![Settings](https://i.postimg.cc/SKdhdWFT/image.png)

![Friends](https://i.postimg.cc/nrmKszcN/image.png)

## install

### any client that supports theme files (vencord / vesktop...)

1. download [`theme/ryoku.theme.css`](theme/ryoku.theme.css)
2. put it in the themes folder and enable it
3. if you want you can also easily customize the theme by opening the file and modifying the variables 

the theme file only has the settings needed, the rest is imported

### templates

[`theme/templates`](theme/templates) has ready versions of the theme file with different settings already changed: light mode, calm (less animation and art), a matugen template and more. install them the same way as `ryoku.theme.css`, and only enable one at a time. see [the templates readme](theme/templates/README.md) for screenshots of each.

<table>
  <tr>
    <td align="center"><strong>light</strong><br><img src="https://i.postimg.cc/KYd9nG6g/image.png" width="300" alt="ryoku light"></td>
    <td align="center"><strong>calm</strong><br><img src="https://i.postimg.cc/P57Kjfrm/image.png" width="300" alt="ryoku calm"></td>
    <td align="center"><strong>calm light</strong><br><img src="https://i.postimg.cc/gJFDxMhB/image.png" width="300" alt="ryoku calm light"></td>
  </tr>
</table>

### matugen (colours from your wallpaper)

[`ryoku-matugen.theme.css`](theme/templates/ryoku-matugen.theme.css) is a [matugen](https://github.com/InioX/matugen) template, not a ready theme, so don't load it in discord as is.

1. put it in your matugen templates folder, for example `~/.config/matugen/templates/`
2. add it to your matugen config:
   ```toml
   [templates.ryoku-discord]
   input_path = "~/.config/matugen/templates/ryoku-matugen.theme.css"
   output_path = "~/.config/vesktop/themes/ryoku-matugen.theme.css"
   ```
3. run matugen on your wallpaper, then enable the rendered `ryoku-matugen.theme.css` in vesktop
4. for a light scheme, add `--light-mode: on;` to the first `body` block of the template


## credits

- [system24](https://github.com/refact0r/system24) and [midnight](https://github.com/refact0r/midnight-discord) by refact0r a lot of the code is based on these themes 
- death's-head moth: [Image by pikisuperstar on Magnific](https://www.magnific.com/free-vector/hand-drawn-death-moth-drawing-illustration_49611618.htm#fromView=search&page=1&position=17&uuid=f43cb916-dd55-40b9-b672-1d1ce8c4de50&track=ais_hybrid&query=Free+svg+moth)

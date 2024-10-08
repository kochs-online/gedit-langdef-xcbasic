# gedit-langdef-xcbasic
## Gnome Editor Language Definition for [XC=BASIC](https://github.com/neilsf/XC-BASIC3/)

Language Definition file to add syntax highlighting for XC=BASIC in gedit (and other editors using GtkSourceView)

### Installation

To install copy the language definition file to `~/.local/share/gtksourceview-${GSV_API_VERSION}/language-specs/`. Create this directory if not existing.

Pre-installed language definition files can be found in `${PREFIX}/share/gtksourceview-${GSV_API_VERSION}/` (where `${PREFIX}` can be `/usr/` or `/usr/local/`).

For more details please refer to the official [GtkSource Language Definition documentation](https://gnome.pages.gitlab.gnome.org/gtksourceview/gtksourceview5/lang-reference.html).

### Custom MIME type

Although not necessary for the definition file to work you might want to add the new custom MIME type `text/xc-basic` for XC=BASIC source files that is referenced in the Language Definition to your MIME type database.

Detailed information on how to do this under GNOME can be found in the [GNOME Help for adding custom MIME types](https://help.gnome.org/admin/system-admin-guide/stable/mime-types-custom-user.html.en)

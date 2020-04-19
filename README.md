# GitHub Repos for Hosting Images of Gist Pages

This Github repos is used to host image files that are used/embedded in your Gist pages.

## Usage

To include them in html/md pages, use this URL structure:

```html
https://raw.githubusercontent.com/<github_user_name>/<repos_name>/<branch>/<image_path_in_repos>
```

For instance, the following URL embeds an images stored in this repos under `Nvim-R-Tmux/nvim-version-toggle.png`:

```html
https://raw.githubusercontent.com/tgirke/my_gist_images/master/Nvim-R-Tmux/nvim-version-toggle.png
```

The result looks like this:

<center><img title="Nvim-R-Tmux" src="https://raw.githubusercontent.com/tgirke/my_gist_images/master/Nvim-R-Tmux/nvim-version-toggle.png" ></center>

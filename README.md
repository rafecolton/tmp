# /tmp

For when you just want to take some notes!

Quickly iterate on notes using markdown.  Basic UI provided with
Twitter Bootstrap

## Setup

0. Fork
0. Clone fork
0. Install [caddy](https://github.com/mholt/caddy)
0. `caddy`

## Usage

0. Create or edit [Markdown](https://daringfireball.net/projects/markdown/) files in `static/`
0. View notes by visiting [http://localhost:9000](http://localhost:9000)

## Other

To tell git to ignore changes to `static/includes/menu-custom.html` when
adding custom pages to the nav, use the following command:

```bash
git update-index --assume-unchanged static/includes/menu-custom.html
```

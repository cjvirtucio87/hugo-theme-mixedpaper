# Mixedpaper for Hugo

Mixedpaper is a minimalist Hugo theme for writers and bloggers.

## Feature

- Clean and minimalist
- SCSS styling
- Syntax highlighting
- Styled Archives
- Minimal vanilla js

## Installation

Navigate to the root directory of your Hugo site and clone this repository.

```
git clone https://github.com/wayjam/hugo-theme-mixedpaper.git themes/mixedpaper
```

Refer to the [Hugo docs](https://gohugo.io/getting-started/quick-start/) for more information.

## Configuration

#### Hightlight

To enable theme-defined highlighting style, please set `pygmentsUseClasses = true` in `config.toml`

#### Archives

```toml
[[menu.main]]
	name = "Archives"
	identifier = "archives"
	url = "/archives/"
```

#### Comments

Supported Disqus and Valine now.

```toml
disqusShortname = ""
```

OR

```toml
[params.comment]
appid = "your-appid"
appkey = "your-appkey"
placeholder = "enjoy~"
avatar = "mm"
pageSize = 10.0
visitor = false
recordIP = true
highlight = true
meta = "nick,mail"
requiredFields = "nick,mail"
```

#### More

Refer to `exampleSite/config.toml` for more example.

## License

Released under the [MIT License](https://github.com/wayjam/hugo-theme-mixedpaper/blob/master/LICENSE).

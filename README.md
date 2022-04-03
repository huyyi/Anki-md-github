# Anki-md-github
This is an anki card template with markdown support using github markdown style.

## Preview


## How to use 
1. Install `Anki-KaTeX-Markdown` addon.
2. Download `_github-markdown.css` and place it to account media folder.
3. Append following scripts to card style
  ```css
  .markdown-body {
	box-sizing: border-box;
	min-width: 200px;
	max-width: 980px;
	margin: 0 auto;
	padding: 45px;
}

@media (max-width: 767px) {
	.markdown-body {
	    padding: 15px;
	}
}
```

## Reference
[Jwrede/Anki-KaTeX-Markdown](https://github.com/Jwrede/Anki-KaTeX-Markdown)

[sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

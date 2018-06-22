# monaco.ttf

The original monaco.ttf improved: add some special characters (which are from "DejaVu Sans Mono")

In my work environment, I need connect to Linux system from Windows system remotely using SecureCRT or Putty, and edit files using VIM tools. So I need one beautiful font in SecureCRT / Putty.

In windows system, there are some original fonts are beautiful, for exemple "Consolas", but they can't support some special characters, for example: ▸, ↪, ⌴. Because they are original fonts in my Windows, I don't want to modify them.

I get "Monaco" from the web. It is tiny and beautiful. But it also can't support those special characters.

So I add the characters by myself and share it.

## CDN
You can use rawgit.com as a CDN:
https://cdn.rawgit.com/todylu/monaco.ttf/d258639b/monaco.ttf

## Web usage
Copy this code into your CSS stylesheet:
  
```css
@font-face {
  font-family: 'Monaco';
  src: url('https://cdn.rawgit.com/todylu/monaco.ttf/d258639b/monaco.ttf') format('truetype'):
  font-weight: normal;
  font-style: normal;
}
/* [...] */
font-family: 'Monaco', monospace;
```
  
  

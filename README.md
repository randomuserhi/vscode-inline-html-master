Fork of https://github.com/pushqrdx/vscode-inline-html

# minor fixes

- code completion for same line: 
```
html`<di...` // used to not code complete
```

- css & style code completion with substitutions: 
```
css`
${something} {
  color: #000; /* used to not code complete */
}
`
```
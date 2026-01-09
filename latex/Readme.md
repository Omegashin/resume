# Setup

## MacOS

1. Install [MacTeX](https://www.tug.org/mactex/)
2. Install perl module: `sudo cpan File::HomeDir`
3. Verify with `which latexindent` and `latexindent -v`
4. Update VS Code settings with:

```json
"latex-workshop.formatting.latex": "latexindent"
"latex-workshop.formatting.latexindent.path": "/Library/TeX/texbin/latexindent"
```

5. Try formatting `resume.tex` and watch for any errors
6. Open `resume.pdf` to make sure it renders correctly

## Windows

1. Install [TeX Live](https://tug.org/texlive/windows.html)
2. Make sure PATH was updated, then reboot Windows
3. Update VS Code settings with:

```json
"latex-workshop.formatting.latex": "latexindent"
"latex-workshop.formatting.latexindent.path": "C:\\texlive\\2025\\bin\\windows\\latexindent.exe"
```

4. Try formatting `resume.tex` and watch for any errors
5. Open `resume.pdf` to make sure it renders correctly

# Todo

- Organize GitHub profile, add placeholders for projects
  - Android app
  - ChatGPT App
- Make a lean Skills list
- Rewrite points in STAR, XYZ and CAR format
- Tools to make points concise
  - https://hemingwayapp.com/
  - https://quillbot.com/
  - https://languagetool.org/paraphrasing-tool
-

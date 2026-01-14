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

- Organize GitHub profile
-
- Add ChatGPT App project
- Add missing terms

  - Testing
  - APIs
  - Architecture
  - Observability
  -

- Tools to make points concise
  - https://hemingwayapp.com/
  - https://quillbot.com/
  - https://languagetool.org/paraphrasing-tool

# Methods for bullet points

If you have strong metrics → lean XYZ.
​
If space is tight → CAR (Challenge/Action/Result in one line).
​
If the story is complex or leadership-heavy → compressed STAR (implied Situation/Task, explicit Action/Result).

Generic high‑impact bullet pattern (covers all three ideas):

“[Action verb] [what you built/improved] to solve [challenge or goal], resulting in [quantified result or clear outcome].”

https://github.com/matiassingers/awesome-readme

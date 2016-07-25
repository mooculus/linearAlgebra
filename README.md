# A Ximera Xandbox

This is a sandbox for exploring Ximera.

1. Edit [first.tex](./first.tex).  As you edit, you can use `pdflatex` to see the PDF version of your handout.
2. Go to the [Ximera website](http://ximera.osu.edu/), login, click on your name, click on Profile.  Generate a key and secret.
3. Open a SageMathCloud [terminal](../terminal.term) and use `cd ~/xandbox` to make sure you're in the xandbox directory.
4. If you have never done so before, type `xake login` and paste in your key and secret.
5. Commit and push your changes to GitHub by running
```bash
git add first.tex
git commit -m 'Here I type a description of the edits'
git push
```
6. Build the HTML files with `xake bake`
7. Publish your worksheet to ximera.osu.edu with `xake publish`
8. Append `/first` to the URL that xake prints out.

Ximera is still a work in progress and there may be bugs.  Please e-mail Jim Fowler or add an [issue](https://github.com/kisonecat/ximera/issues) to the bug tracker.
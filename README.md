# A Ximera Xandbox

This is a sandbox for exploring Ximera.

1. Edit [first.tex](./first.tex).  As you edit, you can be running `pdflatex` to see the PDF version of your handout.
2. Open a SageMathCloud [terminal](../terminal.term) and use `cd ~/xandbox` to make sure you're in the xandbox directory.
3. Commit and push your changes to GitHub by running
```bash
git add first.tex
git commit -m 'Here I type a description of the edits'
git push
```
4. Build the HTML files with `xake bake`
5. Publish your worksheet to ximera.osu.edu with `xake publish`
6. Visit http://ximera.osu.edu/course/xandbox/xandbox/master/first to see your worksheet in action.

Ximera is still a work in progress and there may be bugs.  Please e-mail Jim Fowler or add an [issue](https://github.com/kisonecat/ximera/issues) to the bug tracker.
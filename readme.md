# Documentation

This is a test repository meant to illustrate documentation possibilities on github.

The `feature_importance` folder contains a markdown file.
The `model_evaluation` folder contains an rst file.

Note that 'vanilla markdown' (if there is such a thing...) does not usually support LaTeX-like syntax for expressing and rendering math. Yet, more and more rendering engines - [including GitHub's](https://github.blog/2022-05-19-math-support-in-markdown/) - support LaTeX-like features.

[Rst supports math expressions by default](https://docutils.sourceforge.io/docs/ref/rst/mathematics.html).

# Table of contents

* [feature importance](https://github.com/kklein/documentation_test/blob/main/feature_importances/page1.md)
* [model evaluation](https://github.com/kklein/documentation_test/blob/main/model_evaluation/page1.rst)

# How does working on it look like?
## Markdown files
On the one hand, one would be able to edit the source text directly on GitHub. GitHub provides a 'Preview' tab:

![alt text](/screenshot_github.png)

On the other hand, one would be able to edit the markdown files locally. Some plug-ins should be able to illustrate all of the markdown and most of the LaTeX features. E.g. see [marp extension for VS Code](https://github.com/marp-team/marp-vscode):

![alt text](/screenshot_vs_code.png)

Other plug-ins, e.g. [Markdown + Math](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath) seem to offer similar functionalities. I'd hope similar tooling exists for other editors and IDEs.

## RST files
* GitHub also support editing and preview for rst files.
  * Yet, the preview doesn't render math properly, see [issue](https://github.com/github/markup/issues/83) :(
* It should be even easier to find extensions rendering rst files since it is more of a 'standard' setup than markdown + LaTeX.

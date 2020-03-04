# Setting up Git extension for JupyterLab

Finally, let's look at how Git works inside JupyterLab. While there are many visual interfaces, this one integrates with your Notebook workflow.

![](../.gitbook/assets/jupyter-lab.gif)

Git for JupyterLab is an official Jupyter Lab extension. To get it working, open your Anaconda Prompt \(or Terminal on macOS\) and type in:

```text
pip install --upgrade jupyterlab-git
jupyter lab build
```

You can also do this from a Jupyter cell an

```text
!pip install --upgrade jupyterlab-git
!jupyter lab build
```

From there, just simply close and reopen Jupyter Lab! There should be a panel on the left called "Git" now. To `git add` a file, just hover your cursor on the file in the "Git" panel and click on the up button on the left.

When you're reading to make a commit, type in a commit message and then the check box. That's it! If you want to push changes to a remote repository, relevant buttons will also appear if you configured them like shown in [the first part of this section](1.2-getting-started-with-git.md#getting-started-with-collaborating).

{% embed url="https://github.com/jupyterlab/jupyterlab-git" %}


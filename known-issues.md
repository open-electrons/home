### Git Submodules

You have a theme you added as a git submodule and, you recently re-cloned your project where in this case
the submodule needs to be re-downloaded as well.

This can be done with:

```
git submodule init
git submodule update
```

If this step is not done, then running hugo serve on the local machine will result in "PAGE NOT FOUND ERROR"
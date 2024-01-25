# homebrew-pgplot
This is a Homebrew formula for PGPLOT. [homebrew recently removed pgplot for a Licence issue](https://github.com/Homebrew/discussions/discussions/533).
This is a local backup (+ minor modificaiton) of the latest pgplot formula just before being removed.
You can tap this repository and install pgplot.

## How do I install these formulae?
`brew install kazuakiyama/pgplot/pgplot`

Or `brew tap kazuakiyama/pgplot` and then `brew install pgplot`.

Don't forget to add paths for PGPLOT. For instance, you can add the following line to your ~/.bashrc_profile or ~/.zprofile files (and remember to source the file to update your current session):

```bash
PGPLOT_DIR=`brew --prefix pgplot`/share
if [ -e $PGPLOT_DIR ]; then
  export PGPLOT_DIR=$PGPLOT_DIR
  export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:$PGPLOT_DIR
fi
```

## Contact
If you find any issues related to this brew formula, please post [issues](https://github.com/kazuakiyama/homebrew-pgplot/issues) in this github repository or directly contact me ([Kazu Akiyama](https://sites.mit.edu/kazuakiyama)). I would note that, as **I'm no longer an active user of PGPLOT**, I do not frequently check the repository or its compatibilities in the latest macOS versions or mac hardware.
If you do not see my replies in GitHub issues, please consider directly reaching out to me.

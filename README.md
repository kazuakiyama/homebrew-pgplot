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

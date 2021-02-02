# This is a repo for the first graded assignment.

The repository contains a working manuscript about the challenges of finding realistic solutions to climate change.

I renamed the data files from `.txt` to `.csv` to reflect their content better. I used the following code for the opperation:

```bash
$ for old in *.txt
> do
> new=$(basename "$old" .txt).csv
> #echo "old -> new names: $old -> $new" 
> git mv $old $new
> done
```
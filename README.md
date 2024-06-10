# git-current-lines-by-author

Use this script to count the number of lines of code at the current state of the repo that blames back to each user.

Or, use `git-current-lines-by-author-by-extension` to count by file extension.

# git-lines-contributed

Use this script to quickly count the net lines added and removed by each contributor.

```bash
git-lines-contributed
```

Example Output:

```
Administrator
-----------------
485
Removed: 624
Total Lines Contributed: -139
```



Bash script to print the lines contributed to a repository by each user.

To use the script, copy the [git-lines](https://raw.githubusercontent.com/JakeThurman/git-lines/master/git-lines) file into the desired directory and run the command **git-lines** from the command line. 

## Between Revisions

You can also specify a commit range to search by providing it as an argument: 

```bash
git-lines 2.0_release..3.0_release
```


## CSV

If you want a csv export use the git-lines-csv version

```bash
git-lines-contributed-csv > contributor-stats.csv
```

Example Output:

| Name | Added | Removed | Net |
|---|---|---|---|
| Administrator | 485 | 624	| -139 |

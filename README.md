# git-lines

Use this script to count the net lines added and remove by contributer.

```bash
git-lines
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
git-lines-csv > contributer-stats.csv
```

Example Output:

| Name | Added | Removed | Net |
|---|---|---|---|
| Administrator | 485 | 624	| -139 |

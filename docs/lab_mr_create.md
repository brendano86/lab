## lab mr create

Open a merge request on GitLab

### Synopsis

Creates a merge request (MR created on origin master by default)

```
lab mr create [remote [branch]] [flags]
```

### Options

```
      --allow-collaboration    Allow commits from other members
  -a, --assignee string        Set assignee by username
  -h, --help                   help for create
  -l, --label strings          Add label <label>; can be specified multiple times for multiple labels
  -m, --message strings        Use the given <msg>; multiple -m are concatenated as separate paragraphs
      --milestone int          Set milestone by milestone ID (default -1)
  -d, --remove-source-branch   Remove source branch from remote after merge
  -s, --squash                 Squash commits when merging
```

### SEE ALSO

* [lab mr](lab_mr.md)	 - Describe, list, and create merge requests

###### Auto generated by spf13/cobra on 13-Dec-2019

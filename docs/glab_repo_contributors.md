## glab repo contributors

Get an archive of the repository.

### Synopsis

Clone supports these shorthands
- repo
- namespace/repo
- namespace/group/repo


```
glab repo contributors <command> [flags]
```

### Examples

```
$ glab repo archive profclems/glab
$ glab repo archive  // Downloads zip file of current repository
$ glab repo clone profclems/glab mydirectory  // Clones repo into mydirectory
$ glab repo clone profclems/glab --format=zip   // Finds repo for current user and download in zip format

```

### Options

```
  -h, --help           help for contributors
  -f, --order string   Return contributors ordered by name, email, or commits (orders by commit date) fields. Default is commits (default "zip")
  -s, --sort string    Return contributors sorted in asc or desc order. Default is asc
```

### SEE ALSO

* [glab repo](glab_repo.md)	 - Work with GitLab repositories

###### Auto generated by spf13/cobra on 13-Aug-2020
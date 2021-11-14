# shell
shell

```shell
alias path="type path; echo $PATH | tr : '\n' | sort"; export path
```

```shell
(shoot--cds-stage--cds-b-sus:default)➜  cds-tk-edp-proxy git:(feature/CXCDS-2224-load-tests) ✗ path
path is an alias for type path; echo /usr/local/opt/node@14/bin:/Users/d069924/.pyenv/bin:/Users/d069924/.sdkman/candidates/scala/current/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Library/Apple/usr/bin:/Applications/Privileges.app/Contents/Resources | tr : '\n' | sort

/Applications/Privileges.app/Contents/Resources
/Library/Apple/usr/bin
/Users/d069924/.pyenv/bin
/Users/d069924/.sdkman/candidates/scala/current/bin
/bin
/sbin
/usr/bin
/usr/local/bin
/usr/local/opt/node@14/bin
/usr/sbin
```

```shell
# enable debug shell commands
set -x

# disable
set +x
```

```shell
man bash
```

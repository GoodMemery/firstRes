# firstRes

这是  项目介绍

git命令:

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo
$ git init
Initialized empty Git repository in C:/Users/Administrator/Desktop/new Firtdemo/
.git/

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

Did you mean this?
        add

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git add .

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git commit

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Administrator@ZG-20150323LXKL.(
none)')

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git commit -am "第一个测试仓库"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Administrator@ZG-20150323LXKL.(
none)')

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git config --global "1621403107@qq.com"
error: invalid key: 1621403107@qq.com

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git config --global user.email  "1621403107@qq.com"

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git config --global user.name "GoodMemery"

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git commit -am "第一个测试仓库"
[master (root-commit) e78e9d0] 第一个测试仓库
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt

Warning: Your console font probably doesn't support Unicode. If you experience s
trange characters in the output, consider switching to a TrueType font such as C
onsolas!

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from


Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git remote add origin git@github.com:GoodMemery/firstRes.git

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git push origin master
The authenticity of host 'github.com (192.30.253.113)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? y
Please type 'yes' or 'no': y
Please type 'yes' or 'no': yes
Warning: Permanently added 'github.com,192.30.253.113' (RSA) to the list of know
n hosts.
Counting objects: 3, done.
Writing objects: 100% (3/3), 230 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To git@github.com:GoodMemery/firstRes.git
 * [new branch]      master -> master

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$ git pull  git@github.com:GoodMemery/firstRes.git
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From github.com:GoodMemery/firstRes
 * branch            HEAD       -> FETCH_HEAD
Updating e78e9d0..d447afc
Fast-forward
 README.md | 3 +++
 1 file changed, 3 insertions(+)
 create mode 100644 README.md

Administrator@ZG-20150323LXKL MINGW32 ~/Desktop/new Firtdemo (master)
$

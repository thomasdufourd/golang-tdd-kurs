我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Go lang TDD kurs

Install go lang:
```
brew install go
```

Hjelp deg selv litt med noen ENVs i ```~/.bashrc```:

```bash

# .bashrc : 
export GITHUB_USER="mitt_github_brukernavn"
export GOPATH="~/src/gopath"
export GOROOT="/usr/local/opt/go/libexec"
alias gogo="cd $GOPATH/src/github.com/${GITHUB_USER}" 


# sett opp go kommandoen på PATH:
# You may wish to add the GOROOT-based install location to your PATH:
export PATH="$PATH:/usr/local/opt/go/libexec/bin:$GOPATH/bin"


$ source ~/.bashrc
$ mkdir -p ${GOPATH}/github.com/${GITHUB_USER}
$ gogo # skal flytte deg til din github brukers mappe under Go sources.

$ go get github.com/${GITHUB_USER}/${REPO}
```

Simple:
```
$ go test -v .../.
```

Fancy:

```
$ go get github.com/smartystreets/goconvey
goconvey
```


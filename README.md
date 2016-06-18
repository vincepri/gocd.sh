# gocd
Quick change directory in GOPATH

### Install
```bash
mkdir -p ~/.gocd/
curl -L https://raw.githubusercontent.com/vinceprignano/gocd.sh/master/script.sh > ~/.gocd/script.sh
echo "source $HOME/.gocd/script.sh" >> ~/.bash_profile
```

### Example
```bash
$ gocd vinceprignano
vinceprignano vinceprignano/example
vincenzo at workspation  ~
$ gocd vinceprignano/example
vincenzo at workspation  ~/src/github.com/vinceprignano/example
```



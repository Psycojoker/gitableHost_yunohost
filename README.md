#gitable-host

## Warning this is still a Work in progess!
#### it might never work!

## YunoHost git repo for webhosting


### use case
- Dick wants to use git to locally edit his static website then use ```git push``` to the remove yunohost server


### Usage
- write static page or something like Pelican, jekyllrb, octopress, Hugo and many many more!
- git remote add origin git@hostname:~/gitsourcecode/
- git commit -a -m "my first commit"
- git push #login with the password you set at install
- server then uses a hook to sync to /home/yunohost.app/gitable/githost/
- 

### does it work yet?
- -No-  kinda, yesh but still beta

Makes use of the following scripts
- post-receive.sh
- Author: "FRITZ Thomas" <fritztho@gmail.com> (http://www.fritzthomas.com)
- GitHub: https://gist.github.com/thomasfr/9691385

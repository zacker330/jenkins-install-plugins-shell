```
cd $JENKINS_HOME
git clone https://github.com/zacker330/jenkins-install-plugins-shell.git
cd jenkins-install-plugins-shell
chmod +x install-plugins.sh jenkins-support
export JENKINS_WAR_PATH=<Jenkins war文件的路径>
./install-plugins.sh < plugins.txt
```

plugins.txt:

```
ansible:1.0
powershell:1.3
```

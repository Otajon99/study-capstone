```
mkdir -p /opt/study-capstone
  273  cd /opt/study-capstone
  274  mkdir -p ansible/{inventory,playbook,roles/app/{tasks,templates,vars}}
  275  touch Jenkinsfile README.md
  276  touch ansible/inventory/lab.ini
  277  touch ansible/playbooks/deploy.yml
  278  touch ansible/roles/app/tasks/main.yml
  279  touch ansible/roles/templates/index.html.j2
  280  touch ansible/roles/app/templates/index.html.j2
  281  tree
  282  yum install -y tree
  283  chown -R jenkins:jenkins /opt/study-capstone/
  284  tree
  285  ls -l
  286  git init
  287  git remote add origin git@github.com:Otajon99/study-capstone.git
  288  git config --global --add safe.directory /opt/study-capstone
  289  chown -R jenkins:jenkins /opt/study-capstone/
  290  git config --global --add safe.directory /opt/study-capstone
  291  git config --global user.email "otajonburxonov99@gmail.com"
  292  git config --global user.name "Otajon99"
  293  cat /var/lib/jenkins/.ssh/id_ed25519.pub 
  294  pwd
  295  vi ansible.cfg
  296  vi ansible/inventory/lab.ini
  297  ansible-inventory app --graph
  298  tree
  299  vi ansible/playbook/deploy.yml
  300  ansible-playbook ansible/playbook/deploy.yml --syntax-check
  301  vi ansible/roles/app/tasks/main.yml 
  302  ansible-playbook ansible/playbook/deploy.yml --syntax-check
  303  ansible-playbook ansible/playbook/deploy.yml
  304  vi ansible/roles/app/tasks/main.yml 
  305  ssh deploy@jenkins-client
  306  ssh-copy-id deploy@jenkins-client
  307  ssh deploy@jenkins-client
  308  ansible-playbook ansible/playbook/deploy.yml
  309  tree
  310  vi ansible/roles/app/templates/index.html.j2 
  311  ansible-playbook ansible/playbook/deploy.yml
  312  vi ansible/roles/app/tasks/main.yml 
  313  ansible jenkins-client -m ping
  314  curl http://jenkins-client
  315  vi ansible/roles/app/tasks/main.yml 
  316  vi ansible/roles/app/templates/index.html.j2 
  317  ansible-playbook ansible/playbook/deploy.yml
  318  vi ansible/roles/app/tasks/main.yml 
  319  vi ansible/roles/app/templates/index.html.j2 
  320  ansible-playbook ansible/playbook/deploy.yml
  321  vi Jenkinsfile 
  322  ls -l
  323  chown -R jenkins:jenkins /opt/study-capstone/
  324  ls -l
  325  git add *
  326  git commit -m "learning CICD apache webserver"
  327  git push
  328  git remote add main https://github.com/Otajon99/study-capstone
  329  git push
  330  git push --set-upstream main master
  331  git remote add main git@github.com:Otajon99/study-capstone.git
  332  git push
  333  git push --set-upstream main master
  334  sudo -u jenkins git push --set-upstream main master
  335  sudo -u jenkins git push --set-upstream origin main
  336  sudo -u jenkins git push --set-upstream main
  337  git push -u origin main
  338  git branch -M main
  339  git push -u origin main
  340  git remote add origin git@github.com:Otajon99/study-capstone.git
  341  git push -u origin main
  342  ls -l
  343  sudo -u jenkins git push --set-upstream main
  344* sudo -u jenkins git 
  345  sudo -u jenkins git push --set-upstream origin main
  346  ls -l
  347  vi Jenkinsfile 
  348  history
```

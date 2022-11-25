# 1. Account GIT
```
ownergit@teramedik.com
teramedik_owner

developergit@teramedik.com
teramedik_developer

qcgit@teramedik.com
teramedik_qc

reviewergit@teramedik.com
teramedik_reviewer
```

# 2. Init git project
```
git init
git remote add origin https://gitlab.com/teramedikMaster/kioskmaster.git
git checkout -b master
git add .
git push -uf origin master
```

# 3. Create log autpull
```
#!/bin/bash
rm /home/renaldi/gitlog-kiosk.log
date > /home/renaldi/gitlog-v5.log
cd /var/www/php74/kioskv2
git pull git@gitlab.com:teramedikMaster/kioskmaster.git >> /home/renaldi/gitlog-kiosk.log 2>>/home/renaldi/gitlog-kiosk.log
```

# 4. Dir LOG 
```
KIOSK : /home/renaldi/gitlog-kiosk.log
V5 MASTER : /home/terakorp/gitlog-v5.log
V5 Integration : /home/terakorp/gitlog-integration.log
V5 Hisys : /home/terakorp/gitlog.hisysv5.log
CE : /tmp/gitlog-master.log
CE DEVEL : /tmp/gitlog-devel.log
```

# 5. Dokumentasi teramobile
```
...
```

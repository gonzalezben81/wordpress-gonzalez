---
ID: 549
post_title: Ubuntu Content
author: ben
post_excerpt: ""
layout: post
permalink: >
  https://www.gonzostats.us/index.php/2018/11/19/ubuntu-content/
published: true
post_date: 2018-11-19 04:38:44
---
  284  pcpl --help
  285  pacpl --help
  286  pacpl -t -r mp3 –bitrate 256 *.wav –delete
  287  pacpl -t crip  mp3 –bitrate 256 *.wav –delete
  288  pacpl -t mp3 /home/ben/Desktop/cdrip –bitrate 256 *.wav –delete
  289  pacpl -t mp3 /home/ben/Desktop/cdrip /home/ben/Desktop/cdrip –bitrate 256 *.wav –delete
  290  for file in *.wav; do $(lame -V0 “$file” “${file%.wav}.mp3”); done
  291  for file in *.cdda.wav; do $(lame -V0 “$file” “${file%.wav}.mp3”); done
  292  pacpl --to mp3 -r -p /home/ben/Desktop/cdrip --outdir /home/ben/Desktop/cdrip
  293  pacpl --to mp3 -r -p 'Kid Rock' 'Cocky' /home/ben/Music/ --outdir /home/ben/Desktop/cdrip
  294  pacpl --to mp3 -r -p /home/ben/MusicKidRock/Cocky --outdir /home/ben/Desktop/cdrip
  295  pacpl --to mp3 -r -p /home/ben/Music/KidRock/Cocky --outdir /home/ben/Desktop/cdrip
  296  q
  297  quit() stop
  298  pacpl --to mp3 -r -p /home/ben/Music/Unknown/Hockeytown --outdir /home/ben/Desktop/cdrip
  299  pacpl --to mp3 -r -p /home/ben/Brian --outdir /home/ben/Desktop/cdrip
  300  pacpl --to mp3 -r -p /home/ben/Desktop/Brian --outdir /home/ben/Desktop/cdrip
  301  pacpl --to mp3 -r -p /home/ben/Desktop/Brian --outdir /home/ben/Desktop/Brian
  302  pacpl --to mp3 -r -p /home/ben/Music/Jay-Z/WatchtheThrone --outdir /home/ben/Desktop/cdrip
  303  pacpl --to mp3 -r -p /home/ben/Music/JayZ/WatchtheThrone --outdir /home/ben/Desktop/cdrip
  304  pacpl --to mp3 -r -p /home/ben/Music/JayZ/WatchtheThrone/ --outdir /home/ben/Desktop/cdrip
  305  cd /home/ben/Music/JAYZ
  306  ls
  307  pacpl --to mp3 -r -p /home/ben/Music/JAYZ/WatchtheThrone --outdir /home/ben/Desktop/cdrip
  308  cdparanoia -B
  309  pacpl --to mp3 -r -p /home/ben/Music/Nellyville --outdir /home/ben/Nellyville
  310  pacpl --to mp3 -r -p /home/ben/Music/Nellyville --outdir /home/ben/Music/Nellyville
  311  pacpl --to mp3 -r -p /home/ben/Music/Metallica/Metallica --outdir /home/ben/Music/Metallica/Metallica
  312  pacpl --to mp3 -r -p /home/ben/Music/JAYZ/WatchtheThrone --outdir /home/ben/Music/JAYZ/WatchtheThrone
  313  cd /home/ben/Nirvana
  314  mkdir /home/ben/Nirvana
  315  cd /home/ben/Nirvana
  316  cdparanoia -B
  317  mkdir /home/ben/Bush
  318  cd /home/ben/Bush
  319  cdparanoia -B
  320  vobcopy -b
  321  vobcopy b
  322  cd dvd/sr0
  323  ls
  324  vobcopy b
  325  /dvd/sr0 vobcopy -b
  326  cd dev/sr0
  327  ln /dev/hdb /dev/dvd
  328  ln
  329  ls
  330  /ben/media
  331  cd /home/ben/media
  332  /media/ben
  333  cd /media/ben
  334  ls
  335  vobcopy -b
  336  vobcopy -i
  337  vobcopy
  338  ls
  339  vobcopy -i
  340  ls
  341  /media/ben/HANCOCK_BONUS_DISC
  342  cd /media/ben/HANCOCK_BONUS_DISC
  343  ls
  344  cd /media/ben/HANCOCK_BONUS_DISC/Movies
  345  ls
  346  vobcopy -b
  347  vobcopy
  348  vobcopy -i /home/ben
  349  cd
  350  vobcopy -l -i /dev/sr1
  351  vobcopy -l -i /dev/sr0
  352  cd /home/ben/Desktop
  353  cd
  354  ls
  355  vobcopy -l -i /dev/sr0
  356  cd /home/ben/Desktop
  357  ffmpeg -i Hancock.wmv -s size Hancock.mp4
  358  ffmpeg -i Hancock.wmv  Hancock.mp4
  359  ffmpeg -i Hancock.wmv  Hancock.mkv
  360  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; done
  361  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; done; q; 
  362  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; done
  363  cd /home/ben/Desktop
  364  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; done
  365  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/home/ben/Videos/${f%.wmv}.mp4"; done
  366  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "output/${f%.wmv}.mp4"; done
  367  for f in *.wmv; do ffmpeg -i "$f" -c:v libx264 -crf 18 -c:a aac "${f%.wmv}.mp4"; done
  368  sudo apt-get install ffmpeg w32codecs
  369  apt-get install ffmpeg w32codecs
  370  sudo apt-get install ffmpeg w32codecs
  371  sudo apt-get install w32codecs
  372  sudo apt-get install WinFF
  373  sudo apt-get install WinFF w32codecs
  374  ffmpeg -i Hancock.wmv -b 600 -s 320x240 -ab 128k -vcodec mpeg4 -ab 128 -acodec aac HancockTwo.mp4
  375  ffmpeg -i Hancock.wmv -b 600k -s 320x240 -ab 128k -vcodec mpeg4 -ab 128 -acodec aac HancockTwo.mp4
  376  ffmpeg -i Hancock.wmv -b 600k -s 320x240 -ab 128k -vcodec mpeg4 -ab 128 -acodec aac -strict -2 HancockTwo.mp4
  377  pacpl --to mp3 -r -p /home/ben/Music/IrishXiles/IrishXiles --outdir /home/ben/Music/IrishXiles/IrishXiles
  378  cdparanoia -B
  379  mkdir /home/ben/Desktop/8mile
  380  cd /home/ben/Desktop/8mile
  381  cdparanoia -B
  382  cd /home/ben/Desktop/8mile
  383  cdparanoia -B
  384  cd
  385  mkdir /home/ben/Training
  386  cd /home/ben/Training
  387  cdparanoia -B
  388  sudo apt-get install abcde
  389  abcde
  390  cdparanoia -B
  391  abcde
  392  brasero
  393  brasero
  394  mkdir /home/ben/train
  395  cd /home/ben/train
  396  cdparanois -B
  397  cdparanoia -B
  398  abcde
  399  brasero
  400  mkdir /home/ben/train
  401  cd /home/ben/train
  402  cdparanoia -B -sv
  403  abcde
  404  cd /home/ben/train
  405  cdparanoia -B -sv 5-17
  406  mkdir /home/ben/Desktop/pac
  407  cd /home/ben/Desktop/pac
  408  pacpl --to mp3 -r -p /home/ben/Desktop/pac --outdir /home/ben/Music/Desktop/pac -delete
  409  pacpl --to mp3 -r -p /home/ben/Desktop/pac --outdir /home/ben/Desktop/pac -delete
  410  cd
  411  /mkdir /home/ben/Music/Training
  412  mkdir /home/ben/Music/Training
  413  cd /home/ben/Music/Training
  414  pacpl --to mp3 -r -p /home/ben/Music/Training --outdir /home/ben/Music/Training -delete
  415  cd /home/ben/Desktop/cube
  416  ls
  417  pacpl --to mp3 -r -p /home/ben/Desktop/cube --outdir /home/ben/Desktop/cube -delete
  418  abcde
  419  sudo apt-get install nmap
  420  nmap
  421  iconfig
  422  ifconfig
  423  mkdir /home/Music/WarPeaceIceCube
  424  mkdir /home/ben/Music/WarPeaceIceCube
  425  cd /home/ben/Music/WarPeaceIceCube
  426  ls
  427  pacpl --to mp3 -r -p /home/ben/Music/WarPeaceIceCube --outdir /home/ben/Music/WarPeaceIceCube -delete
  428  pacpl --to mp3 -r -p /home/ben/Music/BetterDayz --outdir /home/ben/Music/BetterDayz -delete
  429  pacpl --to mp3 -r -p /home/ben/Music/3DoorsDown/TheBetterLife --outdir /home/ben/Music/3DoorsDown/TheBetterLife -delete
  430  brasero
  431  sudo ifconfig
  432  sudo apt-get instal cifs-utils
  433  sudo apt-get install cifs-utils
  434  pacpl --to mp3 -r -p /home/ben/Music/MurphyLee/MurphysLaw --outdir /home/ben/Music/MurphyLee/MurphysLaw -delete
  435  q
  436  quit
  437  exit
  438  pacpl --to mp3 -r -p /home/ben/Music/Disturbed/TheSickness --outdir /home/ben/Music/Disturbed/TheSickness -delete
  439  /dev/disk/by-id/ata*
  440  abcde 7
  441  abcde 7 -sv
  442  cdparanoia -B
  443  abcde 7 -sv
  444  abcde 7 --svhistory > history_for_print.txt
  445  abcde 7 
  446  abcde 2
  447  abcde 3-17
  448  pacpl --to mp3 -r -p /home/ben/Desktop/TrainingDay --outdir /home/ben/Desktop/TrainingDay -delete
  449  pacpl --to mp3 -r -p /home/ben/Music/BasedonaTrueStory --outdir /home/ben/Music/BasedonaTrueStory -delete
  450  abcde output:mp3
  451  abcde OUTPUTTYPE="mp3"
  452  abcde 1-18 OUTPUTTYPE="mp3"
  453  abcde 1-12 OUTPUTTYPE="mp3"
  454  abcde
  455  pacpl --to mp3 -r -p /home/ben/Desktop/gottafeelme --outdir /home/ben/Desktop/gottafeelme -delete
  456  vobcopy -b
  457  vobcopy
  458  /dev/sr0 vobcopy
  459  vobcopy /dev/sr0
  460  vobcopy -l
  461  vobcopy -b
  462  vobcopy
  463  vobcopy -d
  464  vobcopy -l
  465  vobcopy -l -i /dev/sr0
  466  vobcopy -d
  467  vobcopy -l
  468  vobcopy -l -i /dev/sr0
  469  sudo apt-get install -y vobcopy
  470  sudo apt-get install -y wodim
  471  wodim --devices
  472  wodim --scanbus
  473  wodim -scanbus
  474  vobcopy -l -i /dev/sr0/
  475  brasero
  476  vobcopy -O
  477  vobcopy -i /dev/sr0
  478  abcde OUTPUTTYPE="mp3"
  479  abcde 1-12, OUTPUTTYPE="mp3"
  480  abcde
  481  ABCDE
  482  abcde
  483  pacpl --to mp3 -r -p /home/ben/Nirvana-Nirvana --outdir /home/ben/Nirvana-Nirvana -delete
  484  abcde 10
  485  abcde
  486  abcde 5-14
  487  pacpl --to mp3 -r -p /home/ben/GreatDepression --outdir /home/ben/GreatDepression -delete
  488  abcde
  489  abcde 13
  490  vobcopy -i /dev/sr0
  491  pwd
  492  cd /home/ben/Music
  493  pwd
  494  cd
  495  ls
  496  cd /usr/bin
  497  ls
  498  cd
  499  cd ./bin
  500  cd ..
  501  pwd
  502  cd ./bin
  503  pwd
  504  cd /usr/bin
  505  cd ./bin
  506  cd
  507  pip3 install nltk
  508  ls ~/udt
  509  ls ~/usr
  510  ls ~/ben
  511  ls -l
  512  ls --all
  513  ls -h
  514  less /etc/passwd
  515  python
  516  pip3 install virtualenv
  517  mkdir projects
  518  cd projects
  519  mkdir hello
  520  virtualenv -p /usr/local/bin/python3 env
  521  virtualenv -p /ben/local/bin/python3 env
  522  virtualenv -p /home/ben/local/bin/python3 env
  523  abcde
  524  ipconfig
  525  iconfig
  526  abcde
  527  vobcopy -i /dev/sr0
  528  vobcopy -l -i /dev/sr0
  529  ffmpeg
  530  ffmpeg -i
  531  sudo apt install dvd decrypter
  532  sudo apt install dvddecrypter
  533  sudo apt install dvd-rip
  534  sudo apt install k9copy
  535  sudo add-apt-repository ppa:tomtomtom/k9copy
  536  sudo apt-get update
  537  sudo apt install k9copy
  538  k9copy
  539  sudo apt-get update
  540  sudo apt-get install ebook-tools
  541  sudo apt-get install ebook-tools
  542  calibre
  543  python
  544  sudo apt-get ebook-tools-dbg
  545  sudo apt-get install ebook-tools-dbg
  546  cd /home/ben/Downloads
  547  ls
  548  ebook-convert BOOK.azw book.pdf
  549  chmod +x kindlepid.py
  550  cd /home/ben/Downloads
  551  chmod +x kindlepid.py
  552  ls
  553  cd /home/ben/Downloads/MobiDeDRM
  554  ls
  555  chmod +x kindlepid.py
  556  kindlepid.py
  557  python kindlepid.py
  558  python kindlepid.py B008A0A0116205T2
  559  cd /home/ben/Downloads
  560  python mobidedrm.py BOOK.azw BOOK.mobi BZUHZKF*KH
  561  cd /home/ben/Downloads/MobiDeDRM
  562  python mobidedrm.py BOOK.azw BOOK.mobi BZUHZKF*KH
  563  python mobidedrm2.py BOOK.azw BOOK.mobi BZUHZKF*KH
  564  python mobidedrm.py BOOK.azw BOOK.mobiBZUHZKF*KH
  565  python mobidedrm2.py BOOK.azw BOOK.mobi BZUHZKF*KH
  566  python mobidedrm.py BOOK.azw BOOK.mobi BZUHZKF*KH
  567  python mobidedrm2.py BOOK.azw BOOK.mobiBZUHZKF*KH
  568  python mobidedrm.py BOOK.azw BOOK.mobiBZUHZKF*KH
  569  python mobidedrm2.py BOOK.azw BOOK.mobi BZUHZKF*KH
  570  python kindlepid.py B008AOAO116205T2
  571  python mobidedrm2.py BOOK.azw BOOK.mobi 531YZWQ*DD
  572  python kindlepid.py B008A0A0116205T2
  573  python kindlepid.py B008 A0A0 1162 05T2
  574  python mobidedrm2.py BOOK.azw BOOK.mobi CCKRCU1*DT
  575  python mobidedrm.py BOOK.azw BOOK.mobiCCKRCU1*DT
  576  python mobidedrm.py BOOK.azw BOOK.mobi CCKRCU1*DT
  577  python mobidedrm2.py BOOK.azw BOOK.mobi 531YZWQ*DD
  578  cd /home/ben/Downloads/DeDRM_plugin
  579  python mobidedrm2.py BOOK.azw BOOK.mobi 531YZWQ*DD
  580  python mobidedrm.py BOOK.azw BOOK.mobi CCKRCU1*DT
  581  python mobidedrm.py BOOK.azw BOOK.mobi file:///home/ben/Downloads/BOOK.azw 
  582  python mobidedrm.py BOOK.azw BOOK.mobi BZUHZKF*KH
  583  python kindlepid.py B008 A0A0 1162 05T2
  584  python kindlepid.py B008A0A0116205T2
  585  python kindlekey.py B008A0A0116205T2
  586  python kindlepid.py B008A0A0116205T2
  587  python mobidedrm.py BOOK.azw BOOK.mobi BZUHZKF*KH
  588  python mobidedrm2.py BOOK.azw BOOK.mobi BZUHZKF*KH
  589  cd /home/ben
  590  cd /home/ben/Desktop
  591  cd /home/ben/Desktop/KindleBooks
  592  python KindleBooks.pyw
  593  pip3 instal python-tk
  594  pip3 install python-tk
  595  sudo apt-get install python-tk
  596  python KindleBooks.pyw
  597  sudo apt-get install pycrypto
  598  python
  599  pip3 install pycrypto
  600  python KindleBooks.pyw
  601  cd /home/ben/Music
  602  ls
  603  mkdir Kramn
  604  rm -r Kramn
  605  mkdir Kram
  606  cd Kram
  607  ls
  608  ffmpeg -i The_Best_Thing.m4a -acodec libmp3lame -ab 256k The_Best_Thing.mp3
  609  ffmpeg -i TheBestThing.m4a -acodec libmp3lame -ab 256k TheBestThing.mp3
  610  ffmpeg -i TheBestThing.m4a -acodec libmp3lame -ab 128k TheBestsThing.mp3
  611  cd Music
  612  cd /home/ben/Music
  613  cd AssassinsCreed
  614  ls
  615  ffmpeg -i TheBlackAngels.m4a -acodec libmp3lame -ab 128k TheBlackAngels.mp3
  616  ffmpeg -i TheBlackAngels.m4a -acodec libmp3lame -ab 256k AssasinsCreedOpen.mp3
  617  cd /home/ben/Music
  618  cd /home/ben/Music/AssassinsCreed
  619  ls
  620  ffmpeg -i BloodRave.opus -acodec libmp3lame -ab 256k BloodRave.mp3
  621  ls
  622  ffmpeg -i BloodRave -acodec libmp3lame -ab 256k BloodRave.mp3
  623  ls
  624  ffmpeg -i BloodIsPumping -acodec libmp3lame -ab 256k BloodIsPumping.mp3
  625  sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6
  626  echo "deb [ arch=amd64,arm64 ] http://repo.mongodb.org/apt/ubuntu xenial/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list
  627  sudo apt-get update
  628  sudo apt-get install -y mongodb-org
  629  sudo service mongod start
  630  cd /var/log/mongodb/mongod.log
  631  mongod
  632  sudo service mongod stop
  633  mongod
  634  sudo service mongod start
  635  ls
  636  exit
  637  pycharm
  638  cd /home/ben/Downloads
  639  ls
  640  ffmpeg -i 'Eminem - Rap God (Explicit).mp4' -acodec libmp3lame -ab 256k Eminem_Rap_god.mp3
  641  ffmpeg -i 'Luis Fonsi - Despacito ft. Daddy Yankee.mp4' -acodec libmp3lame -ab 256k Despacito.mp3
  642  ffmpeg -i 'Enrique Iglesias - Bailando.mp4' -acodec libmp3lame -ab 256k Bailando.mp3
  643  sudo snap install pycharm-community --classic
  644  cd /home/ben/Downloads
  645  ls
  646  ffmpeg -i Black_Honey.mp4 -vn -acodec copy Black_Honey.mp3
  647  ffmpeg -i Black_Honey.mp4 -vn -acodec copy Black_Honey.mp4
  648  ffmpeg -i Black_Honey.mp4 -vn -acodec copy Black_Honey_Audio.mp4
  649  ffmpeg -i Black_Honey_Audio.mp4 -vn -acodec copy Black_Honey_Audio.wma
  650  ffmpeg -i Black_Honey_Audio.wma -vn -acodec copy Black_Honey_Audio.mp3
  651  ffmpeg -i Black_Honey -acodec libmp3lame -ab 256k Black_Honey.mp3
  652  ffmpeg -i Black_Honey.mp4 -acodec libmp3lame -ab 256k Black_Honey.mp3
  653  ffmpeg -i 'Five Finger Death Punch - Wrong Side Of Heave.mp4' -acodec libmp3lame -ab 256k Wrong_Side_Of_Heaven.mp3
  654  ffmpeg -i Five_Finger_Death2_ Punch_ -_ Wrong_Side_Of_ Heaven.mp4 -acodec libmp3lame -ab 256k Wrong_Side_Of_Heaven.mp3
  655  ffmpeg -i Wrong_Side_Of_Heaven.mp4 -acodec libmp3lame -ab 256k Wrong_Side_Of_Heaven.mp3
  656  ffmpeg -i Breaking_Benjamin_I_Will_Not_Bow.mp4 -acodec libmp3lame -ab 256k Breaking_Benjamin_I_Will_Not_Bow.mp3
  657  ffmpeg -i Breaking_Benjamin_Will_Not_Bow.mp4 -acodec libmp3lame -ab 256k Breaking_Benjamin_Will_Not_Bow.mp3
  658  ffmpeg -i Breaking_Benjamin_Will_Not_Bow.mp4 -acodec libmp3lame -ab 256k Breaking_Benjamin _Will_Not_Bow.mp4.mp3
  659  ffmpeg -i Breaking_Benjamin_Will_Not_Bow.mp4 -acodec libmp3lame -ab 256k Breaking_Benjamin _Will_Not_Bow.mp3
  660  ffmpeg -i Breaking_Benjamin_Will_Not_Bow.mp4 -acodec libmp3lame -ab 256k Breaking_Benjamin_Will_Not_Bow.mp3
  661  ffmpeg -i BLack_Sabbath_War_Pigs.mp4 -acodec libmp3lame -ab 256k Black_Sabbath_War_Pigs.mp3
  662  ffmpeg -i Black_Sabbath_War_Pigs.mp4 -acodec libmp3lame -ab 256k Black_Sabbath_War_Pigs.mp3
  663  ffmpeg -i AudioSlave_Like_a_Stone.mp4 -acodec libmp3lame -ab 256k AudioSlave_Like_a_Stone.mp3
  664  ffmpeg -i 'Kanye West - Power.mp4' -acodec libmp3lame -ab 256k Kanye_West_Power.mp3
  665  ffmpeg -i 'Kanye West - Power'.mp4 -acodec libmp3lame -ab 256k Kanye_West_Power.mp3
  666  ffmpeg -i Kanye_West_Power.mp4 -acodec libmp3lame -ab 256k Kanye_West_Power.mp3
  667  echo "deb http://archive.getdeb.net/ubuntu $(lsb_release -cs)-getdeb apps" | sudo tee /etc/apt/sources.list.d/getdeb-apps.list
  668  wget -q -O- http://archive.getdeb.net/getdeb-archive.key | sudo apt-key add -
  669  sudo apt-get update
  670  sudo apt-get install pycharm
  671  cd /home/ben/Downloads
  672  ffmpeg -i 'Nine Inch Nails - Everyday Is Exactly The Same'.mp4 -acodec libmp3lame -ab 256k Everyday Is Exactly The Same.mp3
  673  ffmpeg -i 'Nine Inch Nails - Everyday Is Exactly The Same'.mp4 -acodec libmp3lame -ab 256k Everyday_Is_Exactly_The_Same.mp3
  674  ffmpeg -i 'Nine Inch Nails - 'CLOSER''.mp4 -acodec libmp3lame -ab 256k Closer.mp3
  675  ffmpeg -i 'Nine Inch Nails - CLOSER'.mp4 -acodec libmp3lame -ab 256k Closer.mp3
  676  ffmpeg -i 'NINE INCH NAILS - CLOSER'.mp4 -acodec libmp3lame -ab 256k Closer.mp3
  677  ffmpeg -i 'Legend Has It By RunThe Jewels (Black Panther Trailer Music)'.mp4 -acodec libmp3lame -ab 256k 'Legend Has It'.mp3
  678  ffmpeg -i 'Legend Has It By Run The Jewels (Black Panther Trailer Music)'.mp4 -acodec libmp3lame -ab 256k 'Legend Has It'.mp3
  679  cd /home/ben/Downloads
  680  ffmpeg -i 'Legend Has It By Run The Jewels (Black Panther Trailer Music)'.mp4 -acodec libmp3lame -ab 256k Legend Has It.mp3
  681  ffmpeg -i 'Legend Has It By Run The Jewels (Black Panther Trailer Music)'.mp4 -acodec libmp3lame -ab 256k 'Legend Has It'.mp3
  682  ffmpeg -i 'Eminem - Love The Way You Lie ft. Rihanna'.mp4 -acodec libmp3lame -ab 256k 'Love The Way You Lie ft. Rihanna'.mp3
  683  ffmpeg -i 'Adele - Rolling in the Deep'.mp4 -acodec libmp3lame -ab 256k 'Rolling in the Deep'.mp3
  684  ffmpeg -i 'Adele - Someone Like You'.mp4 -acodec libmp3lame -ab 256k 'Someone Like You'.mp3
  685  ffmpeg -i 'Eminem - Stan (Long Version) ft. Dido'.mp4 -acodec libmp3lame -ab 256k 'Stan ft. Dido'.mp3
  686  abcde
  687  cd /home/ben/Music
  688  mkdir Jack White
  689  cd 'Jack White'
  690  cd Jack White
  691  ls
  692  mkdir 'Jack White'
  693  cd 'Jack White'
  694  cd
  695  cd /home/Ben/Music
  696  cd /home/ben/Music
  697  rm Jack
  698  rm -r Jack
  699  ls
  700  mkdir 'Jack White'
  701  cd 'Jack White'
  702  mkdir Blunderbuss
  703  cd Blunderbuss
  704  ls
  705  abcde
  706  cd /home/ben/Music
  707  cd 'Jack White'
  708  cd Blunderbuss
  709  abcde -o mp3:-V2 -a default,playlist,getalbumart
  710  abcde -c ~/.abcde.conf_mp3 -G
  711  abcde -o mp3: getalbumart
  712  abcde CDDBMETHOD
  713  abcde -G
  714  sudo apt-get install glyrc
  715  abcde -G
  716  sudo apt-get install cddbmethod
  717  abcde-musicbrainz-tool
  718  abcde -G
  719  cd /home/ben/Music
  720  cd 'Jack White'
  721  cd Blunderbuss
  722  abcde -G
  723  abcde -G -mp3
  724  abcde -o mp3 -G
  725  abcde -o mp3: -G
  726  abcde -o mp3
  727  abcde -o mp3:-V2 -a default,playlist,getalbumart
  728  sudo apt-get install eyeD3
  729  sudo apt-get install eyed3
  730  abcde -o mp3:-V2 -a default,playlist,getalbumart
  731  cd
  732  abcde -o mp3:-V2 -a default,playlist,getalbumart
  733  cd home/ben/Music
  734  cd /home/ben/Music
  735  abcde -o mp3:-V2 -a default,playlist,getalbumart
  736  cd /home/ben/Music
  737  abcde -o mp3:-V2 -a default,playlist,getalbumart
  738  cd /home/ben/Music
  739  abcde -o mp3:-V2 -a getalbumart
  740  abcde -o mp3:-V2 -a default,playlist,getalbumart
  741  cd /home/ben/Music
  742  abcde -o mp3:-V2 -a default,playlist,getalbumart
  743  cd /home/ben/Music
  744  abcde -o mp3:-V2 -a default,playlist,getalbumart
  745  cd /home/ben/Music
  746  abcde -o mp3:-V2 -a default,playlist,getalbumart
  747  cd /home/ben/Music
  748  abcde -o mp3:-V2 -a default,playlist,getalbumart
  749  sudo gedit or sudo xed /usr/share/pycharm/bin/pycharm.sh
  750  sudo apt-get install openjdk-8-jdk
  751  abcde -o mp3:-V2 -a default,playlist,getalbumart
  752  cd /home/ben/Music
  753  abcde -o mp3:-V2 -a default,playlist,getalbumart
  754  cd /home/ben/Music
  755  ls
  756  cd /home/ben/Music/'Various-All_Eyez_on_Me_(Disc_1)'
  757  ls
  758  for i in *.wav; do ffmpeg -i "$i" -f mp3 "${i%}.mp3"; done
  759  for i in *.ogg; do ffmpeg -i "$i" -f mp3 "${i%}.mp3"; done
  760  cd /home/ben/Music/'Various-All_Eyez_on_Me_(Disc_1)'
  761  for i in *.ogg; do ffmpeg -i cover.jpg "$i" -f mp3 "${i%}.mp3"; done
  762  for i in *.ogg; do ffmpeg -i "$i" -f mp3 "${i%}.mp3 -an -vcodec copy cover.jpg"; done
  763  cd /home/ben/Music/'Various-All_Eyez_on_Me_(Disc_1)'
  764  for i in *.ogg; do ffmpeg -i "$i" -f mp3 "${i%}.mp3"; done
  765  cd /home/ben/Music/'Various-All_Eyez_on_Me_(Disc_1)'
  766  for i in *.ogg; do ffmpeg -i "$i" -f mp3 "${i%}.mp3"; done
  767  cd /home/ben/Music
  768  abcde -o mp3:-V2 -a default,playlist,getalbumart
  769  cd /home/ben/Music
  770  abcde -o mp3:-V2 -a default,playlist,getalbumart
  771  sudo apt-get install jpegoptim
  772  cd /home/ben/Music/Disturbed-The_Sickness
  773  ls
  774  jpegoptim cover.jpg
  775  jpegoptim -m50 cover.jpg
  776  jpegoptim -m75 cover.jpg
  777  jpegoptim -m45 cover.jpg
  778  jpegoptim -m40 cover.jpg
  779  jpegoptim -m25 cover.jpg
  780  jpegoptim -m15 cover.jpg
  781  sudo add-apt-repository ppa:amigadave/ppa
  782  sudo apt-get update
  783  sudo apt-get install easytag
  784  easytag
  785  cd /home/ben/Music
  786  abcde -o mp3:-V2 -a default,playlist,getalbumart
  787  easytag
  788  cd /home/ben/Trash
  789  cd /Trash
  790  cd Trash
  791  trash-cli
  792  /.Trash
  793  ~/.Trash
  794  /root/.Trash
  795  cd /root/.Trash
  796  sudo cd /root/.Trash
  797  sudo find / -type d -name *Trash* 
  798  cd /home/ben/.local/share/Trash
  799  ls
  800  cd /home/ben/.local/share/Trash/files
  801  ls
  802  cd /home/ben/.local/share/Trash/expunged
  803  ls
  804  cd /home/ben/.local/share/Trash
  805  ls
  806  empty
  807  cd /home/local/share/.Trash
  808  cd /home/.local/share/Trash
  809  sudo find / -type d -name *Trash* 
  810  cd /home/ben/Music
  811  abcde -o mp3:-V2 -a default,playlist,getalbumart
  812  cd /home/ben/Music/Various-All_Eyez_On_Me_(CD2)
  813  cd /home/ben/Music/Various-'/All_Eyez_On_Me_(CD2)'
  814  cd /home/ben/Music/Various-All_Eyez_On_Me_(CD2)
  815  cd /home/ben/Music/2pac_2
  816  jpegoptim -m15 cover.jpg
  817  jpegoptim -m10 cover.jpg
  818  jpegoptim -m05 cover.jpg
  819  cd /home/ben/Music
  820  abcde -o mp3:-V2 -a default,playlist,getalbumart
  821  easytag
  822  cd /home/ben/Music
  823  ls
  824  cd /home/ben/Music/Metallica-Metalica
  825  cd /home/ben/Music/'Metallica-Metallica'
  826  ls
  827  jpegoptim -m100 cover.jpg
  828  cd /home/ben/Music
  829  abcde -o mp3:-V2 -a default,playlist,getalbumart
  830  cd /home/ben/Music
  831  abcde -o mp3:-V2 -a default,playlist,getalbumart
  832  cd /home/ben/Desktop
  833  mkdir aax2mp3tools
  834  cd aax2mp3tools
  835  wget https://github.com/inAudible-NG/audible-activator/archive/master.zip
  836  unzip master.zip
  837  rm master.zip
  838  cd audible-activator-master
  839  ./audible-activator.py -l us
  840  sudo apt-get install chrome
  841  exit
  842  sudo apt-get install chrome
  843  sudo apt-get install chromium-browser
  844  cd /home/ben/Desktop
  845  cd aax2mp3tools
  846  cd audible-activator-master
  847  ./audible-activator.py -l us
  848  sudo apt-get update
  849  sudo apt-get install google-chrome-stable
  850  ./audible-activator.py -l us
  851  sudo apt-get install selenium
  852  sudo apt-get install libxss1 libappindicator1 libindicator7
  853  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  854  sudo dpkg -i google-chrome*.deb
  855  sudo apt-get install -f
  856  sudo apt-get install xvfb
  857  sudo apt-get install unzip
  858  wget -N http://chromedriver.storage.googleapis.com/2.26/chromedriver_linux64.zip
  859  unzip chromedriver_linux64.zip
  860  chmod +x chromedriver
  861  sudo mv -f chromedriver /usr/local/share/chromedriver
  862  sudo ln -s /usr/local/share/chromedriver /usr/local/bin/chromedriver
  863  sudo ln -s /usr/local/share/chromedriver /usr/bin/chromedriver
  864  ./audible-activator.py -l us
  865  exit
  866  sudo apt-get install libxss1 libappindicator1 libindicator7
  867  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  868  sudo dpkg -i google-chrome*.deb
  869  pip install pyvirtualdisplay selenium
  870  ./audible-activator.py -l us
  871  cd /home/ben/Desktop
  872  cd aax2mp3tools
  873  cd audible-activator-master
  874  ./audible-activator.py -l us
  875  sudo apt-get install python2.7
  876  ./audible-activator.py -l us
  877  sudo easy_install pip
  878  pip install selenium requests
  879  git clone https://github.com/inAudible=NG/audible-activator
  880  cd audible-activator
  881  sed -i '' 's,chromedriver_path = "./chromedriver",chromedriver_path = "/usr/local/bin/chromedriver",' audible-activator.py
  882  exit
  883  sed -i '' 's,chromedriver_path = "./chromedriver",chromedriver_path = "/usr/local/bin/chromedriver",' audible-activator.py
  884  brew install chromedriver ffmpeg
  885  sudo apt install linuxbrew-wrapper
  886  brew install chromedriver ffmpeg
  887  sudo easy_install pip
  888  pip install selenium requests
  889  git clone https://github.com/inAudible-NG/audible-activator
  890  cd audible-activator
  891  sed -i '' 's,chromedriver_path = "./chromedriver",chromedriver_path = "/usr/local/bin/chromedriver",' audible-activator.py
  892  ./audible-activator.py
  893  python
  894  pip install print_function
  895  pip install __future__
  896  pip install _future_
  897  pip install __future__
  898  pip install selenium
  899  ./audible-activator.py
  900  chromedriver
  901  java -Dwebdriver.chrome.driver=path_to_chrome_driver -jar selenium_server.jar
  902  sudo Xvfb :10 -ac &
  903  export DISPLAY=:10
  904  import org.openqa.selenium.WebDriver;
  905  import org.openqa.selenium.chrome.ChromeDriver;
  906  public class Sel {
  907  ./audible-activator.py
  908  sed -i '' 's,chromedriver_path = "./chromedriver",chromedriver_path = "/usr/local/bin/chromedriver",' audible-activator.py
  909  cd audible-activator
  910  sed -i '' 's,chromedriver_path = "./chromedriver",chromedriver_path = "/usr/local/bin/chromedriver",' audible-activator.py
  911  ./audible-activator.py
  912  pip install requests
  913  ./audible-activator.py
  914  pip install selenium
  915  sudo apt-get install unzip;
  916  wget -O /tmp/chromedriver.zip http://chromedriver.storage.googleapis.com/2.10/chromedriver_linux64.zip && sudo unzip /tmp/chromedriver.zip chromedriver -d /usr/local/bin/;
  917  ./audible-activator.py
  918  chromedriver -d /usr/local/bin/;
  919  sudo apt-get update
  920  sudo apt-get install python-pip
  921  sudo apt-get install google-chrome-stable
  922  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  923  sudo dpkg -i google-chrome-stable_current_amd64.deb
  924  pip install requests
  925  pip install selenium
  926  wget https://chromedriver.storage.googleapis.com2.27/chromedriver_linux64.zip
  927  wget https://chromedriver.storage.googleapis.com/2.27/chromedriver_linux64.zip
  928  unzip chromedriver_linux64.zip
  929  mkdir aax2mp3tools
  930  cd aax2mp3tools
  931  wget https://github.com/inAudible-NG/audible-activator/archive/master.zip
  932  unzip master.zip
  933  rm master.zip
  934  cd audible-activator-master
  935  ls
  936  ./audible-activatory.py -l us
  937  ./audible-activator.py -l us
  938  wget https://chromedriver.storage.googleapis.com/2.27/chromedriver_linux64.zip
  939  unzip chromedriver_linux64.zip
  940  ./audible-activator.py -l us
  941  cd /home/ben/Desktop/aax2mp3tools
  942  ls
  943  cd /home/ben/Desktop/aax2mp3tools/audible-activator-master
  944  ls
  945  ./audible-activator.py -l us
  946  cd /home/ben/Desktop/aax2mp3tools/audible-activator-master
  947  ls
  948  audible-activator.py
  949  ./audible-activator.py
  950  wget https://chromedriver.storage.googleapis.com/2.27/chromedriver_linux64.zip
  951  unzip chromedriver_linux64.zip
  952  ./audible-activator.py
  953  sudo apt-get samba
  954  sudo apt-get install samba
  955  samba
  956  sudo smbpasswd -a Charlene81#
  957  sudo smbpasswd - a ben
  958  sudo smbpasswd -a Ben
  959  sudo smbpasswd -a ben
  960  mkdir /home/ben/Desktop
  961  mkdir /home/ben/sambashare
  962  sudo cp /etc/samba/smb.conf ~
  963  sudo nano /etc/samba/smb.conf
  964  sudo apt-get install samba dolphin kdenetwork-filesharing
  965  sudo dolphin
  966  samba
  967  sudo smbpasswd -a ben
  968  mkdir /home/ben/text
  969  sudo cp /etc/samba/smb.conf
  970  sudo cp /etc/samba/smb.conf ~
  971  sudo gedit /etc/samba/smb.conf
  972  sudo restart smbd
  973  sudo nano /etc/samba/smb.conf
  974  sudo restart smbd
  975  sudo testparm
  976  samba
  977  sudo apt-get update
  978  sudo apt-get install gnome-user-share apache2.2-bin libapache2-mod-dnssd
  979  sudo apt-get install gnome-user-share apache2-bin libapache2-mod-dnssd
  980  sudo apt-get install gksu
  981  samba
  982  sudo apt-get install network
  983  sudo gedit /etc/nsswitch.conf
  984  sudo nano /etc/nsswitch.conf
  985  smbclient
  986  sudo apt-get install smbclient
  987  sudo apt-get update
  988  sudo apt-get install smbclient
  989  sudo apt-get update --fix-missing
  990  sudo apt-get install smbclient
  991  sudo apt autoremove
  992  sudo apt-get update
  993  sudo apt-get install smbclient
  994  samba
  995  sudo apt-get install smbclient
  996  sudo service restart network-manager
  997  sudo restart network-managetr
  998  sudo restart network-manager
  999  sudo nano /etc/nsswitch.conf
 1000  sudo restart network-manager
 1001  ping google.com
 1002  ping -c 5 google.com
 1003  ping -c 5 www.rgonzo.us
 1004  iwconfig
 1005  sudo ifconfig wlan0 up
 1006  sudo iwlist scan|more
 1007  sudo iwlist scan | more
 1008  ifconfig -a
 1009  route -n
 1010  ping -c3 ubuntuforums.org
 1011  sudo apt-get update
 1012  sudo apt remove samba
 1013  ping 8.8.8.8
 1014  ping google.com
 1015  ping www.gogle.com
 1016  mtr 8.8.8.8
 1017  ping google.com
 1018  sudo resolvconf -u
 1019  ping google.com
 1020  sudo resolvconf -u
 1021  ifconfig
 1022  route
 1023  cat /etc/resolv.conf
 1024  ping google.com
 1025  sudo resolveconf -u
 1026  sudo resolve.conf -u
 1027  sudo resolv.conf -u
 1028  sudo nano /etc/NetworkManager/NetworkManager.conf
 1029  sudo service network-manager restart
 1030  sudo rfkill
 1031  sudo lshw -class network
 1032  sudo lshw -class 
 1033  sudo service network-manager restart
 1034  ping -c3 ubuntuforums.org
 1035  sudo apt-get update
 1036  sudo cat /etc/network/interfaces
 1037  ping -c3 ubuntuforums.org
 1038  sudo lshw -class 
 1039  sudo cat /etc/network/interfaces
 1040  sudo /etc/init.d/networking restart
 1041  sudo systemctl restart
 1042  sudo systemctl restart Network.Manager.service
 1043  sudo systemctl restart NetworkManager.service
 1044  sudo dpkg-reconfigure resolvconf
 1045  ping google.com
 1046  sudo killall dhclient
 1047  ping 8.8.8.8
 1048  sudo gedit /etc/samba/smb.conf
 1049  sudo gedit /etc/nsswitch.conf
 1050  sudo nano /etc/nsswitch.conf
 1051  sudo systemctl restart NetworkManager.service
 1052  sudo apt-get install filezilla
 1053  sudo apt-get update
 1054  filezilla
 1055  sudo apt-get install Samba
 1056  sudo apt-get install samba
 1057  cd /home/ben/Desktop
 1058  mdkir NetData
 1059  mkdir NetData
 1060  smbd
 1061  sudo apt-get install smbd
 1062  samba
 1063  sudo samba
 1064  ipconfig
 1065  ip address
 1066  sudo apt-get update
 1067  google-chrome-stable --password-store=basic
 1068  lpstat -a
 1069  lpr -P
 1070  lpr
 1071  lpr -P
 1072  lpstat -a
 1073  lpstat -p
 1074  lpstat -P
 1075  lpstat
 1076  echo "Hello World"
 1077  echo $Path
 1078  echo $PATH
 1079  cd /home/ben/Desktop
 1080  echo $PATH
 1081  which ruby
 1082  which echo
 1083  ping google.com
 1084  ping -c 5 www.rgonzo.us
 1085  cd /home/ben/Desktop/aax2mp3tools/audible-activator-master
 1086  ls
 1087  ./audible-activator.py
 1088  filezilla
 1089  cd /home/ben/Downloads
 1090  ls
 1091  ffmpeg -i 'Legend Has It By Run The Jewels (Black Panther Trailer Music)'.mp4 -acodec libmp3lame -ab 256k Legend Has It.mp3
 1092  ffmpeg -i 'Linkin Park - Roads Untraveled'.mp4 -acodec libmp3lame -ab 256k Roads Untravled.mp3
 1093  ffmpeg -i 'Linkin Park - Roads Untraveled'.mp4 -acodec libmp3lame -ab 256k RoadsUntravled.mp3
 1094  mkdir /home/ben/Desktop/cdfiles
 1095  cd /home/ben/Desktop/cdfiles
 1096  nano cdripper.sh
 1097  chmod +x cdripper.sh
 1098  ./cdripper.sh
 1099  abcde
 1100  cd /home/ben/Desktop/cdfiles
 1101  abcde
 1102  nano cdripper.sh
 1103  nano loopmp3.sh
 1104  ls
 1105  cd AC-DC-Back_In_Black
 1106  ./loopmp3.sh
 1107  nano loopmp3.sh
 1108  ./loopmp3.sh
 1109  chmod +x loopmp3.sh
 1110  ./loopmp3.sh
 1111  cd..
 1112  cd
 1113  nano loopmp3.sh
 1114  chmod +x loopmp3.sh
 1115  ./loopmp3.sh
 1116  abcde -o mp3:-V2 -a default,playlist,getalbumart
 1117  wget http://kindleforpc.amazon.com/40514/KindleForPC-installer.exe
 1118  wine
 1119  sudo apt-get install update
 1120  sudo apt-get install wine
 1121  wine
 1122  wine kindle
 1123  wget http://kindleforpc.amazon.com/40514/KindleForPC-installer.exe
 1124  sudo apt-get install k3b
 1125  k3b
 1126  sudo apt-get update && upgrade
 1127  sudo reboot
 1128  sudo apt-get update && upgrade
 1129  sudo apt-get upgrad
 1130  sudo apt-get upgrade
 1131  sudo apt-get install squashfs-tools
 1132  sudo apt-get install kpartx
 1133  /home/ben/Desktop
 1134  cd /home/ben/Desktop
 1135  mkdir image
 1136  ls
 1137  cd image
 1138  ls
 1139  ;d
 1140  ls
 1141  sudo kpartx -av retropie-4.3-rpi2_rpi3.img.gz
 1142  sudo kpartx -av retropie-4.3-rpi2_rpi3.img
 1143  sudo kpartx -av pie.img
 1144  sudo mount /dev/mapper/loop7p2/mnt
 1145  sudo mount /dev/mapper/loop7p2 /mnt
 1146  sudo sed -i 's/^\/dev\/mmcblk/#\0/g' /mnt/etc/fstab
 1147  sudo mksquashfs /mnt converted_image_for_berryboot.img -comp lzo -e lib/modules
 1148  sudo umount /mnt
 1149  sudo kpartx -d pie.img
 1150  abcde -o mp3:-V2 -a default,playlist,getalbumart
 1151  cd /home/ben/Desktop
 1152  mkdir openmedia
 1153  cd /openmedia
 1154  openmedia
 1155  ls
 1156  cd /openmedia/
 1157  cd openmedia
 1158  ls
 1159  sudo kpartx -av omv.img
 1160  sudo mount /dev/mapper/loop4p2/mnt
 1161  sudo mount /dev/mapper/loop4p1/mnt
 1162  sudo mount /dev/mapper/loop4p2/mnt
 1163  sudo kpartx -av omv.img
 1164  sudo apt-get install kpartx
 1165  sudo kpartx -av omv.img
 1166  sudo mount /dev/mapper/loop4p1 /mnt
 1167  sudo sed -i 's/^\/dev\/mmcblk/#\0/g' /mnt/etc/fstab
 1168  sudo apt-get install squashfs
 1169  sudo apt-get install mksquashfs
 1170  sudo apt-get install squashfs-tools
 1171  sudo kpartx -av ovm.img
 1172  cd
 1173  cd /home/ben/Desktop/openmedia
 1174  ls
 1175  sudo kpartx -av ovm.img
 1176  cd /home/ben/Desktop/openmedia
 1177  sudo kpartx -av ovm.img
 1178  sudo kpartx -av omv.img
 1179  sudo mount /dev/mapper/loop4p2 /mnt
 1180  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/etc/fstab
 1181  sudo mksquashfs /mnt converted_image_for_berryboot.img -comp lzo -e lib/modules
 1182  sudo umount /mnt
 1183  sudo kpartx -d omv.img
 1184  cd /home/ben/Desktop/Volumio
 1185  mkdir /home/ben/Desktop/Volumio
 1186  cd /home/ben/Desktop/Volumio
 1187  sudo kpartx -d volumio.img
 1188  sudo kpartx -av volumio.img
 1189  sudo mount /dev/mapper/loop6p3 /mnt
 1190  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/etc/fstab
 1191  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/media/ben/volumio
 1192  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/etc/volumio
 1193  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/media/ben/volumio
 1194  sudo mksquashfs /mnt converted_image_for_berryboot.img -comp lzo
 1195  sudo umount /mnt
 1196  sudo kpartx -d image_you_want_to_convert.img
 1197  sudo kpartx -d volumio.img
 1198  sudo sed -i 's/^\/dev\/mmcblk/#)/g' /mnt/etc/fstab
 1199  sudo sed -i 's/^\/dev\/mmcblk/#)/g'/mnt/etc/fstab
 1200  sudo sed -i 's/^\/dev\/mmcblk/#)/g'  /mnt/etc/fstab
 1201  sudo mount /dev/mapper/loop6p1 /mnt
 1202  sudo mount /dev/mapper/loop6p2 /mnt
 1203  sudo sed -i 's/^\/dev\/mmcblk/#)/g'  /mnt/etc/fstab
 1204  ls
 1205  sudo kpartx -d volumio.img
 1206  sudo kpartx -d converted_image_for_verryboot.img
 1207  sudo umount /mnt
 1208  ls
 1209  sudo kpartx -av volumio.img
 1210  sudo mount /dev/mapper/loop6p3 /mnt
 1211  sudo sed -i 's/^\/dev\/mmcblk/#)/g'  /mnt/etc/fstab
 1212  sudo umount /mnt
 1213  sudo sed -i 's/^\/dev\/mmcblk/#)/g'  /mnt/etc/fstab
 1214  sudo kpartx -av volume.img
 1215  cd /media/ben
 1216  ls
 1217  cd /E9E6-0DC2
 1218  cd /E9E6-0DC2/
 1219  cd /E9E6-0DC2
 1220  cd /media/ben/16_GB_Volume
 1221  ls
 1222  sudo kpartx -av volume.img
 1223  cd /E9E6-0DC2/
 1224  cd /media/ben/E9E6-0DC2/
 1225  ls
 1226  sudo kpartx -av volume.img
 1227  sudo apt-get install kpartx
 1228  /home/ben/Desktop
 1229  ls
 1230  cd /home/ben/Desktop/revol
 1231  ls
 1232  sudo kpartx -av Volumio1.55PI.img
 1233  sudo mount /dev/mapper/loop8p3 /mnt
 1234  sudo sed -i 's/^\/dev\/mmcblk/#)/g'  /mnt/etc/fstab
 1235  sudo mksquashfs /mnt converted_image_for_berryboot.img -comp lzo -e lib/modules
 1236  sudo umount /mnt
 1237  sudo kpartx -d volumio.img
 1238  sudo kpartx -d Volumio1.55PI.img
 1239  sudo kpartx -av NewBerry.img
 1240  sudo mount /dev/mapper/loop8p3 /mnt
 1241  sudo mksquashfs /mnt converted_image_for_berryboot.img -comp lzo -e lib/modules
 1242  sudo umount /mnt
 1243  sudo kpartx -d NewBerry.img
 1244  abcde -o mp3:-V2 -a default,playlist,getalbumart
 1245  sudo apt-get update
 1246  python
 1247  sudo apt-get update
 1248  sudo apt update
 1249  sudo apt install putty
 1250  putty
 1251  python
 1252  sudo apt-get update
 1253  abcde -o mp3:-V2 -a default,playlist,getalbumart
 1254  R
 1255  sudo apt-get update
 1256  ~sudo apt-get install git
 1257  sudo apt-get install git
 1258  sudo apt-get update
 1259  sudo apt-get install git
 1260  git
 1261  sudo apt-get install build-essential libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext unzip
 1262  git config --global usern.name "gonzalezben81"
 1263  git config --global usern.email "gonzalezben81@gmail.com"
 1264  git config --list
 1265  sudo nano ~/.gitconfig
 1266  git clone https://github.com/gonzalezben81/WebScraper.git
 1267  ls
 1268  cd ~/www
 1269  sudo adduser git
 1270  ping www.rgonzo.us
 1271  netstat -ie
 1272  ftp fileserver
 1273  ftp www.rgonzo.us
 1274  ssh www.rgonzo.us
 1275  ssh ben@www.rgonzo.us
 1276  ssh-keygen
 1277  sudo nano finalrstudio.txt
 1278  .bash_history
 1279  ls
 1280  ls *
 1281  history > history_for_print.txt
 1282  cd Desktop
 1283  history > history_for_print.txt
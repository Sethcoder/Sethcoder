root@localhost:/system/comma/home$ cd /data/openpilot
root@localhost:/data/openpilot$

root@localhost:/data/openpilot$ git clean -Xfd
root@localhost:/data/openpilot$ git remote add mazda https://github.com/Jafaral/openpilot.git
root@localhost:/data/openpilot$ git fetch mazda
root@localhost:/data/openpilot$ git checkout mazda/mazda-devel -b mazda-devel

# Ansible role and vagrant file to create local hdfs lab with webhdfs

## run
1. cd to repo
2. vagrant up
3. vagrant ssh namenode-1
4. sudo -s
5. su hadoop
6. cd
7. /opt/hadoop/bin/hdfs namenode -format (only once!!!)
8. /opt/hadoop/sbin/start-dfs.sh && ./sbin/start-yarn.sh

## stop
1. cd to repo
3. vagrant ssh namenode-1
4. sudo -s
5. su hadoop
6. cd
7. /opt/hadoop/sbin/stop-all.sh
8. press keys one by one: return ~ .
9. vagrant halt

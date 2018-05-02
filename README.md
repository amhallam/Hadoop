# Hadoop

#configure git repo
git config --global user.email "amine.haXXXX@gmail.com"
git config --global user.name "amhallam"


#Start Local spark docker
docker run -it -p 8088:8088 -p 8042:8042 -p 4040:4040 -h sandbox sequenceiq/spark:1.6.0 bash

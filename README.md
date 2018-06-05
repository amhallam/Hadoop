# Hadoop

#configure git repo
git config --global user.email "amineasuk@gmail.com"
git config --global user.name "amhallam"
git config --global user.password "Loss"
git remote add origin https://github.com/Imrantak/POC
#Start Local spark docker
docker run -it -p 8088:8088 -p 8042:8042 -p 4040:4040 -h sandbox sequenceiq/spark:1.6.0 bash

The idea is to just learn about docker and K8. Nothing fancy.
Steps 
1. Create a few docker files.
2. Create a K8 clusters.
3. Run these dockers in that cluster.
4. Bring down and up some docker, do some fail safe things
5. Shutdown everything.
6. Automate everything - should use what? Terrafam? 
7. How to unit test these terafarm things? or try some other opensource? heard terrafarm is not opensource anymore. 
Anyway will have some understanding. The manual for above will be added here. The folder structure as of now is like maven kind, that means

/main
/test
/main/src
/main/resource
/main/src/dockerFiles
/main/src/k8script
/main/src/driver

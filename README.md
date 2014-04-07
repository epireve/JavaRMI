JavaRMI
=======
javac HelloInterface
javac Hello

rmic Hello

#start rmiregistry
rmiregistry &

#start server
java HelloServer
java HelloClient

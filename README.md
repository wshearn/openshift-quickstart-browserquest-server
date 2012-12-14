openshift-quickstart-browserquest-server
========================================

Mozillas Browser Quest Server for OpenShift

Quickstart
==========

1) Create an account at http://openshift.redhat.com/

2) Create a nodejs application:

    rhc app create -a bqserver -t nodejs-0.6

3) Add this upstream repo

    cd bqserver
    git remote add upstream -m master git://github.com/wshearn/openshift-quickstart-browserquest-server.git
    git pull -s recursive -X theirs upstream master

4) Then push the repo upstream

    git push

5) That's it, you can now you can set up the client by following
   https://github.com/wshearn/openshift-quickstart-browserquest-client



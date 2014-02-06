OpenShift iFlowBPM Quickstart
=============================

This quickstart will let you create a ready-to-use [iFlowBPM](http://www.iflowbpm.com/) instance on Getup Cloud OpenShift.

If you do not have an account yet, please [signup](http://getupcloud.com/#/sign-up) and come back here ASAP.
It is free and gives you a 750h trial period.

Create your iFlowBPM app
------------------------

Open a terminal window and type:

```
rhc app-create iflow jbossews-2.0 mysql-5.1 --from-code https://github.com/caruccio/openshift-iflowbpm-quickstart.git
```

Point your browser to [https://iflow-$namespace.getup.io/Admin/login.jsp](#).

```
Admin Username: admin
Admin Password: admin
```

That's all, folks!

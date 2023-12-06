---
title: Fsirst Kubernetes post
date: 2019-02-01
tags: ["kubernetes", "code"]
---

second post

<!--more-->

```sh
    $ kubectl run kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1 --port=8080
```

Now, check whether it is running:
```sh
    $ kubectl get pods
    NAME                                   READY     STATUS    RESTARTS   AGE
    kubernetes-bootcamp-5c69669756-wv2rp   1/1       Running   0          11s
```
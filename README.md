## k8s-ingress  NGINX


Just created this repo to avoid , searching for bare metal nginx ingress file.


* By default, k8s official mandatory.yml file shows container IP's in ingress status.

* This updated config will show node IP instead of conatiner service IP.


`kubectl apply -f https://raw.githubusercontent.com/jamesarems/k8s-ingress/master/mandatory.yaml`

# openshift-operator-quay-imagescan-vulnerabilities


check the events:

oc get events -n openshift-operators -w

set the our channel: oc describe packagemanifest container-security-operator -n openshift-marketplace | grep -i channel:

apply config: oc apply -f .
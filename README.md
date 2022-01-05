# openshift-operator-quay-imagescan-vulnerabilities


check the events:

oc get events -n openshift-operators -w

set the our channel: oc get packagemanifests -n openshift-marketplace | grep container-security-operatoroc describe packagemanifest container-security-operator -n openshift-marketplace | grep -i channel:

apply config: oc apply -f .
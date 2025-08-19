# SNMP
On harvester we are not able to installed snmp client directly to nodes . We can avoid this problem by installing it on kubernetes 


    kubectl create ns monitoring
    kubectl apply -f snmpd-config.yaml
    kubectl apply -f snmpd-daemonset.yaml

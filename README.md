# Homework

POST https://10.95.43.20/api/mo/aaaLogin.xml
<aaaUser name='admin' pwd='phxlab123'/>

GET https://10.95.43.20/api/node/class/procEntity.xml

Output
<?xml version="1.0" encoding="UTF-8"?>
<imdata totalCount="1">
    <procEntity adminSt="enabled" childAction="" cpuPct="1" dn="topology/pod-1/node-1/sys/proc" maxMemAlloc="13531424" memFree="52045088" modTs="2017-06-15T18:00:37.115+00:00" monPolDn="uni/fabric/monfab-default" name="" operErr="" operSt="enabled" status=""/>
</imdata>

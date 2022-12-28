# AEP


## Infra vlan
- fvDyPathAtt for the infra EPG on all ports part of the AEP where the AVS is present on the leaf where an opflexODev has been created
- fvIfConn for the infra vlan as child of the previous fvDyPathAtt

```
moquery -c fvIfConn
```

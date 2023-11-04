<h1> Simple example for use with AWX to create a Tenant. </h1>

This very basic playbook creates a Tenant in a lab environment using AWX. 

It has a collections directory to specify which collections it should download for use by AWX. We are also specifying an older version, since there seems to be a problem with the latested at this time - 2.7.0. 

In this case, we are only downloading the ACI collection.

```
collections:
  - name: cisco.aci
    version: 2.6.0
```

We are hardcoding the Tenant name. We would normally use a variable here for substituion.

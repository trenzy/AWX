<h1> Simple example for use with AWX to create a Tenant. </h1>

This very basic playbook creates a Tenant in a lab environment using AWX. 

It has a collections directory to specify which collections it should download for use by AWX. In this case, we are only downloading:

```
- cisco.aci
```

We are hardcoding the Tenant name. We would normally use a variable here for substituion.

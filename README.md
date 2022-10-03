# bidsdk-files

## Add reference of BIDStepup.js and BIDStepup.css files into .html inside head section.

```
  <link rel="stylesheet" href="./path to css file" />
  <script src="./path to js file"></script>
```

## Call stepup method by passing params

```
BIDStepup.stepup(
    domElement,
    tenantdns,
    ommunity,
    clientid,
    username,
    state,
    acr,
    postbackCallbackFunction
);
```

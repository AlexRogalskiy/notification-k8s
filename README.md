# notification-k8s
A helm chart for the notification example app

## How to install the chart

1. Create a `values.yaml` file which specifies values for `mail.url` and `mail.toAddress`, like this
```
mail:
  url: "<mailgun smptp server connectiopn string>"
  toAddress: "<to-address needed for mailgun sandbox accounts>"
```
2. Install with Helm
```
cd ..
helm install ./notification-k8s
```

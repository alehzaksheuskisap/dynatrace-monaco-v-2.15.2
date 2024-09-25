# dynatrace-monaco-2.15.2-build

This is a build from https://github.com/dynatrace/dynatrace-configuration-as-code with the next update:
  - pkg > client > dtclient > retry.go - Count of **DefaultRetrySettings.VeryLong.MaxRetries** changes from 60 to 2, to speed up upload using Dynatrace Monaco client.

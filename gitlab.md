# Gitlab Integration

## Get credentials

```
$ sh gitlab-integration.sh 
Kubernetes cluster name:

qbo

API URL:

https://172.17.0.3:6443

CA Certificate:

-----BEGIN CERTIFICATE-----
MIICyDCCAbCgAwIBAgIBADANBgkqhkiG9w0BAQsFADAVMRMwEQYDVQQDEwprdWJl
cm5ldGVzMB4XDTIwMDYyMzA0MTkwMVoXDTMwMDYyMTA0MTkwMVowFTETMBEGA1UE
AxMKa3ViZXJuZXRlczCCASIwDQYJKoZIhvcNAQEBBQADggEPADCCAQoCggEBALkV
k7c1vNjalOxDnDYsVkYlcj/82a3MZEj6g37AFsHNcvBTuy+SFk5P+2Da8b15/6Y1
viZoQtC+jNmxXKvtejMkIBfhHcwISVB1M8zVEmg66Sl3VXKd678/VlsuAvpX4nwp
G++2fCg4lBUSZSbf/OYSWwIVm33ina7aBgF7kBrmnNUdZJGU2jDbnAMbRd6kuV24
ZTytPnhQ6Sgk4gCNPEzRwvQpHqmcn4HvSUv3po7SZpnIpErle5Xl1MdEwROOcg3v
L9jvPf6DuTE/qZKKsu56brSiiG0uehKOrreGqOhtk6AEfpkaMS3Wmw3Fv7G1L/B1
KHqYd/fjPQ5a15sYlWkCAwEAAaMjMCEwDgYDVR0PAQH/BAQDAgKkMA8GA1UdEwEB
/wQFMAMBAf8wDQYJKoZIhvcNAQELBQADggEBAH+jCDlEitI1rklnuSxmgTm/8ffr
AtQ6QDmDqB8RZuH4OxRagDcExRCTag0F8RNnpOXsbBUVevp6XY1z3hbXxrGPYOfQ
5HgHhEHYUxdtYLD/TxQgDPr1OmQYgY5M1GH6wVIyrsUvEh0eeP2yG5CBM38I9b2g
d98Xp76rkFBFILQZ95WRVLHvtVD4ChPkoqLvdaz93BUlZWVM7DzZmyoxnfdcSpHO
U4G3o1bulc6ub5LrcZk4gJMgsOBKwbAbJUXudSuZtNODhk0kGzLQeZccnOEemL4+
bQbY0b6Lkzj9/ymST2wGfcQUfsWf7PGJFbsJ9/5RXfx56+lOOBum7ObKdXc=
-----END CERTIFICATE-----

Service Token:

eyJhbGciOiJSUzI1NiIsImtpZCI6IlRWcGVwRF9FUTM4QmdqT0pJZklfRWpoaEF1NF8xSFlpOEdfXzJnTFFweTQifQ.eyJpc3MiOiJrdWJlcm5ldGVzL3NlcnZpY2VhY2NvdW50Iiwia3ViZXJuZXRlcy5pby9zZXJ1aWNlYWNjb3VudC9uYW1lc3BhY2UiOiJrdWJlLXN5c3RlbSIsImt1YmVybmV0ZXMuaW8vc2VydmljZWFjY291bnQvc2VjcmV0Lm5hbWUiOiJnaXRsYWItYWRtaW4tdG9rZW4tNGpjbjYiLCJrdWJlcm5ldGVzLmlvL2NlcnZpY2VhY2NvdW50L3NlcnZpY2UtYWNjb3VudC5uYW1lIjoiZ2l0bGFiLWFkbWluIiwia3ViZXJuZXRlcy5pby9zZXJ2aWNlYWNjb3VudC9zZXJ2aWNlLWFjY291bnQudWlkIjoiMmIwZjBiMzctOTRlNC00NjYyLWI1ZmItZGZjMzE1YTZiNzYwIiwic3ViIjoic3lzdGVtOnNlcnZpY2VhY2NvdW50Omt1YmUtc3lzdGVtOmdpdGxhYi1hZG1pbiJ9.Tc-_oUBp3FGwFr6HMd0fnRdRnq4oqk3APXomCB03-n0eWP_aLJzucOzgZ5fNkrAgbHqkxENj5YQ_w28g638CGhERb89ZU9I7RL8DxZAPtSOp6qprs6wLL9yHN-5sbtr94LRvgq7qXr0ZgJPYALev3WCLp0_S6n_i28QXUivyH3hD-nYxKY8ncaEutm9uVPX3x4SuAfys0LVI4PDoHNVMOF1p5O4J56rwGSwnYtR5wmPIapDeSqD_3zuI184DDlQceHuluEdjPXlDMTnsB78TFnWflg_n65JazIV53cs7cSwsHr8k_Xn_KAUmyoZp1QJlibb4CO_G72iuMYEtJ_IjUQ
```
## Enter cluster info   

![qbo in Linux](k8s_integration.png)

## Allow outbound connections 
> If the Kubernetes cluster is in the local network  

![qbo in Linux](outbound_requests.png)





Start the devnet:
```bash
./run
```
> Kurtosis currently has no way of restarting an enclave, so we can clean the enclave each time we want to run it


See which services are running and on what ports:
```bash
kurtosis enclave inspect devnet
```

Follow logs for a service: 
```bash
kurtosis service logs -f devnet <name-of-service>
```

Stop an enclave:
```bash
kurtosis enclave stop devnet
```

Tear down an enclave:
```bash
kurtosis enclave rm -f devnet
```

Wipe all enclaves:
```bash
Kurtosis clean -a
```


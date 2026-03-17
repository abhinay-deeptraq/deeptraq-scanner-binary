Download Command: 
``` bash
wget https://raw.githubusercontent.com/abhinay-deeptraq/deeptraq-scanner-binary/main/deeptraq-scanner -O deeptraq-scanner && chmod +x deeptraq-scanner
``` 

For Code Scanning:
``` bash
./deeptraq-scanner . --code-scan --api-key 2eb1c889afc73464002a307da508f3f370eb0e053a7ee7444c13b03cbc6bc6f8

```

For Secrets Scanning
``` bash
./deeptraq-scanner . --secrets-scan --api-key 2eb1c889afc73464002a307da508f3f370eb0e053a7ee7444c13b03cbc6bc6f8
```

For Sonar Scanning
```bash
./deeptraq-scanner . --sonar --api-key 2eb1c889afc73464002a307da508f3f370eb0e053a7ee7444c13b03cbc6bc6f8 --scan-name test
```
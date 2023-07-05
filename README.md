Run 

```bash
mvn -X license:aggregate-add-third-party@generate-and-check-licenses -Dlicense.skipAggregateAddThirdParty=false -Dlicense.thirdPartyFilename=DEPENDENCY-LICENSES -Dlicense.outputDirectory=target -Ptool-license
```

Note:

`DEPENDENCY-LICENSES` in the root directory is a static asset used as a reference to check for license modifications.

# Running Project Summaries

Make sure you can run powershell scripts, open a powershell terminal "as administrator" and then run:
```
Set-ExecutionPolicy Bypass
```

Next up all you have to do is run the following commands from the project's root folder

```
.\generateProjectSummaries.ps1 `
    -sourcePat "<PERSONAL ACCESS TOKEN>" `
    -sourceOrg "https://dev.azure.com/orgname" `
    -outFile ".temp\projects.csv"
```

Then you should see the resulting projects.csv generated.

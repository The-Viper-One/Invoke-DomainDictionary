# Invoke-DomainDictionary
Parses information from the Current or specified Domain into a dictionary file to be used for password cracking


### Load into memory
```
IEX(New-Object System.Net.WebClient).DownloadString("https://raw.githubusercontent.com/The-Viper-One/Invoke-DomainDictionary/main/Invoke-DomainDictionary")
```

### Commands
```
Invoke-DomainDictionary                        # Run with default options
Invoke-DomainDictionary -Domain [Domain]       # Speciy the domain from which to collect from
Invoke-DomainDictionary -File [PATH\FileName]  # Specify name of output file
```


### Sample

![image](https://user-images.githubusercontent.com/68926315/233142893-42ee5835-02d9-44d6-80e1-94356df4a954.png)

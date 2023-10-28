# Install-Windows-11-Unsupported-PC
## 1. Download windows 11
https://www.microsoft.com/software-download/windows11

Modify file ```sources\appraiserres.dll```<br>
Search for ```tpm```

Delete
```
  [FT_All_AssetTypeForTpmVersion]
  I:AssetType=LT_AssetTypeForTpmVersion
```
Save file<br>
Run ```Setup``` file

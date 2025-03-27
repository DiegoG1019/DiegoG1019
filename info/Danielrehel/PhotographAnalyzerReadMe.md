# Danielrehel.PhotographAnalyzer

## Build Process
- Clone [this repository](https://github.com/GLV-Devs/GLV.Shared) in a folder parallel to the folder of this project's repository. See the following image for reference.
  - If the code doesn't work (probably because it's been modified), clone from [this commit](https://github.com/GLV-Devs/GLV.Shared/tree/7bf5f0ffc2c3d761409486469159e85b94587a33) (`7bf5f0f`)
- Fill out `appsettings.json` as shown in a later image
  - Note that `appsettings.Development.json` WILL BE IGNORED when the project is run as a Release Build (such as when using `dotnet publish`)
- Open the solution with Visual Studio and run/compile/publish it.
  - Alternatively, you can also call `dotnet publish` from `./Danielrehel.PhotographAnalyzer/Danielrehel.PhotographAnalyzer` (where `Danielrehel.PhotographAnalyzer.csproj` is located)
 
The folders structure should look like this:
![image](https://github.com/user-attachments/assets/4a2fcfab-1216-4a77-a558-616bc62ac110)
(Note that whatever folders are in the same folder as these two is not important)

The `appsettings.json` should include the following config block with the placeholders filled out appropriately
```json
"ImageKitOptions": {
  "PublicKey": "public_zlb/f5p1sswQ4ByLCajXguXaWR0=",
  "PrivateKey": "private_YifRqVmwi+GPuemnWjcEIAXgnbE=",
  "Endpoint": "https://ik.imagekit.io/diegogduden/"
}
```
![image](https://github.com/user-attachments/assets/2e4022e1-afc3-490e-af99-4b36a3300ed4)
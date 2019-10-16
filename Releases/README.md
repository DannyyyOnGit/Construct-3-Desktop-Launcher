# How To Push Main App Updates
1. Create archive of files inside "Appexports" folder
2. Increment "appver" inside database manifest file (ALSO INCREMENT VARIABLE INSIDE APP ITSELF!)
3. Move archive into releases folder and upload
4. Update "applink" inside database manifest file
5. Post update info on forum

# How To Upload Custom NWjs Builds
1. Download latest Win 64 stable SDK build (https://nwjs.io/downloads/)
2. Rename "nw.exe" to "Construct3.exe"
3. Move "icon.png" from "NWJSexports" into build folder
4. Create release on GitHub and upload (delete old)
5. Increment "c3verNW" inside database manifest file
6. Update "c3linkNW" inside database manifest file

# How To Update Official Builds
1. Increment "c3verO" inside database manifest file
2. Update "c3linkO" inside database manifest file
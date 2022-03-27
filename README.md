# Windows-fake-monitor
windows fake graphics card and fake monitor based on [indirect display] from Microsoft 

link:https://github.com/microsoft/Windows-driver-samples/tree/master/video/IndirectDisplay

this is a prebuild version of the source code 
to use this you will need to do windows advance restart and disable driver signature enforcement 
the install the license under the ":\Windows-driver-samples-master\Windows-driver-samples-master\video\IndirectDisplay\x64\Release"
install for" current user" or insatall for "local machine" seems to be both find then "palce all certificates in the following store" pick "  "Trusted Root Certification Authorities" 

and then install the inf file in the ":\Windows-driver-samples-master\Windows-driver-samples-master\video\IndirectDisplay\x64\Release\"IddSampleDriver" "
back to the ":\Windows-driver-samples-master\Windows-driver-samples-master\video\IndirectDisplay\x64\Release " then run "IddSampleApp.exe " as administrator

then I think the virtual monitor and the virtual graphic card should both show up ???????????

IF YOU WANT TO EDIT THE FILE PLZ REDOWNLOAD FORM :https://github.com/microsoft/Windows-driver-samples YOU WILL NEED ALL OTHER SAMPLES TO COMPLITED THE BUILD WITH VISUAL STUDIO 
2019 (ps. I don't know why it happen like this)
![github-samll](https://cdn.discordapp.com/attachments/857047152684564523/957456110481186936/unknown.png)

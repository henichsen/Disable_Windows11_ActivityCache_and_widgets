# Disable ActivityCache and widgets completely
## tested on Microsoft Windows 11 Home version 25H2 10.0.26200.7171


  check absence of ActivitiesCache with WindowsKey+R 

  ´%LocalAppData%\ConnectedDevicesPlatform´
 
  with the absence of deleted directory after restart
  
  check absence of widgets with no widgets appearing in the taskmanager
  
  additional remove widget package with admin-powershell
  
  ´Get-AppxPackage *WebExperience* | Remove-AppxPackage´

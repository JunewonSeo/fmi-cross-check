Model:
      Modelica Standard library model
      Rectifier
      
      FMI Type:
      ModelExchange
      
      Generation Tool:
      Dymola 2015 FD01
      
      Available Platforms:
      win32, win64
      
      Known Errors:
      
      Additional Information:
      
      
        
      FMUChecker:
      FMUChecker Version 2.0.1 
      
      run command:
      set FMUName=Rectifier
      fmuCheck.win32.exe -k me -e %FMUName%_cc.log -o %FMUName%_cc.csv -h 2e-7 -s 0.1 %FMUName%.fmu
      
      Contact info: karl.wernersson@3ds.com

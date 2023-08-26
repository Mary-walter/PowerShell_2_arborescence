# PowerShell_2_arborescence

**Historiques des commandes**

 Id CommandLine                                                                                                      
  -- -----------                                                                                                      
   1 Set-Location -Path C:\...                                                                                        
   2 Set-Location C:\                                                                                                 
   3 New-Item -Path EvenFolder -ItemType Directory                                                                    
   4 New-Item -Path OddFolder -ItemType Directory                                                                     
   5 Set-Location C:\FolderTest1                                                                                      
   6 Move-Item -Path file2 file4 -Destination C:\EvenFolder                                                           
   7 Move-Item -Path file2 -Destination C:\EvenFolder                                                                 
   8 Move-Item -Path file4 -Destination C:\EvenFolder                                                                 
   9 Move-Item -Path file1 -Destination C:\OddFolder                                                                  
  10 Move-Item -Path file3 -Destination C:\OddFolder                                                                  
  11 Move-Item -Path file5 -Destination C:\OddFolder                                                                  
  12 Set-Location C:\FolderTest2                                                                                      
  13 Move-Item -Path file7 -Destination C:\OddFolder                                                                  
  14 Move-Item -Path file9 -Destination C:\OddFolder                                                                  
  15 Move-Item -Path file6 -Destination C:\EvenFolder                                                                 
  16 Move-Item -Path file8 -Destination C:\EvenFolder                                                                 
  17 Move-Item -Path file10 -Destination C:\EvenFolder                                                                
  18 Set-Location C:\                                                                                                 
  19 Move-Item -Path file1 -Destination C:\OddFolder                                                                  
  20 Get-History > historique.txt                                                                                     
  21 Get-History > historique.txt                                                                                     
  22 Get-History > historique.txt                                                                                     
  23 Get-History > historique.txt                                                                                     
  24 Set-Location C:\FolderTest1                                                                                      

**Listing du contenue de dossier**

 Répertoire : C:\Folder\EvenFolder


Mode                 LastWriteTime         Length Name                                                                
----                 -------------         ------ ----                                                                
-a----        26/08/2023     19:47              0 file10                                                              
-a----        26/08/2023     19:47              0 file2                                                               
-a----        26/08/2023     19:47              0 file4                                                               
-a----        26/08/2023     19:47              0 file6                                                               
-a----        26/08/2023     19:47              0 file8                                                               


    Répertoire : C:\Folder\FolderTest1


Mode                 LastWriteTime         Length Name                                                                
----                 -------------         ------ ----                                                                
-a----        26/08/2023     20:45           6254 historique.txt                                                      
-a----        26/08/2023     20:50              0 listing.txt                                                         


    Répertoire : C:\Folder\OddFolder


Mode                 LastWriteTime         Length Name                                                                
----                 -------------         ------ ----                                                                
-a----        26/08/2023     19:47              0 file1                                                               
-a----        26/08/2023     19:47              0 file3                                                               
-a----        26/08/2023     19:47              0 file5                                                               
-a----        26/08/2023     19:47              0 file7                                                               
-a----        26/08/2023     19:47              0 file9                                                               


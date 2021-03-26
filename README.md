# finding-files

$file = Read-Host -Prompt "what type of file would you like to choose (.jpg, .txt, .jpeg, .png .pdf)"

if($file -eq '.jpg'){
    Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.jpg)
    }else { 
        write-host('check your home screen for a text document labeled output')
    }

if($file -eq '.txt'){
    Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.txt)
    }else { 
        write-host('check your home screen for a text document labeled output')
        }

if($file -eq '.jpeg'){
    Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.jpeg)
     }else { 
        write-host('check your home screen for a text document labeled output')
            }
        
if($file -eq '.png'){
    Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.png)
    }else { 
        Write-host('check your home screen for a text document labeled output')
                }

if($file -eq '.gif'){
    Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.gif)
    }else { 
        write-host('check your home screen for a text document labeled output')
                    }

if($file -eq '.pdf'){
   Add-Content $home\Desktop\output.txt (Get-ChildItem 'C:' -Recurse *.pdf)
    }else { 
        write-host('check your home screen for a text document labeled output')
                    }

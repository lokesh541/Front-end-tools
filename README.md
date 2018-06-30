
##Front end tools docs

###Getting Started with Browser-sync

   - Install browser-sync
   
        npm install -g browser-sync  
      
      
      
   - Starting Browser-sync
   
    command to watch for changes in files from the current directory and it's subdirectories
            
browser-sync start --server --files="**/*" 
 
 
###Git commands

     git init 

Creates an empty git repository or reinitialize existing one

     git status 

You should run the git status command again to see how the repository status has changed

     git add file-name 

 Adds the file to staging are and tracks the changes

     git commit -m "commit message" 

 commits the changes to the files  in the staging area




### Libraries and frameworks

   We can add libraries and frameworks to our project in three different ways 


   1. Downloading a copy of library from  the Official website of the library
   
   2. Using CDN links 
   

        <!-- Latest compiled and minified CSS -->                                                
      ```  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" > ```
    
    
    You can find CDN links for popular libraries here:
    
    

    - [cdnjs](https://cdnjs.com/libraries)
    - [google hosted libraries](https://developers.google.com/speed/libraries/)
        
   3. Install using Package managers 
    
         - Installing a library with bower package manager
         
              bower install [library-name] 
           
           ex:- Install bootstrap with bower

               bower install bootstrap 
           
           - Installing a library using NPM
           
                npm install [library-name] 

    

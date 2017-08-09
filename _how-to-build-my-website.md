# How to Build this site:

1. clone to RStudio
2. library(rmarkdown)  # Probably not necessary as it should be built-in
3. Environment | History | **Build** tab > Build Website button

    - Or, `rmarkdown::render_site()`
    
4. Manipulate some files

5. copy /docs web serving location

    - e.g. github repo served by Netlify
    - in this case:  rfun (blogdown-rfun2 on github)
    - I'm putting the /docs directory into the *static* directory in rfun2

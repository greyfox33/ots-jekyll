# ots-jekyll

# steps for editing/adding 

1. edit the pages in the ots-jekyll repo using VS Code
2. test the pages. from within the ots-jekyll directory 
    $bundle exec jekyl serve
or, to just build and if any errors, do "bundle exec jekyll build"
3. view and test the site to make sure all is well
3. Once everything is working, copy the entire contents of _site to greyfox33.github.io
- make sure the CNAME file is there
5. run $sh update.sh  -- this updates git, and pushes the files to greyfox33.github.io
6. Wait 2 minutes and then check the site. The changes should be pushed there succesfully. 


# steps to build from scratch

+ install node. Then: $npm install jekyll. Then install git bash
+ install ruby. then install jekyll
   ++ gem install jekyll
   ++ gem install bundler
+ cd into the ots-jekyll directory (that is backed up on onedrive) and run 
   ++ bundle exec jekyll serve  -- this should serve the site on 127.0.0.1:4000 

Notes:
based on https://idratherbewriting.com/documentation-theme-jekyll/index.html
# LAYOUT 5 (of the Become a Bootstrap Expert Course on Udemy)

1. Make a New Workspace on C9.io
2. Give it a name: bootstrapbase-accountants-academy
3. Give it a description: Layout 5 (From the Course: Become a Bootstrap Expert, Build 20 Layouts)
4. We are going to do something similar to the 2nd video in Section 7. Only this time we will do it faster and with some more advanced commands, since we've already done it before, so we need to build on our knowledge. If you're curious as to our progress, you can check out the video titled "Add Jekyll and use Bootstrap with it". That's the second video in Section 7.
5. npm install bower
6. bower install bootstrap
7. gem install jekyll
8. which ruby; which jekyll; jekyll -v (this step is optional)
9. jekyll new jekyll --blank
10. jekyll serve --host $IP --port $PORT --baseurl ''
11. cd jekyll; mkdir assets
12. copy from bootstrap docs starter code (at http://getbootstrap.com/getting-started/#template) to c9 index.html
13. Can't reference bower .css and .js files directly; we need to copy-paste them to jekyll/assets/css and jekyll/assets/js
  - mkdir jekyll/assets/css jekyll/assets/js
  - cp bower_components/bootstrap/dist/css/bootstrap.css jekyll/assets/css/bootstrap.css
  - cp bower_components/bootstrap/dist/css/bootstrap.css.map jekyll/assets/css/bootstrap.css.map
  - cp bower_components/jquery/dist/jquery.js jekyll/assets/js/jquery.js
  - cp bower_components/jquery/dist/jquery.min.js jekyll/assets/js/jquery.min.js
  - cp bower_components/jquery/dist/jquery.min.map jekyll/assets/js/jquery.min.map
14. Update the links to bootstrap css, jquery and bootstrap js inside our starter file
15. jekyll serve --host $IP --port $PORT --baseurl ''
16. Click the SHARE link in C9.io editor, and copy-paste the second address from the editor, to a new browser tab's address bar
17. cd into workspace
18. git init
21. github.com/new
21. Add remote repository
22. git checkout -b gh-pages
23. git add --all
24. git commit -m "Initial commit" 
25. git push -u origin gh-pages
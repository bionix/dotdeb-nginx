To build Nginx, copy the `debian/` subdirectory in the Nginx vanilla source directory and clean it this way :
```
find debian/ -name '\.git*' -exec rm -rf {} \; &>/dev/null
rm -r debian/modules/nginx-upload-progress/test/
rm -r debian/modules/ruby-passenger/debian/
rm -r debian/modules/ruby-passenger/rpm/
rm -r debian/modules/ruby-passenger/test/
```

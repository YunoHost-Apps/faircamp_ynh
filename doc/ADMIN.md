- Your Faircamp is installed in `__INSTALL_DIR__`
- Your content should be in `__INSTALL_DIR__/content`
- Your config file is `__INSTALL_DIR__/content/manifest.eno` (see [docs](https://simonrepp.com/faircamp/manual/manifests.html))
- The website will be automatically updated each time you modify something inside the `content` folder!

If you need to run the build by hand:

- `sudo -u __APP__ "__INSTALL_DIR__/faircamp" --build-dir "__INSTALL_DIR__/www" --catalog-dir "__INSTALL_DIR__/content"`

or

- `cd __INSTALL_DIR__`
- `./faircamp --build-dir ./www --catalog-dir ./content`

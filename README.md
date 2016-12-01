# Typo3 - default project, config and extensions
This is a collection of several information about typo3. It is going to start by a short install section with some minor hints and tricks. In the future there will be many examples and templates to get startet fast an easy and setting up bigger project in an easy way. 

## Content:
- [Installing Typo3](#installing-typo3)
- [Setting up language](#setting-up-language)
- [New distribution](#creating-new-distribution)
- more to come

# Installing Typo3

### SSH and symlinks are possible
* Uncompress the `typo3_src-x.x.x.tar.gz` file one level above the document root of your web server:
```
/var/www/site/htdocs/ $ cd ..
/var/www/site/ $ tar xzf typo3_src-x.x.x.tar.gz
```

* Create the symlinks in your document root:
```
  cd htdocs
  ln -s ../typo3_src-x.x.x typo3_src
  ln -s typo3_src/typo3
```

* Copy the .htaccess and index.php to your Document Root:
```
  cp typo3_src/index.php index.php
  cp typo3_src/_.htaccess .htaccess
```

You end up with the follow structure of files:
```
  typo3_src-x.x.x/
  htdocs/typo3_src -> ../typo3_src-x.x.x/
  htdocs/typo3 -> typo3_src/typo3/
  htdocs/index.php
  htdocs/.htaccess
```

# Setting up language
to be done

# Creating new distribution 
to be done

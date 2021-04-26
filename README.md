### Docksal environment setup

**!ATTENTION! installation may take a while, so it will be a great idea to grab yourself some tea**
 
```bash
git clone https://github.com/dlevchik/DreamTeam.git
cd DreamTeam
fin init
fin drush cim [to import sync files]
```

If everything works properly you would be able to see news content type on your drupal installation

### Differences between [original](https://github.com/docksal/boilerplate-drupal9-composer) 
- Edited commands: init, init-site
- Mysql user: DreamTeam::Dreamteam
- Drupal user: admin::DreamTeam
- Drupal Sync: /sync in web root
- Drupal uuid: de42e067-6fab-4359-8296-97489d9c0964

**Make sure you run fin drush cex and fin drush cim every time you commit**


### TODO:
- add modules to composer
- try to import db
- Edit .gitignore
- setup xdebug
- ~~fix [shortcut.set.default.yml](https://www.drupal.org/project/drupal/issues/2583113)~~

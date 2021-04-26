### Docksal environment setup
 
```bash
git clone https://github.com/dlevchik/DreamTeam.git
cd DreamTeam
fin init
fin drush csi [to import sync db]
```

If everything works properly you would be able to see news content type on your drupal installation(don't work at the moment)

### Differences between [original](https://github.com/docksal/boilerplate-drupal9-composer) 
- Edited commands: init, init-site
- Mysql user: DreamTeam::Dreamteam
- Drupal user: admin::DreamTeam
- Drupal Sync: /sync in web root

**Make sure you run fin drush content-sync:export and fin drush content-sync:import every time you commit**


### TODO:
- Edit .gitignore
- setup xdebug
- Fix sync import

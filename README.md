### Docksal environment setup

**!ATTENSION! installation may take a while so it will be a good idea to grab yourself some tea**
 
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
- Drupal uuid: de42e067-6fab-4359-8296-97489d9c0964

**Make sure you run fin drush content-sync:export and fin drush content-sync:import every time you commit**


### TODO:
- Edit .gitignore
- setup xdebug
- Fix sync import

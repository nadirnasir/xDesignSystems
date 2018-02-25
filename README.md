# xDesignSystems

This project is for collecting library items for ×CRM-Alpha

## TO DID
### Structure Replication 
#### Metronic-Angilar/ -> xDesignSystems/
* src/js -> src/includes/js
* src/sass -> src/includes/scss
* src/vendors -> src/includes/vendors
* src/media -> src/assets/media
### Compare package.json
* Copied extra package references as it is from Metronic-Angular/dist/demo/default/package.json to xDesignSystems/package.json
* Renamed package-lock.json to package-lock.old.json
* npm installed again. That installed Metronic related packages and created new package.lock.json
* package.lock.json has some versions discrepencies 
### Compare and Configure angular-cli.json
* Both files almost same with exceptioon of inlineTemplate and inlineStyle set to true in Metronic-Angular/dist/demo/default/.
* Need to add js and scss in angular-cli.json
### Exclude demo files except default
* Keeping all src files for now - In order to manually include each demo related file as needed.
* 


## To DO
- [x] Strcuture Replication
- [x] Compare package.json
- [x] Compare and Configure angular-cli.json
- [x] Add scripts and js angular-cli.json
- [ ] Exclude demo files except default
- [ ] Create modules and routes
- [ ] Copy demo-specific scss in respective modules and components
- [ ] See if /vendors can be installed and included via npm install and moved into node_modules
- [ ] Relink to media files - if needed

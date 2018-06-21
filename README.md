# Magento2 Reindex From admin
Reindex magento module helps admin to process index management from backend.

Reindex in magento 2x you need to run the command from the command prompt php bin/magento indexer:reindex but with this module you don't need to run command and you can Reindex your data easily from the backend Index management section.

Support Magento CE 2.0.x , 2.1.x  and 2.2.x

# Installation Guide for Reindex extension

1) Download module zip file and extract it on your magento root directory.
2) After this run below commands from Magento 2 root directory to install module.

   php bin/magento setup:upgrade<br>
   php bin/magento cache:clean<br>
   php bin/magento setup:static-content:deploy

3) Now login to admin panel and navigate to Stores > Configuration and configure settings for this extension

# Uninstall

  php bin/magento module:uninstall Dmn112_Reindex<br>
  php bin/magento setup:upgrade

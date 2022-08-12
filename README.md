# magento-docker
Docker-based development environment for Magento

### Usage
```bash
# Prepare a folder for Magento Docker
mkdir ~/Sites/magento2docker && cd $_

# One line install
curl -s https://raw.githubusercontent.com/rangerz/magento-docker/main/install | bash -s -- magento2.docker 2.4.5 CE

# Manual install dbin/ script
curl -s https://raw.githubusercontent.com/rangerz/magento-docker/main/update | bash
# Edit dbin/config for setting
dbin/install
dbin/build-compose
dbin/start
dbin/apply-patches
dbin/deploy
dbin/post-deploy
```

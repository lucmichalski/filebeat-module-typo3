A TYPO3 Log Parser Module to use with filebeat and ELK Stack

#Installation
1. On ubuntu: `cp -r module/typo3 /usr/share/filebeat/module` 
2. Copy base config `cp module.d/typo3.yml.disabled /etc/filebeat/module.d`
3. Add path to logfiles in `/etc /filebeat/module.d/typo3.yml.disabled`
4. Run `filebeat module activate typo3`
5. Run `filebeat setup -e`
6. Log Parser should now work.
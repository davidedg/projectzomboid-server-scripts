# projectzomboid-server-scripts
Project Zomboid - Dedicated Server handy scripts 

\
See the `cron` directory
\
Depencies (under the dedicated user home):
- Directories: ~/bin ~/cron /srv/pzserver-restic/online ~/backup-mnt/{online-local,online-s3,s3-raw,s3-raw-cache}
- Restic (https://github.com/restic/restic/releases), symlinked to ~/bin/restic
- install NodeJS NVM ([NVM](https://github.com/nvm-sh/nvm#install--update-script)
- install NodeJS NPM (`npm install --lts`)
- install `gamedig` (`npm install gamedig`)

\
See also: https://github.com/davidedg/projectzomboid-server-arm/tree/main

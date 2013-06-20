gitolite-deploy
===============

deploy system with gitolite

gitolite/hooks/common/post-receive is to put in the .gitolite/hooks/common/ directory of the gitolite user $HOME (default to /home/git )

chmod +x gitolite/hooks/common/post-receive

create dir /home/git/deploy/conf/ ( DEPLOY_CONFIG_DIR)



- umask in gitolite can be configured in .gitolite.rc (for example 0007) : probably required for deploy with correct permissions

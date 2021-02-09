#Set these in my.cnf to prevent MYSQL Server from crashing
wait_timeout = 600
max_allowed_packet = 100M

#Extract sql dump into a database example :
zcat school_spider_dev.gz | mysql -uroot -p -h 127.0.0.1 --max_allowed_packet=1073741824 school_spider_dev

#Create Symbolic link
ln -sf ~/.oh-my-zsh/custom/aliases.zsh ~/dotfiles/aliases.zsh 

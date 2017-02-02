cd /var/www/html
wget https://wordpress.org/latest.zip
unzip latest.zip -d /var/www/html/
mv wordpress/* .
rm latest.zip
chown -R nginx:nginx .

while true; do
    read -p "Did you run the installer in the browser?" yn
    case $yn in
        [Yy]* ) sed -i "/define('WP_DEBUG','false');/a define('FS_METHOD','direct');" wp-config.php; break;;
        [Nn]* ) exit;;
        * ) echo "Please answer yes or no.";;
    esac
done




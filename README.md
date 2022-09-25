
to make your repository faster

Edit the dnf configuration file
sudo nano /etc/dnf/dnf.conf
    
Add the following lines:
deltarpm=false
keepcache=true
ip_resolve=4

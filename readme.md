## Getting Started

 - Install the latest version of PHP and enable all the extensions for magento
 - Install composer
 - Install Docker
 - Create auth.json file for magento credentials https://devdocs.magento.com/guides/v2.3/install-gde/prereq/connect-auth.html
 - Run the following Steps
    - For users running Mac OS or Linux .sh scripts have been provided with the same names. To use the scripts you need to make them executable: ```chmod +x scriptname.sh```, they can be run by using: ```./scriptname.sh```
   

# Step 1

Run MYSQL and ElasticSearch

```bash
    docker-compose up
```

# Step 2 

Download Magento into public_html
```
download
```

# Step 3
```
install
```

# Step 4
```
run
```


# Footnotes

**Getting magento auth credentials:**
https://experienceleague.adobe.com/docs/commerce-operations/installation-guide/prerequisites/authentication-keys.html

**Docker issues**

Windows:
```cmd
wsl -d docker-desktop
sysctl -w vm.max_map_count=262144
```

Linux:
```bash
sysctl -w vm.max_map_count=262144
```

**Helper CLI Scripts**

```bash
# Install Sample Data
sample-data

# Run Magento bin
magento [arguments]

# Clear Caches
cache-clear
```

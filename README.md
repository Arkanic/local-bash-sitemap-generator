# local-bash-sitemap-generator
Generates a .txt sitemap file from the folder that it is inside. Useful for CI sitemap generation scripts.
## Usage
copy/download the script into the folder you want to map
use your preferred text editor and change the "url" variable to the url that the sitemap file will end up on (no / at the end)
give the script file execute perms (`chmod +x sitemap.sh`)
and run (`./sitemap.sh`)
in a couple of seconds you should see a "sitemap.txt" file, which contains the sitemap/folder map of the entire folder, which can be used by almost all search engines to map your site.

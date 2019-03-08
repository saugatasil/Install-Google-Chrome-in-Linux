# Install-Google-Chrome-in-Linux

step 1 : apt-get update

step 2 : dpkg -i chrome_package_name.deb

step 3 : apt-get install -f

step 4 : nano /opt/google/chrome/google-chrome

step 5 : (search this code)            exec -a "$0" "$HERE/chrome" "$0"

step 6 : (add this code beside step 5) --user-data-dir --no-sandbox

step 7 : ctrl + x to save 

start chrome browser and njoy

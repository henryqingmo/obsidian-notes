nativefier https://instagram.com --name Instagram --internal-urls .*instagram.com.* -m -i instagram-nativefier.png
sudo mv Instagram-linux-x64/ /opt/
sudo ln -s /opt/Instagram-linux-x64/Instagram /usr/bin/instagram-nativefier
sudo mv instagram-nativefier.desktop /usr/share/applications/

Icon goes into /usr/share/icons/hicolor/resolution/apps

 



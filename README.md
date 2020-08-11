# Dash to Panel Settings

## Import Settings
1. Download [dash-to-panel](https://extensions.gnome.org/extension/1160/dash-to-panel/) extension. Save the ZIP archive in a directory, e.g. `~/Downloads`.

2. Install the extension.
	```
	gnome-extensions install ~/Downloads/dash-to-paneljderose9.github.com.v38.shell-extension.zip
	```

3. Log out, and log in again to your desktop.

4. Enable the extension.  
Press **Super** key, and type **Extensions** in the search box. Click on **Extensions** in the application search results.  
Then, set the **Dash to Panel** switch to ON.

5. Clone this repository.
	```
	git clone https://github.com/ytx21cn/dash-to-panel-settings.git`
	```

6. Right-click on the **Show Applications** button, and open **Dash to Panel Settings**.

7. Switch to the **About** tab, and click on the **Import from file** button.  
In the file selection window, navigate to the directory where you have cloned this Git repository.  
Then select **`dash-to-panel-settings.txt`**.

8. Now your settings are imported. Everything is done.

## Export Settings
1. Right-click on the **Show Applications** button, and open **Dash to Panel Settings**.

2. Switch to the **About** tab, and click on **Export to file** button.  
In the file selection window, navigate to the directory where you have cloned this Git repository.  
Then select **`dash-to-panel-settings.txt`**.

3. Push changes to GitHub.  
	```
	git add dash-to-panel-settings.txt
	git commit -m "<Your commit message>"
	git push origin master
	```

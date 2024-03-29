# LINUX

<details><summary>Links</summary>
<p>

</p>
</details>

## GENERAL

<details><summary>Linux command line general tips</summary>
<p>

  <details><summary>Remove files starting with a dash</summary>
  <p>
    
  ```bash
  #Method 1
  rm -- --my-file.txt
  ```

  </p>
  
  <p>
    
  ```bash
  #Method 2
  rm ./--my-file.txt
  ```

  </p>
  </details>
  
  <details><summary>Install package on alpine linux</summary>
  <p>
    
  ```bash
  apk -U add <package-name>
  ```

  </p>
  </details>

  <details><summary>Simulate removal of apt-get cache files from disk</summary>
  <p>
    
  ```bash
  sudo apt-get clean --dry-run
  ```

  </p>
  </details>
  
  <details><summary>Remove apt-get cache files from disk</summary>
  <p>
    
  ```bash
  sudo apt-get clean
  ```

  </p>
  </details>
  
  
</p>
</details>

## GNOME

<details><summary>Gnome related settings</summary>
<p>

  <details><summary>Display all buttons on menu bar</summary>
  <p>
    
  ```bash
  # The command gsettings can be used to change multiple gnome settings
  gsettings set org.gnome.desktop.wm.preferences button-layout 'appmenu:minimize,maximize,close'
  ```

  </p>
  </details>

  <details><summary>Disable gnome animations</summary>
  <p>
    
  ```bash
  gsettings set org.gnome.desktop.interface enable-animations false
  ```

  </p>
  </details>

  <details><summary>Watch for changes in gnome configuration</summary>
  <p>
    
  ```bash
  # Change the path to watch for specific settings - /org/gnome/desktop/interface
  dconf watch /
  ```

  </p>
  </details>

</p>
</details>

### TERMUX SETUP TO RUN BOT

## DOWNLOAD TERMUX FROM FOLLOWING LINK

[DOWNLOADS](https://www.mediafire.com/file/3kjthqmugbsgtcq/TERMUX1000.apk/file)

---

## INSTALLATION

1. ```bash
   pkg update && pkg upgrade
   ```
2. ```bash
   pkg install nodejs
   ```
3. ```bash
   pkg install python
   ```
4. ```bash
   pkg install nano
   ```
5. ```bash
   pkg install nano
   ```
6. ```bash
   cd ~
   ```
7. ```bash
   mkdir .gyp
   ```
8. ```bash
   nano .gyp/include.gypi
   ```
9. `Copy this file`

   ```
   {
    "variables": {
    "android_ndk_path": ""
     }
   }
   ```
   **`To Save press CTRL + X + Y
Enter`**

## OR YOU CAN ALSO `COPY` THE CODE BELOW
  
  ```bash
  echo 'export GYP_DEFINES="android_ndk_path="' >> ~/.bashrc && source ~/.bashrc
  ```

  ---
   

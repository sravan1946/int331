# How to install maven in windows
1. Download Maven from the official website: https://maven.apache.org/download.cgi  
2. Extract the downloaded archive to a preferred location on your computer (e.g., `C:\Program Files\Apache\maven`).
3. Add the Maven `bin` directory to your system `PATH`:
   - Open **Control Panel** → **System and Security** → **System** → **Advanced system settings**.
   - Click **Environment Variables**.
   - Under **System variables**, select `Path` and click **Edit**.
   - Add the full path to Maven's `bin` folder (e.g., `C:\Program Files\Apache\maven\bin`).
   - Click **OK** to save.
4. Open a new Command Prompt and type `mvn -version` to verify Maven is correctly installed.

# Hoq to install maven in linux (ubuntu)
1. Update your package index:
   ```
   sudo apt update
   ```
2. Install Maven using apt:
   ```
   sudo apt install maven
   ```
3. Verify the installation:
   ```
   mvn -version
   ```
If Maven is installed correctly, you'll see the version information displayed.


# How to install java in windows
1. Download the latest Java JDK from the official Oracle website: https://www.oracle.com/java/technologies/downloads/

2. Run the installer and follow the installation instructions.

3. After installation, open the Start menu and search for "Environment Variables." Click "Edit the system environment variables."

4. In the System Properties dialog, click the "Environment Variables" button.

5. Under "System variables," find and select the variable named `Path`, then click "Edit."

6. Click "New" and add the path to the `bin` directory of your Java installation (e.g., `C:\Program Files\Java\jdk-XX.X.X\bin`).

7. Click OK to close all dialogs.

8. Open Command Prompt and type `java -version` and `javac -version` to verify the installation.

9. (Optional but recommended) Set the `JAVA_HOME` environment variable:

   - In the "Environment Variables" window, click "New..." under "System variables".
   - For **Variable name**, enter `JAVA_HOME`.
   - For **Variable value**, enter the path to your JDK installation directory (e.g., `C:\Program Files\Java\jdk-XX.X.X` — **do not** include `\bin`).
   - Click OK to save.
   - You may need to restart your Command Prompt or your computer for changes to take effect.

   Setting `JAVA_HOME` allows Java-based tools and applications to locate your Java installation.

# How to install java in linux (ubuntu)
1. Open Terminal.

2. Update your package index:
   ```
   sudo apt update
   ```

3. Install the default Java Development Kit (JDK):
   ```
   sudo apt install default-jdk
   ```

4. Verify the installation:
   ```
   java -version
   javac -version
   ```

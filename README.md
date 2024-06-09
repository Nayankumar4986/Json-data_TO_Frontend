It looks like you're encountering issues with the command syntax for PowerShell. Let's use the correct PowerShell commands to remove the `node_modules` directory and `package-lock.json` file:

1. **Remove `node_modules` directory and `package-lock.json` file** in PowerShell:
   ```powershell
   Remove-Item -Recurse -Force node_modules
   Remove-Item package-lock.json
   ```

2. **Clear npm cache**:
   ```powershell
   npm cache clean --force
   ```

3. **Reinstall dependencies**:
   ```powershell
   npm install
   ```

4. **Ensure Vite is installed locally**:
   ```powershell
   npm install vite --save-dev
   ```

5. **Check if Vite is installed**:
   ```powershell
   Get-ChildItem node_modules/.bin
   ```

6. **Run the development server**:
   ```powershell
   npm run dev
   ```

   ![Example Image](https://github.com/Nayankumar4986/Json-data_TO_Frontend/blob/main/1.png)



By using the correct PowerShell commands, you should be able to remove the `node_modules` directory and `package-lock.json` file, and proceed with reinstalling dependencies and running the development server.

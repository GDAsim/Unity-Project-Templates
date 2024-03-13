# How to Create Project Template

### 1.  Navigate to Unity Install Path
### 2.  Go to Project Templates Folder
### - E.g. Windows:
	C:\Program Files\Unity\Hub\Editor\{Unity Version}\Editor\Data\Resources\PackageManager\ProjectTemplates
### E.g. Mac:
	/Applications/Unity/Unity.app/Contents/Resources/PackageManager/ProjectTemplates
### 3. Copy Existing Template & Rename
	Format: com.unity.template.{name}–{versionnumber}.tgz
	Example: com.unity.template.custom–1.2.3.tgz
### 4. Modify Package.Json
#### 4.1 Open template file using 7-Zip
- Change name to match the updated name of the package done in **Step 3**
- Change version to match the updated version number of the package done in **Step 3**
- Change displayName & description (Optional)
- Change Dependencies if needed (Optional)
- Change Repository if this package is to be hosted in online repository (Optional)

### 6. Create new Unity Project for Template
### 7. Add Scripts & Install Any Packages for Template
### 8. Copy Assets,Packages and ProjectSettings Folder into Template Package

-------------

# How to Install Project Template
### 1. Copy your template over to the Project Templates Folder
### 2. Restart Unity Hub
### 3. The Custom template should be shown upon creating a new project template selection

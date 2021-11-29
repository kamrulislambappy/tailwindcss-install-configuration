# Tailwindcss install & Configuration
Follow the description below.

![Logo](https://github.com/kamrulislambappy/image/blob/main/tailwindcss%20install%20&%20configurations.png?raw=true)

## Install Tailwind CSS by Following 3 Step:

#### 1. Install Tailwindcss with the Terminal.
#### 2. Install Tailwindcss Visual Studio Code Extension.
#### 3. Configuration Tailwindcss Your Project
<br />

### There is no Git Bash Terminal on your PC? <br />
👉 Download Git bash terminal. Go link : [https://git-scm.com/downloads](https://git-scm.com/downloads) <br />
👉 Download Hyper terminal. Go link : [https://hyper.is/](https://hyper.is/)
<br /><br />

### Step number  > 1 :
Install Tailwindcss with the Terminal. 
<br />

**1.** Install Tailwind CSS. Type in the terminal ↓
```bash
 npm install tailwindcss
```
<br />

**2.** Go your file directory. Type in the terminal ↓ 
```bash
 cd desktop
```
<br />

**3.** Create project. Type in the terminal ↓
```bash
 mkdir Tailwindcss
```
<br />

**4.** Go your project directory. Type in the terminal ↓ 
```bash
 cd Tailwindcss
```
<br />

**5.** Type in the terminal ↓
```bash
 npm init –y
```
<br />

**6.** Type in the terminal ↓
```bash
 npm i -D tailwindcss
 ```
<br />

### Step number  > 2 :
Install Tailwindcss Visual Studio Code Extension. 
<br />

- Search extension from Visual Studio Code
```bash
 Tailwind CSS IntelliSense
```
![Logo](https://github.com/kamrulislambappy/image/blob/main/vs%20code%20tailwindcss%20extensions.png?raw=true)
<br /><br />

### Step number  > 3 :
Configuration Tailwindcss Your Project

**1.** Type in the terminal from your project. ↓
```bash
 npx tailwindcss init
```
- created `tailwind.config.js` file from your project. 
<br />

**2.** Create 2 folder. Folder name ↓
```bash
 output
```
```bash
 src
 ```
<br />
 
**3.** Create a `CSS` file inside `Src` folder ↓
```bash
 tailwind.css
```
<br />

**4.** Copy ↓↓↓ this code and paste it inside the `tailwind.css` file
```bash
 @tailwind base;
 @tailwind components;
 @tailwind utilities;
```
<br />

**5.** Create a `.vscode` folder. Create the `settings.json` file inside it. `.vscode/settings.json` 
<br />

**6.** Copy ↓↓↓ this code and paste it inside the `settings.json` file ↓
```bash
 {
 "css.validate": false,
 "tailwindCSS.emmetCompletions": true
 }
```
<br />

**7.** Copy ↓↓↓ this code and paste it inside `“scripts”` properties from `package.json` file. ↓
```bash
 "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w",
```
<br />

**8.** Create a `index.html` file. 
<br />

**9.** Copy ↓↓↓ this code and paste it inside the `index.html` file, above ↓
```bash
 <link rel="stylesheet" href="./output/tailwind.css" />
```
- Completed Tailwind CSS all configuration.
<br />

**10.** Finally run Tailwindcss. Type in the terminal from your project.  ↓
```bash
 npm run build
```

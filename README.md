# JavaScript Command Line Interface 
for Microsoft Windows
## Running the program
1: Open Windows PowerShell as administrator

2: Dowload the program from [GitHub](https://github.com/uvmcs2300f2025/CLI-JHemmett)
```
git clone https://github.com/uvmcs2300f2025/CLI-JHemmett
```
3: Download the Node.js JavaScript runtime environment [Node.js](https://nodejs.org/en/download) 
```
winget install OpenJS.NodeJS
```
4: If necessary, allow Powershell to run scripts
```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass 
```
```
npm --version
```
5: go to the correct directory
```
cd C:\Users\[your directory]
```
6: run greeting.js
```
node greeting.js [your name]     
```
## No .gitignore?
Javascript does not produce any executuable or compiled files, so a .gitignore is not needed.

## Resources used
* [node.js](https://nodejs.org/en/download)
* [Digital Ocean](https://www.digitalocean.com/community/tutorials/nodejs-command-line-arguments-node-scripts?utm_source=chatgpt.com)
* [Bro Code](https://www.youtube.com/watch?v=Ihy0QziLDf0)
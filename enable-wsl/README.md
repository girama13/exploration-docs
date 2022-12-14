# How To Enable WSL in Windows

WSL (Winndows Subsystem for Linux) is a feature of Windows that enables us to run Linux file system.

## Prerequisite
- Windows 10 version 2004 and higher (Build 19041 and higher) or Windows 11.
    
    > Check windows version using __Windows logo key__ + __R__, type __winver__, select __OK__

## Installation
1. Run __Windows PowerShell__ as __Administrator__.</br>
![run powershell as administrator](images/Screenshot1.png)
2. install wsl using this command
    ```
    wsl --install
    ```
3. Select the available Linux distributions using this command
    ```
    wsl --list --online
    ```
    The available distributions that can be installed so far are listed on the below image.</br>
    ![available linux distributions](images/Screenshot2.png)
4. Install the available distributions using this command
    ```
    wsl --install -d <Distro>
    ```
5. Restart computer
6. Go to __Microsoft Store__ and download the distro you have installed on your computer.</br>
    ![microsoft store](images/Screenshot3.png)
7. Access wsl by open your __powershell__ then execute below command
    ```
    wsl
    ```
    ![microsoft store](images/Screenshot4.png)</br>
    Or open the downloaded distributions.</br>
    ![microsoft store](images/Screenshot5.png)
8. Create your username and password
9. Done 

## Uninstall WSL
1. Open __Settings__
2. Click on __Apps__ > __Apps & features__
3. Searh linux on App list searchbar</br>
![uninstall linux](images/Screenshot6.png)
4. Uninstall __Windows Subsystem for Linux WSLg Preview__ and __Windows Subsystem for Linux Update__
5. Your WSL successfully uninstalled

# Installing Expo on Windows

## WSL
The best way to install expo on windows is by first installing WSL (Windows
Subsystem for Linux).

1. Let's start by opening Microsoft Store and search wsl.
    ![2.png](./images/2.png)
2. The first result will allow us to select Ubuntu.
    ![3.png](./images/3.png)
    ![4.png](./images/4.png)
3. Proceed to install it and launch it.
    ![5.png](./images/5.png)
4. On launch it will open this website:
    ![6.png](./images/6.png)
5. Following the instructions we need to run _Windows PowerShell_ as administrator
    ![7.png](./images/7.png)
6. Run the command on the instructions will ask to reboot: write **Y**
    ![8.png](./images/8.png)
    ![9.png](./images/9.png)

7. We successfully installed WSL, on first open it will create the user and
   password for your Linux account.
    ![10.png](./images/10.png)
    ![11.png](./images/11.png)
    ![13.png](./images/13.png)

## Node.js

To use node on our machine we will use nvm this will allow us to maintain
different versions of node if needed.
1. The best way to install it is by using the following command:

        curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

    ![29.png](./images/29.png)
2. We'll have to restart our Ubuntu shell to use nvm.

    ![16.png](./images/16.png)
3. To install node we simply run the command

        nvm install node
    ![17.png](./images/17.png)

## Finally installing expo-cli

Using our installed version of Node we can now install expo.

        npm installl -g expo-cli

![18.png](./images/18.png)
![19.png](./images/19.png)

### Verifying and using with Visual Studio Code

![20.png](./images/20.png)
![21.png](./images/21.png)
![26.png](./images/26.png)

- **The first time we open Visual Studio Code it will ask to install an
extension to use with WSL**

![24.png](./images/24.png)
![27.png](./images/27.png)
![28.png](./images/28.png)
![22.png](./images/22.png)
![23.png](./images/23.png)

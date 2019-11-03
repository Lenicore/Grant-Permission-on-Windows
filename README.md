# Grant-Permission-on-Windows
Take Ownership of files/folder 

### Getting Start

Run CMD as Administrator

```
### Method

Run following commands to grant permission to current user

```
TAKEOWN /F <type in the path of the folder that you want to take access> /R /D Y
```
Then run

```
ICACLS <type in the path of the folder that you want to take access> /grant administrators:F
```

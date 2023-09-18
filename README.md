# Microsoft Edge Uninstaller Script

This script assists users who encounter issues with corrupted Microsoft Edge instances by facilitating a clean uninstallation.

## Usage

1. Download and save the script from: <https://github.com/js1016/edgeuninstaller/releases/download/v1.0.0/UninstallEdge.ps1>
2. Unblock the script from **Properties**.
3. Open a PowerShell as administrator and navigate to the folder where you saved `UninstallEdge.ps1`.
4. Ensure PowerShell script execution is enabled, otherwise you need to run `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned` first.
5. Run script: `.\UninstallEdge.ps1` and follow the instruction to complete the process.

## What the Script Does:

-   **Uninstall**: Removes Edge, EdgeUpdate, and EdgeWebView2.

## Steps After Using the Script:

1. Download and install the [Microsoft Edge MSI](https://www.microsoft.com/en-us/edge/business/download?form=MA13FJ) for reinstallation.
2. Open the **Task Scheduler**.
3. Locate and manually execute the task named **MicrosoftEdgeUpdateTaskMachineUA**. This action will trigger the automatic installation of Edge WebView2.

## **Important Notes**:

-   Microsoft Edge, particularly Edge WebView2, is essential for many built-in Windows components, including Outlook.
-   **It's crucial** that you reinstall Edge promptly after using this script. The primary intent is to help with reinstallation, not to keep Edge uninstalled.
-   Extended periods without reinstalling might cause unpredictable system issues.

## Disclaimer:

Always ensure that you fully understand the implications of running scripts on your system. While this script aims to provide a solution to corrupted Edge instances, users are encouraged to proceed with caution. The author cannot be held responsible for any potential damages or issues arising from the use of this script.

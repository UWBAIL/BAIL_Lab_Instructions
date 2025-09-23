---
title: "Lab Printer"
categories:
  - Printer
---

This guide provides instructions for connecting to the Canon Color ImageCLASS MF753Cdw network printer for both Windows and macOS operating systems.

## Windows

To connect to the printer on a Windows device, please follow the steps below.

1.  Open **Settings** and use the search bar to find "Printers & scanners".

2.  Click on **Add a printer or scanner**.

    ![Windows Settings - Add a printer or scanner](/assets/images/print1.png)

3.  If the printer is not automatically discovered, select **The printer that I want isn't listed**, and then choose **Add a printer using a TCP/IP address or hostname**.

    ![Manually add a printer in Windows](/assets/images/print2.png)

4.  In the next window, configure the following settings:
    *   **Device type**: Select `Autodetect`.
    *   **Hostname or IP address**: Enter `10.18.96.144`

    ![Enter printer IP address](/assets/images/print3.png)

5.  Click **Next** and follow the remaining on-screen prompts to complete the installation.

## macOS

To connect a Mac to the printer using its IP address, follow these instructions:

1.  Open **System Settings**.
2.  Navigate to **Printers & Scanners** in the sidebar.
3.  Click the **Add Printer, Scanner, or Fax...** button.
4.  In the pop-up window, select the **IP** tab (the globe icon).
5.  Enter the following information:
    *   **Address**: `10.18.96.144`
    *   **Protocol**: Select `Line Printer Daemon - LPD` or `Internet Printing Protocol - IPP`.
6.  Click **Add** to complete the setup.

---

<div class="notice--info" markdown="1">
**Troubleshooting**

If you encounter any issues while connecting to the printer, please contact Thanu (thanu56@uw.edu) for assistance :)
</div>
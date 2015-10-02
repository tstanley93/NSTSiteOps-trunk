<%@ Page Title="NST Plotter Win7 Driver Installation" Language="C#" MasterPageFile="~/Site1.Master" AutoEventWireup="true" CodeBehind="Plotter_Drivers.aspx.cs" Inherits="NSTSiteOps.Plotter_Drivers" %>

<asp:Content ID="Content1" ContentPlaceHolderID="Content" runat="server">
    <style>
        body { font-family: Lucida Sans; }
        h1 { text-align: center; font-family: Lucida Sans; }
        h2 { font-family: Lucida Sans; }
        p { margin-left: 15px; text-indent: 15px; }
        td { border: 1px solid black; }
        .MainDiv { background-color: #EEE5DE; padding: 15px 125px 15px 125px;}
    </style>
    <div class="MainDiv">
        <h1>Configuring the Plotter in Windows 7 - <span style="color: Blue;">How To:</span></h1>
        <br />
        <h2>Installing the Driver:</h2>
        <p>Now that you have upgraded to Windows 7, a new set of drivers needs to be downloaded and installed so that you can hookup to the plotter.  The plotter 
        share name is still the same, and all of the features are still configured.  You will need to make sure you have "Administrator" right on your new 
        machine in order to install the drivers, and to configure the plotter.  See the table below to download the drivers for your machine.</p>
        <br />
        <table style=" margin-left: 40px; border: 1px solid black; border-collapse: collapse; "cellspacing="0">
            <tr>
                <td><h2 style="text-align: left; text-indent: 0px; padding: 3px;">Driver</h2></td>
                <td><h2 style="text-align: left; text-indent: 0px; padding: 3px;">Platform</h2></td>
            </tr>
            <tr>
                <td><a href="Files/Plotter/x32/HPDesignjet5500Series.exe" style="padding: 3px;">HP DesignJet 5500 Series</a></td>
                <td><h2 style="text-align: center; text-indent: 0px; padding: 3px;">x32</h2></td>
            </tr>
            <tr>
                <td><a href="Files/Plotter/x64/HPDesignjet5500Series.exe" style="padding: 3px;">HP DesignJet 5500 Series</a></td>
                <td><h2 style="text-align: center; text-indent: 0px; padding: 3px;">x64</h2></td>
            </tr>
        </table>
        <br />
        <p>Once downloaded, select "Run" to execute the installer, or double click on the installer where you downloaded it.  Agree to the "EULA" if you agree.  The 
        installer runs, and then scans the network for a printer.  Select your printer from the list, and follow the on-screen instructions to finish the installation.</p>
        <p>If the printer does not show up in the list of available printers, make sure the printer is powered on, and click the search again button.  If it still does not show up, read the Asset tag 
        number off of the printer.  Using a command window, ping the tag number, and record the IP address that is returned by the ping command.  Select the 
        "Help me find my printer" radial button, and click next.  Then next again for a printer connected to the network.  Select "Specify a printer by address", and 
        type the IP address you recorded earlier into the box, and click Next.   Follow the rest of the on-screen instructions to finish installing your printer.</p>
    </div>
</asp:Content>

<%@ Page Title="EMC Trouble Ticket" Language="C#" MasterPageFile="~/Site1.Master" AutoEventWireup="true" CodeBehind="EMC_Trouble_Ticket.aspx.cs" Inherits="NSTSiteOps.EMC_Trouble_Ticket" %>


<asp:Content ID="Content1" ContentPlaceHolderID="Content" runat="server">
    <style>
        body { font-family: Lucida Sans; }
        h1 { text-align: center; font-family: Lucida Sans; }
        h2 { font-family: Lucida Sans; }
        p { margin-left: 15px; text-indent: 15px; }
        .MainDiv { background-color: #EEE5DE; padding: 15px 125px 15px 125px; }
        .imgFloatRight { margin: 15px 15px 15px 100px; width: 250px; height: 260px; }
    </style>
    <div class="MainDiv">
        <br />
        <h1>EMC Trouble Ticket <span style="color: Blue;">How To:</span></h1>
        <br />
        <h2>Information To Gather:</h2>
        <p>Your first step is to gather the information you will need for the ticket.  From this web page, click on the "Team Tool Sites" link and 
        right click on "EMC Navisphere", and select open in new browser.  This will open the EMC Navisphere tool.  From this tool you will be able to gather all of the information
        that EMC will need to order the correct parts, where to deliver those parts, and how to bill Boeing for the parts under the standard Boeing Service Contract.</p>
        <table>
            <tr>
                <td><img src="_images/APM_Number.PNG"  alt="" class="imgFloatRight" /></td>
                <td><p>Login to Navisphere.  You will find the Serial Number of the EMC machine as you expand the nodes.  The number starts
        with the letters "APM".  Record this number, the EMC helpdesk will take this number and enter it into thier system.  This will tell them ALL of the information they
        need to know about the machine; like its location, type, how it is configured, and what software is loaded, and even what service contract the system is setup on.</p></td>
            </tr>
            <tr>
                <td><img src="_images/EMC_Disks.PNG" alt="" class="imgFloatRight" /></td>
                <td><p>Now expand the "Physical Node".  Expand the Bus, and Eclosure that has the failed device in it, and finally expand the "Disks" node.  You will find all of the physical
        disks listed.</p></td>
            </tr>
            <tr>
                <td><img src="_images/EMC_Disks_TLA_Number.PNG" alt="" class="imgFloatRight" /></td>
                <td><p>To make sure that EMC knows exactly which type of disk drive to send out and replace.  Right click on one of the <span style="color: Green; font-weight: bold;">"GOOD"</span> disks 
        and click properties.  In the properties tab you will find the Clariion TLA Partner of the drives in this enclosure.  This part number exactly describes this 
        type of disk to EMC.  This way there are no mistakes when the part is shipped.</p></td>
            </tr>
        </table>
        <h2>Calling in the Support Ticket:</h2>
        <p>Now that you have gathered all of the information that EMC needs to create a ticket, and get us the right parts, the next step is to call in the ticket.  
        The phone number is <span style="color: Maroon; font-size: larger; font-weight: bold;">1-800-782-4362</span>.  You can press the following options at anytime. <span style="font-weight: bold;">(2), (1), (1)</span>, then you will want to hold to speak with a 
        representitive.  All of the information you will need to answer thier questions has been gathered.  When they ask for a "Site ID", tell them that you have an "APM"
         number.  If this is your first time calling EMC, you will need to provide them with your contact information, like your name, phone number, and email address, so that
         you can recieve the ticket informaiton once it is created.  Your contact information will be used when the engineer has the new part, and wants to install it.</p>
    </div>
</asp:Content>

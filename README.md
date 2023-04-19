<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 Pro  (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

| Terms | Descriptions |
| ------| -------------|
| `Assigned` | Tickets that have been assigned to either an Agent or a Team while also being in the Department or Help Topic listed in the column, or tickets that were assigned to the Agent listed in the column, within the timeframe chosen.
|`Working the Issue(s)` | Communicates with the requesting party letting them the status of the ticket(s) and steps that will be taken to reach a potential resolution
| `Resolution` | Ticket was resolved in order to resolve or close the Ticket. This may or may meet the requesting parties desired end result. |

## Lifecycle Stages

Below shows the Customer/End-User experience in creating a ticket to submit to the help desk

<p align="center">
<img src="https://i.imgur.com/d4GVlJF.png" height="65%" width="65%" alt="end-user experience"/>
</p>

Customer receives notification letting them know that their ticket/request has been received.

<p align="center">
<img src="https://i.imgur.com/S82KGP1.png" height="80%" width="80%" alt="check request submission"/>
</p>

<br />

#### Intake: 
When Help Desk Agent/Admin logs in, they can now see the tickets that are available that have been assigned/not assigned with a provided priority. The priority will be set by help desk agent or queue manager working the tickets. The below screen shows the `Ticket #`, `Last Updated`, `Subject`, `From` (user that created the ticket), priority and `Assigned To` (queue manager can assign the ticket, person viewing the ticket can assign it to themselves or it can be assigned to a team ).

<p align="center">
<img src="https://i.imgur.com/9TfvRro.png" height="80%" width="80%" alt="helpdesk dashboard"/>
</p>

<br />

#### Working the issues:
Working the `entire mobile online banking is down` ticket that has a default priority of Normal, we are going to update it to Emergency since this is a business impacting event. Below reflects the selection of changing the priority and updating the notes: 

<p align="center">
<img src="https://i.imgur.com/bKvZzmJ.png" height="80%" width="80%" alt="changing priority"/>
</p>

<br />

Below reflects the updates that have occurred in the ticket along with the re-assignments of the ticket. The open ticket `Ticket #756285` has been assigned to Jane Doe that was previously unassigned to a member of support.  The ticket was reflects that it has been transferred to the System Administrators Department, which was previously under the Support Department.

<p align="center">
  <img src="https://i.imgur.com/NtzUgK9.png" height="65%" width="65%" alt="ticket updates"/>
  </p>
  
We can now see that the tickets have been updated from previous screenshot reflects that the tickets is assigned to 'Jane Doe' and the Priority is now 'Emergency'.

  <p align="center">
<img src="https://i.imgur.com/8Iywct3.png" height="65%" width="65%" alt="ticket updates"/>
  </p>

##### Resoltuion:
After connecting with the Sys Admin tean, we received a response letting us know that the ticket has been resolved and now reflects those comments (pictured below). 

<p align="center">
<img src="https://i.imgur.com/3q7KJ5c.png" height="65%" width="65%" alt="ticket resolved"/>
     </p>
     
Now that the ticket has been resolved, it will now be reflected in the 'closed' tickets column since it reached a resolution.

<p align="center">
  <img src="https://i.imgur.com/BtPSpZs.png" height="65%" width="65%" alt="ticket marked as closed"/>
</p>
<b><p align="center">Well that's a wrap, now on to the next package</b></p>
<p align="center"><b><i>"Ask yourself: How uncomfortable are you willing to become in order to reach your fullest potential?"</b></i></p>

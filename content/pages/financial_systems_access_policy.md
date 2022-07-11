Title: &nbsp;
TabTitle: ASF Financial Systems Access Policy

<div class="card">

<div class="card-header">

## ASF Financial Systems Access Policy

</div>

<div class="card-body">

## Purpose

The Apache Software Foundation is a recognized 501(c)(3) charitable foundation.  The Treasurer's office is responsible for multiple systems which 
provide control over ASF funds, and data which verifies that control.  Many of these systems contain private information about donors, employees, and 
volunteers of The ASF.  It is important that we be able to both protect privacy and maintain an appropriate level of auditability and oversight in 
these systems.  It is also important that, when new volunteers step up to serve as Treasurer or Assistant Treasurer, we be able to facilitate 
these transitions.  Similarly, it is important that the Foundation not become to dependent on a single vendor.

This policy explains how and for whom user accounts within these systems can be provisioned, and how passwords and user names are to be managed in
order to achieve these goals.

## Who can access Financial systems

Financial systems can be accessed by:
* The Treasurer and Assistant Treasurer
* Employees of the accounting firm which the Treasurer has tasked with keeping the Foundation's books
* Upon request: board members
* Upon request or if needed: The President and Executive Vice President
* If needed: The Infrastructure Administrator
* If needed: The Secretary and Assistant Secretary
* If needed: VP Fundraising and VP Sponsor Relations

People formerly in these roles may continue to have access for a period while the transition takes place.

## Organizational accounts and Individual user accounts vs. Role-based accounts

Many financial systems offer organizational or tenant accounts.  In such systems, multiple user accounts can access the system.  Frequently, actions of those
users such as viewing data or changing data create an audit trail uniquely associated with that user. This audit trail helps to protect The ASF against
mistakes and malicious behavior by making some actions reversable, and all actions discoverable.

Role-based accounts have the advantage that they are easy to transfer and share between individuals.  A frequent pattern is to provide a mailing list as
the email address for an account.  Unfortunately, role-based accounts handicap the auditing capabilities for financial systems.  If multiple users share
the same account, it is no longer possible to know which of them performed an action or viewed data.

Single-user accounts are accounts which only one person has access to.  Single user-accounts are difficult to transition between volunteers, and impossible 
to maintain oversight on.

## Password manager

Infra has provided Treasurer and Fundraising offices with access to a central 
password manager.  If you are performing services for the Treasurer's office and need access to our password manager, please create a Jira ticket with 
Infra.  Infra will then confirm with the Treasurer's office before providing access to any password vaults.

## Policies

* We *never* use systems which only offer single-user accounts.  We will seek alternatives to any such systems, or do without.
* If a system can offer multiple user accounts within an organization, we *never* use role-based accounts within that system.
* If a system contains private information for donors, employees, or volunteers, we *never* use role-based accounts within that system.  If the system 
contains private information and does not offer organizational accounts, we will seek alternatives to using that system.
* If a system makes it possible to move money, we *never* use role-based accounts within that system.
* You *must* use a password manager for your user account passwords.  Those passwords *must not* be visible to anyone but yourself.
* If an account offers some form of Two Factor Authentication, you are *required* to activate it.
* For role-based accounts, you *must* use the central passord manager provided, and place passwords in the appropriate vaults.
* For systems with organizational accounts, at least the Treasurer and Assistant Treasurer *must* have access.  
  Ideally a third and fourth person should also have access for continuity.
* User accounts will be provisioned with the minimum range of capabilities appropriate to the role of the person who is accessing the system.  For example, the 
  accountant requires read access to our bank account, but does not need the ability to transfer funds.  VP Fundraising may need access to 
  certain donor data but does not need access to employee data.
* A complete list of ASF Financial systems will be maintained by the Treasurer on the <a href="https://cwiki.apache.org/confluence/display/ASFP/Treasurer+Internal">Treasurer's Wiki</a>.

</div>

</div>

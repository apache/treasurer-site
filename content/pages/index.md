Title: &nbsp;
TabTitle: ASF Corporate Treasurer Information
<!-- Licensed under ALv2 -->

<div class="panel panel-success">
  <div class="panel-heading">
    <h3 class="panel-title">ASF Corporate Treasurer Overview</h3>
  </div>
  <div class="panel-body">
    The ASF's Treasurer is an <a href="https://www.apache.org/foundation/#who-runs-the-asf">executive officer</a> with responsibility 
    for managing our corporate finances, including overseeing payments recieved and paid, and designing and executing appropriate financial processes.
    <p/>
    The Treasurer submits a <a href="https://whimsy.apache.org/board/minutes/Treasurer">monthly report to the board</a>, 
    and works closely with our accounting firm <a href="http://www.ignitespot.com/">IgniteSpot</a>.  The Treasurer works 
    with our CPA to ensure that our taxes are file regularly.  The Treasurer works with Marketing & Public Relations to ensure that
    our quarterly and annual reports contain up-to-date financial information about the Foundation.  And the Treasurer collaborates 
    with the Vice President of Fundraising to ensure that sponsors and donors payments are received, tracked, and recognized.  The Treasurer 
    ensures the President and all executive officers have access to past and present financial information about their budgets for the 
    purposes of planning and tracking.
  </div>
</div>

<div class="panel panel-info">
  <div class="panel-heading">
    <h2 class="panel-title">ASF Bill Payment Process</h2>
  </div>
  <div class="panel-body">
    <p>Apache officers with an approved annual budget should submit 
      and <a href="#q3">approve expenses</a> within their area of responsibility.
      Most questions should go to the <span class="text-primary">privately-archived operations@ mailing list</span>.
      See also: the private <code>/repos/private/foundation/Finances</code> repository for more procedures.
    </p>
    <h3>Bill Processing Overview</h3>
    <ul>
      <li>Officers recieving invoices should check them into <code>/repos/private/financials/Bills/received/</code> or <a href="#q1">use Whimsy to upload PDFs</a></li>
      <li>An approving Officer should <kbd>svn mv</kbd> approved invoices into the <code>/repos/private/financials/Bills/approved/</code> directory</li>
      <li>The accounting firm collects all invoices approved by the <a href="#q4">fifteenth of the month</a></li>
      <li>The Treasurer releases all payments, and the accounting firm <a href="#q6">issues payments</a> at the end of the month</li>
      <li>Once funds are released, the invoice is moved to <code>/repos/private/financials/Bills/paid/</code> directory</li>
      <li>In this way, all steps are logged by commit messages</li>
    </ul>
  </div>
</div>

## Frequently Asked questions

<h3 id="q1">1. I've received an invoice that the ASF needs to pay, what
      should I do?</h3>
<p>Place it into
  <a href="https://svn.apache.org/repos/private/financials/Bills/received">Bills/received</a>.
  If you like, there is a 
  <a href="https://whimsy.apache.org/treasurer/bill-upload">convenient web interface</a>
  for this function.</p>
<h3 id="q2">2. I've made a payment and need to be reimbursed.  What should
  I do?</h3>
<p>Place a scan of a receipt or whatever documentation you might have into
  <a href="https://svn.apache.org/repos/private/financials/Bills/received">Bills/received</a>.
  If necessary, accompany this with a text file that explains how payment
  should be made.  If this results in multiple files that need to be
  processed as one transaction, please create a new directory for this and
  place the files there.</p>
<h3 id="q3">3. I'm an officer of the ASF with responsibility for a budget.
  How do I arrange for payments to be made?</h3>
<p>Monitor the 
  <a href="https://svn.apache.org/repos/private/financials/Bills/received">Bills/received</a>
  directory and move bills that need to be paid into the
  <a href="https://svn.apache.org/repos/private/financials/Bills/approved">Bills/approved</a>
  directory.  Please indicate the budget item against which this bill
  should be accounted for in the svn commit message.</p>
<h3 id="q4">4. What happens to bills approved after the 15th of the month?</h3>
<p>Bill approved after the 15th will normally get picked up in the
  following month.</p>
<h3 id="q5">5. I'm an officer of the ASF with responsibility for a budget
  and I have a bill that can't wait until the end of the month.  What
  should I do?</h3>
<p>First, move the bill to 
  <a href="https://svn.apache.org/repos/private/financials/Bills/approved">Bills/approved</a>,
  then send an email to
  <a href="mailto:accounting@apache.org">accounting@apache.org</a>
  asking for an out of band payment</p>
<h3 id="q6">6. How does the ASF pay bills?</h3>
<p>Generally US domestic bills are paid by
  <a href="http://en.wikipedia.org/wiki/Automated_Clearing_House">ACH</a>,
  and other bills are paid
  by international wire.  In rare cases, checks will be mailed out.
  Procedurally, <a href="http://www.virtualmgmt.com/">Virtual</a>
  enters the payments and then either the Treasurer
  or Assistant Treasurer releases those payments.  Neither the Treasurer
  nor the Assistant Treasurer have direct access to funds in Citizens.</p>
<h3 id="q7">7. How can I verify that a bill has been paid?</h3>
<p>Upon payment, bills are moved to the
  <a href="https://svn.apache.org/repos/private/financials/Bills/paid">Bills/paid</a>
  directory.
</p>
</div>


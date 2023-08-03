<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This guide outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Resourcs and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)(4vCPU)

<h2>Post-Install Configuration Objectives</h2>
 - Set up <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html"> Roles </a>, <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html"> Deparments </a>, <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html"> Teams  </a>, <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html"> Agents (workers) </a>, <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html"> Users (customers) </a>, as well as  <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html"> SLA </a>

<h2>Configuration Steps</h2>

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html"> Roles </a>
   <img src="https://docs.osticket.com/en/latest/_images/admin_agents_roles.png" />
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Agents -> Roles
        <li>Supreme Admin</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html"> Deparments </a>
   <img src="https://docs.osticket.com/en/latest/_images/admin_agents_departments.png" /> 
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Agents -> Departments
        <li>System Administrators</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html"> Teams  </a>
    <img src="https://docs.osticket.com/en/latest/_images/admin_agents_teams.png" />
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Agents -> Teams
        <li>Level I Support
          <li>Level II Support</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Allow anyone to create tickets
    <img src="https://docs.osticket.com/en/latest/_images/admin_settings_user_userSettings.png">
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Settings -> User Settings
        <li>Registration Required: Require registration and login to create tickets</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html"> Agents (workers) </a>
    <img src="https://docs.osticket.com/en/latest/_images/admin_agents_agents.png" />
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Agents -> Add New
        <li>Jane
          <li>John</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href=" https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html"> Users (customers) </a>
    <img src="https://docs.osticket.com/en/latest/_images/agent_users_userDir_dir.png" />
    <ul><!--Start of nested list-->
      <li>Agent Panel -> Users -> Add New
        <li>Karen
          <li>Ken</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html"> SLA </a>
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Manage -> SLA
        <li>Sev-A (1 hour, 24/7)
          <li>Sev-B (4 hours, 24/7)
            <li>Sev-C (8 hours, business hours)</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<ul><!--Start of main list-->
  <li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html"> Help Topics </a>
    <img src="https://docs.osticket.com/en/latest/_images/admin_manage_ht_htInfo.png" />
    <ul><!--Start of nested list-->
      <li>Admin Panel -> Manage -> Help Topics
        <li>Business Critical Outage
          <li>Personal Computer Issues
            <li>Equipment Request
              <li>Password Reset</li>
    </ul><!--End of nested list-->
  </li>
</ul><!--End of main list-->

<h2>this should conclude the end of set up proccess for osTicket.</h2>


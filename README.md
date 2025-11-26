# tmux-configs
 Custom Config Files For tmux - Split Config Enabled [ TESTING! ]
<hr>

> [!WARNING]
> This code is highly experiemental and has NOT been fully implemented or tested.
<hr>

> [!IMPORTANT]
> Code is not considered stable yet, and still lacks most features.

<hr>
<div id="Features"> <h3> Features </h3>
 This project will enable a static status bar at the bottom of the terminal window via the tmux command (must be installed). <p>
  There are config files and scripts for easily backing up and restoring the config, etc.
  This will be useful for things like:
 <ul>
  <li> Displaying date/time </li>
  <li> Displaying current host and user </li>
  <li> Monitoring CPU and Memory load </li>
  <li> Keeping track of which repo is being updated via MirrorMan-ng </li>
 </ul>
</div>

<hr>
<div id="Usage"> <h3> Usage </h3>
 <ul>
 <li> The included tmux.conf calls the actual configuration files, stored in tmux.conf.d.  This allows easier customization of the configuration. </li>
 <li> You can change the left, right, and other sections independently with easy since they each have their own individual config files. </li>
 <li> The layout is also separated from the actual content displayed for further ease of use/configuration. </li>
 </ul>
 

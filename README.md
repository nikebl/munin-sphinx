# munin-phpfpm
**Setup: **
*make sure that a mysql binary is exist in your system.*
*move the file to munin plugins dir and *
*change path to sphinx configs in it*
*run "munin-node-reconfigure --suggest --shell | grep sphinx_" *
(it will autodetect multiple instances of sphinx)*
*run the suggestions provided symlink creation command,*
*reload munin-node.*

# munin-phpfpm
---
Setup: 
---
1. Make sure that a mysql binary is exist in your system.
2. Move the file to munin plugins dir and 
   Change path to sphinx configs in it,
3. Run "munin-node-reconfigure --suggest --shell | grep sphinx_"
(it will autodetect multiple instances of sphinx),
4. Run the suggestions provided by symlink creation command above,
5. Reload munin-node.

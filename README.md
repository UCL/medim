# MATLAB Gadgetron Client
Demonstration code for a MATLAB Gadgetron client.
Intended as a learning exercise with many features not implemented.
Requires MATLAB Instrument Control Toolbox.

Tested with;
  gadgetron running in Ubuntu on a virtual machine, 
  ISMRMRD raw file generated by test_create_dataset.m from ISMRMRD on Git Hub, and, 
  default Gadgetron configuration file default.xml (both on VM and a copy locally).

Example:

  [imdata, imhdr] = explore_gclient('ipaddr','192.168.230.130', 'local_config_file','');




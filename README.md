# VCVRackPluginCollection

This is a collection of repositories from around Github that can be used to compile modules for the VCVRack virtual Eurorack synthesizer platform.

Not all of the linked modules will work or compile correctly. Whenever possible, this repository links to modules for Rack v0.6. However, some of the linked repositories are optimized for Rack v0.5 and may not compile. Hopefully, in the future, their maintainers will upgrade to the Rack v0.6 API.


To use this repository: 

  -Download the Rack v0.6 source code.

  -Change directory into your Rack source code root directory. 

  -Delete the existing "plugins" directory -- execute "rm -rf plugins" in Linux or msys.

  -Execute "git clone --recursive https://github.com/czchmate/VCVRackPluginCollection.git plugins".

  -Compile Rack as per normal. 
  
  -After Rack finishes compiling, execute "make allplugins" from the Rack root to compile the plugin collection. 
  

If any of the modules give you trouble, delete their directories and rerun "make all plugins".

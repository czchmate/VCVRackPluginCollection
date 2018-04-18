# VCVRackPluginCollection

This is a collection of module repositories from around Github for the VCVRack virtual Eurorack platform.

Not all of the linked modules will work or compile correctly. Whenever possible, this repository links to modules for Rack v0.6. However, some of the linked repositories are optimized for Rack v0.5 and may not compile.

To use this repository, first clone the Rack source code and then cd into your Rack root directory and type "git clone --recursive https://github.com/czchmate/VCVRackPluginCollection.git plugins".

Compile Rack as per normal. After Rack finishes compiling run "make allplugins" from the Rack root to compile the plugin collection. 

If any of the modules give you trouble, delete their directories and rerun "make all plugins".

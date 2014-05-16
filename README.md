os161-sublime
=============

OS/161 project settings and build configuration for Sublime Text 3

Installation
------------

The file `os161.sublime-project` should be copied into your root `os161` folder, wherever that may be located.

The keymap file should be copied into the Sublime Text configuration folder. For Ubuntu Linux, the folder is `~/.config/sublime-text-3/Packages/User/`. Or, if you prefer to keep an existing keymap file, just add the contents to that.

Configuration
-------------

The `working_dir` property should be set to the compile directory for whatever assignment you're currently working on.

You should also make sure the `path` property includes the OS/161 binaries (I couldn't figure out how to make Sublime Text do this automatically).

Usage
-----

To start using the project: under 'Project' in the Sublime Text menu, choose 'Open Project...' and select the sublime-project folder. You should see a file tree starting with the src directory in the sidebar.

To start using the build system: under 'Tools', choose Bmake as the build system. You can now compile the project with Ctrl+B. Additionally, if you set up the keymap, you can install the new kernel with Ctrl+Shift+B. Double-clicking on a compilation error in the build pane will take you to the corresponding file and line.

Additional Notes
----------------

I don't know if this will work with Sublime Text 2. It's only been tested with the Sublime Text 3 Beta.

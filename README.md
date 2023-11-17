# WordPress Composer Standards
A PHP standard project that makes PHP libraries compatible with WordPress Plugins and Themes. 

Every plugin has its own libraries. Sometimes, certain libraries can cause conflicts when used by plugins. This library solves this problem systematically with a PHP standart and a PHP Code compiler.

PHP compiler searches namespaces and use code keys for add plugin's parent namespace to start of the library namespace and use code keys. Our PHP standard makes it easier.

**Rules**
- PHP Standard must be suitable with PSR code standards.
- PHP Standard must not cause any conflicts.
- PHP Standard must be unique.
- PHP Standard must have a JSON config file that contains project settings.
- Compiler certainly must produce reliable and stable outputs.
- Compiler must have logs output system.
- Compiler must run on development environment in VSCode.
- Compiler must run after composer require, update etc. commands.
- Compiler must only compile the libraries that marked with our PHP standard and store them in another directory specified by the settings parameter with our json file.

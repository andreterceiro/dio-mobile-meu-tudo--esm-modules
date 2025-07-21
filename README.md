# Initial comparison: ESM x CJS modules

![comparision-cjs-x-esm](images/comparision-cjs-x-esm.png)


# Talking a little about the past

Teacher explained that in the past we had different browsers implementing different ways to do the same thing and Brendan Eich and Ecma made a standard to do several things. They generated standards as example ECMAScript 6 (or 2015). They recommend the use od ECMA Script modules and teacher also made this recommendation, enforcing that you also will see several libraries using this type of modularization.


# Using ESM modules

You can use through the root node type of the package.json:

![using-esm-modules](images/using-esm-modules.png)

A comment: the default value of this node is "commonjs".


# Export default of ESM modules

![export default of ESM modules](images/export-default-esm-modules.png)


# Importing ESM modules

![importing ESM modules](images/importing-esm-modules.png)

**An important observation**: in this way to import a module, you **must** specify the extension of the file.

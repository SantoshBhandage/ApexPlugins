# ApexPlugins
Many have requirements where we want to freeze the headers or columns or rows in a classic report / interactive report

I have created this plugin to cater the same requirements.

This plugin can be used with below report options.
1. Interactive Report - When using this option, make sure you set "Headfing Fix to None" in region attributes.
2. Classic Report.
3. Dynamic table generated using HTML / PLSQL dynamic content - in this case we need to specfiy the class name of table that needs to be freezed.

Usage Notes:

Its very simple to use this plugin.

1. Just create a dynamic action on the region / report on "After Refresh" event.
2. Choose StickyHeader[Plug-in] in true action
3. Fill the required attributes, In case you need any help filling attributes, Just refer the help section of that attribute.
4. Makesure you choose "Fire on Initialization" to freeze the table on load.

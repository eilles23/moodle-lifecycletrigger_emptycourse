# moodle-lifecycletrigger_emptycourse
This is a trigger-Subplugin for the admin tool [moodle-tool_lifecycle](https://github.com/learnweb/moodle-tool_lifecycle). 
Course without an Activity or Resource are marked for the cleanupprocess of the lifecycle admin tool.

## Settings
Site administrators choose between the activities or resources to not be considered.

## Proceeding
A trigger plugin always receives one course. To determine whether the course should be deleted the plugin 
checks if there are activies or resources within the course. 
Content to be excluded will not be counted and courses will be marked for the cleanupprocess regadless.

 For detailed information on trigger plugins visit the 
[Wiki](https://github.com/learnweb/moodle-tool_lifecycle/wiki) of the lifecycle admin tool.

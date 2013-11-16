Project Estimation Tool
=======================

The tool is a simple spreadsheet to help software companies estimate effort required for software development projects and allocate time for the different actviities involved in the software development lifecycle.

The basic assumption is that estimation at the task level happens for the coding hours involved in the task. Sum of all such hours will give the total coding hours involved in the project. The rest of the activities in the project lifecycle are calculated as percentages of these coding hours. For each activity different individuals would be involved and the percentage of time that each role has to spent on each activity would depend on the operational structure of the organization. Once the time to be spent by different roles are calculated these hours are then split up into hours that are to be spent by individuals who are added with the given roles into the project. The system also accommodates for different productivity levels for individuals with different levels of capabilities. The system also supports inclusion or exclusion of different types of activities based on the size of the project. This is to accommodate the possibility that smaller projects might not need some steps in the SDCL or might only require higher level activities. 

You can see instructions for using the system in the wiki

https://github.com/zyxware/project-estimation-tool/wiki

Currently the system is only really in a form that is usable by people who can read and understand formulas used in spreadsheets. Others will be able to use it but their ability to tweak the system to their workflow will be limited. Hopefully with more people starting to use the template and with better documentation the system will be usable for people without deeper understanding about spreadsheets. But to think of it, project managers should really be able to juggle with spreadsheet formulas :-)

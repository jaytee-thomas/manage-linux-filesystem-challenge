# Managing Filesystem and Directory Permission

You are the system admin of Phoenix Inc. The company runs an e-commerce website. The company’s systems have a lot of data stored about their customers, internal employees, and other sales related data. This data is currently at risk.​

​

To better protect and manage the data, you have ​
been asked to create various partitions where ​
the data will be stored going ahead.

**Requirements​
The company has the following departments: ​

HR, SALES, IT and CUSTOMER RELATIONS.​

​

You need to create a partition for each department to store their data.​

Every partition will need to be assigned a filesystem which is journaling enabled and supports bigger volumes. ​

Also, support should be present for legacy filesystems such as ext2 and ext3 filesystems.​

The filesystem should be able to support a large number of directories.​
You will need to:​

Create separate partitions of 1GB for each of the department.​

Assign the filesystem.​

Create directories for each partition that is to be used to mount (use name format Departmentname_Part)​

Assign filesystem and perform mounting of partition on the created directories.​

Note: Partitions should remain mounted even after reboot.​

The HR, SALES, IT, and CUSTOMER RELATIONS are headed by John, Sara, Emma, and James respectively.​

As owners of these departments  John, Sara, Emma, and James should have complete access of their department’s directories.​

Allocating group ownership on the directory will help ease down the administrative burden in the future. Therefore, create a group for each department (for example: Hr_Group) and provide ownership of all directories to the group as well.​

Directories which needs to create HR, Sales, IT, CustomerRelation

GroupOwner which needs to creeated HR_Group, Sales_Group, IT_Group, C_Relation

UserOwner    John, sara, Emma, James

Permissions to directory Owners  RWX, for all

Others can have only read(r) permission





​

​

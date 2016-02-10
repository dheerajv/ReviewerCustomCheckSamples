#Data Reviewer Custom Check Samples
##Validate Domain Based Attributes

This sample demonstrate how to use IPLTSCNTWorkspaceValExtension interface for building Data Reviewer Custom check.

```
Language:               C#
Subject:                Data Reviewer Custom Check Sample
Contributor:            ArcGIS Data Reviewer Team <DataReviewer_Team@esri.com>
Organization:           Esri, http://www.esri.com
Date:                   02/09/2016
ArcGIS Data Reviewer:   10.4
Visual Studio: 2013
```
#How to use the sample
In this section, you will configure and run the ValidateDomainBasedAttributes custom check by using the Custom Check option on the Data Reviewer toolbar. You can use any workspace in which you need to validate if the attributes in a feature class/table adhere to its domain constraints or not. Attribute field domains can be either coded values or ranges. The value entered for a field, especially if it is a range, can be outside the valid values. This is especially true if no validation has been performed during attribute editing. In addition, if data has been loaded from an external source, features may exist that violate both range and coded value domains. For instance, while your elevation attribute requires values that are between 0 and 4000, some of the data that has been imported can contain features with elevation values that are not within that range. You can use this custom check to find if there are attributes that are outside the domain values.

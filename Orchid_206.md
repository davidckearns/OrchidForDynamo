﻿**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major number follows the Dynamo version, 206.x.x is usable in Dynamo +2.6.x.x versions. The minor number is internal major builds. The build number is internal minor builds. The revision number is an internal build number without public documentation and display in this file.  
  
### History of Orchid for Dynamo 2.5.x and 2.6.x  
  
206.6.0  
- Refactored layout.  
  
206.5.1  
- Addition of guidance and helping files (/doc) for every node/function.  
- Categories (Category, SubCategory) refactored to independent branch.  
- Methods named “All” renamed to “InDocument” where applicable.  
  
206.5.0  
- The Dynamo transactions are being overwritten to give users more information about the transaction.  
- Shared parameters nodes for CCS and BIM7AA classification systems have been deprecated due to decisions taken by the stakeholders of the classification.  
  
206.4.0  
- Orchid types like Document, FamilyDocument, Parameter, and FamilyParameter are deprecated and converted into the alike Dynamo types. Remaining types will follow if possible.  
  
206.3.1  
- Nodes for Materials refactored and updated, do now support all kinds of schemas for appearances.  
  
206.3.0  
- Nodes for (MEP) System is extended with many functions.  
- Nodes for Reference and Assembly is added.  
- A wide range of Geometry functions (Nodes) is added.  
    
206.2.0  
- Version number changed from 260 to 206 to support two-digit Dynamo minor versioning. By this the Dynamo build number has been deprecated in the version number. Before 260 = 2.6.0, now 206 = 2.6.x.  
  
260.1.0  
- Support for external applications is moved to independent assemblies, this includes support for IfxExport.  
  
260.0.3  
- 1st version of Orchid for the Dynamo 2.6.x series.  
  
250.0.2  
- Filters, Schedules, and parameter Definitions (project and family parameters) added.  
  
250.0.1  
- Refactoring of Core nodes, nodes are moved into Common. Several other functions are also refactored into other namespaces.  
  
250.0.0  
- 1st version of Orchid for the Dynamo 2.5.x series.  
# amazonservices_javaclients_modifications

Revision 0c21c194a45bdccf94b907ca4f738582b68dca8b
Includes files from the SDK without any modifications


Revision d7492ecd618867e860f0e34e5eff103e0677ee35
Changed include 
1. To return ResponseHeaderMetadata for Feed APIs 
2. GetMyPriceForASIN API request to accept ItemCondition 
3. Constructing ItemAttributesType field for all Product APIs with the help of XSD

Generates executable jar files with dependencies.

Step 1: 
Clone your project in a separate folder
(note: replace ORGANIZATION and PROJECT)

$ git clone git@github.com:ORGANIZATION/PROJECT.git
Example :
$ git clone https://github.com/DasariArchana/amazonservices_javaclients_modifications.git

Step 2:
Go into the project folder where pom.xml file resides
$ cd my-projectName
Example : 
$ cd <project_path>/amazonservices_javaclients_modifications\ext-lib-amazon-mws-modifications>

Step 3:
Just build it!
$ mvn clean package

Step 4:
And see what you got!
$ dir target 

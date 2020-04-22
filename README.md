# amazonservices_javaclients_modifications

Revision 77894e28fd7bac540413568edd5e0765f3e73637
Includes files from the SDK without any modifications


Revision dc7066db8265e79b9463aa8ecc1bf1021a9cda03
Changed include 
1. To return ResponseHeaderMetadata for Feed APIs 
2. GetMyPriceForASIN API request to accept ItemCondition 
3. Constructing ItemAttributesType field for all Product APIs with the help of XSD

Generates executable jar files with dependencies.

### Step 1: 
Clone your project in a separate folder
(note: replace ORGANIZATION and PROJECT)

```
$ git clone git@github.com:ORGANIZATION/PROJECT.git
```

Example :

```
$ git clone git@github.com:cleo/amazonservices_javaclients_modifications.git
```

### Step 2:
Go into the project folder where pom.xml file resides

```
$ cd my-projectName
```

Example : 

```
$ cd <project_path>/amazonservices_javaclients_modifications/ext-lib-amazon-mws-modifications
```

### Step 3:
Just build it!

```
$ mvn clean package
```

### Step 4:
And see what you got!

```
$ dir target 
```
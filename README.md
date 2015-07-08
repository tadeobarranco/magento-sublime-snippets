# MagentoSublimeSnippets

This files are created to help Magento Developers to create the needed files in a custom Magento Module Application on Sublime Text Editor.

## Usage

The snippets has a scope restriction, snippets about configurations and layouts has xml files scope, this means that to use these snippets you have to create files wiht xml extension.

You can navigate through each snippet so you can change the values of the different components that comprise.

#### mg-module

Gives you the possibility of create a usual Company_Module.xml file

    mg-module + tab

```xml
<?xml version="1.0" encoding="UTF-8"?>
<config>
	<modules>
		<Company_Module>
			<active>true</active>
			<codePool>local</codePool>
		</Company_Module>
	</modules>
</config>
```

#### mg-config 

Gives you the possibility of create a entire config.xml file (This gives you a way to interact with the different tags involved at config.xml file structure)

    mg-config + tab

#### mg-global

Gives you the possibility of create a global tag used at config.xml

    mg-global + tab

```xml
<global>
	<blocks>
		<namespace>
			<class>Company_Module_Block</class>
		</namespace>
	</blocks>
	<helpers>
		<namespace>
			<class>Company_Module_Helper</class>
		</namespace>
	</helpers>
	<models>
		<namespace>
			<class>Company_Module_Model</class>
		</namespace>
	</models>
</global>
```
    
#### mg-blocks

Gives you the possibility of create a blocks declaration tags under global tag at config.xml

    mg-blocks + tab

```xml
<blocks>
	<namespace>
		<class>Company_Module_Block</class>
	</namespace>
</blocks>
```

#### mg-blocks-rewrite

Gives you the possibility of create a rewrite block declaration tags under global tag at config.xml

    mg-blocks-rewrite + tab

```xml
<namespace>
	<rewrite>
		<block_class>Company_Module_Block_New_Class</block_class>
	</rewrite>
</namespace>
```

#### mg-blocks-rewrite-class

Gives you the possibility of create a rewrite block class declaration tag under rewrite tag at config.xml

    mg-blocks-rewrite-class + tab

```xml
<block_class>Company_Module_Block_New_Class</block_class>
```

#### mg-helpers

Gives you the possibility of create a helpers declaration tags under global tag at config.xml

    mg-helpers + tab

```xml
<helpers>
	<namespace>
		<class>Company_Module_Helper</class>
	</namespace>
</helpers>
```

#### mg-helpers-rewrite

Gives you the possibility of create a rewrite helper declaration tags under global tag at config.xml

    mg-helpers-rewrite + tab

```xml
<namespace>
	<rewrite>
		<helper_class>Company_Module_Helper_New_Class</helper_class>
	</rewrite>
</namespace>
```

#### mg-helpers-rewrite-class

Gives you the possibility of create a rewrite helper class declaration tags under global tag at config.xml

    mg-helpers-rewrite-class + tab

```xml
<helper_class>Company_Module_Helper_New_Class</helper_class>
```

#### mg-models

Gives you the possibility of create a models declaration tags under global tag at config.xml

    mg-models + tab

```xml
<models>
	<namespace>
		<class>Company_Module_Model</class>
		<resourceModel>namespace_resource_type</resourceModel>
		<namespace_resource_type>
			<class>Company_Module_Model_Resource_Type</class>
			<entities>
				<table_alias>
					<table>table_name</table>
				</table_alias>
			</entities>
		</namespace_resource_type>
	</namespace>
</models>
```

#### mg-models-rewrite

Gives you the possibility of create a rewrite model declaration tags under global tag at config.xml

    mg-models-rewrite + tab

```xml
<namespace>
	<rewrite>
		<model_class>Company_Module_Model_New_Class</model_class>
	</rewrite>
</namespace>
```

#### mg-models-rewrite-class

Gives you the possibility of create a rewrite model class declaration tags under global tag at config.xml

    mg-models-rewrite-class + tab

```xml
<model_class>Company_Module_Helper_New_Class</model_class>
```

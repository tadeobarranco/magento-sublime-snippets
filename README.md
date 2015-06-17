# MagentoSublimeSnippets

This files are created to help Magento Developers to create the needed files in a custom Magento Module Application on Sublime Text Editor.

## Usage

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

#### mg-config-global

Gives you the possibility of create a global tag used at config.xml

    mg-config-global + tab
    
#### mg-config-global-blocks

Gives you the possibility of create a blocks declaration tags under global tag at config.xml

    mg-config-global-blocks + tab

```xml
<blocks>
	<namespace>
		<class>Company_Module_Block</class>
	</namespace>
</blocks>
```

#### mg-config-global-blocks-rewrite

Gives you the possibility of create a rewrite block declaration tags under global tag at config.xml

    mg-config-global-blocks-rewrite

```xml
<namespace>
	<rewrite>
		<block_class>Company_Module_Block_New_Class</block_class>
	</rewrite>
</namespace>
```

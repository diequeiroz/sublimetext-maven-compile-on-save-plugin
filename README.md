Maven Compile on Save
=============

Usage
-------------

Create a folder named MavenCompileOnSave in your Sublime Text's Packages folder.

Place the maven_compile_on_save.py inside of it.

Open your project settings:

Project > Edit project

Use this setting to activate the plugin and set the file extensions that will trigger the plugin when saved:

```python
{
	"settings":
	{
		"maven_compile_on_save": ["java"]
	}
}
```

For example, if you want html files to trigger the plugin, use this setting:


```python
{
	"settings":
	{
		"maven_compile_on_save": ["java","html"]
	}
}

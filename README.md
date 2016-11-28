#GWTP应用模板
创建一个GWTP项目

##GWTP 文档
* [GWTP Home](https://github.com/ArcBees/GWTP) - Find the GWT-Platform home here.
* [GWTP Documentation](http://dev.arcbees.com/gwtp/) - Find out how to use GWT-Platform here.
* [GWTP Samples](https://github.com/ArcBees/GWTP-Samples) - Find Sample GWT-Platform projects here.

##社区
* [Join the GWT-Platform G+ Community](https://plus.google.com/communities/113139554133824081251) - See whats happening in the community.
* [GWTP Google Group](https://groups.google.com/forum/?fromgroups#!forum/gwt-platform) - Ask for help here.

##ArcheTypes in this Project
Create a project from a project template called an Archetype. Follow the links below for instructions.

* [Eclipse Maven Import Instructions](http://c.gwt-examples.com/home/maven/ide-import/eclipse) - How to import a Maven project into Eclipse. The GWT module will need to be added manually for GWTP project imports!
* [IDEA Maven Import Instructions](http://c.gwt-examples.com/home/maven/ide-import/intellij-idea) - How to import a Maven project into IntelliJ IDEA.

<table>
	<tr>
		<th>Archetype</th>
		<th>Description</th>
	</tr>
	<tr>
		<td><a href="https://github.com/ArcBees/ArcBees-archetypes/tree/master/gwtp-basic">GWTP Basic</a></td>
		<td>Simple basic GWTP Archetype.</td>
	</tr>
	<tr>
		<td><a href="https://github.com/ArcBees/Arcbees-Archetypes/tree/master/gwtp-appengine-guice">GWTP Basic AppEngine</a></td>
		<td>Simple basic GWTP Archetype using App Engine.</td>
	</tr>
</table>

##Eclipse Import Notes
Eclipse users will need to add the module to Google Eclipse Plugin. Since the entry-point module is inherited in GWTP plugin, GPE doesn't see it and has to be added manually.

1. Right click on project > Google > Web Toolkit Settings > Entry point modules > Add
2. Add the entry point module.
3. See the screen shot at the bottom of these directions: [Eclipse Maven Import Instructions](http://c.gwt-examples.com/home/maven/ide-import/eclipse)

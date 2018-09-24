# Plugin-template
Spigot plugin setup for Maven in Eclipse. This repository is a template for Maven projects in Eclipse to develop Java plugins. Maven will update the dependencies and project settings based on the project descriptor. This will help automate the development 

## Table of contents
- [Usage](#usage)
    - [prerequisites](#prerequisites)
    - [steps](#steps)
- [references](#references)
- [License](#license)

## Usage
### Prerequisites
Name | Description | Version
------------ | ------------- | -------------
[Eclipse](https://www.eclipse.org/downloads/packages/) | The essential tools for any Java developer. | Eclipse IDE for Java Developers
[Java](https://www.oracle.com/technetwork/java/javase/overview/index.html) | Java lets you develop and deploy Java applications on desktops and servers. | JDK and JRE 8 or newer

### Steps
  * Clone this git repository into your Eclipse workspace using [EGit](https://www.eclipse.org/egit/), [GitHub](https://desktop.github.com/) or [Git](https://git-scm.com/).
  * Right-click the repository in `Git Repositories` and click `Import projects`.
    * Set the `Import source` to the repository where the `.git` folder is located.
    * Select `Plugin-template/Template` as the folder.
    * Finish the setup
  * Right-click the project in `Package Explorer` and select `Refactor`
    * Rename the `Maven Artifact` to match your namespace.
    * Rename the `Java Project` to match your plugin.
  
  * Open `Template.java` in `src/main/java`
    * Rename the gloryrock.template.main Java package to match your namespace.
    * Rename or replace the main class `Template.java` with something that match your entry point.
  
  * Open `pom.xml` in the project root
    * Rename the `groupId` to match your own namespace.
    * Rename `artifactId` to your own plugin name.
    * Change the `source` and `target` version of Java to the ones you've installed.
    * Change the `spigot-api` version to the most recent one found [here](https://hub.spigotmc.org/nexus/content/groups/public/org/spigotmc/spigot-api/).
  
  * Open `plugin.yml` in `src/main/resources`
    * Change the `name` to your plugin name.
    * Change the `main` to your own main class in the package that matches your namespace.
    * Change the `author` to your username.
    * Change the `description` to match your plugin.
    
## References
[Using the Spigot-API](https://www.spigotmc.org/wiki/spigot-plugin-development/)

[User-contributed code examples for simple plugins](https://www.spigotmc.org/wiki/plugin-snippets/)

[Creating your first bukkit plugin](https://hypixel.net/threads/creating-your-first-bukkit-plugin.286674/)

[The Maven project descriptor](http://maven.apache.org/ref/3.2.3/maven-model/maven.html)

## License
This project is licensed under the [MIT License](https://github.com/Gloryrock/Plugin-template/blob/master/LICENSE.md).
Licenses of tools and dependencies are not included and may vary.

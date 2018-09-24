# Plugin-template
Spigot plugin setup for Maven in Eclipse. This repository is a template for Maven projects in Eclipse to develop Java plugins.

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
  * Clone this git repository into your Eclipse workspace.
  * Go to create a new Java project.
  
  * Rename the gloryrock.template.main Java package under `src/main/java` to reflect your namespace.
  
  * Rename the groupId in `pom.xml` to reflect your own namespace.
  * Rename artifactId in `pom.xml ` to your own plugin name.
  * Change the `source` and `target` version of Java in `pom.xml` to the ones you've installed.
  * Change the `spigot-api` version in `pom.xml` to the most recent one found [here](https://hub.spigotmc.org/nexus/content/groups/public/org/spigotmc/spigot-api/).
  
  * Change the `name` in `plugin.yml` under `src/main/resources` to your plugin name.
  * Change the `main` in `plugin.yml` to your own main class in the package that reflects your namespace.
  * Change the `author` to your username
  * Change the `description` to match your plugin.
    
## References
[Using the Spigot-API](https://www.spigotmc.org/wiki/spigot-plugin-development/)

[User-contributed code examples for simple plugins](https://www.spigotmc.org/wiki/plugin-snippets/)

[Creating your first bukkit plugin](https://hypixel.net/threads/creating-your-first-bukkit-plugin.286674/)

## License
This project is licensed under the [MIT License](https://github.com/Gloryrock/Plugin-template/blob/master/LICENSE.md).
Licenses of tools and dependencies are not included and may vary.

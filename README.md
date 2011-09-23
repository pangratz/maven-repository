This Maven Repository contains projects which are not listed in public Maven Repositories.

# Usage

* add the snapshots and releases repositories to your `pom.xml`

		...
		<repositories>
			...
			<repository>
				<id>pangratz-mvn-repo-releases</id>
				<url>http://pangratz.github.com/maven-repository/releases</url>
			</repository>
			<repository>
		  		<id>pangratz-mvn-repo-snapshots</id>
				<url>http://pangratz.github.com/maven-repository/snapshots</url>
			</repository>
			...
		</repositories>
		...
		
* reference any dependency ...

		<dependency>
			<groupId>de.schildbach.pte</groupId>
			<artifactId>public-transport-enabler</artifactId>
			<version>1.0-SNAPSHOT</version>
		</dependency>
		
* or browse available projects in http://pangratz.github.com/maven-repository/releases/ or http://pangratz.github.com/maven-repository/snapshots/
		
* that's it
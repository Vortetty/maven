# maven

my maven repo

build.gradle
```
repositories {
	maven {
		url = 'https://raw.githubusercontent.com/Vortetty/maven/master/'
	}
}

dependencies {
  modCompile group: 'net.vortetty', name: 'PulaskisAndShaxes', version: '1.1.2'
}
```

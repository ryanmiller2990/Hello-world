@@ -1,18 +1,12 @@
 plugins {
     application
     kotlin("jvm")
 }
 apply plugin: 'application'

 application {
     mainClassName = "cli.Bot"
 }
 mainClassName = 'bot.Bot'

 dependencies {
     compile(project(":shared"))
     compile(kotlin("stdlib"))
     implementation("io.reactivex.rxjava2:rxkotlin:2.4.0")
     implementation("com.mashape.unirest:unirest-java:1.4.9")
     implementation("org.quartz-scheduler:quartz:2.3.0")
     implementation("com.github.scribejava:scribejava-apis:6.0.0")
     implementation("org.jsoup:jsoup:1.7.2")
 }
 } 

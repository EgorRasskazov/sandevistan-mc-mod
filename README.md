RU

мод сделан https://www.youtube.com/@SmI7I
вам понадобится jdk 25 (java development kit 25)
для сборки откройте файл gradle.properties и впишите свою версию майкрафт и фабрик лоадера
потом откроq cmd и пиши команды по порядку:
cd /d путь\к\папке\файлов
gradlew.bat build -Dorg.gradle.java.home="папка\jdk(java developnebt kit}"
minecraft_version=XXXXX
loader_version=XXXXX

ENG

mod created by https://www.youtube.com/@SmI7I
You will need JDK 25 (Java Development Kit 25).
To build the project, open the gradle.properties file and enter your specific versions for Minecraft and Fabric Loader.
Then, open CMD and run the following commands in order:
cd /d path\to\your\project\folder
gradlew.bat build -Dorg.gradle.java.home="path\to\jdk"
minecraft_version=XXXXX
loader_version=XXXXX

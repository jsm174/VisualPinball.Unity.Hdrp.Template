# About

These are custom Unity project templates for Visual Pinball. 

They are based on article found [here](https://manuel-rauber.com/2020/08/21/unity-custom-project-templates).

# Installation

Copy the following files:

```
org.visualpinball.unity.template.universal.tgz
org.visualpinball.unity.template.hd.tgz
```

On Windows:

```
C:\Program Files\Unity\Hub\Editor\<VERSION>\Editor\Data\Resources\PackageManager\ProjectTemplates
```

On macOS:

```
/Applications/Unity/Hub/Editor/<VERSION>/Unity.app/Contents/Resources/PackageManager/ProjectTemplates
```

# To Do

~~Replace all project depedency modules with git submodules.~~

# Notes (for myself)

```
cd org.visualpinball.unity.template.hd/ProjectData~/Assets
zip assets-test-table-hd.zip Scenes/* Scenes/TestTable/* && mv assets-test-table-hd.zip ~/Desktop
(copy to google drive)

cp -r org.visualpinball.unity.template.hd package && tar cvzf org.visualpinball.unity.template.hd.tgz package && rm -rf package
cp org.visualpinball.unity.template.hd.tgz /Applications/Unity/Hub/Editor/2020.2.0b14/Unity.app/Contents/Resources/PackageManager/ProjectTemplates
```

```
cd org.visualpinball.unity.template.universal/ProjectData~/Assets
zip assets-test-table-universal.zip Scenes/* && mv assets-test-table-universal.zip ~/Desktop
(copy to google drive)

cp -r org.visualpinball.unity.template.universal package && tar cvzf org.visualpinball.unity.template.universal.tgz package && rm -rf package
cp org.visualpinball.unity.template.hd.tgz /Applications/Unity/Hub/Editor/2020.2.0b14/Unity.app/Contents/Resources/PackageManager/ProjectTemplates
```


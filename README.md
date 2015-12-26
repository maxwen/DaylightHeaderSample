This is a sample for contributing daylight header images
This consists of two parts
1) file assets/daylight_header.xml
e.g.
```xml
    <hour_header hour="21" image="notifhead_night" />
    <day_header day="25" month="12" image="notifhead_christmas" />
```
2) AndroidManifest,xml
You must provide an activity with
<action android:name="org.omnirom.DaylightHeaderPack" />
e.g.
```xml
		<activity
			android:name=".DaylightHeaderSample"
			android:label="Sample" >
			<intent-filter>
				<action android:name="org.omnirom.DaylightHeaderPack" />

				<category android:name="android.intent.category.DEFAULT" />
			</intent-filter>
		</activity>
```

Label will be the name your pack will appear when selecting



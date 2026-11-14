
-------------------------------------------------------------------------------
   ROBOCOPY     ::     Robust File Copy for Windows                              
-------------------------------------------------------------------------------

  Started : Saturday, November 14, 2026 6:05:00 PM
   Source : C:\src\compteur_app\
     Dest : C:\src\tp-4\tp4-flutter\compteur\

    Files : *.*
	    
 Exc Dirs : build
	    .dart_tool
	    .idea@
# TP4 - Flutter
Premiers pas avec Flutter : Hello World + exercice compteur.

## Lancer un projet
cd compteur
flutter pub get
flutter run
@
	    
  Options : *.* /S /E /DCOPY:DA /COPY:DAT /R:1000000 /W:30 

------------------------------------------------------------------------------

	  New Dir          7	C:\src\compteur_app\
	    New File  		     794	.gitignore
100%  
	    New File  		    1706	.metadata
100%  
	    New File  		    1585	analysis_options.yaml
100%  
	    New File  		     859	compteur_app.iml
100%  
	    New File  		    7105	pubspec.lock
100%  
	    New File  		    3952	pubspec.yaml
100%  
	    New File  		     651	README.md
100%  
	  New Dir          3	C:\src\compteur_app\.idea\
	    New File  		      50	.gitignore
100%  
	    New File  		     413	modules.xml
100%  
	    New File  		    1553	workspace.xml
100%  
	  New Dir          2	C:\src\compteur_app\.idea\libraries\
	    New File  		     970	Dart_SDK.xml
100%  
	    New File  		     614	KotlinJavaRuntime.xml
100%  
	  New Dir          1	C:\src\compteur_app\.idea\runConfigurations\
	    New File  		     276	main_dart.xml
100%  
	  New Dir          8	C:\src\compteur_app\android\
	    New File  		     267	.gitignore
100%  
	    New File  		     561	build.gradle.kts
100%  
	    New File  		    1630	compteur_app_android.iml
100%  
	    New File  		     306	gradle.properties
100%  
	    New File  		    4971	gradlew
100%  
	    New File  		    2404	gradlew.bat
100%  
	    New File  		     157	local.properties
100%  
	    New File  		     797	settings.gradle.kts
100%  
	  New Dir          1	C:\src\compteur_app\android\.gradle\
	    New File  		       8	file-system.probe
100%  
	  New Dir          1	C:\src\compteur_app\android\.gradle\9.5.0\
	    New File  		       0	gc.properties
	  New Dir          1	C:\src\compteur_app\android\.gradle\9.5.0\checksums\
	    New File  		      17	checksums.lock
100%  
	  New Dir          2	C:\src\compteur_app\android\.gradle\9.5.0\executionHistory\
	    New File  		  339997	executionHistory.bin
100%  
	    New File  		      17	executionHistory.lock
100%  
	  New Dir          0	C:\src\compteur_app\android\.gradle\9.5.0\expanded\
	  New Dir          1	C:\src\compteur_app\android\.gradle\9.5.0\fileChanges\
	    New File  		       1	last-build.bin
100%  
	  New Dir          3	C:\src\compteur_app\android\.gradle\9.5.0\fileHashes\
	    New File  		   70265	fileHashes.bin
100%  
	    New File  		      17	fileHashes.lock
100%  
	    New File  		   18973	resourceHashesCache.bin
100%  
	  New Dir          0	C:\src\compteur_app\android\.gradle\9.5.0\vcsMetadata\
	  New Dir          3	C:\src\compteur_app\android\.gradle\buildOutputCleanup\
	    New File  		      17	buildOutputCleanup.lock
100%  
	    New File  		      53	cache.properties
100%  
	    New File  		   22979	outputFiles.bin
100%  
	  New Dir          1	C:\src\compteur_app\android\.gradle\noVersion\
	    New File  		      17	buildLogic.lock
100%  
	  New Dir          1	C:\src\compteur_app\android\.gradle\vcs-1\
	    New File  		       0	gc.properties
	  New Dir          0	C:\src\compteur_app\android\.kotlin\
	  New Dir          0	C:\src\compteur_app\android\.kotlin\sessions\
	  New Dir          1	C:\src\compteur_app\android\app\
	    New File  		    1823	build.gradle.kts
100%  
	  New Dir          0	C:\src\compteur_app\android\app\src\
	  New Dir          1	C:\src\compteur_app\android\app\src\debug\
	    New File  		     385	AndroidManifest.xml
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\
	    New File  		    2245	AndroidManifest.xml
100%  
	  New Dir          0	C:\src\compteur_app\android\app\src\main\java\
	  New Dir          0	C:\src\compteur_app\android\app\src\main\java\io\
	  New Dir          0	C:\src\compteur_app\android\app\src\main\java\io\flutter\
	  New Dir          1	C:\src\compteur_app\android\app\src\main\java\io\flutter\plugins\
	    New File  		     516	GeneratedPluginRegistrant.java
100%  
	  New Dir          0	C:\src\compteur_app\android\app\src\main\kotlin\
	  New Dir          0	C:\src\compteur_app\android\app\src\main\kotlin\com\
	  New Dir          0	C:\src\compteur_app\android\app\src\main\kotlin\com\example\
	  New Dir          1	C:\src\compteur_app\android\app\src\main\kotlin\com\example\compteur_app\
	    New File  		     131	MainActivity.kt
100%  
	  New Dir          0	C:\src\compteur_app\android\app\src\main\res\
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\drawable\
	    New File  		     446	launch_background.xml
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\drawable-v21\
	    New File  		     450	launch_background.xml
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\mipmap-hdpi\
	    New File  		     544	ic_launcher.png
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\mipmap-mdpi\
	    New File  		     442	ic_launcher.png
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\mipmap-xhdpi\
	    New File  		     721	ic_launcher.png
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\mipmap-xxhdpi\
	    New File  		    1031	ic_launcher.png
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\mipmap-xxxhdpi\
	    New File  		    1443	ic_launcher.png
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\values\
	    New File  		    1014	styles.xml
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\main\res\values-night\
	    New File  		    1013	styles.xml
100%  
	  New Dir          1	C:\src\compteur_app\android\app\src\profile\
	    New File  		     385	AndroidManifest.xml
100%  
	  New Dir          0	C:\src\compteur_app\android\gradle\
	  New Dir          2	C:\src\compteur_app\android\gradle\wrapper\
	    New File  		   53636	gradle-wrapper.jar
100%  
	    New File  		     207	gradle-wrapper.properties
100%  
	  New Dir          1	C:\src\compteur_app\ios\
	    New File  		     603	.gitignore
100%  
	  New Dir          5	C:\src\compteur_app\ios\Flutter\
	    New File  		     744	AppFrameworkInfo.plist
100%  
	    New File  		      31	Debug.xcconfig
100%  
	    New File  		     631	flutter_export_environment.sh
100%  
	    New File  		     592	Generated.xcconfig
100%  
	    New File  		      31	Release.xcconfig
100%  
	  New Dir          4	C:\src\compteur_app\ios\Flutter\ephemeral\
	    New File  		       0	.swift_pm.lock
	    New File  		     108	flutter_lldbinit
100%  
	    New File  		    1276	flutter_lldb_helper.py
100%  
	    New File  		     442	flutter_native_integration.env
100%  
	  New Dir          0	C:\src\compteur_app\ios\Flutter\ephemeral\Packages\
	  New Dir          0	C:\src\compteur_app\ios\Flutter\ephemeral\Packages\.packages\
	  New Dir          1	C:\src\compteur_app\ios\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\
	    New File  		     596	Package.swift
100%  
	  New Dir          0	C:\src\compteur_app\ios\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\Sources\
	  New Dir          1	C:\src\compteur_app\ios\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\Sources\FlutterGeneratedPluginSwiftPackage\
	    New File  		      38	FlutterGeneratedPluginSwiftPackage.swift
100%  
	  New Dir          6	C:\src\compteur_app\ios\Runner\
	    New File  		     555	AppDelegate.swift
100%  
	    New File  		     378	GeneratedPluginRegistrant.h
100%  
	    New File  		     225	GeneratedPluginRegistrant.m
100%  
	    New File  		    2292	Info.plist
100%  
	    New File  		      39	Runner-Bridging-Header.h
100%  
	    New File  		      82	SceneDelegate.swift
100%  
	  New Dir          0	C:\src\compteur_app\ios\Runner\Assets.xcassets\
	  New Dir         16	C:\src\compteur_app\ios\Runner\Assets.xcassets\AppIcon.appiconset\
	    New File  		    2641	Contents.json
100%  
	    New File  		   10932	Icon-App-1024x1024@1x.png
100%  
	    New File  		     295	Icon-App-20x20@1x.png
100%  
	    New File  		     406	Icon-App-20x20@2x.png
100%  
	    New File  		     450	Icon-App-20x20@3x.png
100%  
	    New File  		     282	Icon-App-29x29@1x.png
100%  
	    New File  		     462	Icon-App-29x29@2x.png
100%  
	    New File  		     704	Icon-App-29x29@3x.png
100%  
	    New File  		     406	Icon-App-40x40@1x.png
100%  
	    New File  		     586	Icon-App-40x40@2x.png
100%  
	    New File  		     862	Icon-App-40x40@3x.png
100%  
	    New File  		     862	Icon-App-60x60@2x.png
100%  
	    New File  		    1674	Icon-App-60x60@3x.png
100%  
	    New File  		     762	Icon-App-76x76@1x.png
100%  
	    New File  		    1226	Icon-App-76x76@2x.png
100%  
	    New File  		    1418	Icon-App-83.5x83.5@2x.png
100%  
	  New Dir          5	C:\src\compteur_app\ios\Runner\Assets.xcassets\LaunchImage.imageset\
	    New File  		     414	Contents.json
100%  
	    New File  		      68	LaunchImage.png
100%  
	    New File  		      68	LaunchImage@2x.png
100%  
	    New File  		      68	LaunchImage@3x.png
100%  
	    New File  		     340	README.md
100%  
	  New Dir          2	C:\src\compteur_app\ios\Runner\Base.lproj\
	    New File  		    2414	LaunchScreen.storyboard
100%  
	    New File  		    1631	Main.storyboard
100%  
	  New Dir          1	C:\src\compteur_app\ios\Runner.xcodeproj\
	    New File  		   26402	project.pbxproj
100%  
	  New Dir          1	C:\src\compteur_app\ios\Runner.xcodeproj\project.xcworkspace\
	    New File  		     142	contents.xcworkspacedata
100%  
	  New Dir          2	C:\src\compteur_app\ios\Runner.xcodeproj\project.xcworkspace\xcshareddata\
	    New File  		     246	IDEWorkspaceChecks.plist
100%  
	    New File  		     234	WorkspaceSettings.xcsettings
100%  
	  New Dir          0	C:\src\compteur_app\ios\Runner.xcodeproj\xcshareddata\
	  New Dir          1	C:\src\compteur_app\ios\Runner.xcodeproj\xcshareddata\xcschemes\
	    New File  		    4836	Runner.xcscheme
100%  
	  New Dir          1	C:\src\compteur_app\ios\Runner.xcworkspace\
	    New File  		     159	contents.xcworkspacedata
100%  
	  New Dir          2	C:\src\compteur_app\ios\Runner.xcworkspace\xcshareddata\
	    New File  		     246	IDEWorkspaceChecks.plist
100%  
	    New File  		     234	WorkspaceSettings.xcsettings
100%  
	  New Dir          1	C:\src\compteur_app\ios\RunnerTests\
	    New File  		     302	RunnerTests.swift
100%  
	  New Dir          1	C:\src\compteur_app\lib\
	    New File  		    1548	main.dart
100%  
	  New Dir          2	C:\src\compteur_app\linux\
	    New File  		      19	.gitignore
100%  
	    New File  		    4896	CMakeLists.txt
100%  
	  New Dir          4	C:\src\compteur_app\linux\flutter\
	    New File  		    2903	CMakeLists.txt
100%  
	    New File  		     739	generated_plugins.cmake
100%  
	    New File  		     161	generated_plugin_registrant.cc
100%  
	    New File  		     303	generated_plugin_registrant.h
100%  
	  New Dir          4	C:\src\compteur_app\linux\runner\
	    New File  		    1000	CMakeLists.txt
100%  
	    New File  		     186	main.cc
100%  
	    New File  		    4961	my_application.cc
100%  
	    New File  		     472	my_application.h
100%  
	  New Dir          1	C:\src\compteur_app\macos\
	    New File  		      96	.gitignore
100%  
	  New Dir          3	C:\src\compteur_app\macos\Flutter\
	    New File  		      49	Flutter-Debug.xcconfig
100%  
	    New File  		      49	Flutter-Release.xcconfig
100%  
	    New File  		     147	GeneratedPluginRegistrant.swift
100%  
	  New Dir          4	C:\src\compteur_app\macos\Flutter\ephemeral\
	    New File  		       0	.swift_pm.lock
	    New File  		     487	Flutter-Generated.xcconfig
100%  
	    New File  		     595	flutter_export_environment.sh
100%  
	    New File  		     415	flutter_native_integration.env
100%  
	  New Dir          0	C:\src\compteur_app\macos\Flutter\ephemeral\Packages\
	  New Dir          0	C:\src\compteur_app\macos\Flutter\ephemeral\Packages\.packages\
	  New Dir          1	C:\src\compteur_app\macos\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\
	    New File  		     598	Package.swift
100%  
	  New Dir          0	C:\src\compteur_app\macos\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\Sources\
	  New Dir          1	C:\src\compteur_app\macos\Flutter\ephemeral\Packages\FlutterGeneratedPluginSwiftPackage\Sources\FlutterGeneratedPluginSwiftPackage\
	    New File  		      38	FlutterGeneratedPluginSwiftPackage.swift
100%  
	  New Dir          5	C:\src\compteur_app\macos\Runner\
	    New File  		     324	AppDelegate.swift
100%  
	    New File  		     360	DebugProfile.entitlements
100%  
	    New File  		    1092	Info.plist
100%  
	    New File  		     403	MainFlutterWindow.swift
100%  
	    New File  		     248	Release.entitlements
100%  
	  New Dir          0	C:\src\compteur_app\macos\Runner\Assets.xcassets\
	  New Dir          8	C:\src\compteur_app\macos\Runner\Assets.xcassets\AppIcon.appiconset\
	    New File  		  102994	app_icon_1024.png
100%  
	    New File  		    5680	app_icon_128.png
100%  
	    New File  		     520	app_icon_16.png
100%  
	    New File  		   14142	app_icon_256.png
100%  
	    New File  		    1066	app_icon_32.png
100%  
	    New File  		   36406	app_icon_512.png
100%  
	    New File  		    2218	app_icon_64.png
100%  
	    New File  		    1359	Contents.json
100%  
	  New Dir          1	C:\src\compteur_app\macos\Runner\Base.lproj\
	    New File  		   24072	MainMenu.xib
100%  
	  New Dir          4	C:\src\compteur_app\macos\Runner\Configs\
	    New File  		     624	AppInfo.xcconfig
100%  
	    New File  		      79	Debug.xcconfig
100%  
	    New File  		      81	Release.xcconfig
100%  
	    New File  		     593	Warnings.xcconfig
100%  
	  New Dir          1	C:\src\compteur_app\macos\Runner.xcodeproj\
	    New File  		   28632	project.pbxproj
100%  
	  New Dir          0	C:\src\compteur_app\macos\Runner.xcodeproj\project.xcworkspace\
	  New Dir          1	C:\src\compteur_app\macos\Runner.xcodeproj\project.xcworkspace\xcshareddata\
	    New File  		     246	IDEWorkspaceChecks.plist
100%  
	  New Dir          0	C:\src\compteur_app\macos\Runner.xcodeproj\xcshareddata\
	  New Dir          1	C:\src\compteur_app\macos\Runner.xcodeproj\xcshareddata\xcschemes\
	    New File  		    4707	Runner.xcscheme
100%  
	  New Dir          1	C:\src\compteur_app\macos\Runner.xcworkspace\
	    New File  		     159	contents.xcworkspacedata
100%  
	  New Dir          1	C:\src\compteur_app\macos\Runner.xcworkspace\xcshareddata\
	    New File  		     246	IDEWorkspaceChecks.plist
100%  
	  New Dir          1	C:\src\compteur_app\macos\RunnerTests\
	    New File  		     307	RunnerTests.swift
100%  
	  New Dir          1	C:\src\compteur_app\test\
	    New File  		    1100	widget_test.dart
100%  
	  New Dir          3	C:\src\compteur_app\web\
	    New File  		     917	favicon.png
100%  
	    New File  		    2172	index.html
100%  
	    New File  		     955	manifest.json
100%  
	  New Dir          4	C:\src\compteur_app\web\icons\
	    New File  		    5292	Icon-192.png
100%  
	    New File  		    8252	Icon-512.png
100%  
	    New File  		    5594	Icon-maskable-192.png
100%  
	    New File  		   20998	Icon-maskable-512.png
100%  
	  New Dir          2	C:\src\compteur_app\windows\
	    New File  		     308	.gitignore
100%  
	    New File  		    4271	CMakeLists.txt
100%  
	  New Dir          4	C:\src\compteur_app\windows\flutter\
	    New File  		    3851	CMakeLists.txt
100%  
	    New File  		     743	generated_plugins.cmake
100%  
	    New File  		     164	generated_plugin_registrant.cc
100%  
	    New File  		     302	generated_plugin_registrant.h
100%  
	  New Dir         11	C:\src\compteur_app\windows\runner\
	    New File  		    1836	CMakeLists.txt
100%  
	    New File  		    2193	flutter_window.cpp
100%  
	    New File  		     961	flutter_window.h
100%  
	    New File  		    1308	main.cpp
100%  
	    New File  		     448	resource.h
100%  
	    New File  		     616	runner.exe.manifest
100%  
	    New File  		    3166	Runner.rc
100%  
	    New File  		    2237	utils.cpp
100%  
	    New File  		     691	utils.h
100%  
	    New File  		    8822	win32_window.cpp
100%  
	    New File  		    3624	win32_window.h
100%  
	  New Dir          1	C:\src\compteur_app\windows\runner\resources\
	    New File  		   33772	app_icon.ico
100%  

------------------------------------------------------------------------------

               Total    Copied   Skipped  Mismatch    FAILED    Extras
    Dirs :        98        96         2         0         0         0
   Files :       173       173         0         0         0         0
   Bytes :   958.6 k   958.6 k         0         0         0         0
   Times :   0:00:00   0:00:00                       0:00:00   0:00:00


   Speed :           7,113,492 Bytes/sec.
   Speed :             407.037 MegaBytes/min.
   Ended : Saturday, November 14, 2026 6:05:00 PM


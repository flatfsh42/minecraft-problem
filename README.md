minecraft-problem
=================

---- Minecraft Crash Report ----

Description: Initializing game

org.lwjgl.LWJGLException: Pixel format not accelerated
	at org.lwjgl.opengl.WindowsPeerInfo.nChoosePixelFormat(Native Method)
	at org.lwjgl.opengl.WindowsPeerInfo.choosePixelFormat(WindowsPeerInfo.java:52)
	at org.lwjgl.opengl.WindowsDisplay.createWindow(WindowsDisplay.java:244)
	at org.lwjgl.opengl.Display.createWindow(Display.java:306)
	at org.lwjgl.opengl.Display.create(Display.java:848)
	at org.lwjgl.opengl.Display.create(Display.java:757)
	at org.lwjgl.opengl.Display.create(Display.java:739)
	at azd.Z(SourceFile:367)
	at azd.e(SourceFile:689)
	at net.minecraft.client.main.Main.main(SourceFile:103)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at org.lwjgl.opengl.WindowsPeerInfo.nChoosePixelFormat(Native Method)
	at org.lwjgl.opengl.WindowsPeerInfo.choosePixelFormat(WindowsPeerInfo.java:52)
	at org.lwjgl.opengl.WindowsDisplay.createWindow(WindowsDisplay.java:244)
	at org.lwjgl.opengl.Display.createWindow(Display.java:306)
	at org.lwjgl.opengl.Display.create(Display.java:848)
	at org.lwjgl.opengl.Display.create(Display.java:757)
	at org.lwjgl.opengl.Display.create(Display.java:739)
	at azd.Z(SourceFile:367)

-- Initialization --
Details:
Stacktrace:
	at azd.e(SourceFile:689)
	at net.minecraft.client.main.Main.main(SourceFile:103)

-- System Details --
Details:
	Minecraft Version: 1.7.2
	Operating System: Windows Vista (x86) version 6.0
	Java Version: 1.7.0_45, Oracle Corporation
	Java VM Version: Java HotSpot(TM) Client VM (mixed mode, sharing), Oracle Corporation
	Memory: 3798280 bytes (3 MB) / 26808320 bytes (25 MB) up to 518979584 bytes (494 MB)
	JVM Flags: 

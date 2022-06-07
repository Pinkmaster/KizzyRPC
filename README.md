# KizzyRPC
an android library for customising discord rpc written in Java. Now with Buttons support (no support for links ,only button texts will work)

Available at jitpack.io
[![](https://jitpack.io/v/dead8309/KizzyRPC.svg)](https://jitpack.io/#dead8309/KizzyRPC)

>Step 1. Add it in your root build.gradle at the end of repositories:
```gradle
repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
>Step 2. Add the dependency

```gradle
dependencies {
	       implementation 'com.github.dead8309:KizzyRPC:1.0.2'
	}
```


# Demo
```java
KizzyRPCservice rpc = new KizzyRPCservice(token);//Discord account token
        rpc.setName("hi")
        .setDetails("details")
        .setLargeImage("attachments/973256105515974676/983674644823412798/unknown.png")
        .setSmallImage("attachments/973256105515974676/983674644823412798/unknown.png")
        .setState("state")
        .setType(0)
        .setStartTimestamps(System.currentTimeMillis())
        .setButton1("Button1")
        .setButton2("Button2")
        .setStatus("online")
        .build();
```

![RPC _Demo](https://user-images.githubusercontent.com/68665948/172368963-90697dc2-3d7a-42e6-9511-d1497eadb637.png)


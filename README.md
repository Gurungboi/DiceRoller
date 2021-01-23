# DiceRoller
Udacity Kotlin 

---The beginnner of Android Kotlin Class----
---Lesson 1 ----

---Using Binding View instead of R.Id....
---which replace and more flexbility 

--------What is layout inflation? --------

"Inflating" a view means taking the layout XML and parsing it to create the view and viewgroup objects from the elements and their attributes specified within, and then adding the hierarchy of those views and viewgroups to the parent ViewGroup.Jan 2, 2011


--------What is layout inflation?--------
androidx.appcompat.app.AppCompatActivity. 
Base class for activities that wish to use some of the newer platform features on older Android devices. Some of these backported features include: Using the action bar, including action items, navigation modes and more with the setSupportActionBar(Toolbar) API.

--------What is LinearLayout?--------
LinearLayout is a view group that aligns all children in a single direction, vertically or horizontally. You can specify the layout direction with the android:orientation attribute. Note: For better performance and tooling support, you should instead build your layout with ConstraintLayout.Nov 18, 2020

--------What is view binding?--------
View binding replaces findViewById. View binding generates a binding object for each XML layout. You use this binding object to reference views, using their resource ids as the name:
View binding has the following benefits over findViewById:
* Type safety - findViewById requires you to specify the type of view you expect to be returned. For example, if you accidentally specify that you expect an ImageButton to be returned when the actual type is a Button, you'll get a ClassCastException. View binding protects you from this type of error because the view is a correctly typed property of the binding.
* Null safety - findViewById expects an integer parameter, which is meant to be the resource ID of a view. It is possible, though, to pass in any integer as a parameter, including unrelated integers and invalid view ids. If you supply an integer that doesn't match a view resource id in the layout, findViewById returns null and can cause a NullPointerException. View binding is null safe because you reference view objects directly and don't look them up by integer IDs.

--------What is Gradle?--------

Gradle is a build system (open source) which is used to automate building, testing, deployment etc. “Build. gradle” are scripts where one can automate the tasks. For example, the simple task to copy some files from one directory to another can be performed by Gradle build script before the actual build process happens.

--------Summary--------
* What device run your app
* Compile to excitable
* Dependency Management
* App Signing for Google Play
* Automated Tests

Two types of Gradle Files

In a project there are two types of Gradle files:
* build.gradle(Project)
* build.gradle(Module:app)

--------Module --------

A folder with source files and resource for a discrete piece of functionality of your app


--------Repositories-------- -> In gradle

Remote Server where external code is downloaded from

--------Dependency -------- -> In gradle
External code, such as libraries that a project depends on

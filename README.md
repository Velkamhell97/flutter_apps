# Flutter Apps

[1. Common Apps](#common-apps)
<br />
[2. Web Apps](#web-apps)
<br />
[3. Clean Architecture Apps](#clean-architecture-apps)

# Common Apps

## Movies App

Includes:

* Light Mode And Dark Mode
* Splash Screen and App Icon
* Custom Swipe Stack Viewer
* Provider State Management with equitable, dependency Inyection and good practices
* Shimmer Loading Image (skeleton)
* Search Delegate With Debouncer

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649738718/flutter_repos/Flutter%20Beginner/3.%20Movies%20App/movies_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649647976/flutter_repos/Flutter%20Beginner/3.%20Movies%20App/movies_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649647976/flutter_repos/Flutter%20Beginner/3.%20Movies%20App/movies_app_3.gif"></td>
	</tr>
</tbody>
</table>

---

## QR Reader App

Includes:

* Sqflite and Hive
* Hive TypeAdapters
* Provider as State Management with Dependency Inyection and good practices
* PageStorageKey for save scroll position when scan list changes.

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649737090/flutter_repos/Flutter%20Beginner/5.%20QR%20Reade%20Appp/scan_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649737090/flutter_repos/Flutter%20Beginner/5.%20QR%20Reade%20Appp/scan_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649737090/flutter_repos/Flutter%20Beginner/5.%20QR%20Reade%20Appp/scan_app_3.gif"></td>
	</tr>
</tbody>
</table>

---

## Firestore App

Includes:

* Auth service with Firebase Auth, signin and signup with persistent session and unique email validation.
* Products service with Firebase Firestore, retrieve, create and update products with a unique index validation for avoid product's name duplicity.
* Firestore ODM, create typed reference of Firebase collections then you can make CRUD operations to Firestore with dart Objects, another advantage is the possibility to create query's to filter data by properties.
* FirestoreBuilder Widget work as StreamBuilder for Firebase ODM references changes.
* Cloudinary service for store images.
* Offline support with Firestore offline persistence, when you are connected again the products will upload to Firestore automatically.
* Connectivity listener with beauty popup over any screen.
* Google Sign in
* Firebase Push Notifications and Local Notifications

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649875722/flutter_repos/Flutter%20Beginner/8.%20Firestore%20App/firestore_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649875729/flutter_repos/Flutter%20Beginner/8.%20Firestore%20App/firestore_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649875754/flutter_repos/Flutter%20Beginner/8.%20Firestore%20App/firestore_app_3.gif"></td>
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 4</th>
		<th>Demo 5</th>
		<th></th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649875724/flutter_repos/Flutter%20Beginner/8.%20Firestore%20App/firestore_app_4.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649875731/flutter_repos/Flutter%20Beginner/8.%20Firestore%20App/firestore_app_5.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1649648477/flutter_repos/transparent.png"></td>
	</tr>
</tbody>
</table>


--- 

# News App

Includes:

* Api Consumption Service (News Api)
* PageView and TabView Nested
* Provider as State Management with States Logic (equitable), filtering rebuild tricks and good practices.
* Provider Array States syncing with TabView, and Selector.
* Infinite Scroll with debouncer for new pages requests.
* State and Scroll Position Persistence with AutomaticKeepAliveClientMixin

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650328362/flutter_repos/Flutter%20Beginner/10.%20News%20App/news_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650328369/flutter_repos/Flutter%20Beginner/10.%20News%20App/news_app_2.gif"></td>
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 3</th>
		<th>Demo 4</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650328374/flutter_repos/Flutter%20Beginner/10.%20News%20App/news_app_3.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650328362/flutter_repos/Flutter%20Beginner/10.%20News%20App/news_app_4.gif"></td>
	</tr>
</tbody>
</table>


---

## Google maps app

Includes:

* MapBox Places API and MapBox Directions API.
* Google maps, custom markers, polylines, map camera operations.
* Location tracking service for update marker.
* GPS service changes handler, show alert dialog.
* Permissions service handler, show permissions screen.
* Dialogs Notifications Service.
* TextField Autocomplete with Overlays
* Provider Listener implementation with Future.microtask
* Provider as State Management with Dependency Inyection.


Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650312782/flutter_repos/Flutter%20Beginner/11.%20Directions%20App/directions_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650312782/flutter_repos/Flutter%20Beginner/11.%20Directions%20App/directions_app_2.gif"></td>
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 3</th>
		<th>Demo 4</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650312776/flutter_repos/Flutter%20Beginner/11.%20Directions%20App/directions_app_3.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650312780/flutter_repos/Flutter%20Beginner/11.%20Directions%20App/directions_app_4.gif"></td>
	</tr>
</tbody>
</table>

---

## Reponsive themed app

Includes:

* Custom ThemeValueNotifier with Union Class as states
* RouteValueNotifier for share the active page index across the app
* Responsive Designs for Landscape and Portrait
* Custom Painters
* AnimatedContainder, Animated Controller and TweenAnimationBuilder
* Staggered Animations and Sequence Animations
* Slivers, SliverList and SliverPersistenHeader
* Animated ListView Items
* State Management with setState and ValueNotifier
* Drawer

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_2.gif"></td>
	
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 3</th>
		<th>Demo 4</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_3.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_4.gif"></td>
	
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 5</th>
		<th>Demo 6</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_5.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_6.gif"></td>
	
	</tr>
</tbody>
</table>
<table>
<thead>
	<tr>
		<th>Demo 7</th>
		<th>Demo 8</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_7.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1650434433/flutter_repos/Flutter%20Intermediate/9.%20Theme%20Responsive/theme_responsive_8.gif"></td>
	
	</tr>
</tbody>
</table>

-- 

## Shoes App

Includes:

* Hero Animations with flightShuttleBuilder
* Responsive Size Buttons using Wrap and ConstrainedBox
* Provider as State Management
* Explicit Animations (AnimatedController & FooTransition)
* Mockup To Code.

Demo: 

![Shoes App](https://res.cloudinary.com/dwzr9lray/image/upload/v1650514119/flutter_repos/Flutter%20Intermediate/10.%20Shoes%20App/shoes_app.gif)

---

## Music Player App

Includes:

* Audio Provider, play, pause, reset, song duration, PositionStream, StateStream
* Scroll Lyrics Animation synced with song progress
* Song Progress Bar and Duration Labels
* AnimatedController and AnimatedIcon

Demo: 

![Music Player App](https://res.cloudinary.com/dwzr9lray/image/upload/v1650519433/flutter_repos/Flutter%20Intermediate/11.%20Music%20Player%20App/music_player_app.gif)

--- 

## Bands App

Includes:

* Provider as state management
* Client Sockets with Dart
* Server Sockets with Node JS and Express
* Graphs
* Environment variables for Production mode and Development Mode

Demo: 

![Bands App](https://res.cloudinary.com/dwzr9lray/image/upload/v1650678207/flutter_repos/Flutter%20Advanced/1.%20Bands%20App/bands_app.gif)

---

## Chat App

Includes:

* Provider as state management
* Client Sockets with Dart
* Server Sockets with Node JS and Express
* Environment variables for Production mode and Development Mode
* Auth service with different signup/signin methods: email and password, google signin and phone-sms signin.
* Password reset by email.
* User profile with name and editable avatar
* Users list changes in real-time
* User Chats changes in real-time
* Chat conversation page with animated message list.
* Multiple message types allowed: text-message, image-message, video-message, audio-message, file-message
* Text messages with emojis
* Image edition (paint, crop, emojis), the images can be taken from the camera or picked from gallery.
* Video edition (paint, crop, emojis), the video can be recorded with the camera or picked from gallery.
* File thumbnail preview, the files can be open by native apps
* Audio record and waveform visualization, you can seek the audio position
* Camera page has multiple editing options, zoom, exposure, focus point, hold and record.
* You can send multiple multimedia files (image and video)


Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667282202/flutter_repos/Flutter%20Advanced/2.%20Chat%20App/chat_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667282211/flutter_repos/Flutter%20Advanced/2.%20Chat%20App/chat_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667282145/flutter_repos/Flutter%20Advanced/2.%20Chat%20App/chat_app_3.gif"></td>
	</tr>
</tbody>
</table>


Examples: 

https://user-images.githubusercontent.com/54115437/199289538-9fde5ed2-0b13-400c-a78c-d49ca37d489c.mp4

https://user-images.githubusercontent.com/54115437/199291720-d9de1218-9fc2-41d5-b239-33d6672d7a01.mp4

https://user-images.githubusercontent.com/54115437/199305688-424c3169-cdb6-4d74-8d77-e56234884366.mp4

https://user-images.githubusercontent.com/54115437/199305708-01a4197c-5f5e-4f75-9161-02b997b640f7.mp4

https://user-images.githubusercontent.com/54115437/199305732-94af23fa-996b-46a5-88e4-20a3fb2f538d.mp4

https://user-images.githubusercontent.com/54115437/199305771-87b3878a-f862-46b7-ab6c-c91b61e34c28.mp4

---

## Google Maps App

Includes:

* Bloc as state management
* Equtable and Freezed for Handle states
* Google maps, polylines, markers camera tracking
* Custom markers and my location marker
* Location tracking in foreground and background
* Search delegate with debouncer
* Animations
* Navigation mode in google maps app

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667802368/flutter_repos/Flutter%20Advanced/3.%20Maps%20App/maps_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667802368/flutter_repos/Flutter%20Advanced/3.%20Maps%20App/maps_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1667802368/flutter_repos/Flutter%20Advanced/3.%20Maps%20App/maps_app_3.gif"></td>
	</tr>
</tbody>
</table>

---

## Payments App

Includes:

* Bloc as state management
* Equtable and Freezed for Handle states
* Paymnets with stripe, google pay, apple pay
* Notifications service: snackbars, dialogs, popups
* Fetch Serivce: http requests listeners, handle success, error status
* Save credit card with stripe form and custom form
* Server with node js to handle payment intents and webhook events
* Light and Dark mode
* Custom TextFieldInputFormatters for credit card fields
* Card brand detection with regular expresion
* Route Observer for tracking current route
* tri state widgets and animations

Demo: 

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1668703694/flutter_repos/Flutter%20Advanced/4.%20Payments%20App/payments_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1668703694/flutter_repos/Flutter%20Advanced/4.%20Payments%20App/payments_app_2.gif"></td>
	</tr>
</tbody>
</table>

---

# Web Apps

## Dashboard App

Includes:

* Bloc as state management
* Equtable and Freezed for Handle states
* Auth module - jwt
* Notifications service: snackbars, dialogs, popups
* Fetch Service: http requests listeners, handle success, error status, overlays, cancel tokens, etc..
* Local storage (SharedPreferences)
* PaginatedDataTable, with actions (edit, delete), pagination, rows per page, etc..
* AsyncDataSource and AsyncPageRequest
* Sorting columns
* Shortcuts (ESC to close)
* Nested navigation - url navigation (can save path as favorite)
* Responsive - layout changes based on screen size
* Route Observer for tracking current route
* Route guards


Demo:

https://user-images.githubusercontent.com/54115437/211112764-1ec70340-776e-4a1d-b62e-b3853a22dbb5.mp4

https://user-images.githubusercontent.com/54115437/211113148-488279b6-524f-49db-8a64-eb2014a27883.mp4

https://user-images.githubusercontent.com/54115437/211114099-92ff0e2a-4736-4635-9b5c-53e7a9a8a8e0.mp4

https://user-images.githubusercontent.com/54115437/211114191-018414da-811b-4dc7-8648-2c814d8b2394.mp4

https://user-images.githubusercontent.com/54115437/211114208-0ac3794e-cfd0-48b6-bbc4-42c2d183b3c4.mp4

--- 

# Clean Architecture Apps

## See you here

Includes:   

* Clean Architecture
* Bloc as state management
* Equtable for Handle states
* Google Signin and Anonymous Signin (can link with google) - Firebase Auth
* Push Notifications Service - Firebase Messagging
* Cloud Firestore database
* Google Maps - Custom Markers - Fit camera to bounds - InfoWindow
* Google Places Autocomplete Api - Google Geocoding Api
* Realtime markers position update (Firestore snapshots)
* Gps Service Handler
* Connection Service Handler

Demo:

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1675137563/flutter_repos/Flutter%20CA/2.%20See%20You%20Here/see_you_here_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1675137568/flutter_repos/Flutter%20CA/2.%20See%20You%20Here/see_you_here_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1675137638/flutter_repos/Flutter%20CA/2.%20See%20You%20Here/see_you_here_3.gif"></td>
	</tr>
</tbody>
</table>

## Chat App

Includes:   

* Clean Architecture
* Bloc as state management
* Equtable for Handle states
* Google Signin and Anonymous Signin (can link with google) - Firebase Auth
* Push Notifications Service - Firebase Messagging
* Cloud Firestore database
* Google Maps - Custom Markers - Fit camera to bounds - InfoWindow
* Google Places Autocomplete Api - Google Geocoding Api
* Realtime markers position update (Firestore snapshots)
* Gps Service Handler
* Connection Service Handler

Demo:

<table>
<thead>
	<tr>
		<th>Demo 1</th>
		<th>Demo 2</th>
		<th>Demo 3</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1677543615/flutter_repos/Flutter%20CA/3.%20Chat%20App/chat_app_1.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1677543904/flutter_repos/Flutter%20CA/3.%20Chat%20App/chat_app_2.gif"></td>
		<td><img src="https://res.cloudinary.com/dwzr9lray/image/upload/v1677543904/flutter_repos/Flutter%20CA/3.%20Chat%20App/chat_app_3.gif"></td>
	</tr>
</tbody>
</table>


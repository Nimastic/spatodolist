Last login: Mon Jan  8 17:03:24 on ttys000
/Users/jerielchan/.virtualenvs/ocv4/bin/python3: Error while finding module specification for 'virtualenvwrapper.hook_loader' (ModuleNotFoundError: No module named 'virtualenvwrapper')
virtualenvwrapper.sh: There was a problem running the initialization hooks.

If Python could not import the module virtualenvwrapper.hook_loader,
check that virtualenvwrapper has been installed for
VIRTUALENVWRAPPER_PYTHON=/Users/jerielchan/.virtualenvs/ocv4/bin/python3 and that PATH is
set properly.
(base) jerielchan@r-92-112-25-172 ~ % ls                         
*.js				Documents			Orbital				WebForum			flutterdev			sheares-app-frontend
A.class				Downloads			Picture 1.jpg			allen				forum-system			src
Applications			HelloWorld.java			Pictures			anaconda3			gymnext				todolist
AwesomeProject			IdeaProjects			Postman				app.py				index.html			todolistorbital
B.class				Library				Projects			codenext			lab8.circ			zshrc
CS2030S				Main.java			Public				crypto_wallet			my_virtual_envs
CVWO				Movies				StudioProjects			cv.py				myenv
CalendarApp			Music				Taxi.java			cv2.so				package-lock.json
Chicken Toy Web			MutataApp			TaxiManager.java		edb_pgjdbc.app.zip		pg_hba.conf
Desktop				MutataShowcase-Android		Test.java			edb_postgis_3_1_pg14.app.zip	sample-react-app
(base) jerielchan@r-92-112-25-172 ~ % cd sheares-app-frontend 
(base) jerielchan@r-92-112-25-172 sheares-app-frontend % vim -p README.md 










































# Installation

### 1. Clone the repository

```
git clone https://github.com/ShearesWeb/sheares-app-frontend.git
```

### 2. Install libraries

```
>>> npm ci
```

### 3a. [Install Android (Windows Users)](https://reactnative.dev/docs/environment-setup?guide=native)

Follow the guide [here](https://reactnative.dev/docs/environment-setup?guide=native) for installing Android Studio.

At the time of writing the linked guide is outdated and written for Android 13. For Android 14, just note that we are on version 34.

Once you've finished the installation, make sure you have a virtual device as seen [here](https://docs.expo.dev/workflow/android-studio-emulator/#set-up-a-virtual-device).

### 3b. Install Android & IOS (Mac Users)

Android:

Follow the guide [here](https://reactnative.dev/docs/environment-setup?guide=native) for installing Android Studio.

Once you've finished the installation, make sure you have a virtual device as seen [here](https://docs.expo.dev/workflow/android-studio-emulator/#set-up-a-virtual-device)

IOS:

Install Xcode from Mac App Store. 

Launch Xcode, a dialog will be presented that indicates which Simulator runtimes are built-in, and which Simulator runtimes you may download. For now, choose Continue to finish setting up Xcode.

Once you've finished setting up, install IOS Simulators using this guide [here](https://developer.apple.com/documentation/safari-developer-tools/installing-xcode-and-simulators).



### 4. Add the ```.env``` file

Add to the base directory. If you don't have it ask someone for it.
Take note of "." infront of env when downloading on MacOS.


### 5. Run
```
>>> npm run android
>>> npm run ios
```

Possible Issues for MacOS:
1.

Solution:

>>> gradle init
>>> npx expo start --dev-client

~                                                                                                                                                                                                           
~                                                                                                                                                                                                           
-- INSERT --

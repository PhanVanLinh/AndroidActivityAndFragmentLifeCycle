# AndroidActivityAndFragmentLifeCycle

## Activity

#### Launch app
```
ACTIVITY: onApplyThemeResource
ACTIVITY: onCreate
ACTIVITY: onStart
ACTIVITY: onResume
```
#### Rotate screen
```
ACTIVITY: onPause
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
ACTIVITY: onDestroy
ACTIVITY: onApplyThemeResource
ACTIVITY: onCreate
ACTIVITY: onStart
ACTIVITY: onRestoreInstanceState
ACTIVITY: onResume
```
#### Press Home
```
ACTIVITY: onPause
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
```
###### Launch again from background (after press home)
```
ACTIVITY: onRestart
ACTIVITY: onStart
ACTIVITY: onResume
```
#### Press Back
```
ACTIVITY: onPause
ACTIVITY: onStop
ACTIVITY: onDestroy
```
##### Launch again from background
```
ACTIVITY: onApplyThemeResource
ACTIVITY: onCreate
ACTIVITY: onStart
ACTIVITY: onResume
```
#### Press recent app
```
ACTIVITY: onPause
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
```
###### Launch again from background
```
ACTIVITY: onRestart
ACTIVITY: onStart
ACTIVITY: onResume
```
###### Kill app
```
ACTIVITY: onDestroy
```

#### Open new Activity
```
ACTIVITY: onPause
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
```
#### Resume from other Activity
```
ACTIVITY: onRestart
ACTIVITY: onStart
ACTIVITY: onResume
```
#### Open Alert Dialog
**NOTHING CALL**
#### Close Alert Dialog
**NOTHING CALL**

#### Open Request Permission DIalog
```
ACTIVITY: onPause
```
#### Close Request Permission Dialog
```
ACTIVITY: onResume
```
**NOTHING CALL**

## Fragment

#### Add
```
FRAGMENT: onAttach
FRAGMENT: onCreateView
FRAGMENT: onViewCreated
FRAGMENT: onStart
FRAGMENT: onResume
```
#### Open new Activity
```
ACTIVITY: onPause
FRAGMENT: onPause
FRAGMENT: onSaveInstanceState
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
FRAGMENT: onStop
```
#### Resume from other Activity
```
ACTIVITY: onRestart
ACTIVITY: onStart
FRAGMENT: onStart
ACTIVITY: onResume
FRAGMENT: onResume
```

#### Press Home
```
ACTIVITY: onPause
FRAGMENT: onPause
FRAGMENT: onSaveInstanceState
ACTIVITY: onSaveInstanceState
ACTIVITY: onStop
FRAGMENT: onStop
```

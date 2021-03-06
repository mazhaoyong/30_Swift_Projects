# 30 Swift Projects

## 01. Change Font
### Change font by pressing button.
Use **CocoaPods** to manage frameworks, **SnapKit** for autolaying.

## 02. Timer
### A simple timer tool
Use **CocoaPods**, **SnapKit**, **Timer**.

## 03. Pull To Refresh
### Pull the tableview to refresh data
Use **UITableView**, **UIRefreshControl**, **Date**, **DateFormatter**

## 04. Emoji Slot Machine
### A slot machine game using UIPickerView
Use **UIPickerView** to make the view, **UILongPressGestureRecognizer** to make a gesture to cheat.

## 05. Photo Viewer
### A photo viewer using gesture to resizing.
Use **UIScrollView** to resize picture and display part of it.

## 06 Color Gradient
### Change UIView color gradient.
Use **UIPanGestureRecognizer**, **CAGradientLayer**.

## 07_Swipe_Row
### Swipe on UITableViewRow, actions will display on the right.
Use **UITableViewRowAction**, **UIAlertController**.

## 08_Stretchy_Header
### Pull UITableVIew down, the header picture will resize.
Use **UIScrollView** - scrollViewDidScrol to get offset to resize picture.

## 09_Video_Background
### Spotify-like video background on UIViewController
Use **AVPlayerViewController**

## 10_Tumblr_Menu
### Tumber-like menu. Use tap gesture to display a motion effect menu.
Use **UIVisualEffectView**, **animate()**.

## 11_3D_Touch
### Quick action with 3D touch press on home screen and peek view in app.
Use **UIApplicationShortcutItem**, **UIViewControllerPreviewingDelegate**.


## 12_Spotlight_Search
### Search items in Spotlight.
Use **CSSearchableItem** to create an item supports Spotlight. Use **CSSearchableItemAttributeSet** to configurate it.
Implement
    func application(_ application: UIApplication, continue userActivity: NSUserActivity
in AppDelegate.swift to process after selecting a result in Spotlight.


## 13_Today_Extension
### Add today extension to Today View.
Use **App Group** to share data between App and Extension. Use **NSUserDefault** to save and load data.

## 14_Core_Data
### Use Core Data to save and load data.
Use **CoreData** kit. Define entity first. Use *appDelegate.persistentContainer.viewContext* to save and read data.

---
layout: page
title: What's New
include_in_header: true
---

# Changelog

<br>

### `Latest`
# **Version 1.1.0**
The entire library fetching system has been reworked to be cleaner, and work with Jellyfin. Almost every component has been touched up in some way. Images now get defined qualities significantly improving performance on top of the new system. Reworked caching ensures your data doesn't go stale, but is remembered. Opt-in analytics have been introduced in an effort to get more tester feedback. + **A WHOLE LOT MORE**

#### What's New
- **Jellyfin Support**
- Reworked library fetching, the app now defines adapters for Navidrome and Jellyfin that it can use throughout the app.
- Touched up screens throughout.
- Images now define what quality they should be. No more fetching a big image for a smaller image in the app.
- Tanstack Query is now used by components, directly talking to the api adapter.
- Query lets the app know when to refetch, and can persist data.
- A **New** server screen lets users easily switch between Navidrome and Jellyfin.
- Reworked playback, RNTP isn't reliable so the app handles the queue now, increasing performance and load times.
- Optional remove AI button from playing bar.
- Skeleton loading
- Read more on Last.fm via artist screen
- Get started screen shows up once
- Select from multiple AI Providers
- Opt-in analytics
- Type-safe updates

#### Bug Fixes
- Android playing bar touch works
- Glitchy queue after dragging
- Jellyfin duration bug
- Confusing lidarr plugin toggle

<br>

### **Version 1.1.1**
Light mode fully complete, touchups and bug fixes.

#### What's New
- Skeleton loading on homepage
- Lightmode
- Improved lidarr (if the program itself would work)

### **Version 1.1.2**
Small improvements and bug fixes

#### What's New
- Borders on headers
- Lightmode touchups, playlist list
- Discord about button
- Stats make more sense

#### Bug Fixes
- Local addresses on android?
- Seeking on android?

### **Version 1.1.3**
Upgrading and stabalizing dependencies.

#### What's New
- Expo SDK 53
- React 9
- Replaced react-native-ios-context-menu with @react-native-menu/menu

#### Bug Fixes
- Android insets on playing screen
- Android local addresses?

### **Version 1.1.4**

#### What's New
- Lyrics
- Light and darkmode selector
- New context menus
- New context options
- New info modal for items
- Internal only toggle

#### Bug Fixes
- IOS connection issue
- Android playing screen
- Android glass fix

### **Version 1.1.5**

#### What's New
- Discovery page
- Listenbrainz & MusicBrainz instead of Last.fm
- Accurate playcounts
- External types
- Placeholder images for every image
- Consistent bottom sheets
- Scrobbling
- Removed AI Button
- Action buttons

#### Bug Fixes
- Toasts showing below playing screen bottom sheet
- Server URL overflows
- Jellyfin seeking?
- Tapping connectivity errors

### **Version 1.1.6**

#### What's New
- External album and artist pages
- Three categories to browse from
- View all bottom sheet
- View external album from library album
- Octo-fiesta support

#### Bug Fixes
- Scrobbles are legit

### **Version 1.1.7**

#### Bug Fixes
- Playing screen lag ( still exists )
- Media image loading fix ( still exists? )

### **Version 1.1.8**

#### What's New
- Slskd downloader support
- Bottom sheets fully replacing other menus
- Queue touchups
- Explore rework ( more to come )

#### Bug Fixes
- Skipping

### **Version 1.1.9**

#### What's New
- Recently played
- Playing screen remodel
- Search now includes artists, albums, and playlists
- Discovery section remodel
- Play similar music queues via the Dial on the Discovery page
- Add to playlist action button
- Artist bottom sheet

#### Bug Fixes
- Smoother loading

### **Version 1.1.10**

#### Bug Fixes
- Recently played music and playcounts relying on a ListenBrainz connection
- Alignment on Discovery page

### **Version 1.1.11**

#### Bug Fixes
- Dial misalignment
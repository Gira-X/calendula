# Calendula

I am using this excellent app to keep track of [Medical Medium supplements](https://www.medicalmedium.com/preferred/supplements) from his newest book: [Cleanse To Heal](https://www.medicalmedium.com/) but I had to adjust the app slightly for my use-cases.

The Medical Medium supplements can be taken almost whenever throughout the day, so the schedules in the app are not too important for me.


### Small fixes

* Removed annoying confirmation dialogs in ConfirmActivity about past or future times
* Supplements are sorted alphabetically in Agenda and ConfirmActivity
* Removed many icons from the Agenda view and enlargened `RecyclerView` supplement texts for easier display
  * The pill icons are not useful for me, as well as the multiple users feature
* Fixed the height bug in the ConfirmActivity `RecyclerView` by not using a collapsing toolbar
  * When one has a long list, the height is calculated incorrectly and it happened that the last items get cut off from display
* Also removed a few fancy materialish-animations

All of those are super quick dirty-hotfixes for myself, so take care ;)

### Screenshots

<img src="https://github.com/Gira-X/calendula/raw/master/assets/screenshots/screen.png" width="230px"/> <img src="https://github.com/Gira-X/calendula/raw/master/assets/screenshots/screen2.png" width="230px"/>

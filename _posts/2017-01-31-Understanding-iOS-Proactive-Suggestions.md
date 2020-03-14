---
layout: post
tags: [sitepoint, ios]
---

With the introduction of the “Proactive” feature in iOS 9, Apple is trying to *proactively* assist you. The system learns from your actions and attempts to anticipate them. It starts showing suggestions, recommendations, apps you frequently use, etc.

## Handoff

The Handoff feature hasn’t changed but the space usually reserved for it in the lock screen is used for *suggested* apps. Apps shown in the bottom-left corner of the lock screen and in the app switcher are based on your location or habits. The following screenshots show quick access to the Music app when I plug in my headphones.

<span style="display:block;text-align:center">![Lock screen](/assets/images/2017-01-31/1481067428IMG_8438.png)

<br/>

<span style="display:block;text-align:center">![App switcher](/assets/images/2017-01-31/1481067437IMG_8439.png)

iOS has noticed that when I plug in my headphones, I immediately go to the Music app, so it now gives me quicker access to it. The same will happen for an app that uses location. It will appear when you are near your favorite restaurant, for instance.

## Spotlight search

Spotlight search can be reached from the home menu; by swiping down or by swiping all the way left. The first thing to notice are the Siri suggestions below the search bar. By default, you’ll see the 4 apps you are likely to use at that given *time* (of the day or night), but it can be expanded up to 8 apps. It also depends on your location, or on whether your headphones are plugged in. So Siri suggests apps depending on your previous behavior or on the time of the day.

In the screenshot below on the left, Siri has suggested messaging apps and a game I currently play. Notice that in the screenshot on the right, the suggestions change as I plugged in my headphones. Just as in the previous example, the system is trying to help access the Music app quicker.

<span style="display:block;text-align:center">![Siri suggestions](/assets/images/2017-01-31/1481067390IMG_8434.png)

<br/>

<span style="display:block;text-align:center">![Siri suggestions](/assets/images/2017-01-31/1481067448IMG_8440.png)

When searching for a word, results are grouped based on where they are found. I tried searching for ‘Pi’ and many results listed, including the number as a top hit, applications, contact names containing ‘pi’, messages, emails, etc. Any third-party app that makes use of the spotlight search API would also show its content in the list of results.

<span style="display:block;text-align:center">![Spotlight search](/assets/images/2017-01-31/1481067400IMG_8435.png)

<br/>

<span style="display:block;text-align:center">![Spotlight search](/assets/images/2017-01-31/1481067410IMG_8436.png)

You can always turn off Spotlight Search in *Settings -> General -> Spotlight Search*.

## Siri with context

In iOS 10 Siri is more open to the developers. This means more interaction with third party apps. Now Siri has contextual awareness on what you are doing and what you are looking at on your device. For example, if you are writing an email and ask Siri “Remind me to send *this* this afternoon”, Siri will know what “this” is and create a reminder for you. The reminder will have a link to the Mail app and the current email you are looking at, so it will take you at the same spot when the time is right.

## Maps

Apps that provide locations can now share their information with the system. So let us suppose you are searching for a restaurant location in your favorite app. If you open app switcher you will be able to get directions to that restaurant location right away. The Maps app will suggest this location even if you manually open it. Or if you are writing to a friend to set a meeting place, the restaurant address will be suggested. Finally, the location would be available even in the Spotlight search.

## Keyboard suggestions

QuickType provides enhanced auto-correction in iOS 10. The keyboard is automatically selected by the system depending on the type of input the field requires. So the system will detect whether you are writing a phone number, an email address, or a street address, and the keyboard will show only the characters you need. Furthermore, knowing what type of input to expect allows better suggestions to be shown. If you were interacting with the Maps app and viewing a restaurant or viewing a contact you have, the suggestions will be based on that interaction. This is again done by better integration of third-party apps with the system.

## Contact interactions

When writing an email to a group of colleges or classmates, proactive suggestions make it easy to select the recipients. Based on recent conversations you had, and based on the people you tend to include in the same group, it gives a few choices from which to select. This is very handy, especially when you are in a hurry and don’t want to lose time writing long email addresses. It can also remind you to add someone you forgot to.

For third-party apps, the integration with the Contacts app has made it possible to share contact information as shown below.

<span style="display:block;text-align:center">![Contacts](/assets/images/2017-01-31/1481238629IMG_8551-e1481241064303.png)

## Conclusion

Apple wants to offer you the best experience possible by anticipating your needs and wishes. For this to happen, the system will need time to learn from and adapt to your habits and preferences. Apple has made this clear: The more you use your phone, the better the phone serves you.

***May the Code be with you!***
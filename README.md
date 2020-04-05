# timestamp_parser
A lightweight java app which parses generic timestamps in text form to an Audacity-compatible textmarker format.

I have made this as a Java 12 Command-Line app previously and decided to downport it to Java 8u241 for more widespread platform support and as it never utilized any features specific to Java >8.
The purpose of this app is solely to make it easier to organize compound audio files by auto-generating the required Audacity textmarkers.

Currently, I'm working on rewriting the lost source code from the original app and then creating a swing GUI for it.
Plans for the future are direct Audacity Integration (either as a plugin for said Program or recycling some of the Audacity source Code to directly split and label audio files) and subsequently either additional tntegration to Tag-Editors like MusicBrainz, MP3Tag or EasyTag, or the possibility of automatically editing the Audio metadata in the Java app.

Side Note: Use the app for whatever you want, share it, edit the source code, copy and change this entrire repository, simply use it as the text-to-text parser it's supposed to be or repurpose it for something completely different.
I don't care, as long as you don't use it to violate the law or anyone's rights. Using, sharing or possessing this software in any way is on your own risk, I don't take any responsibility for anything that happens as a consequence of that, I especcially don't take responsibility for any data loss or hardware corruption due to programming errors or bugs in the software. I also do not guarantee that this software works as intended or even at all, as it is just a hobby project.

# DayZ-Books
My repository of the books types.xml codes I use in my server to add books into the game world for DayZ. Aesthetically fits with the rest of the types.xml file.

1. Usage

This is a free to use resource for any DayZ server owner to easily add these items to your game world.

2. Function

This code functions by copy & pasting the text into your own types.xml file within your community server for DayZ. It will add books to the loot pool.
How to do it:
1. Download your types.xml file from your community server
   - It is preferred to work on a downloaded, locally saved file to avoid unneccesary errors causing game issues.
2. Download my file from here (books.xml)
3. Open your types.xml file in your preferred text editor (I use Notepad)
4. Open the downloaded books.xml in the same application (new window)
5. Scroll to the BOTTOM of your types.xml file (open locally)
6. Make a line down between the lowest </type> and </types> (the end of the XML code)
7. Copy the text from my books.xml and paste it in the line down you have made
8. Save your new types.xml as "types.xml"
9. Upload your new types to the db folder in your community (Nitrado) server
   - Web interface>file browser>db - upload here to db (will overwrite the original types.xml)
-----------------------------------------------------------------------------------------------------------------------------
Do not upload the books.xml to the db or anywhere else in the server. It will not function on its own!! It **MUST** be part of the types.xml file.

Note: Books in DayZ cannot currently be read but make interesting collector, quest or character items. For example, HaRP has a character who is documenting the old world by collecting books for storage.

If you want more books to spawn, simply change the <nominal>1</nominal> number to a different value.
If you want books to spawn in different areas, simply copy & paste the <usage name="Town"/> line, make a line down, paste it in there and change the value from Town to another one (see types.xml for all usage names). Alternatively, change the existing usage names to the one you want. For example, if usage name is Military this will change them to spawn in a barracks/tent/checkpoint etc.

ALWAYS VALIDATE ANY NEW FILE BEFORE UPLOADING TO YOUR SERVER
If you encounter any issues please email outlanderess@protonmail.com

Have fun, book collectors!!

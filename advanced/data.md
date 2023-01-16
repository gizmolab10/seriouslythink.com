# Storing Your Data Locally or in Cloud

Every change you make is automatically saved. You don’t need to do anything, ever. If you are connected to the network, your changes are stored in your iCloud account. The public graph’s data is stored in Thoughtful’s public iCloud account, where everyone can access it.

## Files

During those times when you aren’t connected, your changes are stored in a local file. Thoughtful will detect when your resume connection, and will immediately store your unsent changes in the cloud. If you are curious to see the local file, **hold the COMMAND and OPTION keys down and tap the O key** (capital o). You will see four files. Two of them are current, one for each graph (yours and public). The other two are backups, in case file corruption happens while not connected.

These files are always kept current for two reasons. (1) If you launch Thoughtful while not connected, you can still work on your graph. (2) Reading data from the cloud is much slower than from a file, so Thoughtful reads from the files when it launches and then fetches any more recent data from the cloud.

## Import and Export

You may want at some point to share some of your data with a friend. Sending one of the files mentioned above is probably not what you want. Thoughtful can export a single idea and all its subordinates to a local file with a single command. Focus on your idea-to-be-shared and **tap the S key**. A new file will be named the same as your idea, with _.thoughtful_ as the extension.. Give this file to your friend and tell them to drag and drop it onto the Thoughtful app’s icon. This will import your ideas into their current focus. Another way to import a file is to select the idea inside which you want the data to be placed, the **tap the O key (capital o)** and in the Open File Dialog, select the file. Your data will appear instantly.

Since Thoughtful graphs have the same structure as an outline, you can save any idea as an outline: **hold the OPTION key down and tap the S key**. Importing an outline file is not supported yet.

## Refresh from Cloud

Although I think this no longer happens, I have seen Thoughtful fail to show some of my data. I know I did not delete it or move it somewhere else. So I added three features for you to use to re-fetch data from the cloud. (1) **Tap the G key** to fetch the immediate subordinate ideas of the currently selected idea. (2) **Hold the OPTION key and tap the G key** to fetch all of its subordinate ideas. (3) **Hold the COMMAND key and tap the G key** to fetch the entire graph.
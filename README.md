# Text Message Analysis Notebook

[This notebook](Text%20Analysis.ipynb) shows how to visualize the number of text
messages exchanged (with a specific person, or overall), and the volume of characters
exchanged.

![Example of the plot of the number of texts
received/sent with a specific person over time](docs/example-absolute-text-count.png)

![Example of the plot of the rescaled number of texts
received/sent with a specific person over time](docs/example-rescaled-text-count.png)

## Rationale

It is surprising to notice how much information can be extracted from the visualization
of the _patterns_ of communication alone—without the contents of the messages. For
instance, in the example above, it is clear that the person sending messages (in green)
is more invested in the relationship: In the _rescaled plot_, we can see that in
the beginning, both of the correspondents are responsible for about 50% of the messages;
but this trend quickly changes over time.

## Requirements

- [iMazing](https://imazing.com/): This is the app I recommend to
  extract text messages from your iPhone, it works both on Windows and macOS.
  It is able to handle SMS, iMessage and WhatsApp
  seamlessly. It currently costs $34.95 for a Lifetime License, and has been
  [available and reliable since 2008](https://en.wikipedia.org/wiki/IMazing)—but there
  is also a trial version that will work for this (it is limited to 25 messages).

- Jupyter Notebook and `pandas`: These are the tools I use in this notebook to analyze
  and plot my text messages.

### For Android users

For Android phones, you can use the [SMS Backup and Restore
app](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore&hl=en).
Read [this article](https://www.wideanglesoftware.com/blog/backup-sms-android.php)
for more information. The notebook provided here may need to be adapted.

# Gif Reply Slack App

Do you like reaction gifs? Do you use Slack too? Do you sometimes that people would reply to your 
comments with reaction gifs too?? If so, then this Slack App for you. Based upon the award-winning advanced NLP
by Xingyao Wang and David Jurgens, this app will add a chatbot to any Slack channel
of your choosing and have the bot reply automatically reply to comments with appropriate and often hilarious 
reaction gifs. No more waiting for someone to use the `/giphy` command&mdash;AI has now taken that job too&mdash;
leading to a more entertaining and gif-filled Slack workspace.


# Usage

## How to Install the Slack App

To install the Slack App.... [details here]

### Add the app to your work space
1. Launch your Slack workspace
2. Go to Setting &amp; administration -> Manage apps (this will probably open a browser)
3. ????

### Add the app to a particular channel

Once you have the app installed in your workspace, you can add it channels in which you want the slackbot to interact.

1. Either (1) right click on channel name -> Open channel details, or (2) left click on channle and click the down-carrot at the top by its name
2. Click the Integrations ta
3. In the Apps box, click Add apps

### Configuring the slackbot itself

The app has several models of interacting:
* Reply to all comments
* Reply to only the top-level comments (but not replies to these comments in threads)
* Reply only when then `gif

# Important notes

* This Slack App is intended for entertainment purposes only. We (the developers) have done our best to avoid having the slackbot reply to offensive content. However, due to the creativity of humans to be weird and mean, it might still reply when it shouldn't. Moreover, some gifs may be interpreted as offensive replies to certain content. We, again, have done our best to avoid this, but it could still happen. **Any offensiveness made a result of a reply is entirely unintentional and does not reflect the views of the Slack App's creators nor of our intentions when building this App.** Our intent is to bring joy in an appropriate manner. Please feel free to report any notable cases as GitHub issues to this repository.

* This Slack App is backed by very fancy deep learning and, as a result, requires some computer to run those deep learning models to figure out which gif to use. **Using this app will send any message that need gifs to servers operated by us to run the model!** Do not use this App if you intend to send private or protected communications. We have to receive this text to select the right gif reply so there is no technical way to not get it (though pull requests welcomed?). We reserve the right store these comments and which gifs are used in order to audit and improve the model (e.g., find bugs, identify cases where the model should not have replied). This data is always protected and will *never* be shared externally.

* Similar to the above, **Using an emoji reaction to a gif will be sent to servers operated by us*. We use these emojis as natural reactions to identify cases where the model has done well (yay!) or has made someone upset (hopefully rare) and further improve the model. This data will never be shared anywhere else.

* The slackbot's name is officially "Pepe the King Prawn". However, you may also address the slackbot as Pepino Rodrigo Serrano Gonzales as well. Pepe does not react to mentions of its name, nor does using the name matter, but it's still neat to know.

# Getting Help

If you running into issues, we're happy to help. We run all of the support for this project through this's Github repository's issues. Please do not try to track us down and email us for support because we will probably just redirect you to the repo, but then we'll feel guilty and you'll wait longer and I don't think either of us want that.

# Final Details and Credits

This project is based on work described in 
```
Xingyao Wang and David Jurgens. An Animated Picture Says at Least a Thousand Words: Selecting Gif-based Replies in Multimodal Dialog.
Proceedings of the Findings of the 2021 Conference on Empirical Methods in Natural Language Processing (Findings of EMNLP). 
```
You can read all about this project, data, model, etc in the exciting PDF technical report _or_ in the general-audience [Imgur post](https://imgur.com/gallery/G0oSrLV) that goes into more detail than it probaly should. 

If you are an academic who for whatever reason needs to mention this project in your paper, please cite the above so that Xingyao will get more citations and go on to be a successful highly-cited researcher.

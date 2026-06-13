# Whatsapp_ChatAnalyzer


A simple WhatsApp Chat Analyzer ( for both Private &amp; Group chats ), made with :heart:

**With concurrency support !!!**


## Functionality

- So these scripts are for analyzing **WhatsApp** Chat _( both Private & Group )_, which can easily be exported into a _*.txt_ file from WhatsApp Mobile Application.
- That _*.txt_ is parsed, cleaned & objectified, so that it can be analyzed with ease.
- Using this tool, now each minute spent on a certain Chat can get noticed _( or may be how someone else spent )_ or how many times someone started a conversation _( which might be a good indicator of interest of participant(s) towards Chat )_
- For sake of **Privacy** test data file(s), which were used for plotting following chart(s), are kept private. Also Contact Name(s)/ Number(s) are partially grayed.

## Usage

- Install `chanalyze` from PyPI

```bash
$ python3 -m pip install --user chanalyze
```
- Make sure you've added `$HOME/.local/bin` to your `$PATH` environment variable
- Export target Whatsapp chat into `*.txt` file, while omitting media.
- Now analyze your exported WhatsApp chat(s), using **chanalyze**

##  _( Chat Analysis )_

- [x] [Total Contribution of Chat Participants](docs/totalContribution.md)
- [x] [Hourly Contribution of Chat Participants](docs/hourlyContribution.md)
- [x] [Activity of Chat Participants on every Minute of Day](docs/contributionByMinute.md)
- [x] [Activeness of Chat](docs/chatActiveness.md)
- [x] [Conversation Initializing Chat Participant Identification _( using Mean & Median Delay )_ - Reflecting Participant's interest towards Chat](docs/conversationStartingPerson.md)
- [x] [Top Emojis used in Chat](docs/emojiStat.md)
- [x] [Chat Activity HeatMap](docs/heatmap.md)
- [x] [Word Cloud from Messages](docs/wordCloud.md)

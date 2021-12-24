## Evernote example

Service for working with api [Evernote](https://evernote.com/intl/ru/)

This script is written as part of the task of the courses [Devman](https://dvmn.org).


## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Python Version

Python 3.6 and later.

### Installing

To install the software, you need to install the dependency packages from the file: **requirements.txt**.

Perform the command:

```

pip3 install -r requirements.txt

```

## Getting API keys
- EVERNOTE_CONSUMER_KEY="username"

- EVERNOTE_CONSUMER_SECRET="your symbols"

- EVERNOTE_PERSONAL_TOKEN="your symbols"

- JOURNAL_TEMPLATE_NOTE_GUID="your symbols"
- JOURNAL_NOTEBOOK_GUID="your symbols"
- INBOX_NOTEBOOK_GUID="your symbols"
- EVERNOTE_CONSUMER_KEY - [Get here](https://dev.evernote.com/doc/)
- EVERNOTE_CONSUMER_SECRET - [Get here](https://dev.evernote.com/doc/)
- EVERNOTE_PERSONAL_TOKEN - [Get here](https://dev.evernote.com/get-token/)

JOURNAL_NOTEBOOK_GUID - We get from the URL:


JOURNAL_TEMPLATE_NOTE_GUID 
https://www.evernote.com/shard/.../guid_JOURNAL_NOTEBOOK_GUID?...
INBOX_NOTEBOOK_GUID - GUID this is an inbox


##Examples:


#### add_note2journal.py
Creates notes. Notes will be created in notepad JOURNAL_NOTEBOOK_GUID:

**parameters:**
- `date` - defined field

- `dow` - determine the day of the week


```
$ bin/python add_note2journal.py 2021-12-23
```


#### list_notebooks.py
Get a list of your notebooks:

```
$ python list_notebooks.py
```

#### dump_inbox.py
Get the contents of notepad:

```
$ bin/python dump_inbox.py 
```




## Authors

**vlaskinmac**  - [GitHub-vlaskinmac](https://github.com/vlaskinmac/)

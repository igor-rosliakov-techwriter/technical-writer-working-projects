# CloudBox CLI installation

CloudBox CLI is a tool for working with cloud files. 

Available systems for working: Windows, macOS, Linux.

CloudBox CLI works with any type of the files. Maximum size of the file -- 100Mb.


## Installation

**First**, install Python. You need the version 3.10 or later. Use the [official page] (https://www.python.org/downloads/)

**Second**, install CloudBox using the command:

```bash
pip install cloudbox-cli
```

TODO: check whether the installation is successful.

After installation, run:

```bash
cloudbox
```

If everything works, you can start using it.

TODO: add the troubleshooting if the installation was unsuccessful.

## Configuration

Before uploading files you need configure your account.

**Step 1.** Get the token from your CloudBox account.

**Step 2.** To set the configuration, run the command:

```bash
cloudbox config --token YOUR_TOKEN
```

TODO: explain configure options

## Uploading files

To upload a file, use `cloudbox upload` command. For example:

```bash
cloudbox upload file.txt
```

The file will be uploaded to the cloud. 

TODO: add more information about managing my uploads.

## Troubleshooting

If something doesn't work, try reinstalling the application or contact support.

TODO: add the few commonly ways to fix problems.

---

# Questions for the Developer

- How can i understand than "everything works" after the installatiion?
- What is commonly problems during the installation and what the commonly ways to solve these problems?
- What can i configure in the Account settings run by `cloudbox config --token YOUR_TOKEN` command?
- What can i do with my files after uploading?
- How can i fix commonly problems during the managing out service?


---

# Editorial Decisions

I would like to make our documentation more specific. To do this, i made several things:
- Deleted speaking-style phrases that do not have practical usage.
- Added *TODO* memories to fill the gaps of instructions.
- Separated fuzzy instructions for the steps.

Now i will be waiting answers on my questions for continuing the work.

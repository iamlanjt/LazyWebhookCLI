# LazyWebhookCLI
A CLI(Command Line Interface) for making webhook API requests to the Discord social service.

# How to run winBinary

1. Download .ZIP file from Releases link
2. Unzip/Unpack both files from the .ZIP file and put them **in the same directory you will run the terminal in**.
3. Open a command prompt **with a current-directory of where you put both files** and run the .EXE with ``LWHCLI.exe``
4. (extra) Without any tags, running ``LWHCLI.exe`` alone will result in an error, so use ``LWHCLI.exe -?``/``LWHCLI.exe -h``/``LWHCLI.exe --help``

# How to run winBinary (via the PowerShell installer)

1. Go to releases page and install ``main1.ps1`` or any file which has the extension ``.ps1`` at the end of it.
2. Type in your search bar ``PowerShell``, right click it and click run as administrator.
3. When PowerShell loads into Administrator mode, type the command "``Set-ExecutionPolicy RemoteSigned``", this will allow you to run the script.
4. Just type in the path/location of where you installed the ``.ps1`` file and it will download both the zipped version and the unzipped version in a new directory, ``C:\Users\$USER$\Downloads\LWHCLI``.
5. Easiest way to run from here is to go to ``C:\Users\$USER$\Downloads\LWHCLI\unzipped\$PROJFILE$\LWHCLI.exe``

# Error/Success messages

If your WebhookURL is invalid, you will see this specific error message:

![Imgur](https://i.imgur.com/8QJhjZq.png)

Or, if you're using the ``--verbose``/``-v`` option:

![Imgur](https://i.imgur.com/oTXKR9w.png)

Any other error messages will be shown to you. If you determine that the error was not at your fault, then please create a new Issue and we will solve it for you in due time.

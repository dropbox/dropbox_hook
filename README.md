## dropbox_hook.py: Test your Dropbox webhook endpoints

    Usage: dropbox_hook.py [OPTIONS] COMMAND [ARGS]...
    
      This tool makes it easier to test Dropbox webhooks, particularly on
      localhost. Usage:
    
          dropbox_hook.py verify URL
          dropbox_hook.py notify URL -s APP_SECRET -u USER_ID
    
      For detailed help, try this:
    
          dropbox_hook.py COMMAND --help
    
    Options:
      --help  Show this message and exit.
    
    Commands:
      notify  Send a notification request.
      verify  Send a verification request.

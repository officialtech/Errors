# Errors
I will post all the errors and possible solutions here on random topics


***
<details>
  
  <summary>Could not open mysql.plugin table. Some plugins may be not loaded</summary>
  
  ### Xampp
  Delete following files from `C:\xampp\mysql\data` and restart the server
  ```ruby
    aria_log.00000001
    aria_log_control
```

</details>

***
<details>
  
  <summary>If you are not able to install required plugin on wordpress with child theme</summary>
  
  ### Wordpress plugin
  Here are the possible solutions
  ```ruby
    Activate the parent theme and install the plugin and activate
    Install all the plugins and lastly install the tough one
    Increase the memory size and execution time settings on wordpress file
    Flush the cache
```

</details>


***
<details>
  
  <summary>ERROR: Could not install packages due to an OSError: [Errno 13] Permission denied: '/var/www/fourthX.com/djpdf/venv/lib/python3.12/site-packages/decouple.py'Check the permissions.</summary>
  
  ##### WARNING: Running pip as the 'root' user can result in broken permissions and conflicting behaviour with the system package manager, possibly rendering your system unusable.It is recommended to use a virtual environment instead: https://pip.pypa.io/warnings/venv. Use the --root-user-action option if you know what you are doing and want to suppress this warning.
  Here are the possible solutions
  ```bash
    Change the ownership, using below command
    `sudo chown your_username /var/www/fourthX.com/djpdf`
    The chown command (short for "change owner") is used to change the owner and/or group of a file or directory in a Unix-like operating system. This is particularly useful when you need to grant or revoke access permissions to a specific user or group.
```

</details>






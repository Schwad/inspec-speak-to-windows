Spin up a windows instance using kitchen.

Using this shell, run:


`kitchen create`

This will take roughly 15 minutes.

Then use the data witihin `.kitchen/default-windows-16.yml` to construct your link to your windows target, ala:

inspec exec my_profile -t winrm://administrator@host --password 'password'

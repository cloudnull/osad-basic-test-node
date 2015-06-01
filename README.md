Basic OSAD test node
####################

This is a simple playbook that creates a public cloud vm and then installs OSAD as is
done on the gate job. This is a fast way to provision new development builds.


How to use this
---------------

* You will need a Rackspace Public Cloud account.
* Fill in the os-creds.yml file with your Public Cloud Credentials.
* Execute the simple regions playbook.

Example command

.. code-block:: bash

    ansible-playbook -i inventory -e @os-creds.yml osad-basic-test-aio-playbook.yml

Running
-------

Using Snap
~~~~~~~~~~

Make sure you have `snapd`_ installed. Install PTP:

::

   $ sudo snap install camus

Once installed, Camus runs automatically as a Snap service. See the Snap
`service management`_ documentation for details on starting and stopping
services.

Go to ``localhost:5000`` in your browser. For local testing, you can visit the
same room in multiple tabs and each tab will act as a separate client.

Using Python
~~~~~~~~~~~~

Camus requires `Python 3.7`_ or higher since it makes use of `Quart`_ and async
syntax. As usual, it's best to use a virtual environment.

Install Camus:

::

   $ pip install camus-chat

Run Camus:

::

   $ camus

Go to ``localhost:5000`` in your browser. For local testing, you can visit the
same room in multiple tabs and each tab will act as a separate client.

Using Docker
~~~~~~~~~~~~

You can find a `pre-built Docker image`_ on Docker Hub. Use the following
command to pull the image and run a container:

::

   $ docker run -d -p 5000:5000 mrgnr/camus

Go to ``localhost:5000`` in your browser. For local testing, you can visit the
same room in multiple tabs and each tab will act as a separate client.

Using Heroku
~~~~~~~~~~~~

|Deploy to Heroku|

Simply click the button above or see the `deployment documentation`_ for
detailed instructions.

